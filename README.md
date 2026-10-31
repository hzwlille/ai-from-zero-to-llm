# AI from Zero to LLM

> **Status: learning plan — all projects are planned or not started. No learning results are claimed yet.**

A 12-month hands-on path from mathematical foundations and neural networks to small language models, training systems, and selected AI research topics.

## Learning goals
- Build an intuitive and mathematical understanding of neural networks and backpropagation.
- Implement a small GPT-style language model and explain tokenization, attention, transformer blocks, and training.
- Learn the data, optimization, and evaluation decisions behind LLM training.
- Explore GPU memory, distributed training, inference optimization, and interpretability through small, documented experiments.

## Four-stage roadmap
1. **Months 1–3 — Neural-network foundations / Zero to Hero:** derivatives, micrograd, backpropagation, MLPs; planned outcome: a tiny autodiff engine and character-level model with explanations and controlled experiments.
2. **Months 4–6 — GPT from scratch:** tokenizer, attention, transformer; planned outcome: a compact GPT implementation and reproducible training/sampling walkthrough.
3. **Months 7–9 — LLM training:** data processing, optimization, evaluation; planned outcome: small-scale pipeline experiments with documented decisions.
4. **Months 10–12 — Systems and research:** GPU/distributed AI, inference, paper reproduction, interpretability; planned outcome: focused systems experiments and one scoped study.

The schedule is flexible; adjust scope to available time and compute.

## Weekly rhythm (8–10 hours)
- 3–4 hours: lessons and reading, with notes in your own words.
- 3–4 hours: implementation and debugging.
- 1–2 hours: experiments, review, and a learning-log entry.
- Record what was attempted, what worked or failed, and the next small step.

## Project completion standard
Every project should eventually include **implementation**, **explanation**, **experiments**, and **results**. Record results only after actually running experiments. Until then mark work **Planned** or **Not started**.

## Repository map
- [00-math-foundations](00-math-foundations/)
- [01-neural-networks](01-neural-networks/) — micrograd, backpropagation, MLP, experiments
- [02-gpt-from-scratch](02-gpt-from-scratch/) — tokenizer, attention, transformer
- [03-llm-training](03-llm-training/) — data-processing, optimization, evaluation, experiments
- [04-gpu-and-distributed-ai](04-gpu-and-distributed-ai/) — cuda, gpu-memory, distributed-training, inference-optimization
- [05-ai-research](05-ai-research/) — paper-reproduction, interpretability
- [docs](docs/) — learning log and technical reports

Start with the [Zero to Hero issues](https://github.com/hzwlille/ai-from-zero-to-llm/issues). Keep dated notes in docs/learning-log.md and link commits or pull requests from issues.
