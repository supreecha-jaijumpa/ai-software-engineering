# Module 01: AI Fundamentals

> Status: 🔒 Locked (Session 1 will unlock this)
> Estimated Time: 2 weeks (Weeks 1–2)
> Level: 1
> Fast Track: If you use Claude Code daily, skim — but still do topics 1.5, 1.9, and the milestone comparison. They are the vocabulary for everything later.

---

## Learning Objectives
After completing this module you will be able to:
- [ ] Explain what an LLM can and cannot be relied on for
- [ ] Reason about tokens, the context window, and cached input when a session gets slow, expensive, or forgetful
- [ ] Tell prompt engineering, context engineering, and verification apart
- [ ] Describe the tool-use cycle and what makes a workflow "agentic"
- [ ] Identify missing information and unsupported assumptions in a task or an AI answer
- [ ] Write clear acceptance criteria and explain why AI output must be verified

---

## Topics

- [1.1 LLMs — Capabilities & Limitations](1.1-llm-capabilities-and-limitations.md)
- [1.2 Tokens & Tokenization](1.2-tokens-and-tokenization.md)
- [1.3 Input, Output, Cached Input & the Context Window](1.3-input-output-cached-and-context-window.md)
- [1.4 Context Window vs Persistent Project Knowledge](1.4-context-window-vs-persistent-knowledge.md)
- [1.5 Prompt Engineering vs Context Engineering](1.5-prompt-vs-context-engineering.md)
- [1.6 System Instructions & Instruction Hierarchy](1.6-system-instructions-and-hierarchy.md)
- [1.7 Tool Calling & Tool-Use Cycles](1.7-tool-calling-and-tool-use-cycles.md)
- [1.8 Agentic AI — Chat vs Action-Oriented Workflows](1.8-agentic-ai-chat-vs-action.md)
- [1.9 Hallucinations, Uncertainty & Verification](1.9-hallucinations-uncertainty-verification.md)
- [1.10 Prompt Injection & Untrusted Input (Concepts)](1.10-prompt-injection-untrusted-input.md)

Cross-cutting, scheduled with this level: [7.1 Token Economics](../07-token-context-optimization/7.1-token-economics.md)

---

## Exercises
*(Unlocks as each topic is covered)*

- [ ] Exercise 1.1: Give Claude Code the same task three ways — minimal instructions, useful context, and context plus acceptance criteria.
- [ ] Exercise 1.2: Compare the three runs on correctness, unnecessary file changes, test quality, and required rework.
- [ ] Exercise 1.3: Before an implementation, ask the model to identify its uncertainty and the missing requirements — then judge which of its questions actually mattered.
- [ ] Exercise 1.4: Inspect an AI-generated answer and mark every unsupported assumption.

---

## Module Assessment
- Pass when: all exercises done with evidence + teach-back of the three mental models (prompt engineering, context engineering, verification)
- Milestone: You can explain why context matters, identify missing information, write clear acceptance criteria, and explain why AI output must be verified.
- Unlocks: Level 2 (Claude Code Mastery)
