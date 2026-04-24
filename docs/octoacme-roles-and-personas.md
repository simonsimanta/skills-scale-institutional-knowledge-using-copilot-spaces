# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

For a quick overview of how roles interact across the project lifecycle, see the [RACI-Lite Matrix Template](./octoacme-raci-template.md).

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## UX/UI Designer

### Role Summary
UX/UI Designers advocate for user experience quality throughout the product lifecycle. They create and validate UI/UX flows, ensuring that what gets built is usable, accessible, and aligned with user needs.

### Responsibilities
- Research user needs and translate them into wireframes, prototypes, and design specs
- Collaborate with Product Managers and Developers on design trade-offs and feasibility
- Define and enforce UX standards and accessibility requirements
- Participate in user testing and incorporate feedback into designs
- Ensure design handoff documentation is clear and complete for developers

### Goals
- Deliver intuitive, accessible experiences that meet user needs
- Reduce rework from late-stage UX feedback
- Build shared design language and component library

### Typical Interactions
- **Product Managers**: align on user stories and acceptance criteria containing UX expectations
- **Developers**: design handoff sessions; clarify intent and edge cases during implementation
- **QA/Test Lead**: provide test scenarios for usability and accessibility checks
- **Backlog**: author and prioritize design-related stories and spikes
- **Retrospectives**: surface UX learnings and propose process improvements to design–dev handoff

---

## Data Analyst

### Role Summary
Data Analysts define, track, and surface metrics that inform product and project decisions. They ensure the team is building the right things and measuring outcomes effectively.

### Responsibilities
- Partner with Product Managers to define KPIs and success metrics for each initiative
- Design and maintain dashboards and reports for delivery and product health
- Instrument data collection in collaboration with engineering when new tracking is required
- Design and evaluate experiments (A/B tests, feature flags with measurement plans)
- Surface insights and anomalies to support data-informed decisions

### Goals
- Ensure every initiative has measurable outcomes defined before delivery starts
- Reduce time-to-insight for PM and leadership decision making
- Enable the team to detect and respond to regressions or unexpected outcomes quickly

### Typical Interactions
- **Product Managers**: co-own success metrics definition and experiment design
- **Project Managers**: contribute metrics updates to status reports and risk register
- **Developers**: specify instrumentation requirements as acceptance criteria on tickets
- **Stakeholders**: present dashboards and analysis in milestone reviews
- **Retrospectives**: provide data-driven evidence for what worked or didn't in the last cycle

---

## Sponsor

### Role Summary
The Sponsor is the senior stakeholder who champions the business case for a project, secures resources, and removes organizational blockers that the PM and PdM cannot resolve on their own.

### Responsibilities
- Formally authorize the project and secure budget and headcount
- Break organizational deadlocks when escalated by the PM
- Champion the initiative with executive leadership and external stakeholders
- Give go/no-go decisions at defined decision gates (e.g., Initiation → Planning, Release)
- Review milestone summaries and hold the team accountable to committed outcomes

### Goals
- Ensure the project delivers expected business value
- Protect team capacity and remove systemic blockers
- Align the initiative with broader organizational strategy

### Typical Interactions
- **Project Managers**: receive escalated blockers and risk register updates; provide decisions on escalated issues
- **Product Managers**: validate and support business case, product strategy, and trade-off decisions
- **Stakeholders**: represent the initiative at the executive or cross-org level
- **Initiation / Decision Gate**: formally approve moving from initiation into planning and from planning into execution
- **Risk Register**: final owner of accepted risks that exceed the PM's authority to manage

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with a vested interest in the project outcome. They may represent business functions (support, sales, compliance, operations, legal) or external parties (customers, partners, regulators). Stakeholders provide requirements, feedback, and approvals from their functional perspective and are kept appropriately informed throughout the lifecycle.

### Responsibilities
- Provide input on requirements and constraints from their functional domain
- Review and approve deliverables or decisions within their remit (e.g., legal sign-off, compliance review)
- Participate in milestone demos and provide actionable feedback
- Escalate concerns through defined channels rather than ad hoc interrupts to the delivery team
- Accept or sign off on delivered work as part of release readiness

### Goals
- Ensure the project outcome meets their functional needs and organizational constraints
- Stay informed on progress, risks, and decisions that affect their area
- Provide timely decisions and approvals to avoid blocking delivery

### Typical Interactions
- **Project Managers**: receive periodic status updates, risk communications, and milestone summaries
- **Product Managers**: provide requirements and trade-off inputs; participate in roadmap reviews
- **Sponsor**: escalate cross-functional blockers or strategic concerns
- **Release Checklist**: sign off as required by their function before a release goes to production
- **Retrospectives**: may be invited to provide external perspective on outcome quality and collaboration

---

## Engineering Manager / Tech Lead

### Role Summary
The Engineering Manager (EM) or Tech Lead provides technical leadership, guides architectural decisions, and supports developer growth. They serve as the primary interface between the engineering team and PM/PdM on technical feasibility and trade-offs.

### Responsibilities
- Own architectural decisions and technical standards for the team
- Review and approve significant technical designs before implementation begins
- Partner with the PM and PdM on scope, feasibility, and effort estimation
- Manage engineering capacity, hiring, and skills development
- Identify and escalate technical risks to the Project Manager

### Goals
- Maintain a healthy, maintainable codebase and platform
- Enable sustainable delivery velocity without accumulating unmanageable technical debt
- Grow engineers' skills and ownership

### Typical Interactions
- **Developers**: provide technical mentorship, code review guidance, and architectural oversight
- **Product Managers**: align on technical trade-offs, feasibility, and non-functional requirements
- **Project Managers**: surface technical risks and dependencies for the risk register
- **Risk Register**: co-own entries related to technical debt, platform stability, and security
- **Sprint Planning**: confirm capacity and flag dependencies or technical constraints

---

## QA / Test Lead

### Role Summary
The QA/Test Lead owns the testing strategy and quality bar for the project. They ensure that acceptance criteria are testable, that automation coverage is sufficient, and that releases meet the quality standards required before deployment.

### Responsibilities
- Define and maintain the test strategy, including automation, manual, and performance testing
- Collaborate with developers and PdM to ensure acceptance criteria are specific and testable
- Review PRs for testability and flag missing test coverage
- Execute or coordinate QA sign-off as part of the release checklist
- Track and triage defects; escalate blockers to the PM

### Goals
- Prevent regressions from reaching production
- Reduce manual testing effort through automation investment
- Ensure every release has a clear quality sign-off trail

### Typical Interactions
- **Developers**: pair on test design, review automated test coverage, and triage defects together
- **Product Managers**: validate acceptance criteria are testable; raise ambiguity early
- **Project Managers**: report defect counts and blockers in status updates; flag release readiness risks
- **UX/UI Designers**: coordinate usability and accessibility test scenarios
- **Release Checklist**: own the QA sign-off gate before each production release
- **Retrospectives**: report on quality trends and propose improvements to test processes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Use the [RACI-Lite Matrix Template](./octoacme-raci-template.md) to map responsibilities across these roles for your specific project.

