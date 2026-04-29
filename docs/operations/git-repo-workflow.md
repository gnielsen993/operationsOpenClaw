# Git & Repo Workflow

## Non-negotiable sync rule
For every GitHub repo workflow:

1. `git fetch --prune`
2. `git pull --ff-only`
3. Preserve/resolve dirty local work before editing
4. Make focused changes
5. Verify with the smallest meaningful gate: build/test/lint/inspection
6. Commit
7. `git push`
8. Confirm clean/up-to-date branch state

## Why
user works across machines. Completed work should not be stranded on one machine.

## Current public repo inventory
- `user/DesignKit`
- `user/FitnessTracker`
- `user/GameKit`
- `user/HabitTracker`
- `user/PantryTracker`
- `user/operationsOpenClaw`

