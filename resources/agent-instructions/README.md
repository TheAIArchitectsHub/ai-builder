# Agent instructions

This section will contain reusable instruction packs for AI coding agents.

## Where `AGENTS.md` and `CLAUDE.md` belong

The correct location depends on their purpose.

### Instructions that govern this repository

Save them at the repository root:

```text
/AGENTS.md
/CLAUDE.md
```

- `AGENTS.md` is the repository-wide instruction file for Codex and tools that support the AGENTS.md convention.
- `CLAUDE.md` is the repository-wide instruction file for Claude Code.

Root files should describe how agents must work **inside this repository**: architecture, commands, code style, validation, safety rules, and contribution expectations. Do not use the root files merely as a download area, because AI tools may treat them as active instructions.

### Files intended for your audience to download

Publish each instruction pack in its own folder here:

```text
resources/agent-instructions/<pack-name>/
  README.md
  AGENTS.md
  CLAUDE.md
```

People only need the file supported by the tool they use. Providing both makes the pack useful across tools. Make each file understandable on its own, even when the two files share many of your principles.

## Recommended contents

A strong instruction pack normally defines:

- The role and intended outcome
- Project context and boundaries
- How to inspect and change files
- Coding and documentation standards
- Required tests and validation
- Security and privacy rules
- Actions that require human approval
- Completion and handoff expectations

Keep rules specific, testable, and short enough to follow. Separate your universal principles from language- or framework-specific guidance when the pack grows.

