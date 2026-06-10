# Volve OS

A personal AI operating system built by Hugh — Senior Leader, builder, and operator across multiple ventures.

This is not a project-specific resource. It is the way Hugh thinks, decides, builds, and communicates — made portable so any LLM can work the way he works.

---

## How to use this

**Starting any session in any LLM:**
Load the universal layer first, then add the relevant project context if needed.

1. Open `advisory-board/system-prompt.md` — paste for strategic decisions
2. Open `coding-standards/CLAUDE.md` — paste for any build session
3. Open `writing-style/style-guide.md` — paste for any writing task
4. Add `projects/[relevant-project].md` for project-specific context

**In Claude Code / Cursor:**
Copy `coding-standards/CLAUDE.md` into the root of any project as `CLAUDE.md`.

**In n8n or agent pipelines:**
Fetch raw file URLs at runtime and inject as system prompts.

Raw URL format:
```
https://raw.githubusercontent.com/Hugh-D/volve-os/main/[path-to-file].md
```

---

## Structure

| Folder | Purpose |
|---|---|
| `/advisory-board` | 8-role strategic decision panel — use for any major decision |
| `/coding-standards` | AI-assisted coding principles — use for any build session |
| `/writing-style` | Voice, tone, and communication standards |
| `/frameworks` | DISC, Working Genius, EOS language reference |
| `/projects` | Lightweight context per active project — add and archive as needed |
| `/templates` | Reusable prompt templates for common tasks |

---

## Principles

- Universal standards at the top. Project context is just context.
- Direct, frank, action-oriented. No filler.
- Validate before building. Root causes over temporary fixes.
- PHD: Pig-Headed Discipline.

---

## Raw file URLs

Copy these directly into any LLM, n8n workflow, or agent pipeline:

```
# Universal layer
https://raw.githubusercontent.com/Hugh-D/volve-os/main/advisory-board/system-prompt.md
https://raw.githubusercontent.com/Hugh-D/volve-os/main/coding-standards/CLAUDE.md
https://raw.githubusercontent.com/Hugh-D/volve-os/main/writing-style/style-guide.md
https://raw.githubusercontent.com/Hugh-D/volve-os/main/frameworks/reference.md

# Templates
https://raw.githubusercontent.com/Hugh-D/volve-os/main/templates/prompt-templates.md
https://raw.githubusercontent.com/Hugh-D/volve-os/main/templates/decision-log.md

# Projects
https://raw.githubusercontent.com/Hugh-D/volve-os/main/projects/mex-engineering.md
https://raw.githubusercontent.com/Hugh-D/volve-os/main/projects/ai-business-audit.md
https://raw.githubusercontent.com/Hugh-D/volve-os/main/projects/soil-and-snout.md
```
