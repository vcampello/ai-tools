# ai-tools

Portable guidelines and skills shared across AI harnesses.

## Contents

- **AGENTS.md:** shared working preferences, auto-loaded by all three harnesses.
- **skills/:** shared skills in the common SKILL.md format; each harness wires this folder to its own skills directory.

## Skills

| Skill      | Description                                                               |
| ---------- | ------------------------------------------------------------------------- |
| `describe` | Generates short, copy-pasteable descriptions matching your writing style. |

## Global setup

To load these guidelines and skills across all projects:

### opencode

Edit `~/.config/opencode/opencode.json`:

```json
{
  "instructions": ["/home/kore/dev/ai-tools/AGENTS.md"],
  "skills": { "paths": ["/home/kore/dev/ai-tools/skills"] }
}
```

Restart opencode after saving.
