```markdown
[Version française](README.fr.md)

# NAVA  Neural Agentic Virtual Agent

NAVA is a local agentic AI assistant developed by IA NAVA.

It is designed to understand natural instructions, identify the appropriate software, plan actions, execute workflows in a real Windows environment, verify the results, correct certain errors, and progressively improve its behavior.

## Objective

Create an AI agent capable of assisting a user with everyday computer tasks without requiring code, copy-paste operations, or technical manipulation.

NAVA aims to make office automation accessible to non-technical users by allowing them to control real software through a simple written or spoken request.

The goal is not only to open software or respond to isolated commands, but to transform a human intention into a complete digital action:

understand → plan → execute → verify → correct → report.

## Demonstrated Capabilities

- Understanding natural language commands
- Automatic routing to the right software
- Multi-application workflow execution
- Sequential planning of complex tasks
- Word document creation
- Excel file creation and modification
- PowerPoint presentation creation
- Thunderbird email draft preparation without automatic sending
- Thunderbird inbox reading for configured accounts
- Thunderbird replies using the signature of the selected account
- Thunderbird attachment management
- Google Calendar follow-up creation
- Web navigation and search with Google Chrome
- Office file generation
- Verification of executed actions
- Validation of created files
- Validation of opened Thunderbird compose windows
- Validation of requested attachments
- Multi-screen detection
- Windows environment perception
- Local voice mode
- Cloud LLM or local Ollama operation depending on the task
- Modular architecture with software adapters
- ProcessRegistry with software actions
- Agentic multi-step orchestrator
- Behavioral memory
- Self-correction and progressive improvement

## Validation Results

NAVA has been tested through several internal validation suites executed in a local Windows environment.

### Full System Test v3

- Final score: 98.2%
- Level: Excellent
- Result: 221 validations OK, 4 failures, 5 warnings
- Windows environment validation
- Project structure validation
- Critical import validation
- Screen perception validation
- Multi-screen detection validation
- Local voice stack validation
- Voice router validation
- Replay engine validation
- Intent executor validation
- Software adapter validation
- ProcessRegistry validation
- Word, Excel, PowerPoint, PDF, Thunderbird and Google Chrome action validation
- Voice → intent → execution routing validation

### Runtime Test v6

- Final score: 93.0%
- Level: Production Ready
- Result: 160 validations OK out of 172
- Full pipeline validation
- Complex multi-step command validation
- Generic routing validation
- Multi-application workflow validation
- Google Chrome → Word workflow validation
- Excel → Thunderbird workflow validation
- Chrome → Excel → Thunderbird workflow validation
- Robustness validation on long, ambiguous and multi-application commands
- Thunderbird attachment auto-detection validation
- Word, Excel, Thunderbird and Google Chrome scenario validation

### Recent Agentic Validations

Recent internal tests validated more advanced workflows:

- Local Excel table creation with columns, rows and formulas
- Local Word document creation and PDF export
- Local 3-slide PowerPoint presentation creation
- PowerPoint → Word workflow
- Excel → Word → Thunderbird workflow
- Thunderbird → Excel → Word → Thunderbird → Google Calendar workflow
- Email draft preparation with the correct attached files
- Google Calendar follow-up creation with corrected relative dates
- Cloud LLM operation
- Local-only operation through Ollama
- Reinforced validation of created files and attachments

## Validated Demonstrations

NAVA has demonstrated its ability to execute concrete scenarios such as:

- Open Google Chrome, perform a web search, then create a Word report
- Create an Excel table with dynamic columns, rows and formulas
- Modify an existing Excel file
- Create a 3-slide PowerPoint presentation
- Create a Word document and export it to PDF
- Prepare a Thunderbird email draft with one or several attachments
- Read the latest received email from a specific Thunderbird account
- Reply to a Thunderbird email without sending it
- Use the signature of the Thunderbird account being used
- Generate a professional reply from a received email
- Create an Excel client sheet from an email
- Automatically attach the correct file to a Thunderbird draft
- Schedule a follow-up in Google Calendar
- Execute a Chrome → Word workflow
- Execute an Excel → Thunderbird workflow
- Execute an Excel → Word → Thunderbird workflow
- Execute a Thunderbird → Excel → Word → Thunderbird → Calendar workflow

## Public Demo Outputs

Anonymized examples generated during NAVA validation tests are available here:

[View NAVA demo outputs](assets/demo-outputs/)

## Areas Still Under Improvement

NAVA remains in private development.

The latest tests identified several stabilization areas:

- Fine stabilization of voice mode and microphone behavior
- Reinforcement of the proof log after each workflow
- Stricter validation of very long workflows
- Improved user-specific business memory
- Reinforced security for sensitive actions: sending, deleting, archiving, moving
- Better distinction between one-shot voice commands and continuous listening
- Improved handling of certain very complex multi-application scenarios

These points are identified, tracked and integrated into the technical roadmap.

## Status

The core NAVA engine remains proprietary and private.

This public repository presents only:

- The project vision
- The general architecture
- The demonstrated capabilities
- The validation results
- The public demonstrations
- The roadmap

The complete source code, internal modules, advanced adapters, memory system, routing files, detailed logs and self-correction mechanisms are not published.

## Intellectual Property

NAVA is a proprietary project developed by IA NAVA.

Copyright © 2026 IA NAVA — All rights reserved.

No reproduction, modification, redistribution or commercial exploitation of the source code, architecture, internal mechanisms or technical concept is authorized without prior written agreement.

## Contact

IA NAVA  
https://www.ianava.fr  
contact@ianava.fr
```
