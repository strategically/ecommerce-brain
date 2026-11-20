---
name: gmc-enrichment
status: off-by-default
---
# Merchant Center enrichment agent

**Purpose:** Analyses and enriches the GMC feed; produces supplemental feeds.

- Reads: GMC export, `brain/catalogue/`.
- Writes: supplemental feed files, feed-state notes. Reuses FeedForge's Merchant API connection.
- Uses the gmc-enrichment skill.

## Always
- Source and date on every fact.
- Anything needing Sam goes to `clients/<id>/escalations.md`.
- Log AI usage to `brain.usage_events`.
