# RESUME (2026-10-23)

## Current state
- Fork `c10vis-poem/NvAEx-skills` of `mattpocock/skills`; default and PR base `main`, protected with required status checks; CI workflow `ci.yml` runs a `check` job (gitleaks). Open PRs: none.
- Operator rule: no custom skills in this fork (see MEMORY.md).
- Repo rule: no em-dashes anywhere in prose.

## Changed this week (2026-10-18..2026-10-23)
- PR #2 (merged 2026-10-18): `ci: add check job with gitleaks secret scan`.
- Upstream sync merge 1896c4d (2026-10-20) brought in upstream #1304 `chief-of-staff: keep memory in a dated, commit-cited wiki` (2026-10-19).

## Open items (in order)
1. Per CLAUDE.md, a changed promoted skill needs its docs page re-synced (`docs/<bucket>/<skill>.md`) and `ask-matt` re-checked; confirm whether `chief-of-staff` is in a promoted bucket and whether its docs page and `ask-matt` reflect upstream #1304. Not checked this session.
2. Run `scripts/link-skills.sh` if skill folders changed, so installed symlinks stay current.

## Next steps
- Sync the fork with upstream (`gh repo sync c10vis-poem/NvAEx-skills`) before any install.

## Sources
Read: AGENTS.md, MEMORY.md, `git log origin/main --since=2026-10-18`, PR #2 body, branch protection, grep of *.md for dropped tools (none found). Not read: CLAUDE.md beyond session context, upstream #1304 diff, docs pages, ask-matt SKILL.md.
