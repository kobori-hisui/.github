# .github

Organization-wide defaults for **kobori-hisui**. GitHub applies the files in this repository to every repository in the organization that does not define its own version.

| File / folder | Purpose |
|---|---|
| `profile/README.md` | Public organization profile page |
| `CONTRIBUTING.md` | How to contribute |
| `SECURITY.md` | How to report a vulnerability |
| `SUPPORT.md` | Where to get help |
| `CODE_OF_CONDUCT.md` | Community standards |
| `GOVERNANCE.md` | How decisions are made |
| `FUNDING.yml` | Sponsor button |
| `ISSUE_TEMPLATE/` | Issue forms (bug, feature, task) |
| `PULL_REQUEST_TEMPLATE.md` | Pull request description template |
| `DISCUSSION_TEMPLATE/` | Discussion category forms |
| `workflow-templates/` | Starter GitHub Actions workflows (CI, release) |

A repository that has its own copy of a file keeps using it. Issue templates are all-or-nothing: if a repository has its own `.github/ISSUE_TEMPLATE/` folder, the defaults here are not used.

`LICENSE`, `CODEOWNERS` and `dependabot.yml` are **not** inherited; they live in each repository.
