# OctoAcme RACI-Lite Matrix Template

This template provides a lightweight, copy-pastable RACI matrix for mapping role responsibilities across key project activities. Use it at the start of a project during initiation or planning to clarify ownership before work begins.

**RACI key:**
| Code | Meaning |
|------|---------|
| **R** | **Responsible** – does the work |
| **A** | **Accountable** – final decision-maker / sign-off owner (only one per activity) |
| **C** | **Consulted** – provides input before decisions or actions |
| **I** | **Informed** – kept up to date on decisions and progress |

---

## How to use this template

1. Copy the matrix below into your project's planning doc or `docs/` folder.
2. Replace the sample activities with the actual activities or deliverables for your project.
3. Assign RACI codes for each role column. Every row must have exactly one **A**.
4. Review the completed matrix with your team during kickoff to confirm shared understanding.
5. Update it as the project evolves (scope changes, role changes, new activities).

> **Tip:** Keep the matrix focused on decision points and key deliverables—not every task. Aim for 10–20 rows.

---

## RACI Matrix

| Activity / Deliverable | Sponsor | Project Manager | Product Manager | Engineering Manager / Tech Lead | Developers | UX/UI Designer | QA / Test Lead | Data Analyst | Stakeholders |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| **Initiation** | | | | | | | | | |
| Define problem statement & business case | A | C | R | C | | | | C | C |
| Approve project charter / one-pager | A | C | R | C | | | | | I |
| Identify stakeholders & communication plan | I | R/A | C | | | | | | C |
| **Planning** | | | | | | | | | |
| Define success metrics / KPIs | C | C | A | C | | C | | R | C |
| Create and prioritize backlog | I | C | A | C | C | C | C | C | C |
| Define Definition of Done | I | C | A | A | R | C | R | | |
| Create risk register | C | A | C | C | | | | | I |
| Resource and capacity planning | A | R | C | C | | | | | |
| **Execution** | | | | | | | | | |
| Sprint planning | I | C | A | C | R | C | C | | |
| Technical design / architecture | | C | C | A | R | C | C | | |
| UX design & prototyping | | I | C | C | C | A | C | | C |
| Feature implementation | | I | I | C | A | C | C | | |
| Code review | | | | C | A | | C | | |
| Defect triage | | C | C | C | R | C | A | | |
| **Release** | | | | | | | | | |
| Pre-release QA sign-off | I | C | C | C | C | C | A | | |
| Stakeholder release approval | A | C | C | | | | C | | R |
| Production deployment | | C | I | C | A | | C | | |
| Post-deploy verification | | R | C | C | C | | A | C | I |
| Stakeholder release announcement | I | R | C | | | | | | A |
| **Retrospective** | | | | | | | | | |
| Facilitate retrospective | | A | C | C | C | C | C | C | |
| Capture and assign action items | | A | C | C | R | R | R | R | |
| Report outcomes & metrics to stakeholders | I | C | R | | | | | A | I |

---

## Notes

- **Multiple R's** on a row are fine when several people share execution; only one **A** per row is permitted.
- **R/A** in a single cell means the same person is both doing the work and accountable for it (common for small teams).
- Blank cells mean the role has no involvement in that activity—review blanks to confirm they are intentional.
- This matrix complements (not replaces) the role definitions in [Roles & Personas](./octoacme-roles-and-personas.md).

---

## Related Docs

- [Roles & Personas](./octoacme-roles-and-personas.md) – Full role descriptions, responsibilities, and interaction patterns
- [Project Initiation](./octoacme-project-initiation.md) – Use the RACI matrix as part of your initiation deliverables
- [Project Planning](./octoacme-project-planning.md) – Reference the matrix during sprint and capacity planning
- [Risks & Communication](./octoacme-risks-and-communication.md) – Cross-reference the RACI to confirm risk owners
- [Release & Deployment](./octoacme-release-and-deployment.md) – Confirm sign-off owners align with the RACI before each release
