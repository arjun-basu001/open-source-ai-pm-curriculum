# 03 — AI Product Management

> **Goal:** Learn to ship AI behaviors, not just AI features — with clear specs, measurable outcomes, and realistic failure handling.

---

## What changes in AI PM work

Classic PM playbooks assume deterministic software. AI systems are probabilistic.
That means your job expands: you’re defining quality bands, acceptable error rates, fallback paths, and evaluation plans — not just feature requirements.

---

## Core concepts

- Opportunity sizing for AI (where it genuinely adds value)
- AI-native PRDs and spec patterns
- Quality metrics for probabilistic behavior
- Trade-offs with engineering: cost, latency, controllability
- User expectation setting and trust design
- Feedback loops for iterative model/prompt improvement
- Discovery for high-signal, low-risk use cases
- Build vs buy vs fine-tune decision-making

---

## Resources

### Foundations
- 📖 **[HelloPM — Free AI PM Course](https://hellopm.co/free-ai-pm-course/)**
- 🎧 **[Lenny’s Podcast](https://www.lennyspodcast.com/)** (search AI PM episodes)
- 📖 **[Reforge — AI for PMs](https://www.reforge.com/blog/ai-for-product-managers)**

### Specs and systems
- 📖 **[Eugene Yan — System design for recommendations/search](https://eugeneyan.com/writing/)**
- 📖 **[Martin Fowler — Is quality worth the cost?](https://martinfowler.com/articles/is-quality-worth-cost.html)**

### Metrics and evals
- 📖 **[OpenAI Cookbook — Evals intro](https://cookbook.openai.com/examples/evaluation/getting_started_with_openai_evals)**
- 📺 **[DeepLearning.AI — AI Python for Beginners](https://www.deeplearning.ai/courses/ai-python-for-beginners/)**

---

## Exercises

**Exercise 1 — Opportunity audit**  
Pick a product you use daily. Identify 3 AI opportunities with clear JTBD and why AI beats non-AI alternatives.

**Exercise 2 — Write a one-page AI PRD**  
Include problem, users, solution sketch, metrics, failure modes, fallback UX, and launch thresholds.

**Exercise 3 — Build/buy/fine-tune memo**  
Write a short recommendation for one use case with justification across control, speed, cost, maintenance.

---

## Exit criteria

- [ ] Explain how AI PM specs differ from standard PM specs
- [ ] Write a practical one-page AI PRD with measurable thresholds
- [ ] Define an acceptable error rate and communicate it clearly
- [ ] Design a feedback loop from real user behavior to system changes
- [ ] Defend a build/buy/fine-tune decision for one concrete product idea

---

**Next: [04 — Prompting & Context Engineering](./04-prompting-and-context.md)**
