# 07 — Safety, Privacy & Governance

> **Goal:** Learn to ship responsibly by turning AI risks into explicit design, policy, and rollout decisions.

---

## Why this work is core product work

Safety and governance are not legal side quests.
They directly affect launch readiness, user trust, and long-term viability.

If your system can hallucinate, leak sensitive information, or mishandle copyrighted content, those are product risks — and you own them.

---

## Core concepts

- Hallucination risk types and practical mitigations
- Prompt injection and data exfiltration paths
- PII and privacy risk in prompts, logs, and retrieval stores
- Copyright and output ownership uncertainty
- Bias and fairness in decision-support products
- EU AI Act risk tiers and relevance to product teams
- NIST AI RMF as an operational framework
- Transparency patterns (disclosure, provenance, guardrails)
- Staged release + human-in-the-loop controls

---

## Resources

### Safety basics
- 📖 **[Anthropic — Reduce hallucinations](https://docs.anthropic.com/en/docs/test-and-evaluate/strengthen-guardrails/reduce-hallucinations)**
- 📖 **[OpenAI — Safety best practices](https://platform.openai.com/docs/guides/safety-best-practices)**
- 📺 **[DeepLearning.AI — Red Teaming LLM Applications](https://www.deeplearning.ai/short-courses/red-teaming-llm-applications/)**

### Regulation and copyright
- 📖 **[EU AI Act overview](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai)**
- 📖 **[UK Government — AI & copyright consultation](https://www.gov.uk/government/publications/ai-regulation-a-pro-innovation-approach)**
- 📖 **[Alan Turing Institute — Copyright and AI](https://www.wipo.int/about-ip/en/frontier_technologies/ai_and_ip.html)**

### Risk frameworks and privacy
- 📖 **[NIST AI RMF](https://www.nist.gov/itl/ai-risk-management-framework)**
- 📖 **[OECD AI Principles](https://oecd.ai/en/ai-principles)**
- 📖 **[CNIL — AI and GDPR](https://gdpr.eu/)**

---

## Exercises

**Exercise 1 — Red-team sprint (60 mins)**  
Try to break your own prototype: hallucination, prompt leakage, policy bypass, biased outputs. Keep a failure log.

**Exercise 2 — Risk register**  
Create a 5-row register with:
- risk type,
- likelihood,
- impact,
- mitigation,
- residual risk.

Include: hallucination, injection, PII leakage, copyright exposure, and bias.

**Exercise 3 — Copyright position memo**  
Write one internal paragraph for a product that summarizes third-party docs. Clarify data handling, derivative-work risk, and user disclosure.

**Exercise 4 — NIST mapping**  
Map one feature to Govern, Map, Measure, Manage. Note what’s already covered vs missing.

---

## Exit criteria

- [ ] Identify at least five major AI product risks and mitigations
- [ ] Demonstrate a baseline defense against prompt injection
- [ ] Explain high-risk system implications under the EU AI Act
- [ ] Write a practical internal copyright/IP position note
- [ ] Produce a complete risk register for one product scenario

---

**Next: [08 — Deployment & Ops](./08-deployment-and-ops.md)**
