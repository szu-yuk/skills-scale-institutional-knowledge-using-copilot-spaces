# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management knowledge base. This documentation centralizes our project management processes so teams can deliver value consistently, maintain transparency, and support organizational learning. Use this README as the starting point to find lifecycle guidance, role definitions, communication templates, and process checklists.

## Brief overview of OctoAcme project management processes

This summary is derived from the OctoAcme process documents stored in docs/. OctoAcme runs projects with an iterative, customer-first mindset: projects start with a lightweight initiation (a Project One-pager to capture the problem, goal, success metrics, and stakeholders), move into planning to produce a prioritized, estimated backlog and Definition of Done, and then execute in small, shippable increments with a clear release and close/retrospective phase. Key artifacts—one-pagers, roadmaps/release plans, sprint backlogs, acceptance criteria, and a living risk register—are emphasized as the single sources of truth for decisions and status.

Workflows are centered on a project board and a disciplined pull request process. The project board uses columns like Backlog → Ready → In Progress → In Review → QA → Done, and PRs are expected to be small, linked to issues with acceptance criteria, pass CI (tests and linting), and require approvals before merging. Planning guidance covers kickoff, backlog grooming, estimation, and dependency identification so that execution pulls only items that meet the DoD. The release process enforces pre-release checks (passing CI/security scans, release notes, rollback plans) and a deployment checklist that includes staging smoke tests and post-deploy verifications.

Roles and communication are explicit: Product Managers own outcomes and success metrics, Project Managers coordinate delivery and risk, Developers implement and test, and QA validates acceptance criteria. The team rhythm documented includes brief daily standups for progress and blockers, a weekly delivery sync for progress and risk review, sprint/milestone demos, and monthly or milestone stakeholder updates. Communication templates (e.g., weekly status) and formal escalation paths (team → PM → Product Lead → Sponsor, with a separate path for security incidents) ensure consistent stakeholder engagement and transparent risk handling.

Quality assurance and risk management are treated as integral to delivery rather than afterthoughts. Testing expectations include unit and integration tests, end-to-end smoke tests for critical flows, CI-based security scanning, and manual QA when needed; these are reinforced in execution and release docs. The risk register captures ID, impact, likelihood, owner, mitigation, and status and is reviewed regularly. Finally, there is an ISSUE_TEMPLATE to propose updates so the practices remain living artifacts aligned with team learning.

## Workflows & processes (at-a-glance)

- Project lifecycle: Initiation → Planning → Execution & Tracking → Release & Deployment → Retrospective & Continuous Improvement
- Project board: Backlog → Ready → In Progress → In Review → QA → Done
- PR expectations: small PRs, link to issue and acceptance criteria, CI (tests, lint, security), approvals required
- Meetings: daily standups, weekly delivery syncs, sprint demos, retrospectives

## Roles & communication

- Product Manager (PdM): defines outcomes, prioritizes, measures success
- Project Manager (PM): coordinates delivery, schedules, risks, and stakeholder communication
- Developers: implement, write tests, participate in reviews
- QA: validate acceptance criteria, run test plans

## Quality & risk

- Testing: unit, integration, and smoke tests; require CI passes before merges
- Security: CI-based security scanning
- Risk register: ID, impact, likelihood, owner, mitigation, status
- Escalation: team → PM → Product Lead → Sponsor; security incidents follow Security runbook

## Table of contents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## Quick start

- New to OctoAcme PM? Start with the [Project Management Overview](octoacme-project-management-overview.md).
- Starting a new project? Read the [Project Initiation Guide](octoacme-project-initiation.md) and use the One-pager template.
- Preparing a release? Follow the [Release & Deployment](octoacme-release-and-deployment.md) checklist.

## How to contribute

- Keep these docs current: update when processes change.
- Use the [.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template to request edits or additions.
- Link relevant docs from issues, PRs, and project boards to keep the single source of truth discoverable.

## Acceptance criteria for this README

- Provides a clear entry point and short summary of OctoAcme PM processes.
- Links to all existing process documents in docs/.
- Includes guidance on how to use and contribute to the documentation.
