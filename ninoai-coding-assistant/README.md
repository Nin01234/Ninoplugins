# NinoAI Coding Assistant

Version: 0.1.0

A skills-only coding assistant for explaining code, debugging errors, reviewing code, and planning tests.

## Capabilities

- Explain code and programming concepts.
- Investigate errors using user-provided code and logs.
- Review likely bugs, maintainability issues, and common security risks.
- Suggest relevant tests and verification steps.

## Limitations

This skill works with context provided in the conversation. It does not independently access repositories, connect to GitHub, execute code, or run tests. Users should verify suggested changes in their own environment.

## Contents

- `plugin.json` — plugin listing and metadata
- `skills/coding-assistant/SKILL.md` — main skill instructions
- `skills/coding-assistant/references/debugging.md` — debugging workflow
- `skills/coding-assistant/references/code-review.md` — code review guidance

## Before public submission

- Add the real icon asset referenced by `plugin.json`.
- Validate the manifest against the current submission schema.
- Confirm the listing category and all four public website URLs.
- Confirm the target-country settings in the submission portal.

## Pricing

Intended to be free, with no purchases or paid features.
