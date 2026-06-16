---
name: bootstrap-github-skills-exercise
description: "Bootstrap a GitHub Skills exercise repository from an approved outline. Use this when the user asks to create exercise files, step Markdown, issue templates, GitHub Actions workflows, validation scripts, starter content, or repository structure for a GitHub Skills-style learning experience."
---

# Bootstrap GitHub Skills exercise

Use this skill when an outline is ready and the user wants repository content or automation.

## First inspect the repo

Before editing, identify existing conventions:

- Where learner steps live.
- How workflows create issues, post comments, and validate progress.
- Whether reusable local actions or scripts already render Markdown templates.
- Existing test commands or workflow harnesses.

## Bootstrap outputs

Create or update the smallest coherent set of files:

- `README.md`: goal, audience, prerequisites, duration, start instructions, and reset/retry behavior.
- `.github/steps/`: learner-facing step instructions.
- `.github/markdown-templates/`: issue and comment templates when workflow-published content is needed.
- `.github/workflows/`: start, check, feedback, and completion workflows.
- `.github/actions/` or `scripts/`: shared rendering/validation helpers when repeated logic appears.
- Tests or a maintainer validation guide for the exercise flow.

## Workflow design guidance

- Use least-privilege `permissions`.
- Keep workflow inputs, outputs, and comment markers stable.
- Make check workflows fail helpfully before they pass.
- Prefer updating existing feedback comments over posting duplicates.
- Avoid hardcoded repository-specific URLs in source Markdown; render them at runtime.
- Prevent one-shot bootstrap workflows from overwriting legitimate later edits.

## Completion criteria

Before declaring the bootstrap done, verify the file set supports:

1. A clear starting point.
2. Step-by-step learner progression.
3. Automated or documented validation.
4. Clear completion feedback.
5. Maintainer instructions for local or CI validation.
