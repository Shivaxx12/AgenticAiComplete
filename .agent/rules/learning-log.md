---
trigger: always_on
---

# RULE: Learning Log

Goal: turn every doubt or lesson into a permanent record of what I asked,
what I misunderstood (if anything), and what is actually true, so I can
revise later.

## When to log
Log any exchange where I learned something I did not already know or had
wrong. This includes, but is not limited to:
- "Where did this part of the code come from?" / "What does this line do?"
- "Why is it done this way?" / "Why did this error happen?"
- Concept explanations, comparisons (X vs Y), and "how does this work inside".
- Corrections to a wrong or partial belief of mine.
- Check-my-understanding rounds, once graded and explained.
- Anything I mark with "log this".

Do NOT log: trivial lookups, small talk, pure yes/no confirmations, or
topics already logged. For a topic already logged, append a short
"Revisited" entry (new entry at the bottom, referencing the earlier date)
instead of editing the old one.

Timing: log after the explanation is complete. Add the entry automatically
and end your reply with one line:
"Logged to notes/learning-log.md: <topic>".
If I say "don't log" or "skip", do not log that exchange.

## Where
- Append ONLY to `notes/learning-log.md` (create it if missing). Never edit or
  delete earlier entries, and never touch any other file.
- Add each new entry at the bottom. Keep entries concise but complete.

## Entry format
Every entry starts with this header and these two fields:

### [YYYY-MM-DD] Topic: <specific concept> (<LangGraph | RAG | Guardrails | ...>)

**What I asked / assumed:** my question and any assumption I had, as I stated it.
**What it actually is:** the explanation, including where the code or concept
comes from (library, module, default behaviour, convention).

Then add ONLY the sections that apply:

**What I answered vs. reality** (only after a Check-my-understanding round)
| # | My answer (as I gave it) | Verdict | What was actually right and why |
|---|--------------------------|---------|---------------------------------|
Verdict is one of: Correct / Right answer, wrong reasoning / Partially correct / Wrong.

**The misunderstanding:** the underlying wrong mental model, in one or two
sentences (not just the wrong answer). Skip if I had none.

**Correct mental model:** the accurate concept in plain language, plus a small
snippet or diagram if it helps.

**Rules to remember:**
- [ ] short, testable rule
- [ ] short, testable rule

**Gotchas / edge cases:** bullets.

**Try yourself:** one experiment to run in the scratch folder.

**Status:** Needs revision | Understood | Mastered

## Honesty rules
- Record my answers exactly as I gave them. Never rewrite them to look better.
- If my reasoning was wrong even though the answer was right, say so explicitly.
- Note the library version if the lesson is version-specific.