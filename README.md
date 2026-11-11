# bhem_skills

Start with [PREFERENCES.md](PREFERENCES.md): my standing preferences for any AI working for me.

Boon Eng's personal AI skills. Each folder in `skills/` is one skill: a `SKILL.md` (YAML frontmatter with `name` and `description`, then the instructions) plus any helper files.

| Skill | What it's for |
|---|---|
| `frontend-design` | Distinctive, intentional visual design; avoids templated defaults |
| `impeccable` | Design, critique, audit and polish of UI; detects AI design slop (includes `scripts/impeccable detect`) |
| `web-design-inspiration` | Curated design reference sites and how to use them before drafting mockups |
| `ui-library-reference` | Which component library or UI primitive to use when building or restyling a web UI |

Also used (installed from their own sources, not copied here): shadcn/ui skill (https://ui.shadcn.com), Notion skills (Notion connector).

## Using these skills
- **Claude Code:** copy a skill folder into `~/.claude/skills/` (personal) or `.claude/skills/` in a project.
- **Claude.ai:** zip a skill folder and upload it under Settings > Capabilities > Skills.
- **Cursor / Grok Bot:** same `SKILL.md` format; add it to the skills library.
- **Other AIs (ChatGPT, Gemini…):** paste the `SKILL.md` text into custom instructions or project knowledge.

This repo is the master copy. Edit here, then copy out.
