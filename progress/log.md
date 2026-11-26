# Session Log
> Last Updated: 2026-11-26
> Total Sessions: 1
> Current Streak: 1 day

---

## Current Status

| Field | Value |
|-------|-------|
| **Current Module** | 01 — AI Fundamentals (in progress) |
| **Current Level** | Level 1 — AI Fundamentals |
| **Overall Progress** | 1 / 10 L1 topics (Week 1 of 20) |
| **Next Topic** | 1.2 Tokens & tokenization |

---

## Level 1: AI Fundamentals

| Topic | Status | Score | Date | Evidence / Notes |
|-------|--------|-------|------|------------------|
| LLMs — capabilities & limitations | ✅ | Pass | 2026-11-26 | Trust-map artifact committed in practice repo; teach-back on independent oracle vs mutation check |
| Tokens & tokenization | ⏭️ Next | — | — | — |
| Input, output, cached input & the context window | 🔒 | — | — | — |
| Context window vs persistent project knowledge | 🔒 | — | — | — |
| Prompt engineering vs context engineering | 🔒 | — | — | — |
| System instructions & instruction hierarchy | 🔒 | — | — | — |
| Tool calling & tool-use cycles | 🔒 | — | — | — |
| Agentic AI — chat vs action-oriented workflows | 🔒 | — | — | — |
| Hallucinations, uncertainty & verification | 🔒 | — | — | — |
| Prompt injection & untrusted input (concepts) | 🔒 | — | — | — |

> Levels 2–6 + Capstone: 🔒 Locked — complete the current level first. See `plan/roadmap.md` for the full plan.

---

## Session History

| # | Date | Topic | Outcome | Score | Evidence / Notes |
|---|------|-------|---------|-------|------------------|
| 1 | 2026-11-26 | Setup + 1.1 LLM capabilities & limitations | Pass | — | Both test suites green from student's terminal; deliberate code defect caught on both sides; trust map committed |

---

## Homework Log

| Week | Homework | Status | Feedback |
|------|----------|--------|----------|
| 1 | Revisit real-work trust-map row after next AI-assisted UI task | Assigned | — |

---

## Skills Gained

### Concepts Understood
- Fluency ≠ correctness; out-of-context facts are guessed (1.1)
- Independent oracle vs mutation check — both needed for AI-written tests (1.1)

### Claude Code Mechanisms Practiced
*(none yet)*

### Artifacts Built (configs, skills, hooks, workflows, evals)
- Practice repo skeleton: Next.js + Vitest, Go + Gin, one real test each (2026-11-26)
- Trust map — verification tier per task type (2026-11-26)

---

## Areas Needing Review
- Gives answers / "done" without reasons or evidence — needs prompting for the "why"
- First mutation attempt broke the test, not the code — corrected
- Prompt-writing relied on mentor's example; acceptance criteria not yet written unaided
- Real-work self-assessment ("nothing changed") left unexplained

---

## 2026-11-26
- Topic: Setup + 1.1 LLM capabilities & limitations
- Covered: Practice repo scaffold via Claude Code with a spec-style prompt (goal, contract, acceptance criteria, out-of-scope, process); agent self-check vs independent re-run; break-the-code vs break-the-test; next-token model, context gaps, training cutoff, probabilistic output; A/B/C verification tiers; independent-oracle rule
- Outcome: pass
- Evidence: go test and vitest output pasted from student's terminal; failure output after a deliberate defect in production code (both sides); trust map committed; teach-back identified that human-owned expected values (not mutation) catch a shared spec misreading
- Next: 1.2 Tokens (skim); review real-work trust-map row
