# OctoAcme Project Management Docs

## Overview

OctoAcme uses a structured, iterative lifecycle covering initiation, planning, execution, release, and retrospective improvement.

- **Initiation** uses a one-pager defining the problem, SMART goal, success metrics, stakeholders, timeline, risks, dependencies, and proposed team.
- **Planning** creates a prioritized backlog, acceptance criteria, Definition of Done, estimates, dependencies, milestones, and release plan.
- **Execution** uses a board with Backlog, Ready, In Progress, In Review, QA, and Done to track day-to-day delivery.
- **Release** follows a standardized deployment process to reduce risk and improve observability, including staging smoke tests, rollback planning, and post-deployment verification.
- **Retrospective & continuous improvement** happens after sprints, releases, and incidents, producing owned improvement actions.

## Roles & Personas

- **Project Managers** coordinate schedules, risks, resources, meetings, documentation, and stakeholder communications.
- **Product Managers** define outcomes, prioritize the roadmap/backlog, and measure success.
- **Developers** implement and test features, participate in estimation/reviews, and identify technical risks.
- **QA/Testing** validates acceptance criteria and quality.
- **Stakeholders** provide input, approvals, and feedback.

See [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) for full details.

## Communication & Risk Escalation

- Daily standups and weekly delivery/PM syncs keep teams aligned.
- Sprint or milestone demos/reviews and regular stakeholder updates keep everyone informed.
- Escalation flows from team to PM to Product Lead to sponsor when needed.
- Risks are tracked with impact, likelihood, owner, mitigation, and status.

See [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) for full details.

## Quality Assurance

Quality practices include unit tests for new logic, integration tests where appropriate, end-to-end smoke tests for critical flows, CI tests and linting, security scans, code review approvals, staging smoke tests, rollback planning, and post-deployment verification.

## Documentation Index

- [octoacme-project-management-overview.md](octoacme-project-management-overview.md) — Concise introduction to OctoAcme's project management approach, roles, and key artifacts.
- [octoacme-project-initiation.md](octoacme-project-initiation.md) — Initial steps to validate and authorize work, align stakeholders, and create a lightweight plan.
- [octoacme-project-planning.md](octoacme-project-planning.md) — Turning an approved initiative into an actionable plan and backlog for delivery.
- [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) — Guidance for managing day-to-day execution and tracking progress toward project milestones.
- [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks and dependencies.
- [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) — How OctoAcme releases features to production to reduce risk and improve observability.
- [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and converting them into actionable improvements.
- [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) — Typical roles and responsibilities used in OctoAcme project docs and exercises.
