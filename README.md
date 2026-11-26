# AI Software Engineering Classroom

Your personal AI-software-engineering learning workspace — powered by an adaptive AI mentor.

The goal is **not** to memorize prompts or maximize automation. It is to build reliable engineering systems in which AI helps deliver correct, maintainable, secure, tested, and reviewable software — while you stay responsible for the technical decisions.

---

## Quick Start

New here? Two steps to get going:

**Step 1 — Initialize your classroom**

Type `/init-classroom` in the chat. The mentor will walk you through setting up your profile, entry point, practice repo, and first week plan — all in one guided flow.

**Step 2 — Start and end every session**

Type `/start` to begin each session. When you are done, type `/done` — the mentor will save your progress, update your streak, and prepare a summary for next time.

That is it — come back next session and type `/start` again to keep your momentum going.

---

## Commands

| Command            | Description                                               |
| ------------------ | --------------------------------------------------------- |
| `/init-classroom`  | First-time setup — guided profile, entry point, week plan |
| `/start`           | Begin session — greet + last summary + what's next        |
| `/done`            | End session — update progress files and sign off          |
| `/teach`           | Teach current topic with real example + guiding questions |
| `/teach [topic]`   | Teach a specific topic e.g. `/teach hooks`                |
| `/next`            | Advance to next topic (checks unlock criteria first)      |
| `/exercise`        | Give today's exercise for current topic                   |
| `/check`           | Review and score what I just wrote above                  |
| `/submit-hw`       | Submit homework — mentor reviews and scores it            |
| `/progress`        | Show module progress table and streak                     |
| `/commit`          | Save today's session to git                               |

---

## Folder Structure

```
ai-software-engineering/
├── README.md               ← You are here
├── CLAUDE.md               ← Mentor rules (do not edit)
├── me.md                   ← Your profile — fill this in first!
├── CURRENT.md              ← Session snapshot (auto-updated by mentor)
├── corrections.md          ← Misconceptions the mentor has corrected
│
├── plan/
│   ├── roadmap.md          ← Full learning path with your entry point
│   ├── roadmap-phase1.md   ← Levels 1–2 topic tables
│   ├── roadmap-phase2.md   ← Levels 3–4 topic tables
│   ├── roadmap-phase3.md   ← Levels 5–6 + capstone topic tables
│   ├── this-week.md        ← Your plan for this week
│   └── source-roadmap.md   ← Original mastery roadmap (reference)
│
├── progress/
│   ├── log.md              ← Session-by-session history + evidence
│   ├── streaks.md          ← Streak tracker + milestone badges
│   └── log-archive.md      ← Older sessions (archived here)
│
├── notes/
│   └── journal.md          ← Your post-session reflections
│
├── lectures/               ← Knowledge-only review notes, written after each session
│
├── modules/                ← Learning content by topic
│   ├── 01-ai-fundamentals/             ← Level 1 — LLMs, tokens, context, prompts, agentic behavior
│   ├── 02-claude-code-mastery/         ← Level 2 — CLAUDE.md, rules, skills, agents, hooks, MCP, permissions
│   ├── 03-ai-workflow-engineering/     ← Level 3 — Context architecture, skill design, workflow structure
│   ├── 04-loop-engineering-pstack/     ← Level 4 — Bounded loops, verification, Pstack
│   ├── 05-ai-orchestrated-engineering/ ← Level 5 — Delegation, parallel agents, worktrees, integration
│   ├── 06-ai-engineering-architecture/ ← Level 6 — Harness, specs, evals, observability, security
│   ├── 07-token-context-optimization/  ← Cross-cutting — studied alongside every level
│   └── 08-capstone/                    ← Target operating model + capstone system
│
├── exercises/              ← Scratch space for practice (git-ignored)
├── assessments/            ← Workflow challenges
└── projects/               ← Mini projects and capstone
```

---

## Learning Path

```
Weeks 1–5   → Foundations: how LLM tools behave + Claude Code's building blocks   (Levels 1–2)
Weeks 6–12  → Workflows: context architecture, skills, bounded verification loops (Levels 3–4)
Weeks 13–20 → Systems: orchestration, harness, evaluation, security + capstone    (Levels 5–6)
```

See [plan/roadmap.md](plan/roadmap.md) for the full plan, your adaptive entry point, and what you can skim based on your background. The schedule is a guide, not a deadline — spend more time where practical understanding is weak.

---

## Tips

- 5 sessions per week, 45–60 minutes each — learn → read the docs → demonstrate → apply → review
- Always start with `/start` and end with `/done`
- Every topic ends with a small practical artifact in your practice repo — don't learn only by reading
- "It's done" is not evidence. Show the command output, the diff, or the test result
- Don't skip the journal — 5 bullet points after each session is enough
- If something is confusing, just ask in chat — "อธิบายง่ายๆ หน่อย" works fine
- The mentor teaches in your preferred language (set in `me.md`)

> *Do not aim to become an engineer who asks AI to write code faster. Aim to become an engineer who designs reliable systems in which AI can help deliver software correctly, safely, and repeatedly.*
