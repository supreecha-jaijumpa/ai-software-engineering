# Init Classroom

Set up the student profile by asking questions and filling in `me.md` and `CURRENT.md`.

## Usage

```
/init-classroom
```

## Behavior

Walk the student through a guided intake interview. Ask each group of questions conversationally — do **not** dump all questions at once. Wait for the answer before moving to the next group.

### Step 1 — Role & Goal
Ask:
1. "What is your current job/role and main programming language/stack?" *(maps to Current Role, Main stack, Strong in)*
2. "How many years have you been writing software?"
3. "What is your goal with AI-assisted engineering — what do you want to be able to do, and by when?"
4. "Which language do you prefer for our sessions? (e.g. English, Thai, etc.)"

### Step 2 — AI Tooling Today
Ask:
5. "Which AI coding tools do you use today, and how? (chat only, daily coding, custom skills/hooks/agents)"
6. "Which repository can we use for practice? It should be one where you can freely create branches and config files."
7. "What feels weakest right now? (e.g. getting reliable output, context management, verification, multi-agent work, security)"

### Step 3 — Self-Assessment
Tell the student: *"I'll ask you to rate yourself from 0 (zero knowledge) to 10 (expert) in each area. Be honest — these scores just help me calibrate the teaching pace."*

Ask scores one by one (or as a grouped list):
- Software Engineering Fluency (code, tests, git)
- LLM Fundamentals (tokens, context, prompting)
- Claude Code Features (CLAUDE.md, skills, hooks, MCP, permissions)
- Context & Workflow Design
- Verification Loops & Testing
- Multi-agent Orchestration
- Evaluation, Security & Governance

### Step 4 — Learning Style
Ask:
8. "How do you learn best? (e.g. hands-on, reading docs, diagrams, exercises)"
9. "How many sessions per week can you commit to? (the roadmap assumes 5 × 45–60 minutes)"
10. "What apps or codebases do you know well? (used as examples to reason about)"

### Step 5 — Motivation
Ask:
11. "In 2–3 sentences, why do you want to master AI-assisted software engineering?"
12. "Anything else I should know? (work constraints, tool or data restrictions at work, learning blockers, etc.)"

### Step 6 — Write & Confirm
1. Fill in `me.md` with all collected answers.
2. Read `plan/roadmap.md` — use the entry point table to determine the student's starting point based on their self-assessment scores.
3. Initialize `CURRENT.md` with the starting level/module and set **Next Action** accordingly.
4. Show a brief summary of the completed profile and ask: *"Does this look right? Want to change anything?"*
5. After confirmation, say: *"You're all set. Type /start to begin your first session."*

## Notes
- Never fill in placeholder values — only write answers the student actually gave.
- If a student skips a question, leave the `*(fill in)*` placeholder in `me.md`.
- Preferred language must be set before teaching begins — if skipped, default to English and note it.
- If there is no practice repo yet, note it — the first homework is to pick or create one.
- Keep the tone friendly and low-pressure; this is an intake, not a quiz.
