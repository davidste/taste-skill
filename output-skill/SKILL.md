---
name: output-skill
description: Force complete, placeholder-free deliverables. Use when the task requires full files, exhaustive sections, or multi-part outputs and the model might otherwise truncate, summarize, or leave placeholders.
---

# Output Skill

## Baseline

Treat missing deliverables as failures. Match the requested scope exactly.

## Hard failures

Never produce:

- Placeholder code such as `// ...`, `/* ... */`, `TODO`, `rest of code`, or `implement here`
- Prose shortcuts such as `for brevity`, `the rest follows the same pattern`, or `let me know if you want me to continue`
- Skeletons, partial lists, or one example standing in for multiple requested deliverables

## Execution process

1. Count the requested deliverables before drafting.
2. Produce every deliverable completely.
3. Cross-check the final output against the original scope.
4. Remove any sentence that explains missing work instead of doing the work.

## When the response is too long

- Do not compress the remaining sections.
- Stop only at a clean breakpoint such as the end of a function, file, or section.
- End with:

```text
[PAUSED - X of Y complete. Send "continue" to resume from: next section name]
```

- Resume exactly from that breakpoint on the next turn.

## Final check

- Confirm every requested item is present.
- Confirm code blocks contain runnable code rather than commentary.
- Confirm no banned placeholder patterns appear anywhere in the response.
- Confirm nothing was shortened just to save tokens.
