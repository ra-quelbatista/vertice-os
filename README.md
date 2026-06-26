# vertice-os
Operating system for RÁ-QUEL Studio: positioning, offers, leads, sales, delivery and creative intelligence.
 [README.md](https://github.com/user-attachments/files/29395400/README.md)
 # VÉRTICE
## Build packet for Base44

**VÉRTICE** is a private operating system for RÁ-QUEL: a place where studio operations, commercial clarity, content, research, life administration and shared agreements can coexist without becoming a noisy, generic dashboard.

The first goal is not to "do everything". It is to close the distance between **good work** and **reliable commercial proof**:

1. turn services into clear offers;
2. capture and qualify leads without scattered conversations;
3. connect content to a real offer and next action;
4. turn completed work into reusable proof;
5. preserve a private space for reflection, planning, and shared agreements with explicit consent.

## What is in this pack

- `prompts/00_plan_first_prompt.txt` — Paste into Base44 with **Plan mode / Discuss mode** on.
- `prompts/01_build_mvp_prompt.txt` — Paste after approving the plan.
- `prompts/02_build_superagent_prompt.txt` — Creates the NÚCLEO operational Superagent.
- `skills/nucleo_superagent_skill.md` — Upload as a reusable Base44 skill.
- `docs/01_product_brief.md` — Product vision, scope and non-goals.
- `docs/02_information_architecture.md` — Page map and user flows.
- `docs/03_data_model.md` and `data/entities.json` — Database model.
- `docs/04_automation_rulebook.md` — Approved automations and human checkpoints.
- `docs/05_design_system.md` — UI art direction for the app.
- `docs/06_privacy_permissions.md` — Role matrix and sensitive-data rules.
- `docs/07_research_protocol.md` — Web-research quality standard.
- `docs/08_launch_sequence.md` — Build order and acceptance checklist.
- `docs/09_source_map.md` — How to use the current Drive materials without copying sensitive data.
- `data/offers_seed.csv` — Seed offer catalogue based on the existing commercial catalogue.
- `data/content_seed.csv` — Seed editorial records for a first import test.
- `.gitignore` / `CHANGELOG.md` — GitHub-ready governance files.

## First use in Base44

1. Start a **new app** named `VÉRTICE`.
2. Switch on **Plan mode** or use **Discuss mode**.
3. Paste `prompts/00_plan_first_prompt.txt`.
4. Review the proposed pages, database and permissions. Do not build before the plan matches this packet.
5. Paste `prompts/01_build_mvp_prompt.txt`.
6. Connect services in this order: Google Drive (read-only first), Google Sheets, Google Docs, Google Calendar, Gmail, LinkedIn, then GitHub.
7. Build the NÚCLEO Superagent only after the MVP navigation and permissions work.

## Important operating rule

This app is a tool for clarity, operations and reflection. It must **not** claim spiritual certainty, diagnose mental health, make legal/financial decisions, fabricate research, invent analytics, or send/post/commit anything without explicit approval.

## Suggested GitHub repository

Create a private repo called `raquel-vertice-os`, then upload this folder. Use GitHub for versioning the product spec, prompts, changes, bug reports and release notes. Do **not** mirror client files, private journals, Gmail content, passwords or OAuth tokens into Git.

## Reference documents used for this packet

- Existing services catalogue: 16 mapped services and 5 commercial package structures.
- Existing ecosystem calendar: 40 planned content pieces, three brands, and operating priorities such as unified lead links, proof collection and batch production.
- Existing brand direction: current RÁ-QUEL principles should override old or exploratory visual documents when they conflict.
