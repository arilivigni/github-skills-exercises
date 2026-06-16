---
name: publish-github-skills-exercise
description: "Prepare a GitHub Skills exercise for publication, contribution, or rollout. Use this when the user asks for release readiness, final checklist, README/marketplace copy, PR description, validation evidence, launch notes, or publishing guidance for a GitHub Skills-style exercise."
---

# Publish GitHub Skills exercise

Use this skill for final release preparation after an exercise has been built and reviewed.

## Publication workflow

1. Confirm the repository communicates the exercise clearly.
2. Confirm the learner flow has been validated from a fresh start.
3. Confirm workflow permissions, triggers, and reset behavior are safe.
4. Confirm all images, links, snippets, and badges render correctly.
5. Prepare release or contribution copy.
6. Identify any remaining risks and the owner of each follow-up.

## Release-readiness checklist

- README includes title, summary, learner audience, prerequisites, duration, start path, and support path.
- Exercise steps match the stated objectives.
- Workflows use least-privilege permissions and have clear trigger behavior.
- Validation evidence is available: tests, dry run, or documented manual checks.
- Reset/retry behavior is documented and safe for repeated learners.
- No source content contains repository-specific absolute URLs unless required.
- License, attribution, and contribution notes are present where needed.

## Output template

```markdown
## Publish recommendation

## Release summary

## Validation evidence

## Final checklist

## Suggested PR description

## Suggested release notes

## Remaining risks
```

Be direct if the exercise is not publishable yet. Include the shortest concrete path to readiness.
