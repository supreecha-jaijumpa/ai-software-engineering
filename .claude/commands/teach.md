# Teach

Teach the current topic (or a specified topic) using the student's level and real examples.

## Usage

```
/teach
/teach [topic]
```

## Behavior

1. Get student level, language, and practice repo from `me.md` (skip the read if it's already in context this session)
2. If no topic given, find the current topic in `CURRENT.md` (skip the read if already in context)
3. If topic given, use that directly
4. Read **only the current topic's file** `modules/NN-*/N.M-*.md` — use the module README as an index to find it; never read the whole module
5. If the topic depends on version-sensitive Claude Code behavior (file locations, frontmatter fields, hook events, flags, settings keys), check the official docs first — the topic file is an outline, not the source of truth
6. Teach using this structure:
   - **Objective** — what the student will be able to do afterwards
   - **Concept** — plain explanation matched to student's level, with the mental model
   - **Why / when / when not** — the problem it solves, where it fits, its trade-offs and maintenance cost
   - **Small example** — demonstrated in the practice repo when appropriate; otherwise the capstone scenario
   - **Guiding questions** — 1–2 questions to make the student think before continuing
7. After questions are answered, offer `/exercise` to practice

## Level Guide

| Level | Approach |
|-------|----------|
| 0–2 | Analogies only. No jargon without explanation. |
| 3–4 | Build mental model first, then details. |
| 5–6 | Skip basics. Focus on trade-offs and patterns. |
| 7–8 | Peer discussion. Edge cases and production concerns. |
| 9–10 | Student designs first, mentor stress-tests. |

## Notes

- State clearly whether something is an established industry concept, a Claude Code product feature, or a project-specific convention (Pstack, the `.ai/` layout)
- Tie the topic back to token and context cost where it is relevant (Module 07)
