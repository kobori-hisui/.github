# Contributing

Thanks for taking the time to contribute. This guide applies to every repository in the organization unless the repository ships its own `CONTRIBUTING.md`.

By participating you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Ways to contribute

- **Report a bug** using the bug report form.
- **Suggest a feature** using the feature request form.
- **Improve the documentation.** Typos and clarifications are welcome.
- **Send a pull request** that fixes a bug or implements an accepted feature.

For security problems, do **not** open a public issue. Follow [SECURITY.md](SECURITY.md).

## Before you start

1. Search the existing issues and pull requests to avoid duplicates.
2. For anything larger than a small fix, open an issue first and wait for feedback. This avoids work that cannot be merged.
3. Read the repository's `README` for setup instructions. Most of our projects use Node.js and pnpm.

## Workflow

1. **Issue.** Every change starts from an issue. Write what should happen and how to tell it is done (acceptance criteria).
2. **Branch.** Create a branch from an up-to-date `main`, named `type/<issue>-<short-slug>`:
   `fix/42-graphql-non-json`, `feat/57-collab-coauthors`.
3. **Commits.** Use [Conventional Commits](https://www.conventionalcommits.org/): `type(scope): description`, and reference the issue in the body (`Refs #42`).
4. **Pull request.** Open it against `main`, use the same Conventional Commit format for the title, and include `Closes #42` in the description.
5. **Review.** A maintainer reviews. Please respond to comments and keep the branch up to date with `main`.
6. **Merge.** Pull requests are merged with **squash**, so the PR title becomes the commit on `main`.

### Commit types

| Type | Use for | Version bump |
|---|---|---|
| `feat` | New functionality | minor |
| `fix` | Bug fix | patch |
| `docs` | Documentation only | none |
| `refactor` | Code change that neither fixes a bug nor adds a feature | none |
| `test` | Adding or fixing tests | none |
| `chore` | Tooling, dependencies, release housekeeping | none |

A breaking change is marked with `!` (`feat(api)!: ...`) or a `BREAKING CHANGE:` footer. While a project is on `0.x`, breaking changes bump the minor version.

## Pull request checklist

- [ ] The change is focused: one issue, one pull request.
- [ ] I ran the project locally and tested the reported case and the normal case.
- [ ] I did not include unrelated files (local config, `.env`, build output).
- [ ] I updated the documentation and the `CHANGELOG.md` when behavior changed.
- [ ] The title follows Conventional Commits and the description contains `Closes #<issue>`.

## Versioning and releases

Projects follow [Semantic Versioning](https://semver.org/) and keep a [Keep a Changelog](https://keepachangelog.com/) style `CHANGELOG.md`. Maintainers publish releases by tagging `vX.Y.Z` on `main`.

## Licensing

By contributing, you agree that your contributions are licensed under the license of the repository you contribute to.
