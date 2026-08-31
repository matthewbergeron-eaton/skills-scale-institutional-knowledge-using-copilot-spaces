# OctoAcme Project Management Docs

## Overview
OctoAcme uses a structured project management approach centered on seven core processes that guide work from idea through closure. The approach emphasizes customer-first delivery, iterative increments, clear ownership, data-informed decisions, and psychological safety. This README is the central hub for process documentation and navigation for contributors and stakeholders.

## Quick Summary of Core Processes

1. Initiation
   - Capture the problem, objective, success metrics, and stakeholders in a Project One-pager. Use the one-pager to decide whether to move into planning.

2. Planning
   - Turn approved initiatives into an actionable plan: kickoff, prioritized backlog, estimates, Definition of Done, and a release timeline.

3. Execution & Tracking
   - Work through a project board (Backlog → Ready → In Progress → In Review → QA → Done), use small PRs with linked issues and acceptance criteria, hold daily standups, and track velocity and burndown.

4. Release & Deployment
   - Prepare releases with pre-release checks, smoke tests, deployment automation where possible, and a rollback/incident playbook.

5. Risks & Communication
   - Maintain a Risk Register, use weekly status templates for stakeholder updates, and follow escalation paths from team-level up to sponsor.

6. Retrospective & Continuous Improvement
   - Run timeboxed retrospectives after sprints/releases/incidents, create prioritized action items, and track improvements in the backlog.

7. Roles & Personas
   - Clear roles (Project Manager, Product Manager, Developers, QA/Testing, Stakeholders) define responsibilities for planning, delivery, quality, and communication.

## How to use these docs
- Start with the Project Management Overview for a high-level introduction.
- Follow the Project Lifecycle section below to find the process you need.

## Project Lifecycle & Links
- 📄 [Project Management Overview](./octoacme-project-management-overview.md)
- 📄 [Project Initiation Guide](./octoacme-project-initiation.md)
- 📄 [Project Planning](./octoacme-project-planning.md)
- 📄 [Execution & Tracking](./octoacme-execution-and-tracking.md)
- 📄 [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- 📄 [Risk Management & Communication](./octoacme-risks-and-communication.md)
- 📄 [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- 📄 [Roles & Personas](./octoacme-roles-and-personas.md)

## Brief Process Overview (from summary)
OctoAcme starts with a lightweight initiation that confirms business need and measurable outcomes, then moves into planning to build a prioritized, estimated backlog with acceptance criteria. Execution focuses on small, testable increments tracked on a project board, enforced by CI, PR conventions, and daily/weekly cadence. Releases are gated by pre-release checks, smoke tests, and rollback plans. Risks are monitored in a Risk Register and communicated via templates and escalation paths. Each sprint or release finishes with a retrospective to capture learnings and convert them into tracked action items.

## Contribution
To propose changes to these docs, use the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/. For updates, open an issue referencing this README and the target document.

## License / Ownership
Maintained by the OctoAcme PMs and Project Leads. Please coordinate major structural changes with the Project Manager.
