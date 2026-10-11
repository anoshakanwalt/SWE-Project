# AI-Assisted Service Management with Trust Verification

CS3151 Software Engineering, Effat University, Fall 2026 (Dr. Passent Elkafrawy)

**Team:** Anosha Kanwal, Amira Atiah, Busra Suleymanoglu

## What this project is

A service request and approval workflow for an industrial automation service department. An AI agent classifies each incoming request into one of six service categories, routes it to the owning department, and assesses its urgency, with a confidence score and one-sentence reasoning for each. Low-confidence requests and any Critical or Urgent request always go to a manager. Every AI and human decision is written to an immutable audit trail, and a dashboard tracks how often the AI was accepted, modified, or overridden.

The workflow is modelled on how an industrial automation services department handles requests today (email, WhatsApp, and phone, with no structured tracking).

## Start here

- **[Project-Package.pdf](Project-Package.pdf)** is every document below merged into one file with a cover page and index.
- **[docs/00-project-reference.pdf](docs/00-project-reference.pdf)** is the short sheet of agreed definitions (roles, categories, urgency, confidence routing, lifecycle). All documents follow it.
- **[CHANGES.md](CHANGES.md)** lists what was corrected since earlier submissions.

## Documents (reading order)

| # | Document | Files |
|---|----------|-------|
| 00 | Project Reference Sheet | `docs/00-project-reference.docx` / `.pdf` |
| 01 | Project Overview | `docs/01-project-overview.docx` / `.pdf` |
| 02 | Market Study | `docs/02-market-study.docx` / `.pdf` |
| 03 | Feasibility Study | `docs/03-feasibility-study.docx` / `.pdf` |
| 04 | Personas (Lab 2) | `docs/04-personas-lab2.docx` / `.pdf` |
| 05 | User Stories | `docs/05-user-stories.docx` / `.pdf` |
| 06 | Requirements (Lab 3) | `docs/06-requirements-lab3.docx` / `.pdf` |

Each document is provided as `.docx` (editable) and `.pdf` (opens directly in the browser).

## Repository layout

```
docs/   all written deliverables (latest version of each)
src/    source code (added from the implementation labs onward)
```

## Versioning

Only the latest version of each document is kept in `docs/`. Each lab submission is tagged (`lab3`, `lab4`, ...) so earlier states can be recovered.
