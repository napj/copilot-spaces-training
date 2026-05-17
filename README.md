# OctoAcme Project Management Documentation

Welcome to the OctoAcme Project Management Docs — your central reference for every process, template, and best practice used by the team.

OctoAcme follows a clear project lifecycle: Initiation → Planning → Execution → Release → Retrospective. Work begins with a short one‑pager that confirms the business need, success metrics, stakeholders, and a high‑level timeline. Approved initiatives move into planning where the team breaks work into prioritized, estimated backlog items with acceptance criteria and a documented Definition of Done. Planning includes a kickoff, backlog grooming, and a release plan identifying dependencies and risks.

Execution focuses on iterative delivery of small, testable increments. Teams track work on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and use a pull request workflow that encourages small PRs, links to issues and acceptance criteria, and requires CI checks and at least one approval before merging. Roles are explicit: Project Managers coordinate delivery and communications; Product Managers define outcomes and prioritize; Developers implement and test; QA validates acceptance criteria; Stakeholders provide input and approvals. This clarity of ownership keeps work moving and simplifies escalation.

Quality assurance is integrated across the workflow: unit and integration tests, end‑to‑end smoke tests for critical flows, and security scanning run in CI before merges. Pre‑release checklists require passing CI and security scans, release notes, rollback plans, and smoke tests on staging; post‑deploy verification and monitoring dashboards (velocity, burndown, errors/latency/usage) inform release health. Retrospectives capture action items with owners and due dates and feed improvements back into the backlog so the process continually evolves.

## Documentation index

- [Project Management Overview](octoacme-project-management-overview.md) — Principles, roles, lifecycle, key artifacts
- [Project Initiation Guide](octoacme-project-initiation.md) — One-pager template, stakeholder alignment checklist
- [Project Planning](octoacme-project-planning.md) — Backlog templates, estimation, planning checklist
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Team rhythm, PR workflow, metrics and reporting
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Release types, checklists, rollback playbook
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Retros structure and action tracking
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk register format, communication templates
- [Roles & Personas](octoacme-roles-and-personas.md) — Role descriptions and typical responsibilities

## How to use
- New teammate: Start with the Project Management Overview.
- Initiating a project: Follow the Initiation Guide and create the one-pager in the project repo.
- Updating process docs: Use the .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml template to propose changes.

_Last updated: 2026-05-17_
