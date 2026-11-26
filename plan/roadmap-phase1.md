# Roadmap — Phase 1 (Foundations: Levels 1–2)
> Weeks 1–5 | Goal: Understand how LLM-based tools behave, and learn Claude Code's building blocks well enough to choose between them

---

## Level 1: AI Fundamentals (Weeks 1–2)
> Goal: Understand how LLM-based tools behave and what is required to give them reliable work

| # | Topic | Status | Score | Completed |
|---|-------|--------|-------|-----------|
| M01 | LLMs — capabilities & limitations | 🔒 | — | — |
| M01 | Tokens & tokenization | 🔒 | — | — |
| M01 | Input, output, cached input & the context window | 🔒 | — | — |
| M01 | Context window vs persistent project knowledge | 🔒 | — | — |
| M01 | Prompt engineering vs context engineering | 🔒 | — | — |
| M01 | System instructions & instruction hierarchy | 🔒 | — | — |
| M01 | Tool calling & tool-use cycles | 🔒 | — | — |
| M01 | Agentic AI — chat vs action-oriented workflows | 🔒 | — | — |
| M01 | Hallucinations, uncertainty & verification | 🔒 | — | — |
| M01 | Prompt injection & untrusted input (concepts) | 🔒 | — | — |
| M07 | Token economics — input, output & cached tokens *(cross-cutting)* | 🔒 | — | — |

**Level 1 Milestone:** Give Claude Code the same task three ways — minimal instructions, useful context, context plus acceptance criteria. Compare correctness, unnecessary file changes, test quality, and rework. Then explain why context matters, what information was missing, and why the output still had to be verified.

> **Why fundamentals first?** Every later technique — skills, loops, subagents, evals — is a way of managing the same three things: what the model sees (context), what it may do (tools), and how you know it is right (verification). Without that mental model, the features of Level 2 look like a list of interchangeable Markdown files.

---

## Level 2: Claude Code Mastery (Weeks 3–5)
> Goal: Understand Claude Code's capabilities, configuration model, execution boundaries, and reusable building blocks

| # | Topic | Status | Score | Completed |
|---|-------|--------|-------|-----------|
| M02 | Claude Code operating model & sessions | 🔒 | — | — |
| M02 | `CLAUDE.md` & instruction loading | 🔒 | — | — |
| M02 | `.claude/rules/` & scoped rules | 🔒 | — | — |
| M02 | Skills & progressive disclosure | 🔒 | — | — |
| M02 | Slash commands — skills vs legacy custom commands | 🔒 | — | — |
| M02 | Agents & subagents | 🔒 | — | — |
| M02 | Hooks — event-driven deterministic automation | 🔒 | — | — |
| M02 | MCP servers & external tool integration | 🔒 | — | — |
| M02 | Plugins & capability packaging | 🔒 | — | — |
| M02 | Permissions, tool approvals & safe execution | 🔒 | — | — |
| M02 | Built-in tools, terminal workflows & Git integration | 🔒 | — | — |
| M02 | Session continuity, compaction & resuming work | 🔒 | — | — |
| M02 | Settings — project vs user configuration | 🔒 | — | — |
| M02 | Choosing the right mechanism | 🔒 | — | — |
| M07 | Targeted exploration & output filtering *(cross-cutting)* | 🔒 | — | — |

**Level 2 Milestone:** In your practice repo, build a lean setup: a minimal `CLAUDE.md`, one scoped rule, three skills (requirement-analysis, implementation-planning, verify-feature), two read-only subagents (e.g. architecture-researcher, code-reviewer), and one useful hook. For each piece, explain why that mechanism and not another — its loading behavior, scope, risks, and maintenance cost.

> **Why "choosing" is the skill:** CLAUDE.md, rules, skills, commands, and agents can all contain Markdown instructions, but they load at different times, cost different amounts of context, and fail in different ways. Putting the right content in the wrong mechanism is the most common Claude Code mistake.

**Phase 1 Project:** Write a one-page decision note for your practice repo: what goes in `CLAUDE.md`, what became a rule, a skill, a subagent, or a hook, and what you decided **not** to add — with the reason for each.
