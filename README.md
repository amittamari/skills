# Agent Skills

A collection of skills for AI coding agents. Skills are packaged instructions that extend agent capabilities. Compatible with the [Agent Skills](https://agentskills.io) format.

## Available Skills

| Skill | Description |
|-------|-------------|
| [garden-docs](skills/garden-docs) | Audit project documentation for staleness by comparing what changed in code since docs were last updated |

## Installation

```bash
npx skills add amittamari/skills
```

Or install a specific skill:

```bash
npx skills add amittamari/skills --skill garden-docs
```

## Usage

Skills activate automatically when relevant tasks are detected. For example, saying "garden the docs" or "are the docs up to date?" will trigger the `garden-docs` skill.

## License

MIT
