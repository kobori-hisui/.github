# Governance

This document describes how decisions are made in the projects of this organization.

## Roles

**Contributors** are anyone who opens an issue, sends a pull request, improves the documentation or helps other users.

**Maintainers** have write access. They review and merge pull requests, triage issues, publish releases and enforce the [Code of Conduct](CODE_OF_CONDUCT.md).

## Decision making

- Most decisions happen in the open, in issues and pull requests.
- We use **lazy consensus**: a proposal is accepted if no maintainer objects within a reasonable time (typically 7 days for non-trivial changes).
- If maintainers disagree, they discuss until there is consensus. If there is none, the **project lead** makes the final decision and records the reason in the issue.
- Security fixes and urgent regressions can be merged without the waiting period. They are explained in the pull request afterwards.

## Becoming a maintainer

Contributors who show sustained, high-quality contributions and good judgment in reviews can be invited by the existing maintainers. Maintainers who are inactive for an extended period may be moved to emeritus status.

## Releases

Projects follow Semantic Versioning. A maintainer prepares the release (version bump and changelog in the same pull request as the change), merges it into `main`, and tags `vX.Y.Z`.

## Changes to this document

Changes to governance are proposed through a pull request and need approval from the project lead.
