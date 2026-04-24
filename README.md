# SkillLayer

**The Knowledge Crystallizer** — A layer that captures AI session context and distills it into reusable, shareable .skill.md files.

## What is this?

Skills are encoded context. The problem is not intelligence — it is context transfer. SkillLayer watches how experts work, identifies what is repeatable, and packages it into a format that anyone can use in any future AI session.

## Core Flow

1. User selects past conversations about a recurring task
2. One-click distillation into a structured .skill.md file
3. Load the skill into any fresh AI session — start at week 6, not day 1

## Project Structure

\`\`\`
skilllayer/
├── src/                  # MCP server source code
│   ├── tools/            # MCP tool implementations
│   ├── distillation/     # Core distillation engine
│   └── privacy/          # PII scrubbing layer
├── prompts/              # Distillation prompt versions
├── docs/                 # Technical documentation
│   └── skill-schema.md   # .skill.md format specification
├── tests/                # Test suite
└── examples/             # Example .skill.md files
\`\`\`

## Status

Pre-MVP — Validation phase

## License

MIT
