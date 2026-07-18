# 01 — Foundations of AI

> **Goal:** Build a clear mental model of modern AI so you can make strong product decisions without drowning in math.

---

## Why this pillar matters

Most AI mistakes at work aren’t coding mistakes — they’re thinking mistakes.
Teams overpromise what models can do, under-plan for failure cases, or confuse demos with production readiness.

This module fixes that by giving you a practical foundation you can apply immediately.

---

## Core concepts

- What a model is (and isn’t)
- Supervised, unsupervised, and reinforcement learning — intuitive view
- Training vs. fine-tuning vs. inference in real product workflows
- Generative AI vs. predictive AI
- Why probabilistic outputs change product design
- Tokens, context windows, and hard system limits
- Parameters/weights and what model "size" really means

---

## Resources

### Start here
- 📺 **[3Blue1Brown — Neural Networks](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi)** — Best visual intuition for neural nets. Watch episodes 1–4.
- 📺 **[Andrej Karpathy — Intro to LLMs](https://www.youtube.com/watch?v=zjkBMFhNj_g)** — Clear, practical, and essential.
- 📖 **[DeepLearning.AI — AI for Everyone](https://www.deeplearning.ai/courses/ai-for-everyone/)** — Great for non-technical framing and shared vocabulary.

### Go deeper
- 📺 **[Karpathy — How I’d learn ML today](https://www.youtube.com/watch?v=1bUy-1hGZpI)**
- 📖 **[Fast.ai — Practical Deep Learning for Coders](https://course.fast.ai/)**
- 📖 **[Anthropic — Intro to Claude](https://docs.anthropic.com/en/docs/intro-to-claude)**

### Hands-on reference
- 🧪 **[OpenAI Tokenizer](https://developers.openai.com/cookbook/examples/how_to_count_tokens_with_tiktoken)** — Spend 10 minutes here. It will change how you write prompts and estimate cost.

---

## Exercises

**Exercise 1 — Redraw your mental model**  
Draw how you think an LLM works from input to output (no Googling).  
Watch Karpathy’s intro, then redraw it. Keep both versions.

**Exercise 2 — Failure mode journal**  
Pick 3 AI features you used recently. For each, write one likely failure reason tied to a concept here (e.g., context limit, tokenization, probabilistic output).

**Exercise 3 — Token cost sanity check**  
Use the tokenizer on:
1) one user question, 2) a full system prompt, 3) a long document.  
Estimate cost for 1,000 runs on a current frontier model.

---

## Exit criteria

You’re ready for Pillar 02 when you can:
- [ ] Explain tokens and context windows in plain language
- [ ] Explain training vs inference without jargon
- [ ] Classify a use case as generative or predictive
- [ ] Explain why repeated prompts can produce different outputs
- [ ] Estimate rough token/cost impact for a feature idea

---

**Next: [02 — LLMs & AI Systems](./02-llms-and-ai-systems.md)**
