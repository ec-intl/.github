# .github v1.0.2 — release candidate

Prepared from staging for human review on 2026-11-19. No tag, release, or deployment has been published.

## Included change record

- chore: Refresh staged issue templates and shared workflow guard configuration.

These candidate notes are prepared on the release branch for review before promotion.

## Net change inventory

- `.github/workflows/guard_template.yml`
- `.github/workflows/super-linter.yml`

## Promotion

Review and merge the release-preparation PR into staging first, then review staging → main. Keep auto-merge disabled. Release/CD jobs may publish packages, update production branches, and build/push images after promotion.
