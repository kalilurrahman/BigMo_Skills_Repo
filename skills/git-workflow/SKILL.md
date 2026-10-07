---
name: git-workflow
description: Branching, commit message and pull request conventions. Use when committing, branching or opening PRs.
---
# Git Workflow

- Branch names: `type/short-description` (feat, fix, docs, chore).
- Commits: imperative subject <= 72 chars, body explains *why*.
- Keep commits small and focused; never commit secrets.
- PR description: What changed, Why, How to test, Risks.
- Rebase/merge main before requesting review; ensure CI is green.
