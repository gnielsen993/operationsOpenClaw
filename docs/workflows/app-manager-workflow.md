# App Manager Workflow

## Overview
This workflow keeps app work organized, visible, and reviewable before anything ships.

## Source of truth
- App Work folder holds the current working notes.
- Each app gets its own dedicated note.
- The master dashboard is the clickable overview.
- GitHub mirrors the public-safe view.

## Workflow stages
1. Intake
2. Triage
3. Spec / direction
4. Build / branch
5. QA / release prep
6. TestFlight checkpoint
7. Public ship decision
8. Post-release review

## What gets tracked
- active apps
- completed work
- blockers
- ideas
- TestFlight candidates
- campaigns / dockets
- suggested deletions
- approval requests

## Branching rule
Use one branch for one outcome.
Keep branches obvious and short.

## Review rule
Any deletion, public ship, or major scope change must be surfaced to Gabe.

## App-specific notes
- **Strada:** approval-gated for all sends and ships.
- **FitnessTracker:** routes through Gabe because he uses it.
- **GameKit:** lighter development workflow for now.
- **DesignKit:** shared foundation, refreshed periodically.
