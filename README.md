# Gemini Agents & Skills Hub

This repository centralizes the documentation and configuration for custom agents and their skills for Gemini CLI.

## Repository Structure

- `skills/`: Contains subdirectories for each specific skill. Each skill must include a `SKILL.md` file.
- `agents/`: (Optional) Documentation regarding specific agent configurations.

## How to Add a New Skill

1. Create a new directory in `skills/skill-name`.
2. Copy the `SKILL_TEMPLATE.md` file into that directory and rename it to `SKILL.md`.
3. Complete the skill's documentation.
4. Register the skill in Gemini CLI using the absolute path to the `SKILL.md` file.

## Gemini CLI Registration

For Gemini CLI to recognize a skill, it must be configured in your environment. You can use the Gemini CLI configuration commands to point to the `SKILL.md` files within this repository.

## Current Agents

- **Orchestrator**: The primary agent responsible for strategic planning and delegation.
- **Researcher**: Specialized in codebase analysis and technical requirements gathering.
- **Coder**: Focused on implementing solutions from abstract specifications (Clean Room approach).
- **Reviewer**: Responsible for code review, security, and automated validation.
