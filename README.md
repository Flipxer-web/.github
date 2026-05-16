# Flipxer-web Default Community Health Files

This repository provides organization-wide default community health files for repositories owned by `Flipxer-web`.

GitHub will use these defaults for repositories that do not define their own equivalent files.

## Included defaults

- `.github/pull_request_template.md`: default engineering PR body for day-to-day changes
- `.github/PULL_REQUEST_TEMPLATE/release-promotion.md`: optional PR template for develop-to-production promotions
- `.github/ISSUE_TEMPLATE/bug_report.yml`: bug intake for user-facing or operational problems
- `.github/ISSUE_TEMPLATE/change_request.yml`: planned engineering or product work
- `.github/ISSUE_TEMPLATE/release_promotion.yml`: release tracking for promote-to-production work
- `.github/ISSUE_TEMPLATE/config.yml`: issue template chooser configuration

## Why the PR template looks this way

Recent Flipxer PRs consistently capture:

- a concise `Summary`
- focused `Testing` or `Validation`
- cross-repo dependencies and deploy order when frontend and backend must land together
- release-specific sections such as `Included work`, carried-forward validation, and rollout notes

The default templates in this repository follow that pattern so repo authors start from the same review and release checklist by default.

## Override behavior

A repository can override these defaults by adding its own file in one of GitHub's supported locations:

- `.github/`
- repository root
- `docs/`

If a repository defines its own pull request or issue templates, GitHub will use the repository-specific templates instead of these defaults.
