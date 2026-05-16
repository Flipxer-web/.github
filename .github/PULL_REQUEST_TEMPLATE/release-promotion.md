## Summary
- Promote the selected source branch into the target release branch.
- Describe what this release is intended to ship.

## Included Work
- List the included PRs and major fixes.
- Call out anything intentionally excluded from this promotion.

## Validation
- Describe the carried-forward validation from the source branch.
- List any release-specific smoke checks, browser checks, Docker checks, or deployment verification.

## Rollout Notes
- Document cross-repo deploy order.
- Note migrations, env var changes, feature flags, queue impacts, webhooks, or cache clears.

## Risks / Rollback
- Call out the highest-risk areas in this promotion.
- Document rollback or mitigation steps if the release needs to be reverted.

## Checklist
- [ ] Included PRs are listed.
- [ ] Validation evidence is captured.
- [ ] Cross-repo deploy order is documented.
- [ ] Rollback considerations are documented.
