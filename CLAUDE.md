# Commit message convention

This repo has no ticket system, so commit messages do **not** use a ticket-ID prefix.

- Subject line: an imperative-present sentence, capitalized, no trailing period, no type prefix (no `feat:`, `fix:`, `chore:`, etc.).
  - Good: `Add mobile hamburger nav`
  - Bad: `feat: added mobile nav`, `MOB-12 Add mobile nav`
- Keep the subject to one line. If the change needs more explanation (why, not just what), add it as a blank-line-separated body — plain prose paragraphs, no bullet-point template required.
- One logical change per commit where practical; don't bundle unrelated fixes into one commit.
