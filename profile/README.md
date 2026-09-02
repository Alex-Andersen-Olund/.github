# Repository Guidelines

Conventions all members should follow when creating a new repo in this organization.

## Naming Convention

Always **kebab-case**, following a hierarchy-based pattern:

```
<domain>-<system>-<function>
```

**Examples:**
- `cps-trip-sync`
- `datawarehouse-migration-app`
- `webbooking-api-sync`
- `manager-portal-app`
- `navision-toolbox`

## New Repo Checklist

- **About section**: add a short sentence describing what the repo does. This shows up in the repo list and helps others find it quickly.
- **README.md**: every repo must include one, covering:
  - Tech stack used
  - Prerequisites / setup (e.g. install PHP, set up a SQL/MySQL server, etc.)
  - How to run the app locally
  - How and where it's deployed
- **.env.example**: if the project uses environment variables, include an example file so setup doesn't require guessing.
- **.gitignore**: appropriate to the stack, added from the first commit.
- **CODEOWNERS**: define who owns/maintains the repo, so review requests and questions go to the right people.
- **Branch strategy**: define default branch name and any protection rules (e.g. require PR review before merging to `main`).

Optional
- **LICENSE**: add the org's default license (or note if intentionally omitted).
- **CONTRIBUTING.md / PR template**: basic guidance on how to submit changes, even if just a few lines.
- **Issue templates**: optional, but useful for recurring bug/feature request formats.
- **Topics/tags**: add relevant topics on the repo for discoverability across the org.
- **CI/CD status**: if pipelines exist, link or badge them in the README.
- **Changelog / versioning**: note how releases/versions are tracked, if applicable.

## Why this matters

Consistent naming and documentation make repos easier to find, understand, and onboard into — for both current and future team members.
