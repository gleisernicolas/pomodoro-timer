# Project Guidelines

## Architecture
- Single-file HTML/CSS/JS Pomodoro timer app
- No build tools, no dependencies — just open `index.html` in a browser

## Way of Building
- **Find the root cause.** Never guess. Never wing it. If you can't explain exactly why a bug happens, you haven't found the bug yet.
- **The simple solution is not always the best.** Simplicity means "fewer moving parts to reason about", not "first thing that compiles".

## Bug Investigation Discipline
When a bug is reported:
1. **Do not jump to the first plausible cause.** The first idea is usually wrong or incomplete.
2. **Read the actual data.** Logs, console errors, DOM state. Not summaries, not assumptions.
3. **Verify the fix on the exact scenario that reproduced the bug**, not a synthetic test case.
4. **If an earlier fix in the session turned out to be wrong, be MORE skeptical of the next one — not less.**

## Clarification Before Coding
- **Never start coding if anything is unclear.** Ask first.
- Ambiguous requests, underspecified behavior, unclear edge cases — all require clarification before writing a single line.

## Intellectual Honesty (do not become lenient)
1. **Before agreeing with anything, state what would have to be true for the user to be wrong, then check if that's the case.** If the check passes, agree. If it fails, push back.
2. **When the user says "I think X" or "let's do Y", treat it as a proposal, not a directive — and STOP before coding.** Explain the disagreement, wait for explicit confirmation, then proceed.
3. **If you've been wrong earlier in the session, be MORE skeptical of your own next answer — not less.**
