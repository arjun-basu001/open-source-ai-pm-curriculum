# 04 — Prompting & Context Engineering

> **Goal:** Build prompts and context pipelines that produce dependable outputs in production — not just nice one-off demos.

---

## Prompting is only part of the story

Great outputs come from full context design: system prompt, user input format, retrieved evidence, examples, schemas, and guardrails.

If you only tweak wording but ignore context architecture, quality won’t hold up in production.

---

## Core concepts

- System prompt design and role boundaries
- Zero-shot vs few-shot trade-offs
- Chain-of-thought implications and reasoning control
- Structured outputs (JSON schemas, function calling)
- Context packing order and truncation strategy
- RAG context interaction with instructions
- Prompt injection patterns and mitigations
- Prompt testing with evals, not gut feel

---

## Resources

### Core guides
- 📖 **[Anthropic — Prompt engineering overview](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview)**
- 📖 **[OpenAI — Prompt engineering guide](https://platform.openai.com/docs/guides/prompt-engineering)**
- 📺 **[DeepLearning.AI — Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)**

### Advanced methods
- 📖 **[Anthropic — Extended thinking](https://docs.anthropic.com/en/docs/build-with-claude/extended-thinking)**
- 📺 **[DeepLearning.AI — Building Systems with ChatGPT](https://www.deeplearning.ai/short-courses/building-systems-with-chatgpt/)**
- 📖 **[OpenAI Cookbook — Structured outputs](https://cookbook.openai.com/examples/structured_outputs_intro)**

### Security and reliability
- 📖 **[Simon Willison — Prompt injection explained](https://simonwillison.net/tags/prompt-injection/)**

---

## Exercises

**Exercise 1 — System prompt rewrite**  
Pick an existing assistant use case. Write your own system prompt and test behavior changes.

**Exercise 2 — Structured extraction flow**  
Convert messy input into strict JSON with schema validation. Test on 10 varied examples.

**Exercise 3 — Few-shot experiment**  
Run a classification task zero-shot, 3-shot, and 10-shot. Compare accuracy and failure style.

**Exercise 4 — Adversarial test**  
Try to break your prompt with injection attempts. Note what failed and what hardening you added.

---

## Exit criteria

- [ ] Produce a strong system prompt for one scoped use case
- [ ] Return stable, schema-valid JSON across diverse inputs
- [ ] Explain when few-shot helps (and when it backfires)
- [ ] Identify prompt injection risks and apply baseline mitigation
- [ ] Run and document an A/B prompt comparison with eval results

---

**Next: [05 — Building with Tools & Frameworks](./05-building-with-tools.md)**
