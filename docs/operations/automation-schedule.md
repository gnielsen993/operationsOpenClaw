# Automation Schedule

All times: America/Denver.

| Automation | Time | Expected behavior |
|---|---:|---|
| Daily Morning Controller | 8:15 AM daily | Sends focused daily plan |
| App Manager Daily Triage | 9:00 AM daily | Updates App Work, flags changes/deletions, surfaces blockers |
| App Manager Weekly Review | Wednesday 4:00 PM | Summarizes app status, readiness, blockers, and next priorities |
| End-of-Day Review | 10:00 PM daily | Sends progress review + tomorrow start |
| Weekly Memory Compaction | Sunday 8:30 PM | Compacts memory and summarizes carry-over priorities |

## Failure policy
- Automations should not fail silently.
- Failure alerts should notify user.
- If an automation depends on model auth, expired OAuth/API credentials are treated as blockers to fix immediately.


## Missing capability backlog
When a requested automation/workflow is blocked by missing API access, account login, desktop setup, app install, or credentials, add it to the private Obsidian `Connection Backlog` so user can resolve setup items next time he is at the desktop.
