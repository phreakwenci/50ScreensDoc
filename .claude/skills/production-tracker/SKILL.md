---
name: production-tracker
description: >-
  Run the "50 Screens" production rhythm — build meeting agendas, capture meeting notes,
  and create/track tasks in the Notion Production Bible. Use whenever the user wants an
  agenda for an upcoming check-in, wants to log what was decided in a meeting, or wants to
  add/assign/review production tasks. Triggers on: "agenda", "meeting", "check-in", "notes",
  "action items", "tasks", "to-do", "weekly sync", "standup", "what should we cover".
---

# 50 Screens — Production Tracker

You keep the team's operating rhythm tight and light. The team runs **weekly Saturday
9:00 AM check-ins** (Google Meet / Zoom), usually Jan-David (director), Richard (producer,
East Coast), and Sophia (producer, West Coast); Tyrone (DP) as needed. Availability varies
— sometimes only 2–3 people are on.

## Reference file
- `references/cadence.md` — meeting rhythm, the standing agenda template, the meeting-note
  template, task fields, owners, and the current live threads to draw agenda items from.

Shared context: the Notion **Production Bible** is the hub. IDs (Bible page, Meeting Notes
DB, Tasks DB) are in `../grant-applications/references/sources.md`. Project facts:
`../grant-applications/references/project-facts.md`.

## Core workflows

### 1. Build a meeting agenda
Ask (or infer) the meeting date and who's likely on. Then build a **short, prioritized**
agenda from the current live threads (see `cadence.md`): grants status, fiscal sponsorship,
Phase 1 shoot readiness, crowdfunding, theater outreach, admin/LLC. **Right-size to the
room** — fewer people or a holiday means fewer items and shorter time boxes. Prefer
**decisions and single next-steps** over open-ended discussion. Each item: owner, topic,
time box, priority, and a one-line desired outcome. Push anything non-urgent to the Tasks
DB instead of the agenda.

**Anti-overwhelm rules:** default to **4–6 items / ~30–45 min**; on a light/holiday week
with 2–3 people, **3–5 items / ~30 min**. One clear ask per item. If it isn't blocking or
time-sensitive, it's a task, not an agenda line.

### 2. Capture meeting notes
Use the meeting-note template in `cadence.md`: attendees, time, decisions made, assignments
(owner + next step + date), and a "monitor" list for risks. Append to the Bible's meeting
log or the Meeting Notes DB (with confirmation).

### 3. Create / assign / review tasks
Add tasks to the existing **Tasks — 50 Screens Production** database (don't create a new
tasks DB). Each task: what, owner, due window, and the thread it belongs to. Review = pull
open tasks grouped by owner.

## Where things go (don't duplicate)
- **Agendas** → their own "Meeting Agenda" database on the Bible page (create once, reuse
  per meeting). Distinct from meeting notes and tasks.
- **Meeting notes** → the Bible meeting log / Meeting Notes DB.
- **Tasks / to-dos** → the existing Tasks DB (by owner). **Not** the agenda.

## Guardrails
- **Confirm before writing to Notion** (creating databases/pages, editing the Bible, adding
  tasks). Reversible, but it's the team's live workspace.
- Keep agendas lean — protecting the team from overwhelm is the point of this skill.
- Don't move a decision into an application/campaign/outreach action without routing through
  the relevant skill and its confirmation step.

## Related skills
`grant-applications`, `crowdfunding-campaign`, `theater-outreach` — most agenda items and
tasks originate in those lanes; this skill schedules and records them.
