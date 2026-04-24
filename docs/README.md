# OctoAcme Project Management Docs

This README is the entry point for all OctoAcme project management process documentation. It provides a high-level summary of how projects are run at OctoAcme and links to the individual process docs for deeper guidance.

## Purpose of This Repository / Copilot Space

This repository centralizes OctoAcme's project management knowledge in the `docs/` folder, making it easy to discover, search, and maintain. Issue templates in `.github/ISSUE_TEMPLATE/` provide a structured way for anyone on the team to propose updates or additions to the process docs—supporting continuous improvement and transparent knowledge sharing.

---

## Process Overview

OctoAcme follows a lightweight but structured project lifecycle:

**Initiation → Planning → Execution & Tracking → Release & Deployment → Retrospective & Continuous Improvement**

### Key Workflows

- **Initiation** – Validate the business need, define measurable outcomes, align stakeholders, and produce a Project Charter/One-pager, initial risk list, stakeholder communication plan, and high-level timeline. A decision gate confirms success metrics, stakeholder priority, and team availability before planning begins.
- **Planning** – Scope work into a prioritized backlog with acceptance criteria, plan capacity-aware sprints, document a Definition of Done, and identify dependencies with escalation paths.
- **Execution & Tracking** – Build and test in small, shippable increments. Work moves through stages: **Backlog → Ready → In Progress → In Review → QA → Done**. PRs are kept small, linked to issues and acceptance criteria, and require at least one approval before merging.
- **Release & Deployment** – Pre-release checklist (CI green, acceptance criteria met, release notes, rollback plan), staging validation, production release, post-deploy verification, and stakeholder announcement.
- **Retrospective & Continuous Improvement** – Convert learnings into tracked action items with owners and due dates; feed improvements back into the next cycle.

---

## Personas & Roles

| Role | Key Responsibilities |
|------|---------------------|
| **Project Manager (PM)** | Coordinates delivery, manages schedule, risks, dependencies, and communications |
| **Product Manager (PdM)** | Defines outcomes, prioritizes backlog, measures success |
| **Developers** | Design and implement shippable increments with tests and documentation |
| **Engineering Manager / Tech Lead** | Owns architecture decisions, technical standards, and engineering capacity |
| **UX/UI Designer** | Designs and validates user experience flows; ensures usability and accessibility |
| **QA / Test Lead** | Owns test strategy and quality sign-off; ensures releases meet the quality bar |
| **Data Analyst** | Defines KPIs, tracks metrics, surfaces insights for data-informed decisions |
| **Sponsor** | Champions the business case, secures resources, and removes organizational blockers |
| **Stakeholders** | Provide functional requirements, approvals, and strategic direction from their domain |

Each project has a named PM and Product Lead. Backlog items and risk mitigations have clear owners throughout delivery. Use the [RACI-Lite Matrix Template](./octoacme-raci-template.md) to map role responsibilities for your specific project.

---

## Communication Strategies & Cadence

- **Daily standups** – Progress, blockers, and dependencies for the delivery team
- **Weekly delivery sync** – PM + PdM alignment, risk and status updates
- **Sprint demos / reviews** – End-of-sprint or milestone showcases
- **Monthly stakeholder updates** – Status, risks, and decisions for broader audiences
- **Incident communications** – Structured templates with clear escalation paths; security incidents handled separately
- **Escalation path** – Team triage → PM/Product Lead → Sponsor-level when needed

---

## Quality Assurance Practices

- Unit tests required for all new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before every release
- Security scanning in CI on every PR
- Manual QA when automated coverage is insufficient
- PR review: at least one approval required before merging (per team policy)
- Pre-release: CI must be green, acceptance criteria met, rollback plan documented
- Post-deploy: verification steps run in production; rollback executed if critical issues arise

---

## Process Docs

| Document | Description |
|----------|-------------|
| [Overview](./octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and lifecycle summary |
| [Project Initiation](./octoacme-project-initiation.md) | How to kick off a new project with clear goals and alignment |
| [Project Planning](./octoacme-project-planning.md) | Scope, backlog, milestones, and sprint planning guidance |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Workflows, board stages, PR practices, and Definition of Done |
| [Risks & Communication](./octoacme-risks-and-communication.md) | Risk register, escalation paths, and communication templates |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Pre-release checklist, deployment steps, and rollback procedures |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Retrospective format, action item tracking, and process feedback loops |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed responsibilities and communication patterns for each role |
| [RACI-Lite Matrix Template](./octoacme-raci-template.md) | Reusable template for mapping role responsibilities across project activities |

---

## Proposing Updates

Use the issue templates in [`.github/ISSUE_TEMPLATE/`](../.github/ISSUE_TEMPLATE/) to suggest additions or improvements to any of the process docs above. All proposed changes are reviewed via pull request before merging.
