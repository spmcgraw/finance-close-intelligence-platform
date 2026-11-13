# Finance Close Intelligence Platform

Close-health analytics platform on a synthetic close dataset: PostgreSQL schema, SQL views and a Power BI spec.

## Working conventions

- **Branch from `main` before starting any work.** Never commit directly to `main`.
  Start each piece of work with `git switch main && git pull && git switch -c <branch>`.
- **Name branches with a type prefix**: `feature/`, `chore/`, `bug/` (also `fix/`,
  `docs/`, `refactor/`), followed by a short kebab-case description, e.g.
  `feature/close-checklist`, `bug/duplicate-entries`, `chore/deps-bump`.
- Work in the main checkout, not a git worktree.

## Agent skills

### Issue tracker

Issues are tracked as GitHub issues in `spmcgraw/finance-close-intelligence-platform` via the `gh` CLI. See `docs/agents/issue-tracker.md`.

### Triage labels

Default canonical triage labels (`needs-triage`, `needs-info`, `ready-for-agent`, `ready-for-human`, `wontfix`). See `docs/agents/triage-labels.md`.

### Domain docs

Single-context: `CONTEXT.md` + `docs/adr/` at the repo root. See `docs/agents/domain.md`.

### Project board (Finance Intelligence)

Issues are labelled `finance-close` and tracked on the **Finance Intelligence** GitHub Project, with Status set per its state (Backlog/Ready/In Progress/Done). See `docs/agents/project-board.md`.
