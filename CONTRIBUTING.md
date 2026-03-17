# Contributing to Claude Lenny Skills

Thank you for your interest in contributing! This guide explains how to add new skills, templates, and improvements to the PM toolkit.

## How to Contribute

### 1. Fork and Clone

```bash
git clone https://github.com/<your-username>/claude-lenny-skills.git
cd claude-lenny-skills
```

### 2. Create a Branch

```bash
git checkout -b feature/your-skill-name
```

### 3. Make Your Changes

See the sections below for guidelines on each type of contribution.

### 4. Submit a Pull Request

Push your branch and open a PR against `main`. Fill out the PR template and describe what your changes add or fix.

---

## Adding a New Skill

Each skill lives in `skills/<skill-name>/SKILL.md`. Follow this structure:

```markdown
---
name: lenny-<topic>
description: Brief one-line description
version: 1.0.0
---

# Skill Title

## Overview
What this skill covers and when to use it.

## Frameworks
Actionable frameworks with steps, anti-patterns, and examples.

## Key Takeaways
Bullet points summarizing the most important insights.
```

**Guidelines:**
- Skill names use the `lenny-` prefix
- Include actionable frameworks, not just advice
- Add anti-patterns (common mistakes to avoid)
- Reference specific Lenny's Podcast episodes where applicable

## Adding a Template

Templates live in `templates/<template-name>.md`. A good template includes:

- Clear section headers with instructions
- Placeholder text showing what to fill in
- Examples where helpful
- A checklist at the end for completeness

## Improving Existing Content

- Fix typos, clarify wording, or add missing context
- Add new frameworks or anti-patterns to existing skills
- Update outdated references

## Code Style

- Use standard Markdown formatting
- Keep lines under 120 characters where practical
- Use ATX-style headers (`#`, `##`, `###`)
- Tables should be aligned for readability

## Commit Messages

Use clear, descriptive commit messages:

```
Add lenny-pricing skill with freemium framework
Fix typo in pm-strategy module
Update hiring template with remote interview section
```

## Questions?

Open an [issue](https://github.com/LeoLin990405/claude-lenny-skills/issues) and we will be happy to help.
