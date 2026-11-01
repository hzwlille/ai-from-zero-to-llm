# Learning log

**Status: planned template.** Add an entry after each study session or weekly review; no completed work is claimed here.

## Entry template

### YYYY-MM-DD — topic — planned / in progress / completed
- Time spent:
- What I studied or attempted:
- Implementation:
- Experiments and settings:
- Observed results (only after running):
- What I learned / questions:
- Next step:
- Links to issues, commits, reports:

## Entries

### 2026-11-01 — Zero to Hero Lesson 0: micrograd — in progress
- Video progress: Watched through approximately 1:09:00.
- What I studied: Manual backpropagation through a simple neuron; the lecture then begins turning those calculations into per-operation `_backward` closures.
- Implementation: No implementation recorded in this session; this entry records the video progress and concepts covered.
- Experiments and settings: None.
- Observed results (only after running): None.
- What I learned / questions: Each operation can store its local backward rule. During backpropagation, the output gradient is multiplied by the local derivative and accumulated into the input gradients with `+=`.
- Next step: Continue from approximately 1:09:00 and implement the value operations and their backward closures.
- Links to issues, commits, reports: [Issue #3 — Build micrograd](https://github.com/hzwlille/ai-from-zero-to-llm/issues/3)
