# NAVA — Technical status, October 2026

This note separates observed prototype behavior from capabilities that still require broader validation. It is a public summary, not an independent certification report.

## Observed in documented tests

- Real interaction with supported Windows application windows.
- Calendar-oriented scenarios exercised through the user interface.
- Real minimization and restoration of the NAVA window.
- Native Excel quotation output observed and checked in a specific scenario.
- A local-first execution model with optional, controlled cloud assistance.

These observations are scenario-specific. They should be reproduced with the same acceptance protocol before being treated as a release guarantee.

## Not yet comprehensively certified

- Complete multi-application business missions from one natural-language request.
- Reliable recovery of browser tab context in every supported situation.
- All email and attachment workflows.
- Autonomous repair across arbitrary runtime failures.
- General productivity gains, latency, cost, and reliability across customer environments.

## NAVA Mail — October 29, 2026 update

**Source:** IA NAVA's updated ten-slide NAVA Mail presentation. **Status:** functional demonstrator under validation, not an end-to-end certification.

The presented workflow is: receive email → understand message and attachments → multi-action plan → execute → verify and preserve evidence → reply with attachments. Supported output types depend on the request and available integration. Calendar identities, invitees and Meet links require exact, real verification.

**Reported campaign:** 4,533 PASS, 2 FAIL (Calendar formatting) and 31 passing subtests. Later corrective work has been reported, but no subsequent fully passing campaign has been established. The counts must not be treated as verified end-to-end production reliability.

**Operating modes:** supervised approval for sensitive external actions; a narrowly pre-authorized Auto mode is intended to send a complete verified response without per-message confirmation. This is a demonstrator policy requiring independent end-to-end acceptance, not unrestricted permission or a certified guarantee.

**Open validation:** real-interface multitask email in both modes, complete output and attachment checks, Calendar/Meet details and full regression suite.

[Public NAVA Mail overview](nava-mail.md).

## Evidence discipline

NAVA distinguishes a successful command, a generated response, and a completed business outcome. A capability is considered ready for a scoped release only when the real effect, its verification, and persistent evidence are reproduced across repeated runs.

## Confidentiality boundary

The public repository does not contain the private engine, credentials, customer data, proprietary algorithms, or sensitive execution logs. This document intentionally describes behavior and validation boundaries at a functional level.
