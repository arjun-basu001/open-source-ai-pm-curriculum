# 02 — LLMs & AI Systems

> **Goal:** Understand how LLM-based systems are assembled so you can make better architecture, cost, and UX decisions.

---

## Core concepts

- Transformer architecture (intuition, not equations)
- Pre-training, instruction tuning, and RLHF
- Hosted APIs vs open-source/self-hosted models
- Context length, latency, throughput, and cost trade-offs
- Embeddings and vector search basics
- RAG architecture and failure modes
- Tool/function calling
- Multimodal systems (text + image + audio)
- Pipelines vs agents: when each wins

---

## Resources

### Core reading
- 📺 **[Karpathy — Let’s build GPT](https://www.youtube.com/watch?v=kCc8FmEb1nY)**
- 📖 **[Anthropic — Model overview](https://docs.anthropic.com/en/docs/about-claude/models/overview)**
- 📖 **[OpenAI docs — Function calling & structured output](https://platform.openai.com/docs/introduction)**

### RAG and retrieval
- 📺 **[DeepLearning.AI — Building & Evaluating Advanced RAG](https://www.deeplearning.ai/short-courses/building-evaluating-advanced-rag/)**
- 📖 **[LlamaIndex concepts](https://docs.llamaindex.ai/en/stable/getting_started/concepts/)**

### Open-source ecosystem
- 📖 **[Hugging Face Open LLM Leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard)**
- 📺 **[Hugging Face NLP Course](https://huggingface.co/learn/nlp-course/)** (focus on chapters 1–4)

### Agents
- 📖 **[Anthropic — Building effective agents](https://www.anthropic.com/research/building-effective-agents)**
- 📖 **[Microsoft — AI Agents for Beginners](https://github.com/microsoft/ai-agents-for-beginners)**

---

## Exercises

**Exercise 1 — Model shootout**  
Run one task across at least 3 models (e.g., GPT-4o, Claude Sonnet/Opus, one open model). Compare quality, latency, and cost.

**Exercise 2 — RAG architecture sketch**  
Design a RAG flow for one use case. Include ingestion, chunking, retrieval, re-ranking, and where it can break.

**Exercise 3 — Tool-calling mini build**  
Build a tiny function-calling workflow (weather, stock, calculator, or mock API). Log one surprising behavior.

---

## Exit criteria

- [ ] Explain RAG clearly (what it solves + where it fails)
- [ ] Explain hosted vs self-hosted model trade-offs
- [ ] Explain embeddings with one real use case
- [ ] Justify pipeline vs agent for a feature
- [ ] Build and demo a tool/function-calling example

---

**Next: [03 — AI Product Management](./03-ai-product-management.md)**
