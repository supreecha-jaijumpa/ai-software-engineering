# Git Commit Skill

Create well-formatted git commits for a learning journal.

## Usage

```
/commit
```

## Behavior

1. Analyze staged changes with `git diff --staged`
2. Infer the type from file paths:
   - `modules/` → `study`
   - `progress/` or `notes/` → `reflect`
   - `me.md`, `plan/`, config files → `setup`
3. Write the message in **past simple tense** with today's date

## Commit Format

```
<type>(<module>): YYYY-MM-DD — <past-simple description>

[optional body — bullet points, past tense]
```

## Types

| Type | When to use |
|------|-------------|
| `study` | Read, watched, or discussed a concept |
| `hw` | Submitted or revised homework |
| `vocab` | Added new terms or glossary entries |
| `notes` | Wrote or updated study notes / summaries |
| `setup` | Installed tools, configured environment |
| `fix` | Corrected a misconception or wrong note |
| `reflect` | Wrote a retrospective or journal entry |

## Example Output

```
study(02-claude-code-mastery): 2026-12-08 — understood how hooks enforce what instructions only suggest

- Read module 2.7 and added a post-edit formatting hook to the practice repo
- Noted the difference: a CLAUDE.md rule is advice, a hook always runs
```
