# 06 — Evaluation & Evals

> **Goal:** Replace “looks good to me” with a repeatable evaluation practice you can trust.

---

## Why this pillar matters

Most AI product failures happen because teams skip rigorous evaluation.
If you can’t measure quality, you can’t improve it reliably — and you definitely can’t defend it to leadership, legal, or customers.

---

## Core concepts

- Anatomy of an eval (dataset, rubric, scoring, review)
- Scoring methods: exact match, similarity, preference, LLM-as-judge
- Building high-signal eval sets
- Golden datasets and maintenance
- Prompt/model regression testing
- Human review workflows
- Production quality monitoring
- Failure taxonomies by error type

---

## Resources

### Start here
- 📖 **[OpenAI Cookbook — Evals getting started](https://cookbook.openai.com/examples/evaluation/getting_started_with_openai_evals)**
- 📖 **[Anthropic — Evaluate your prompts](https://www.promptfoo.dev/docs/)**
- 📺 **[DeepLearning.AI — Evaluating & Debugging GenAI](https://www.deeplearning.ai/short-courses/evaluating-debugging-generative-ai/)**

### Strong practical perspectives
- 📖 **[Hamel Husain — Your AI Product Needs Evals](https://hamel.dev/blog/posts/evals/)**
- 📺 **[DeepLearning.AI — Advanced RAG evals](https://www.deeplearning.ai/short-courses/building-evaluating-advanced-rag/)**

### Production framing
- 📖 **[Eugene Yan — LLM system patterns](https://eugeneyan.com/writing/llm-patterns/)**

---

## Exercises

**Exercise 1 — Build a 25-case eval set**  
Use your own product/use case. Include expected outputs, rubric, and at least 5 adversarial cases.

**Exercise 2 — LLM-as-judge pass**  
Score outputs with an evaluator model, then manually review 10 items to measure judge reliability.

**Exercise 3 — Regression check**  
Change a prompt/model variable and rerun the full eval suite. Document what shifted and why.

**Exercise 4 — Failure taxonomy table**  
Label 20 outputs by failure type (hallucination, format, instruction miss, tone, etc.).

---

## Exit criteria

- [ ] Maintain a 25-case eval set with clear rubric
- [ ] Run LLM-as-judge and cross-check against human labels
- [ ] Perform regression testing for prompt/model changes
- [ ] Build a failure taxonomy from real outputs
- [ ] Explain golden datasets and a plan to keep them current

---

**Next: [07 — Safety, Privacy & Governance](./07-safety-and-governance.md)**
