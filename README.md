# NAVA — Neural Agentic Virtual Agent

**From human intent to real, verifiable Windows execution.**

[English](README.md) · [Français](README-FR.md) · [Technology status](docs/status-october-2026.md) · [Stabilization roadmap](docs/roadmap.md) · [Partnership](docs/partnership.md)

NAVA is a **local-first, hybrid agentic AI project** developed by **IA NAVA in Occitanie, France**. It aims to understand natural-language requests, use Windows software to perform tasks, produce native files, check actual outcomes and preserve evidence. It is more than a text-generating assistant: the objective is **computer-based execution with verification**.

## What NAVA is built to do

- **Understand objectives:** interpret requests formulated in ordinary language and identify the expected outcomes.
- **Operate Windows:** interact with supported application windows and local files.
- **Produce deliverables:** Word, Excel and PowerPoint documents in supported scenarios.
- **Assist with calendars and email:** read and interpret appointments, prepare documents and email drafts; obtain human approval before sensitive actions.
- **Coordinate workflows:** work across several applications while preserving the original user objective.
- **Verify the result:** distinguish a successful technical command from a completed business mission.
- **Learn with safeguards:** retain useful execution experience; autonomous recovery is still being evaluated.

## From intent to verified results

```text
Natural-language request
          ↓
Identify all requested outcomes
          ↓
Propose an execution plan (advisory)
          ↓
Select existing capabilities
          ↓
Execute in the Windows environment
          ↓
Observe and verify actual results
          ↓
Track completed and remaining outcomes
          ↓
Report evidence / require approval where needed
```

A planning model must not silently narrow the user’s objective. A click, a generated response, or a passing unit test does not by itself prove that a task is complete.

## Example business scenario

> Review my upcoming meetings, prepare the required documents, and draft the associated emails.

The intended workflow is to inspect relevant appointments, understand their requirements, find the information already available, create the documents, prepare email drafts and attachments, and verify the resulting files and application states. Sending messages or making other sensitive changes requires the relevant authorization.

## Local-first, with controlled cloud assistance

NAVA is developed for the user's Windows environment, with local models and applications as a foundation. Cloud assistance may be used when enabled and permitted. A cloud-generated response is **not** considered proof that a final native file exists on the PC: delivery and content must be verified separately.

## Real-world capability status

NAVA has demonstrated individual Windows and office operations, including recent calendar-related tests through its interface and successful real minimization/restoration of the NAVA window. Native Excel quotations have also been observed and verified in specific tests. However, **full multi-application business completion, Chrome tab-context recovery, all email/attachment scenarios and autonomous self-repair are not yet comprehensively certified**.

See the [October 2026 evidence summary](docs/status-october-2026.md) for a clear separation between observed results, passing technical tests and remaining validation work.

## Engineering and acceptance principles

1. **No new features during stabilization:** prioritize reliability of existing commands.
2. **One acceptance reference:** the existing natural-language command test protocol.
3. **Real interface first:** direct runner success is not a substitute for interface-based execution.
4. **Repeated evidence:** a completed capability must show real effects, verification and persistent proof on repeat runs.
5. **No scenario-specific hardcoding:** fix general causes; keep ownership and approval safeguards intact.
6. **Reuse existing modules:** avoid unnecessary architectural proliferation.

## Why this matters to SMEs

The target is practical delegation of recurring administrative tasks: meeting preparation, document production, quotations, management dashboards, customer dossiers and correspondence drafts. The expected value is less time spent coordinating software and more time available for decisions and customer work. Performance and economic gains must be measured in actual deployments; no general productivity percentage is claimed here.

## Public documentation and confidentiality

This repository is a **public project presentation**, not the full private source repository or a claim of independent certification. Detailed orchestration, proprietary code, memory structures, credentials, business records and sensitive execution logs are not published.

- [Technology status — October 2026](docs/status-october-2026.md)
- [Public architecture](docs/architecture-public.md)
- [Current stabilization roadmap](docs/roadmap.md)
- [Partnership, investment and acquisition](docs/partnership.md)
- [French presentation](README-FR.md)

**IA NAVA** · [ianava.fr](https://www.ianava.fr) · [contact@ianava.fr](mailto:contact@ianava.fr)

© 2026 IA NAVA. Proprietary project; all rights reserved.
