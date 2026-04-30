# Workflow Catalog

## Scheduled workflows

### Daily Morning Controller
- Schedule: 8:15 AM America/Denver
- Output: Top 3 priorities, Ignore today, Work order, Start now, Main risk
- Purpose: turn current context into a focused day

### End-of-Day Review
- Schedule: 10:00 PM America/Denver
- Output: Moved the needle, Low-value work, Unresolved, Start tomorrow with, Pattern to watch
- Purpose: preserve real progress and sharpen tomorrow

### Weekly Memory Compaction
- Schedule: Sunday 8:30 PM America/Denver
- Purpose: compact private OpenClaw memory and produce a human weekly summary

## Trigger/manual workflows

### Build Execution Agent
Trigger examples:
- "build mode"
- "time to build"
- "how do we ship this feature fast"
- "break this into coding steps"

Output:
- MVP definition
- What to cut from v1
- Atomic 30–60 minute implementation steps
- Biggest technical risk
- Exact first step

### Build From Notes
Trigger examples:
- "use my notes"
- "gather my notes"
- "build from notes"

Purpose:
- Convert rough notes into build-ready requirements
- Force missing clarification before implementation planning

### Momentum Agent
Trigger examples:
- "I'm stuck"
- "help me start"
- "momentum"
- "I keep avoiding this"

Output:
- Likely issue
- Next 10-minute step
- Step after that
- What to ignore for now

### Strategic Critic
Trigger examples:
- "critique this"
- "tear this apart"
- "is this worth building"

Output:
- Core weakness
- Underestimated factors
- Unnecessary parts
- Fast validation test
- Verdict: pursue / shrink / test / drop

### Handoff Packet
Trigger examples:
- "handoff"
- "context packet"
- "get me oriented"

Output:
- Active projects
- Current goals
- Blockers
- Next steps
- Open decisions

### Close Session
Trigger examples:
- "close session"
- "save context before we reset"
- "prune this down"

Purpose:
- trim working context before the next session
- keep durable items
- reduce token usage going forward

Output:
- Kept
- Trimmed
- Dropped
- Next step

Reference:
- `scripts/close-session-workflow-prompt.md`

### TestFlight Upload Watchdog
Trigger example:
- "push to TestFlight"

Completion gate:
- Build uploaded
- Build visible in App Store Connect
- Export compliance set/verified
- Internal beta group attached
- Beta state confirmed
- Final status sent with evidence

