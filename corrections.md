# Misconceptions & Corrections

> AI tooling is easy to misunderstand — features look interchangeable and confident output looks correct. This file tracks your misconceptions so you don't repeat the same mistake twice.
> Mentor adds entries here during sessions. Review this before each new module.

---

## Format

> ❌ Wrong: *what you thought*
> ✅ Right: *the correct understanding*
> 💡 Why: *explanation + when it matters*

---

## Your Corrections

### 2026-11-26 — Verifying AI-written tests
> ❌ Wrong: AI-written tests are fine if I read them and they pass with the type check.
> ✅ Right: Tests written against existing code pass by construction. Check sensitivity (break the *code*, watch the test fail) **and** correctness (expected values come from the spec / a human, decided before reading the AI's version).
> 💡 Why: A shared misreading of the spec lives in both code and test — only an independent oracle catches it.

### 2026-11-26 — "Watch the test fail"
> ❌ Wrong: Inverting the assertion to make the test fail proves the test works.
> ✅ Right: Break the production code; the test must catch the defect.
> 💡 Why: Breaking the test proves it runs, not that it detects bugs.

### 2026-11-26 — Who runs the tests
> ❌ Wrong: Either the agent runs the tests or I do.
> ✅ Right: Both — the agent runs them to self-correct; I re-run them as the evidence.
> 💡 Why: An agent's "all tests pass" is a claim, not proof.
