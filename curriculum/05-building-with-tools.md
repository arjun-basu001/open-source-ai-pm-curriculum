# 05 — Building with Tools & Frameworks

> **Goal:** Build AI applications that are testable, explainable, and useful in the real world.

---

## Core concepts

- LangChain vs LlamaIndex: practical fit by use case
- RAG implementation lifecycle (index → retrieve → generate)
- Function calling and tool orchestration
- Memory strategies (session, long-term, episodic)
- Agent patterns (ReAct, planner-executor, multi-agent)
- Framework abstractions vs raw API control
- Eval-first building
- Local prototype vs deployed prototype considerations

---

## Resources

### Framework docs
- 📖 **[LangChain docs](https://python.langchain.com/docs/introduction/)**
- 📖 **[LlamaIndex starter](https://docs.llamaindex.ai/en/stable/getting_started/starter_example/)**
- 📖 **[Microsoft — AI Agents for Beginners](https://github.com/microsoft/ai-agents-for-beginners)**

### Hands-on courses
- 📺 **[DeepLearning.AI — LangChain for LLM Apps](https://www.deeplearning.ai/short-courses/langchain-for-llm-application-development/)**
- 📺 **[DeepLearning.AI — Agentic RAG with LlamaIndex](https://www.deeplearning.ai/short-courses/building-agentic-rag-with-llamaindex/)**
- 📺 **[Hugging Face — Agents Course](https://huggingface.co/learn/agents-course)**

### API-level references
- 📖 **[OpenAI Cookbook](https://cookbook.openai.com/)**
- 📖 **[Anthropic API docs](https://docs.anthropic.com/en/api/getting-started)**

---

## Exercises

**Exercise 1 — RAG prototype**  
Build a doc-chat assistant that always cites sources and can explicitly say “I don’t know” when evidence is weak.

**Exercise 2 — Tool-using workflow**  
Build an agent/workflow that can search web info, read a file, and write a summary report.

**Exercise 3 — Raw API vs framework**  
Implement the same mini use case twice (raw API + framework). Compare control, speed, complexity, and debugging effort.

---

## Exit criteria

- [ ] Build and demo a working RAG app with citations
- [ ] Build a tool-using workflow with at least 2 tools
- [ ] Explain framework trade-offs with concrete examples
- [ ] Identify when agentic design is unnecessary overhead
- [ ] Publish a reproducible build note another person can follow

---

**Next: [06 — Evaluation & Evals](./06-evaluation-and-evals.md)**
