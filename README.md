# Skill Design Guide

> Design principles and quality checklist for building AI Agent Skills — distilled from Anthropic, OpenAI, and LangChain engineering practices.

## What It Does

This skill auto-loads when you're designing, creating, reviewing, or optimizing any Skill or Agent. It provides:

- **Principle Zero**: Simplicity-first design (industry consensus)
- **Pattern Selection**: 5 workflow patterns to choose from (Prompt Chaining, Routing, Parallelization, Orchestrator-Workers, Evaluator-Optimizer)
- **SKILL.md Template**: Copy-paste ready template with all required sections
- **Quality Checklist**: 5-dimension review (Structure / Principles / Tools / Guardrails / Observability)
- **Anti-Pattern Warnings**: 8 common mistakes to avoid

## Installation

### WorkBuddy / CodeBuddy

Install via ClawHub, or manually:

1. Download or clone this repo
2. Place the folder in your skills directory:
   - **User-level** (all projects): `~/.workbuddy/skills/skill-design-guide/`
   - **Project-level**: `.workbuddy/skills/skill-design-guide/`
3. Restart your agent

### Claude Code

```bash
# Clone to your skills directory
git clone https://github.com/haiyangchenbj/skill-design-guide-skill.git ~/.claude/skills/skill-design-guide
```

## Usage

The skill triggers automatically when your conversation mentions:

- "design a skill", "create a skill", "new agent"
- "skill review", "agent architecture", "skill quality"
- "optimize skill", "skill checklist"

Or explicitly: "Load the skill-design-guide skill."

## File Structure

```
skill-design-guide/
├── SKILL.md                           # Core instructions (design guide)
└── reference/
    ├── agent-design-research.md       # Full industry research report
    └── anthropic-tool-design.md       # Anthropic tool design essentials
```

## Sources

- [Anthropic — Building Effective Agents](https://www.anthropic.com/research/building-effective-agents) (2024.12)
- [Anthropic — Writing Effective Tools for Agents](https://www.anthropic.com/engineering/writing-tools-for-agents) (2025.09)
- [OpenAI — A Practical Guide to Building Agents](https://everawelabs.com/learn-it/a-practical-guide-to-building-agents) (2025.04)
- [LangChain — State of Agent Engineering 2025](https://blog.langchain.dev/) (2025.12)

## License

MIT License. See [LICENSE](LICENSE).

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).
