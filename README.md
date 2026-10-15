[![Protected by Tracebit Community Edition](https://raw.githubusercontent.com/tracebit-com/tracebit-community-action/main/assets/badges/tracebit-badge.svg)](https://community.tracebit.com/supplychainattacks)

# asmldfklasfjkljasf-public

Scratch repository for testing GitHub Actions workflows.

## Workflows

| Workflow | File | Triggers |
|----------|------|----------|
| CI | `.github/workflows/ci.yml` | push to `main`, pull requests, manual |
| Lint | `.github/workflows/lint.yml` | push to `main`, pull requests |
| Manual | `.github/workflows/manual.yml` | manual (`workflow_dispatch`) |

Run a manual workflow:

```sh
gh workflow run manual.yml -f message="hello"
```
