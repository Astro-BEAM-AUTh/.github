# Astro - BEAM AUTh
This repository defines **shared templates, workflows, and policies** for all repositories under the telescope organization.

It ensures that every project follows consistent practices for:
- Issues & Pull Requests
- Continuous Integration (CI)
- Contribution guidelines
- Security & conduct standards

## 📁 Structure
| File | Purpose |
|------|----------|
| `.github/ISSUE_TEMPLATE/` | Templates for bug reports and feature requests |
| `.github/workflows/` | Common GitHub Actions workflows (tests, linting, stale issues) |
| `CONTRIBUTING.md` | Universal guide for contributing |
| `CODE_OF_CONDUCT.md` | Behavior expectations for collaborators |
| `SECURITY.md` (*optional*)| Responsible disclosure policy |
| `PULL_REQUEST_TEMPLATE.md` | Default PR structure |

## ⚙️ Usage
These files automatically apply to **all repositories** in the organization, unless overridden at the repo level.

To modify or suggest changes:
1. Open an issue or PR in this `.github` repo.
2. Add the relevant maintainers as reviewers.
3. After merge, all repos inherit updates automatically.
