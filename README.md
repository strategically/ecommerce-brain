# Ecommerce Brain

Strategically's operating system for an agentic agency. Only Sam and the agents use it.

- **Numbers** live in Postgres (Supabase project `ecommerce-brain`, one schema per client; register in `brain.clients`).
- **Words** live here: tasks, call notes, curated client knowledge, decisions.

## Layout
- `playbook/` agency-wide: agent definitions, rules, templates. Shared by every client.
- `clients/<id>/` one folder per client. `<id>` = `brain.clients.id`.
- `_system/` register and run logs.

## Rules for agents
1. Read `clients/<id>/CLAUDE.md` first, then `tasks.md`, then `brain/` as needed.
2. Every fact line carries a source and date, e.g. `(call 2026-11-19)`.
3. Never write to `main` except status changes in `tasks.md`. Everything else: push a branch, open a PR, Sam merges.
4. Stage 1 (until 15 Dec 2026): agents recommend, Sam approves and applies changes himself.
5. Judge on profit contribution and cost per new customer, never platform ROAS alone.
6. Agents are off by default. They run only when a scheduled task or Sam starts them.
