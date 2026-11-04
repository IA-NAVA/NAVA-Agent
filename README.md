# NAVA — AI that moves from conversation to execution

**An agentic Windows technology built to turn business requests into actions, native documents and verifiable outcomes.**

[Français](README-FR.md) · [Technical evidence](docs/update-2026-11-04.md) · [Architecture](docs/architecture-public.md) · [Partnership opportunities](docs/partnership.md)

NAVA is a **Python-based, proprietary, local-first agentic AI project** created by **IA NAVA in Occitanie, France**. Its objective is to let professionals delegate work across familiar desktop applications, not just obtain text responses. NAVA combines language-model reasoning, mission orchestration, Windows execution, observation and result verification.

**Project stage — November 4, 2026:** advanced functional prototype; selected real-world capabilities demonstrated, with reliability and end-to-end autonomous recovery still under stabilization.

## The opportunity

Small businesses lose time switching between inboxes, calendars, documents and desktop software. NAVA targets the workflow itself: interpret a request, perform coordinated actions, produce the expected deliverables and verify what happened.

### Practical scenarios

| Product | What it is designed to do | Evidence to date |
| --- | --- | --- |
| **NAVA Mail** | Turn incoming requests into document preparation, quotations, drafts and verified attachments | Actual Office deliverables, message drafts and matching MIME attachments found in audited mission archives |
| **NAVA Agenda** | Turn calendar event descriptions into executable work: prepare files and communications, create/update events where authorized | Event-related execution archives, Office outputs and SMTP/calendar receipts |
| **NAVA Core + Computer Agent** | Coordinate tasks and operate supported Windows applications | Real Windows text-file operations and a Thunderbird draft reported in targeted tests |

**A real workflow example:** a meeting request can become an interpreted mission, a prepared document, an associated email draft and a record of the actual results. Sending or changing remote data is subject to appropriate authorization.

## Technology, not a no-code workflow template

NAVA is developed as a **Python software system**, not simply a collection of no-code or n8n automations. Its architecture is designed to preserve business intent and coordinate different tools while checking effects rather than assuming a successful response means the work is complete.

```text
Business request
      ↓
Language model / authorized local or cloud reasoning
      ↓
NAVA Core — mission planning and coordination
      ↓
NAVA Bridge — execution orchestration
      ↓
Computer Agent / Mail / Agenda / Office — real actions
      ↓
Observer + Supervisor — monitoring and evidence
      ↓
Self-Healer — controlled recovery research
      ↓
Verified outcome / human approval where required
```

Mail and Agenda are specialized applications alongside the general-purpose Core. The ecosystem also contains Supervisor, Observer/Watcher, Bridge, Self-Healer and an evolving Community Manager module. [Full nine-module status](docs/module-status-2026-11-04.md).

## Evidence, not just a concept

A November 2026 offline review documented:

- **18 structurally checked native Office files:** 9 Excel, 6 Word and 3 PowerPoint.
- **9 MIME attachments** byte-for-byte matching archived files.
- **9 NAVA Mail mission folders** (8 with deliverables and drafts) and **11 Agenda execution folders**, including recorded calendar and SMTP operations.
- Targeted Windows and application-execution tests; a Self-Healer **isolated repair scenario** reported a real code fix and passing test.

The developer reported successful sending and event creation in the test environment. **Independent delivery verification, complete GUI workflow repeatability and autonomous recovery of a real interrupted business mission are not yet certified.** Test totals refer to different campaigns and must not be added together.

[Explore the scoped execution evidence](docs/evidence-review-november-2026.md) · [Read the November 4 technical update](docs/update-2026-11-04.md).

## Why it matters

NAVA's differentiating **engineering direction** is a single chain from **intent → coordinated desktop action → native output → observation → proof**. The opportunity is to automate cross-application administrative tasks in SMEs using their existing work environment. Productivity gains, pricing and scalability will need validation through measured pilots; no unsupported market-leadership or financial claims are made.

## Development priorities

1. Reliable multi-application execution initiated from the real interface.
2. Automatic collection and independent verification of actual mission outcomes.
3. Repair-and-resume capability on an interrupted real mission.
4. Reproducible Mail, Agenda and Office acceptance scenarios and secure permissions.

**The product is not yet marketed as fully autonomous or production-certified.** Technical failures and outstanding verification are documented openly in the linked audit and roadmap.

## Collaboration and investment

IA NAVA is exploring **technical partnerships, supervised pilot deployments and investment conversations** to accelerate stabilization, productization and market validation. A live demonstration and the available test evidence can be discussed directly.

[Partnership and investment information](docs/partnership.md) · [Stabilization roadmap](docs/roadmap.md) · [Full technical status](docs/status-november-2026.md)

**IA NAVA — France** · [ianava.fr](https://www.ianava.fr) · [contact@ianava.fr](mailto:contact@ianava.fr)

© 2026 IA NAVA. Proprietary project. All rights reserved. This public repository is a project presentation, not the private source code.
