---
name: code-review
description: Review code changes for correctness, security, readability and test coverage. Use when asked to review a diff, PR, or file.
---
# Code Review

## Steps
1. Read the diff and understand the intent before judging it.
2. Check correctness: edge cases, error handling, off-by-one, null/empty inputs.
3. Check security: input validation, secrets, injection, authz.
4. Check maintainability: naming, duplication, unnecessary complexity.
5. Check tests: are new behaviors and failure paths covered?

## Output format
- **Summary** (1-2 sentences)
- **Blocking issues** (file:line, problem, suggested fix)
- **Non-blocking suggestions**
- **Praise** for anything done well

Keep feedback specific and actionable; do not nitpick style the linter already enforces.
