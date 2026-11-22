# Learning log

Entries record study sessions; experiments and results are included only when actually run.

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

### 2026-11-22 — Zero to Hero Lesson 1: makemore — in progress
- Watched through 1:25:36.
- Next: Continue the lesson and implement the bigram character language model; record actual study time and results afterward.
- [Lesson 1 video](https://youtu.be/PaCmpygFfXo) · [Issue #4 — Build makemore bigram model](https://github.com/hzwlille/ai-from-zero-to-llm/issues/4)

### 2026-11-18 — Zero to Hero Lesson 1: makemore — in progress
- Studied this lesson; stopping point not recorded.
- Video length: 30:44 (video duration, not study time).
- Next: Continue the lesson and implement the bigram character language model; record actual study time and results afterward.
- [Lesson 1 video](https://youtu.be/PaCmpygFfXo) · [Issue #4 — Build makemore bigram model](https://github.com/hzwlille/ai-from-zero-to-llm/issues/4)

### 2026-11-15 — Zero to Hero Lesson 0: micrograd and MLP — completed
- Studied the scalar-value autodiff engine: computation graphs, operation-level backward functions, topological ordering, and gradient accumulation.
- Built up the neuron, layer, and MLP abstractions; traced how inputs flow through layers and how weights and biases are collected as parameters.
- Worked through training: forward pass, squared-error loss, clearing gradients, backpropagation, and gradient-descent updates. Each parameter changes according to its own gradient; parameters do not all decrease.
- Compared the custom Value gradients with PyTorch autograd on the same tanh neuron. Fixed a call-site typo: o.backward references the method; o.backward() executes it.
- Key takeaway: MLPs and LLMs share parameters, loss, gradients, and optimization, but LLMs use Transformer blocks, tokenization, and attention to process text.
- Next: Learn tensor operations and classification with cross-entropy, then tokenization, embeddings, attention, and Transformer blocks.
- [Issue #3 — Build micrograd](https://github.com/hzwlille/ai-from-zero-to-llm/issues/3)

### 2026-11-01 — Zero to Hero Lesson 0: micrograd — in progress
- Watched through 1:09, covering manual backpropagation and the start of per-operation backward functions.
- Next: Continue the video and implement the backward functions.
- [Issue #3 — Build micrograd](https://github.com/hzwlille/ai-from-zero-to-llm/issues/3)
