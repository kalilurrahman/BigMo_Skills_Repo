# BigMo Skills Repo

A shared library of reusable **Skills** (instruction packs for AI assistants such as Claude) for BigMo projects.

## Structure
```
skills/
  <skill-name>/SKILL.md   # YAML frontmatter (name, description) + instructions
```

## Included skills
| Skill | Purpose |
|---|---|
| `code-review` | Structured review of diffs/PRs |
| `documentation` | READMEs, guides, runbooks |
| `data-analysis` | Profile, clean, analyze, report on data |
| `research-summary` | Cited multi-source research summaries |
| `git-workflow` | Branch, commit and PR conventions |
| `skill-template` | Starting point for new skills |

## Using a skill
- **Claude Code:** copy a skill folder into `~/.claude/skills/` (personal) or `<project>/.claude/skills/` (project).
- **Claude.ai:** zip the skill folder and upload it under Settings → Skills.
- **Other assistants:** paste the SKILL.md body into the system prompt/instructions.

Or unzip `bigmo-skills.zip` and copy everything in `skills/`.

## Adding a skill
1. Copy `skills/skill-template` to `skills/<new-name>`.
2. Set `name` (matches folder, lowercase-hyphenated) and a `description` stating *what* it does and *when* to use it.
3. Keep instructions concise, concrete and testable.
4. Add it to the table above and open a PR.

## Contributing guidelines
- One skill = one job. No secrets or customer data.
- Test the skill on a real task before submitting.
