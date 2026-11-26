# Learning Roadmap
> Adaptive 20-week path from AI coding-tool user to AI software engineer
> Mentor generates or adjusts this after reading `me.md`
> Source reference: [source-roadmap.md](source-roadmap.md) (AI Software Engineering Mastery Roadmap v1.0)

---

## Before You Start — Self-Assessment

Answer these five questions so the mentor can find your entry point:

1. Can you explain what a context window is, and why more context is not automatically better?
2. Do you write acceptance criteria before asking an AI to implement something — and verify the result independently?
3. Have you configured Claude Code beyond the defaults (CLAUDE.md, rules, skills, subagents, hooks, MCP, permissions)?
4. Have you built a workflow where the AI verifies its own work in a bounded loop and stops or escalates when blocked?
5. Have you coordinated several agents on one task, or measured an AI workflow with numbers (success rate, rework, cost)?

> Type your answers in the chat. The mentor will mark which levels to **skim** or **go deep** on.

### Prerequisite Check
> This roadmap assumes you already work as a software engineer. It does not reteach programming.

Before Level 1, make sure you can do these in a project of your own:
- Create a branch, commit, and read a diff with git
- Run the project's tests, linter, and build from the terminal
- Install Claude Code and start a session in a repository

You also need a **practice repo** — a project where you can freely create branches and config files (ideally a small full-stack app with tests). If you don't have one, ask the mentor to help you pick or scaffold one before starting. This is a prerequisite, not a module.

---

## Adaptive Entry Points

| Your Background | L1 | L2 | L3 | L4 | L5 | L6 |
|---|---|---|---|---|---|---|
| New to AI coding tools | Full | Full | Full | Full | Full | Full |
| Uses AI chat / autocomplete, new to Claude Code | Full | Full | Full | Full | Full | Full |
| Daily Claude Code user, default configuration | Skim | Full | Full | Full | Full | Full |
| Power user — already writes skills, hooks, subagents | Skim | Skim | Full | Full | Full | Full |
| Tech lead rolling AI workflows out to a team | Skim | Skim | Full | Full | Full | Deep² |

> **Skim** — move fast, you know most of this already. Still do the level milestone with evidence; nobody skips a milestone.
> **Full** — go deep, this is foundational for you.
> ² **Deep** — spend extra time on evaluation, governance, and team policy; they decide whether a rollout survives.

---

## Overview Timeline

```
Level 1  Weeks  1–2   AI Fundamentals             LLMs, tokens, context, prompts, agentic behavior
Level 2  Weeks  3–5   Claude Code Mastery         Use Claude Code's core capabilities deliberately
Level 3  Weeks  6–8   AI Workflow Engineering     Project context, reusable workflows, structure
Level 4  Weeks  9–12  Loop Engineering & Pstack   Bounded implementation and verification loops
Level 5  Weeks 13–16  AI-Orchestrated Engineering Delegate and coordinate specialized agents safely
Level 6  Weeks 17–20  AI Engineering Architecture Build, evaluate, secure, and improve a complete system
Capstone End          AI Software Engineering System — requirement to QA handoff
```

Token & context optimization (Module 07) is studied **throughout**, one topic per level — not at the end.

The schedule is a guide, not a deadline. Spend more time where practical understanding is weak.

---

## Weekly Routine

5 sessions per week, 45–60 minutes each, in addition to normal project work.

| Session | Activity |
|---------|----------|
| Day 1 | Learn the concept and mental model |
| Day 2 | Inspect official documentation and examples |
| Day 3 | Demonstrate the concept in a small task |
| Day 4 | Apply it to a real project workflow |
| Day 5 | Review, assess, record learning, and plan next week |

Every topic produces a small practical artifact: a configuration, skill, workflow, test, diagram, evaluation, or written decision.

---

## Key Milestones Summary

| Milestone | Target Week | Status |
|-----------|-------------|--------|
| Explain why context matters, spot missing information, write clear acceptance criteria, and explain why AI output must be verified | Week 2 | 🔒 |
| Choose the correct Claude Code mechanism for a use case and explain its loading behavior, scope, risks, and maintenance cost | Week 5 | 🔒 |
| Design a small, understandable, low-maintenance AI workflow structure that provides the right context at the right time | Week 8 | 🔒 |
| Build a repeatable, bounded workflow that plans, implements, observes, corrects, verifies, and reports with evidence | Week 12 | 🔒 |
| Decide when multiple agents add value, define safe boundaries, coordinate work, and integrate results with independent verification | Week 16 | 🔒 |
| Design and evaluate an AI engineering workflow using evidence, security controls, operational feedback, and measurable quality criteria | Week 20 | 🔒 |
| Capstone: an AI Software Engineering System that takes a full-stack feature from written requirement to QA handoff | End | 🔒 |

> Full level details: [Phase 1 — Levels 1–2](roadmap-phase1.md) | [Phase 2 — Levels 3–4](roadmap-phase2.md) | [Phase 3 — Levels 5–6 + Capstone](roadmap-phase3.md)

---

## Definition of Mastery

You are progressing toward mastery when you can:

- Explain how context, instructions, tools, skills, agents, and verification work together
- Design a lean Claude Code project structure
- Build reusable skills and bounded agent roles
- Choose single-agent, subagent, or multi-agent execution based on task dependencies
- Create reliable implementation and verification loops
- Preserve state and recover from interruptions
- Verify output using tests and independent evidence
- Protect the repository and external systems with appropriate permissions
- Measure quality, rework, latency, and cost
- Improve workflows based on observed failures
- Explain the trade-offs and teach the system to another engineer

---

## Official Resources

Prefer current official documentation for version-sensitive product behavior.

- Claude Code documentation: https://code.claude.com/docs/en/overview
- Claude Code best practices: https://code.claude.com/docs/en/best-practices
- Claude Code subagents: https://code.claude.com/docs/en/sub-agents
- Claude Code skills: https://code.claude.com/docs/en/skills
- Model Context Protocol: https://modelcontextprotocol.io/docs/getting-started/intro
- GitHub Actions: https://docs.github.com/en/actions

Also study engineering material on specification-driven development, test-driven development, harness engineering, agent evaluation, observability, secure tool execution, and Git worktrees.

---

## Current Focus
> Updated by mentor after each session

**Active Module:** Not started — waiting for first session
**Current Week Goal:** —
**Next Milestone:** Week 2 — Explain why context matters, write clear acceptance criteria, and explain why AI output must be verified
