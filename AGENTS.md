# Repository Instructions

## Purpose

Maintain this repository as a lightweight, public, Chinese-first personal AI toolkit. Optimize for two outcomes: people can navigate from the root README, and Codex can add or use content consistently.

## Required workflow

- Use the `content-maintainer` skill whenever adding, importing, reorganizing, or indexing knowledge-base content.
- Classify by content form only: `prompts`, `skills`, `workflows`, `coding-tips`, or `templates`.
- Give each content item its own kebab-case directory directly below its content type. Do not introduce tool- or scenario-based category directories.
- Keep one authoritative copy of every item.
- Update both the relevant category README and the root README whenever content is added, renamed, moved, or removed.
- Write explanations primarily in Chinese. Preserve English product names, commands, code, and standard technical terms where useful.

## Classification rules

- Prompt: a self-contained instruction submitted once in a fresh conversation.
- Workflow: a task that depends on multiple turns, prior conversational context, multiple steps, or several outputs.
- Skill: an installable capability containing `SKILL.md` and optional rules, resources, or scripts.
- Coding tip: usage or configuration guidance for AI coding tools.
- Template: a reusable project initialization or agent-instruction artifact.

## Safety and attribution

- Never add personal information, secrets, tokens, private conversations, unpublished research material, or sensitive project data.
- Generic research workflows are allowed only after removing personal topics, data, notes, and conclusions.
- Store original content in full when appropriate.
- For third-party content, write only a short description, applicable scenario, and verified original link. Do not copy the full work.
- Do not add third-party material when the original source cannot be established.

## Maintenance constraints

- Do not add YAML front matter to ordinary knowledge entries unless an indexing system is deliberately introduced later.
- Do not add status labels, case studies, tag systems, generated sites, or automation infrastructure without an explicit requirement.
- Avoid empty speculative categories. Add directories only when adding real content.
