# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.
It also lists additional personas commonly involved in cross-functional delivery and describes how they interact
with existing roles.

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

## Additional Personas (proposed additions)

These personas augment the existing core roles for clearer ownership and handoffs across delivery, ops, design, and business functions. For each persona we list: primary responsibilities, key deliverables, interactions with existing roles, and a short onboarding checklist.

### Engineering Lead
- Responsibilities:
  - Own technical direction for a feature area or service.
  - Make architecture and trade-off decisions with input from architects and developers.
  - Mentor engineers and ensure code quality and consistency.
- Key deliverables:
  - Technical designs, architecture decisions, high-level estimates, and release readiness sign-off.
- Interactions:
  - Works closely with Developers, Product Manager (PdM) for prioritization, Project Manager (PMgr) for scheduling, and Architect for cross-service considerations.
- Onboarding (30/90 days):
  - 30d: Review architecture docs and active work; meet dev leads.
  - 90d: Own technical roadmap for assigned area; propose improvements.

### Release / CI Engineer
- Responsibilities:
  - Maintain CI/CD pipelines and release automation.
  - Produce deployment runbooks and rollback procedures.
  - Coordinate release validations and post-deploy checks.
- Key deliverables:
  - Release pipeline configurations, deployment checklists, automated verifications.
- Interactions:
  - Coordinates with Developers for pipeline changes, QA for release validation, SRE for production readiness, and PM for release windows.
- Onboarding:
  - 30d: Review pipelines and current release cadence.
  - 90d: Own a release and runbook for a minor release.

### Site Reliability Engineer (SRE)
- Responsibilities:
  - Maintain production reliability, monitoring, alerting, and on-call rotations.
  - Author runbooks and lead incident response.
- Key deliverables:
  - SLIs/SLOs, runbooks, incident postmortems, alert tuning.
- Interactions:
  - Partners with Developers and Release Engineer on reliability, with PM for risk/impact communication, and with Support for customer-impacting incidents.
- Onboarding:
  - 30d: Review monitoring and recent incidents.
  - 90d: Lead incident response and propose reliability improvements.

### UX Researcher / Designer
- Responsibilities:
  - Lead user research, interaction design, and prototyping.
  - Produce designs and acceptance criteria for usability.
- Key deliverables:
  - Research summaries, wireframes/prototypes, design specs, and accessibility checks.
- Interactions:
  - Works with PdM to define user needs, with Developers for handoffs, and QA for UX acceptance.
- Onboarding:
  - 30d: Review user journeys and recent research artifacts.
  - 90d: Deliver a validated prototype for an upcoming feature.

### Test Automation Engineer / QA Lead
- Responsibilities:
  - Define test strategy and automation approach.
  - Ensure coverage for critical flows and sign-off on quality gates.
- Key deliverables:
  - Test plans, automation suites, QA reports, and test criteria for releases.
- Interactions:
  - Coordinates with Developers for testability, PdM for acceptance criteria, and Release Engineer for release validation.
- Onboarding:
  - 30d: Evaluate current test coverage and flaky tests.
  - 90d: Implement automation for a key flow and enforce quality gates.

### Data Analyst / Analytics Owner
- Responsibilities:
  - Define product metrics and instrument telemetry.
  - Build dashboards and analyze outcomes against success criteria.
- Key deliverables:
  - Metric specifications, dashboards, and periodic analysis reports.
- Interactions:
  - Works with PdM to define success metrics, with Developers to implement instrumentation, and with PM for reporting cadence.
- Onboarding:
  - 30d: Inventory existing dashboards and events.
  - 90d: Own a dashboard used to validate a release.

### Security / Compliance Owner
- Responsibilities:
  - Review designs for security and compliance, run security scans, and manage remediation.
- Key deliverables:
  - Security checklists, scan results, compliance evidence, and risk mitigation plans.
- Interactions:
  - Partners with Developers for fixes, with PdM/PM for risk communication, and with SRE for operational security.
- Onboarding:
  - 30d: Review security posture and open findings.
  - 90d: Implement remediation tracking for one major finding.

### Architect (Systems Architect)
- Responsibilities:
  - Guide system-level design, cross-team integration, and long-term technical strategy.
  - Ensure consistency and manage cross-service dependencies.
- Key deliverables:
  - Architecture diagrams, interface contracts, and cross-team dependency plans.
- Interactions:
  - Advises Engineering Leads, coordinates with PdM and PM on cross-team scheduling, and escalates to leadership for trade-offs.
- Onboarding:
  - 30d: Map service boundaries and key dependencies.
  - 90d: Propose architecture improvements for upcoming milestones.

### Support Liaison / Customer Success Rep
- Responsibilities:
  - Act as the bridge between support/customers and the product/engineering teams.
  - Prioritize and communicate operational issues and customer-impacting bugs.
- Key deliverables:
  - Triage notes, bug prioritization, customer-impact assessments.
- Interactions:
  - Works with PM for prioritization, SRE for incident handling, and Developers for fixes/patches.
- Onboarding:
  - 30d: Review top support tickets and escalation paths.
  - 90d: Own communication for an incident/customer escalation.

### Business Stakeholder / Sponsor
- Responsibilities:
  - Provide strategic context, approve scope and funding, and make priority decisions.
- Key deliverables:
  - Sign-off on major milestones, budget approval, and strategic guidance.
- Interactions:
  - Engages with PdM and PM for status, risks, and decisions.
- Onboarding:
  - 30d: Read project charter and metrics.
  - 90d: Participate in milestone reviews and provide feedback.

---

## Onboarding checklist (per persona) — template
Use a short checklist per persona to make onboarding consistent.

- First 7 days: Intro meetings with PM, PdM, and core team; access to repos and systems
- First 30 days: Review relevant docs, attend working meetings, and own a small deliverable
- First 90 days: Full ownership of role-specific deliverable and present a short status to PM/PdM

Include this checklist under each persona in the expanded roles doc.

---

## Example scenarios / handoffs (brief)

- Design -> Development -> Release
  - UX Researcher/Designer provides prototype and acceptance criteria to PdM.
  - PdM finalizes scope and success metrics; Engineering Lead and Developers estimate and implement.
  - Release/CI Engineer validates the pipeline; QA Lead runs release validation; SRE approves production rollout.
  - Support Liaison prepares customer communications if needed.

- Incident triage (production outage)
  - SRE detects/triages incident and notifies on-call Developers and Release Engineer (if rollback needed).
  - Support Liaison and PM communicate customer impact and status.
  - Security Owner is engaged if security implications exist.
  - Post-incident, SRE + Developers produce a blameless postmortem; PM assigns action items.

---

## How to use this doc
- Expand each persona into a dedicated subsection with:
  - Primary responsibilities
  - Key deliverables
  - Interaction matrix (who they coordinate with)
  - 30/90-day onboarding checklist
  - Example scenario(s)
- Cross-link responsibilities to other process docs (planning, release, incident playbook).
- Track changes via a PR that references the corresponding process doc issue (e.g., Closes #4).
