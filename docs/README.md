# OctoAcme Project Management Docs

Welcome to OctoAcme's centralized project management documentation. These guides provide the processes, templates, and best practices used to run successful projects.

## Quick Navigation

### Core Concepts
- [Project Management Overview](./octoacme-project-management-overview.md) — High-level approach, principles, roles, and lifecycle
- [Roles & Personas](./octoacme-roles-and-personas.md) — Definitions of key team members and responsibilities

### Project Lifecycle
1. **Initiation** → [Project Initiation Guide](./octoacme-project-initiation.md)
2. **Planning** → [Project Planning](./octoacme-project-planning.md)
3. **Execution & Tracking** → [Execution & Tracking Guide](./octoacme-execution-and-tracking.md)
4. **Release & Deployment** → [Release & Deployment Guide](./octoacme-release-and-deployment.md)
5. **Close & Retrospective** → [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

### Cross-cutting Concerns
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks and dependencies

## OctoAcme Process Summary

OctoAcme follows a customer-first, iterative delivery model with clear ownership and data-informed decisions. Projects move through five phases:

- **Initiation**: Validate business need, align stakeholders, define success criteria
- **Planning**: Break work into shippable increments, identify dependencies, establish timelines
- **Execution**: Build, test, review, and iterate with daily standups and weekly syncs
- **Release**: Deploy to production with pre-release verification and rollback plans
- **Retrospective**: Capture learnings and drive continuous improvement

Key principles include customer focus, iterative delivery, clear ownership (PM + PdM), data-informed decisions, and psychological safety.

### Key Workflows and Practices

**Roles and Responsibilities**: OctoAcme defines clear ownership through four core personas. **Project Managers** coordinate schedules, risks, and communications to ensure on-time delivery; **Product Managers** define what to build by prioritizing the roadmap and measuring success; **Developers** implement features, write tests, and identify technical risks; and **QA/Testing** validates quality and acceptance criteria.

**Communication**: Communication is structured and frequent—weekly syncs between PM and Product Manager, twice-weekly team standups, monthly stakeholder updates, and ad-hoc escalations following a clear escalation path (team → PM → Product Lead → Sponsor). A single source of truth (project README or release doc) ensures all stakeholders have visibility into progress, risks, and decisions.

**Quality Assurance**: Quality is embedded throughout the delivery process via unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, security scanning in CI, and manual QA for feature acceptance. The team maintains a Risk Register throughout the project lifecycle—identifying risks during planning and ongoing execution, assessing impact and likelihood, implementing mitigations, and monitoring status at weekly syncs. A Definition of Done is documented for each sprint, and acceptance criteria are clearly defined in every backlog item.

**Execution Framework**: Day-to-day execution relies on a disciplined workflow: small pull requests (≤400 lines when possible) linked to issues with clear acceptance criteria, automated tests and linting before review, and at least one approval before merge. The project board uses standardized columns (Backlog, Ready, In Progress, In Review, QA, Done) to provide real-time visibility, and velocity and burndown metrics are tracked to inform planning and decision-making.

## Getting Started

- **New team member?** Start with [Project Management Overview](./octoacme-project-management-overview.md) and [Roles & Personas](./octoacme-roles-and-personas.md)
- **Starting a new project?** Begin with the [Project Initiation Guide](./octoacme-project-initiation.md)
- **In execution?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management](./octoacme-risks-and-communication.md)
- **Wrapping up?** See [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
