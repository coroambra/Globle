# Skills

This folder contains reusable skill modules. Each skill is a subfolder with a `SKILL.md` file and optional supporting files.

## How to Add a Skill

1. Create a new subfolder (e.g., `skills/web-scraping/`)
2. Add a `SKILL.md` file with YAML frontmatter and instructions
3. Optionally add `scripts/`, `examples/`, or `resources/` subdirectories

## Skill Folder Structure

```
skills/
└── my-skill/
    ├── SKILL.md          # Main instruction file (required)
    ├── scripts/          # Helper scripts and utilities
    ├── examples/         # Reference implementations
    └── resources/        # Additional files, templates, assets
```

## SKILL.md Template

```markdown
---
name: Skill Name
description: What this skill enables
---

## Overview
Describe what this skill does.

## Instructions
Step-by-step instructions for using this skill.

## Examples
Usage examples and patterns.
```
