# 08 — Deployment & Ops

> **Goal:** Learn how to run AI features in production with reliability, visibility, and controlled iteration.

---

## Core concepts

- Rollout patterns: feature flags, canaries, staged release
- Latency/throughput/cost trade-off triangle
- Streaming vs non-streaming response design
- Caching strategies and where they fail
- Logging and observability design
- Monitoring for quality drift + system regressions
- Human review checkpoints
- Feedback loops from user behavior to model/prompt updates
- Incident response for AI-specific failures

---

## Resources

### Deployment and runtime
- 📖 **[OpenAI — Production best practices](https://platform.openai.com/docs/guides/production-best-practices)**
- 📖 **[Anthropic — Deploying Claude apps](https://developers.google.com/machine-learning/guides/rules-of-ml)**
- 📺 **[DeepLearning.AI — LLMOps](https://www.deeplearning.ai/short-courses/llmops/)**

### Observability and monitoring
- 📖 **[LangSmith docs](https://docs.smith.langchain.com/)**
- 📖 **[Eugene Yan — LLM patterns](https://eugeneyan.com/writing/llm-patterns/)**

### Broader MLOps context
- 📖 **[Made With ML](https://developers.google.com/machine-learning/guides/rules-of-ml)**
- 📺 **[DeepLearning.AI — ML in Production](https://www.deeplearning.ai/courses/machine-learning-in-production/)**

---

## Exercises

**Exercise 1 — Real deployment**  
Deploy your Pillar 05 prototype. Observe what breaks first (latency, rate limits, malformed inputs, cost spikes).

**Exercise 2 — Add observability**  
Log input, output, latency, token usage, and errors. Review one week of traces.

**Exercise 3 — Incident simulation**  
Write a one-page plan for a sudden quality drop (e.g., 15% hallucination rate). Cover detection, communication, mitigation, and recovery.

**Exercise 4 — Cost model**  
Estimate monthly API spend at 100 / 1,000 / 10,000 DAU. Propose cost reductions that don’t destroy quality.

---

## Exit criteria

- [ ] Deploy a public prototype with basic observability
- [ ] Explain a concrete latency/cost/quality trade-off decision
- [ ] Build a cost model across three usage scales
- [ ] Draft an incident response plan for quality regression
- [ ] Define a practical feedback loop from production signals to improvements

---

**Next: [09 — Portfolio & Career](./09-portfolio-and-career.md)**
