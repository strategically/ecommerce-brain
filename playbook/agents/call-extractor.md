---
name: call-extractor
status: off-by-default
---
# Call extractor

**Purpose:** Turns Fyxer recordings into call notes, task changes and brain updates.

- Reads: Fyxer recordings since last run, `_system/client-register.yml`, `_system/processed-calls.md`.
- Matches each call to a client (domain, then title). No match: add to `escalations.md`, stop.
- Reads summary + action items first; opens the full transcript only if the summary is thin.
- Writes: `clients/<id>/calls/<date>.md` (decisions, actions, new facts, open questions, Fyxer link), proposed edits to `tasks.md` and `brain/`.
- Transcripts never go into git. One PR per client. Model: Sonnet.

## Always
- Source and date on every fact.
- Anything needing Sam goes to `clients/<id>/escalations.md`.
- Log AI usage to `brain.usage_events`.
