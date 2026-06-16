# OctoAcme Project Management Docs

This README provides a single entry point to OctoAcme's project management process documents. It summarizes each document and links to the full content in the `docs/` folder.

## OctoAcme Project Management Overview

OctoAcme follows a structured, customer-first lifecycle that spans five phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. During Initiation, the team validates business need through a Project One-pager, identifies stakeholders, and decides whether to proceed. Planning transforms approved initiatives into actionable backlogs by breaking work into shippable increments, estimating scope, and mapping dependencies and milestones. Execution centers on day-to-day delivery using GitHub Projects with a pull request workflow, daily standups, and weekly syncs to track progress and surface blockers. Release standardizes the path to production with pre-deployment checklists, smoke testing, and clear rollback procedures. Finally, Retrospectives capture learnings after each sprint or milestone and convert them into measurable improvements, closing the feedback loop.

The organizational structure emphasizes clear ownership across three core roles: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes, prioritize the backlog, and measure success; and **Developers** implement features, write tests, and collaborate on design and quality. This separation of concerns ensures that planning, delivery, and product strategy remain aligned while distributed teams maintain psychological safety and ownership. All work is guided by a Definition of Done, acceptance criteria, and a shared commitment to data-informed decisions.

Quality and risk management are embedded throughout the lifecycle. Execution includes unit tests, integration tests, security scanning in CI, and manual QA for feature acceptance. A formal **Risk Register** captures identified threats with impact assessments and mitigation plans, reviewed weekly during syncs. Risk escalation follows a three-level hierarchy: team-level triage in standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues. Stakeholder communication uses a consistent weekly status template covering progress, blockers, risks, and decisions needed, while incident communication triggers a blameless retrospective and formal triage.

Communication cadence is disciplined and repeatable: daily standups (15 minutes) focus on progress and blockers, weekly delivery syncs show demos and flag risks, weekly PM/PdM alignment ensures product and project strategies stay synchronized, and monthly stakeholder updates keep executives informed. This rhythm, combined with lightweight but comprehensive artifact templates (One-pagers, Risk Registers, Release Notes, Retrospective Action Items), enables OctoAcme to scale institutional knowledge, reduce single-person dependency risk, and maintain transparency across all team members.

## Process Documents

Navigate to the documents below for detailed guidance on each phase and practice area:

| Document | Purpose | Path |
|----------|---------|------|
| **OctoAcme Project Management Overview** | Overview of principles, roles, lifecycle, and how to use the process docs | [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) |
| **Project Initiation Guide** | Steps and minimum deliverables to validate and authorize new projects | [octoacme-project-initiation.md](./octoacme-project-initiation.md) |
| **Project Planning** | How to turn an approved idea into a plan and backlog with milestones and risks | [octoacme-project-planning.md](./octoacme-project-planning.md) |
| **Execution & Tracking** | Team rhythm, workflows, PR conventions, quality and tracking guidance | [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) |
| **Risk Management & Communication** | Risk register, lifecycle, stakeholder communication, and escalation paths | [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) |
| **Release & Deployment** | Release types, pre-release checks, deployment checklist, and rollback playbook | [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) |
| **Retrospective & Continuous Improvement** | Running retros, tracking action items, and measuring improvements | [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) |
| **Roles & Personas** | Role summaries and responsibilities used across the OctoAcme process docs | [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) |

## Purpose

Centralize process knowledge so team members can find, reference, and contribute to OctoAcme project management guidance. Additions or updates to process docs should follow the repository's [process doc update template](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml).

## Getting Started

- **New to OctoAcme?** Start with [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
- **Need role clarity?** See [Roles & Personas](./octoacme-roles-and-personas.md)
- **Managing risks?** Consult [Risk Management & Communication](./octoacme-risks-and-communication.md)
