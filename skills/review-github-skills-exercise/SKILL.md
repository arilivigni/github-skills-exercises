---
name: review-github-skills-exercise
description: "Review GitHub Skills exercises for learner experience, validation correctness, workflow safety, accessibility, and publish readiness. Use this whenever the user asks to audit, review, improve, QA, or validate a GitHub Skills-style exercise repository or draft."
---

# Review GitHub Skills exercise

Use this skill to review an exercise draft with a high signal-to-noise ratio.

## Review process

1. Read the README and identify the promised learner outcome.
2. Trace the learner journey from start through completion.
3. Inspect workflows, local actions, scripts, and templates that drive validation or feedback.
4. Check tests or validation docs.
5. Report only findings that affect learning, reliability, safety, accessibility, or publication.

## Rubric

### Learner experience

- The start path is obvious.
- Each step explains what to do and why it matters.
- Feedback helps the learner recover from common mistakes.
- Completion is visible and satisfying.

### Validation reliability

- Checks verify the intended behavior.
- Failing states produce actionable messages.
- Success criteria are neither too loose nor too brittle.
- Re-running the exercise does not create confusing duplicate state.

### Workflow safety

- Workflow permissions are least-privilege.
- Automation does not overwrite learner or maintainer work unexpectedly.
- Issue comments use stable markers if they are updated.
- Repository-specific links are rendered safely.

### Accessibility and maintainability

- Images have useful alt text.
- Links are descriptive.
- Markdown is readable in GitHub.
- Repeated logic is shared or documented.

## Output format

```markdown
## Overall readiness

## Blocking findings

## Important findings

## Nice to improve

## Suggested validation
```

If no issues are found in a category, say `None`.
