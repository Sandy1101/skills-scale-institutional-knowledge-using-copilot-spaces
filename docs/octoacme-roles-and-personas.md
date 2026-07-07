# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Engineering Lead

Responsibilities:
- Technical ownership of the codebase and high-level architecture decisions within the project scope.
- Mentor and guide developers; enforce engineering standards and code quality.
- Review and approve major technical designs and coordinate cross-repo or cross-team technical dependencies.

Interactions:
- Works with the Product Manager (PdM) and Project Manager (PM) to translate product requirements into a technical scope and acceptable technical tradeoffs.
- Coordinates with Developers and QA to align on implementation approach, testability, and acceptance criteria.
- Escalates significant technical risks or resource needs to the Product Lead.

---

## Release Engineer

Responsibilities:
- Maintain and improve release pipelines and automation.
- Define and own release steps, rollback plans, and runbooks for deployment.
- Ensure release checklists are followed and coordinate pre-release verifications.

Interactions:
- Collaborates with Developers and QA for pre-release verification and staging validation.
- Coordinates deployment windows with the PM and communicates release status to stakeholders and Support.
- Works with Observability/Oncall Lead to confirm monitoring and alerting are in place for releases.

---

## UX Researcher / Designer

Responsibilities:
- Lead user research, create prototypes and final designs, and validate designs with users.
- Produce UX acceptance criteria and accessibility considerations as part of backlog items.
- Support usability testing and provide recommendations to improve UX outcomes.

Interactions:
- Works with PdM to define user outcomes and success metrics.
- Partners with Developers to ensure designs are feasible and with QA to validate UX-related acceptance criteria.

---

## Data Analyst

Responsibilities:
- Define success metrics and measurement plans for features and releases.
- Instrument events and build dashboards to track impact.
- Analyze release impact and recommend product or process adjustments.

Interactions:
- Partners with PdM to set and validate success metrics.
- Provides telemetry requirements to Developers and insights for Retrospectives.

---

## Support Liaison

Responsibilities:
- Act as the bridge between Engineering and Support teams for customer issues and incidents.
- Triage customer reports, maintain customer-facing communications during incidents, and maintain runbooks.
- Ensure high-priority customer issues are fed back into the backlog with clear owners.

Interactions:
- Works with PM and Engineers during incidents, coordinates post-incident communications, and contributes to prioritization decisions when customer impact is high.

---

## Observability / Oncall Lead

Responsibilities:
- Define monitoring, logging, and alerting requirements for services.
- Maintain on-call rotations, runbooks, and incident response coordination.
- Lead post-incident reviews for operational issues and track remediation items.

Interactions:
- Collaborates with Developers and Release Engineer to ensure systems are observable before release.
- Escalates operational risks to the PM and Product Lead and coordinates operational readiness activities.

(End of additions — keep existing persona entries; place these as new subsections.)
