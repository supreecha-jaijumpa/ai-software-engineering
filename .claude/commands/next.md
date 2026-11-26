# Next Topic

Advance to the next topic in the current module.

## Usage

```
/next
```

## Behavior

1. Read `CURRENT.md` — get current module, topic, and unlock status
2. Check unlock criteria: exercise passed with evidence + teach-back given + reflection submitted
3. If criteria met:
   - Mark current topic ✅ Done in `CURRENT.md`
   - Set next topic as 📖 In Progress
   - Update `CURRENT.md` with new current topic and next action
   - Briefly introduce the next topic (2–3 sentences)
4. If criteria not met:
   - List what's still missing (exercise / evidence / teach-back / reflection)
   - Do not advance

## Unlock Criteria

Student must complete all three before advancing:
- Pass the topic exercise (`/check` returns Pass) **with observable evidence** — not a completion claim
- Give a short teach-back: explain the concept, when to use it, and when not to
- Submit a brief reflection (even 2–3 sentences counts)

## Notes

- Never skip topics silently — always state what was unlocked and what comes next
- Do not skip ahead automatically, even if the student seems strong — confirm with practical work or a teach-back first
- If the student is at the end of a module, check the module milestone, then announce module completion and show the next level
- Module 07 (token & context optimization) is cross-cutting: its topics are scheduled inside the level tables in `plan/roadmap-phase*.md`, not after Level 6
