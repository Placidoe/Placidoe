<p align="center">
  <img src="./assets/ai-systems-banner.png" alt="AI systems lab: a cyan data stream through a midnight compute landscape" width="100%" />
</p>

<h1 align="center">Placidoe · AI Systems Lab</h1>

<p align="center">
  Building practical AI systems — measuring first, optimizing second.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/focus-vLLM%20performance-00D9FF?style=for-the-badge&labelColor=0B0F19" alt="Focus: vLLM performance" />
  <img src="https://img.shields.io/badge/hardware-Kaggle%20T4%C3%972-7C4DFF?style=for-the-badge&labelColor=0B0F19" alt="Hardware: Kaggle T4 times 2" />
  <img src="https://img.shields.io/badge/mindset-measure%20%3E%20guess-00D9FF?style=for-the-badge&labelColor=0B0F19" alt="Mindset: measure greater than guess" />
</p>

## `whoami`

I learn by shipping small systems, inspecting their bottlenecks, and keeping the experiments reproducible. Right now I am exploring how to get more useful LLM throughput from constrained GPU resources.

```text
observe → benchmark → profile → optimize → document → repeat
```

## `now()`

- Studying **vLLM** from first principles: PagedAttention, KV cache management, continuous batching, and scheduling.
- Running controlled inference experiments on **Kaggle T4 × 2**.
- Comparing throughput, TTFT, TPOT, tail latency, and memory efficiency — not just one headline number.

## `stack`

`Python` · `Go` · `Java` · `CUDA` · `PyTorch` · `vLLM` · `Docker` · `GitHub Actions`

## `lab_notes`

> A fast demo is nice. A measured system that explains *why* it is fast is better.

This profile is the public front door for ongoing experiments. Each project should answer three questions:

1. What constraint are we working under?
2. What did we measure?
3. What changed, and what did it cost?

---

<p align="center">
  <sub>Signal over noise. Systems over slogans.</sub>
</p>
