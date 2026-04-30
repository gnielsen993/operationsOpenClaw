# Close Session Workflow (Trigger Mode)

Use when Gabe says "close session" or asks to save context before starting fresh.

---

Goal:
- shrink working context before the next session
- keep durable information
- drop obvious noise
- reduce token usage going forward

Steps:
1. Review the current active thread and identify:
   - durable facts/decisions
   - short-term active work
   - disposable chatter
2. Promote durable items to the right long-term home:
   - `MEMORY.md` for lasting decisions and stable context
   - `memory/YYYY-MM-DD.md` for fresh session notes
   - project notes / decision logs when relevant
3. Keep short-term items only if they still matter for the next session.
4. Drop the rest.
5. End with a concise handoff:
   - what was kept
   - what was trimmed
   - the best next action

Rules:
- do not dump transcript history
- prefer concise, actionable notes
- treat this as the pre-`/new` cleanup path
- if `/new` is unreliable, this workflow still stands on its own

Output format:
- Kept
- Trimmed
- Dropped
- Next step