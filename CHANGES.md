# Changes

## 9 October 2026: consistency pass across all documents

Corrections made so that every document describes the same project.

**Project title**
- One title used everywhere: *AI-Assisted Service Management with Trust Verification*. The earlier working name was removed from all documents.

**Urgency (new rule, applied everywhere)**
- The client selects an urgency level (Normal, Critical, Urgent) when submitting, the AI assesses urgency independently, and the system applies the higher of the two, so a request is never under-escalated.
- Updated in: Project Overview (urgency section, use cases, database schema), User Stories (US-01, US-03), Personas, Requirements (Lab 3), Feasibility Study.
- "Priority level" wording replaced by "urgency level" wherever it meant the client's input.

**Low confidence defined as below 50%**
- Matches the confidence-routing table (below 50% goes to the manager). The earlier User Stories used a 70% threshold, which contradicted the table.

**User Stories rebuilt (10 to 14 stories)**
- Removed the old urgency labels (Routine / Safety-Critical) and the old fault-type categories.
- Added stories for the applied-urgency rule, manager-agreed quotation, manager report review, automatic invoice and report email, and payment confirmation.
- Added "no role, including Admin, can edit or delete audit entries" to the audit-trail story.

**Personas (Lab 2)**
- Quotation is now issued by the manager (previously described as auto-generated); the AI never touches pricing.
- Client journey uses the defined client-visible statuses; stories match the rebuilt User Stories.

**Requirements (Lab 3, Part 4)**
- Project story list now mirrors the 14 rebuilt User Stories.
- Added two requirements (AI urgency assessment; applied urgency rule); requirements renumbered REQ-1 to REQ-10.

**Other**
- Market Study: team names added to the header table.
- Feasibility Study: table of contents page numbers corrected.
- Project Overview: team names added; database schema now has `client_urgency` and `applied_urgency`; state machine uses the 50% rule.
- Added the Project Reference Sheet and a merged `Project-Package.pdf`.
- The first-draft standalone Market Study was removed (superseded by the version on the course template).
