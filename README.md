# second-brain

Personal second brain — research, memory, and agent workspace for Lukas.

Cloud agents connected via [Cursor Cloud Agents](https://cursor.com/dashboard?tab=cloud-agents).

## Structure

```
second-brain/
├── MEMORY.md          ← Start here. Canonical context for all agents.
├── notes/             ← General notes on any topic
├── research/          ← Research outputs (dated, sourced)
├── journal/           ← Daily logs
├── tasks/             ← Open action items
└── .cursor/rules/     ← Agent behavior instructions
```

## For agents

1. Read `MEMORY.md` at the start of every session.
2. Save research to `research/YYYY-MM-DD-topic-slug.md`.
3. Update `MEMORY.md` when you learn something durable.
4. Commit and push changes so future sessions can see them.

See `.cursor/rules/second-brain.mdc` for full instructions.

## For Lukas

**Talk to your second brain:**
- Web/mobile: [cursor.com/agents](https://cursor.com/agents) → select this repo
- Desktop: Agents Window → Cloud → `second-brain`

**Example prompts:**
- "Read MEMORY.md and tell me what's on my plate today."
- "Research [topic] and save findings to research/."
- "Log today's progress in journal/ and update open tasks."

**Automations:** Set up scheduled research at [cursor.com/automations](https://cursor.com/automations) with memory enabled.
