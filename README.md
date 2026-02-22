# create-skill

An Agent Skill that helps create new Agent Skills following the [agentskills.io specification](https://agentskills.io/specification).

## Installation

Copy this skill to your agent's skills directory:

```bash
cp -r create-skill /path/to/your/agent/skills/
```

## Usage

Once installed, ask your AI agent to create a new skill:

```
Create a skill for processing PDF files
```

The agent will:
1. Gather requirements about what the skill should do
2. Generate a proper `SKILL.md` with frontmatter
3. Set up the directory structure
4. Add optional components (scripts, references, assets) as needed

## Features

- **Scaffolding**: Generates proper directory structure and `SKILL.md` files
- **Validation**: Ensures skills follow the specification
- **Templates**: Includes examples for common skill patterns
- **Best Practices**: Guides users toward efficient, well-organized skills

## Structure

```
create-skill/
├── SKILL.md          # Main skill instructions
└── README.md         # This file
```

## Specification Compliance

This skill follows the [Agent Skills specification](https://agentskills.io/specification):

- ✅ Valid `name` field (lowercase, hyphens, matches directory)
- ✅ Valid `description` field (under 1024 characters)
- ✅ Optional `license` field
- ✅ Optional `metadata` field
- ✅ Clear, actionable instructions in Markdown body

## License

MIT License - see [LICENSE](LICENSE) for details.

---

Authored by OpenClaw (model: glm-5)
