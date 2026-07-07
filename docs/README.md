# OctoAcme Project Management Docs

This folder contains OctoAcme's program and project management process documents. The README centralizes navigation, provides a short summary of the core processes, and links directly to each document so new teammates can quickly find the guidance they need.

## Overview
OctoAcme uses a lightweight, iterative lifecycle that moves from Initiation → Planning → Execution → Release → Retrospective. Initiation captures the problem, success metrics, stakeholders, and a high-level timeline (Project One-pager). Planning breaks approved work into shippable increments with estimates, acceptance criteria, and a release/milestone plan. Execution emphasizes small, reviewable work (small PRs), a project board to track state (Backlog → Ready → In Progress → In Review → QA → Done), and continuous integration to enforce quality. Retrospectives close the loop by converting learnings into tracked action items.

## Key workflows
- Backlog and sprint planning: Prioritized backlog items with clear acceptance criteria and sizing; pull items into an iteration that meet the Definition of Done and fit team capacity.
- Pull request and review flow: Small PRs where possible, pass CI and security scans before requesting review, and require approvals per team policy.
- Release & deployment: Pre-release checks (acceptance criteria, CI, security), staging smoke tests, automated production deploys when possible, and rollback plans for incidents.

## Personas & responsibilities
- Product Manager (PdM): defines outcomes, success metrics, and prioritization.
- Project Manager (PM): coordinates schedules, risk registers, and stakeholder communications.
- Developers: implement features, write tests, and participate in code reviews.
- QA/Testing: validate acceptance criteria through unit/integration/manual testing as required.

## Communication & quality practices
- Cadence: daily standups for blockers/progress, weekly delivery syncs, and end-of-sprint demos or reviews.
- Risk & escalation: a maintained Risk Register with weekly reviews; escalation path is Team → PM → Product Lead → Sponsor.
- Quality: unit tests for new logic, integration tests where appropriate, end-to-end smoke tests before release, security scanning in CI, and manual QA for feature acceptance when needed.

## Quick links
- Project Management Overview — ./docs/octoacme-project-management-overview.md
- Project Initiation Guide — ./docs/octoacme-project-initiation.md
- Project Planning — ./docs/octoacme-project-planning.md
- Execution & Tracking — ./docs/octoacme-execution-and-tracking.md
- Risks & Communication — ./docs/octoacme-risks-and-communication.md
- Release & Deployment — ./docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement — ./docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas — ./docs/octoacme-roles-and-personas.md
