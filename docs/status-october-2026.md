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

## Evidence discipline

NAVA distinguishes a successful command, a generated response, and a completed business outcome. A capability is considered ready for a scoped release only when the real effect, its verification, and persistent evidence are reproduced across repeated runs.

## Confidentiality boundary

The public repository does not contain the private engine, credentials, customer data, proprietary algorithms, or sensitive execution logs. This document intentionally describes behavior and validation boundaries at a functional level.
