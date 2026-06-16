---
name: create-github-skills-outline
description: "Create learner-centered GitHub Skills exercise outlines from a topic, demo, workshop, or rough idea. Use this whenever the user wants to design a GitHub Skills exercise, convert training material into a self-paced GitHub exercise, define learning objectives and steps, or plan validation before building repository files."
---

# Create GitHub Skills outline

Use this skill to design a self-paced GitHub Skills-style exercise before implementation begins.

## Workflow

1. Clarify the topic, target learner, prerequisites, time box, and desired outcome.
2. Narrow broad ideas to one primary learner outcome.
3. Design a scenario that gives the learner a reason to complete the task.
4. Break the exercise into small steps with one learner action per step.
5. Define validation signals and feedback for each step.
6. Identify repository files, workflows, and assets needed for implementation.
7. Call out open questions instead of inventing domain details that affect correctness.

## Outline template

Return this structure by default:

```markdown
# [Exercise title]

## Summary

## Target learner

## Prerequisites

## Learning objectives

## Scenario

## Learner journey

| Step | Learner action | Why it matters | Validation signal | Feedback |
| --- | --- | --- | --- | --- |

## Repository plan

## Success criteria

## Risks and open questions
```

## Quality bar

- Objectives should be observable: the learner can demonstrate them through repository activity.
- Steps should be small enough that validation can give targeted feedback.
- Validation should check intent, not only file existence.
- The outline should be implementable as GitHub issues, comments, workflows, and Markdown content.
