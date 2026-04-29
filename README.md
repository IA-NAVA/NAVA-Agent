[Version française](README-FR.md)

# NAVA — Neural Autonomous Virtual Agent

NAVA is a local AI agent developed by IA NAVA.

It is designed to understand natural language instructions, identify the appropriate software, execute actions in a real Windows environment, verify results, and progressively improve its behavior.

## Objective

Create an AI agent capable of assisting users with everyday computer tasks without requiring code, copy-paste operations, or technical manipulation.

NAVA aims to make office automation accessible to non-technical users by allowing them to control real software through natural language instructions.

## Demonstrated Capabilities

- Understanding natural language commands
- Automatic routing to the appropriate software
- Execution of workflows across Word, Excel, Thunderbird, Google Chrome, and PowerPoint
- Multi-application workflow management
- Creation of Word documents
- Creation and modification of Excel files
- Preparation of Thunderbird emails with attachments
- Web navigation and search with Google Chrome
- Generation of office documents
- Verification of executed actions
- Multi-screen detection
- Perception of the Windows environment
- Local voice mode
- Modular architecture with software adapters
- ProcessRegistry with software actions
- Behavioral memory
- Self-correction and progressive improvement

## Validation Results

NAVA has been tested with two internal validation suites executed in a local Windows environment.

### Full System Test v3

- Final score: 98.2%
- Level: Excellent
- Result: 221 successful validations, 4 failures, 5 warnings
- Validation of the Windows environment
- Validation of the project structure
- Validation of critical imports
- Validation of screen perception
- Validation of multi-screen detection
- Validation of the local voice stack
- Validation of the voice router
- Validation of the replay engine
- Validation of the intent executor
- Validation of software adapters
- Validation of the ProcessRegistry
- Validation of Word, Excel, PowerPoint, PDF, Thunderbird, and Google Chrome actions
- Validation of voice → intent → execution routing

### Runtime Test v6

- Final score: 93.0%
- Level: Production Ready
- Result: 160 successful validations out of 172
- Validation of the full pipeline
- Validation of complex multi-step commands
- Validation of generic routing
- Validation of multi-application workflows
- Validation of Google Chrome → Word workflows
- Validation of Excel → Thunderbird workflows
- Validation of Chrome → Excel → Thunderbird workflows
- Validation of robustness on long, ambiguous, and multi-application commands
- Validation of Thunderbird attachment auto-detection
- Validation of Word, Excel, Thunderbird, and Google Chrome scenarios

## Validated Demonstrations

NAVA has demonstrated its ability to execute concrete scenarios such as:

- Opening Google Chrome, performing a web search, then creating a Word report
- Creating an Excel table with dynamic columns and rows
- Modifying an existing Excel file
- Preparing a Thunderbird email with an attachment
- Reading unread emails in Thunderbird
- Generating a structured Word document with sections
- Executing a Chrome → Word workflow
- Executing an Excel → Thunderbird workflow
- Executing a multi-step workflow across several applications

## Areas Still Under Improvement

NAVA is still in private development.

The latest tests identified a few remaining improvement areas:

- Isolated Word-to-PDF export in some cases
- Handling some Excel commands without commas between column names
- Excel → Thunderbird transfer in some complex scenarios
- Stabilization of very long workflows

These points are identified, monitored, and integrated into the technical roadmap.

## Status

The core NAVA engine remains proprietary and private.

This public repository only presents:

- The project vision
- The general architecture
- Demonstrated capabilities
- Validation results
- Public demonstrations
- The roadmap

The complete source code, internal modules, advanced adapters, memory, routing files, detailed logs, and self-correction mechanisms are not published.

## Intellectual Property

NAVA is a proprietary project developed by IA NAVA.

Copyright © 2026 IA NAVA — All rights reserved.

No reproduction, modification, redistribution, commercial exploitation of the source code, architecture, internal mechanisms, or technical concept is authorized without prior written agreement.

## Contact

IA NAVA  
https://www.ianava.fr  
contact@ianava.fr
