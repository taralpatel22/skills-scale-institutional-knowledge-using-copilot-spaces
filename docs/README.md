# OctoAcme Project Management Docs

This README centralizes OctoAcme's project management process documents and provides quick links and a short summary of the processes used across initiation, planning, execution, release, and continuous improvement. Use this as the single source of truth for process references and onboarding.

---

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-driven approach to project management, spanning five key phases: **Initiation, Planning, Execution, Release, and Retrospective**. Every project begins with a lightweight one-pager that defines the problem statement, SMART objectives, success metrics, and stakeholder alignment before any planning begins. A formal decision gate ensures teams only proceed to planning once success metrics are clear, stakeholders agree on priority, and team availability is confirmed. This disciplined entry point reduces wasted effort and keeps projects anchored to measurable business outcomes.

The team operates with **clearly defined personas and shared ownership** across five core roles: Project Manager (coordinates delivery, schedules, and risk), Product Manager (owns the backlog and success metrics), Developers (implement and test features), QA/Testing (validates acceptance criteria), and Stakeholders (provide inputs and approvals). Day-to-day execution is governed by a consistent team rhythm — daily 15-minute standups focused on progress and blockers, weekly delivery syncs to surface risks, and sprint-end demos. Work is tracked on a GitHub Projects board with columns (Backlog → Ready → In Progress → In Review → QA → Done), and pull requests are kept small (≤400 lines), linked to issues, and require at least one approval and passing CI before merging.

**Risk management and communication** are treated as continuous, first-class activities rather than one-time events. A living Risk Register captures each risk's impact, likelihood, owner, and mitigation plan, and is reviewed every week. Stakeholder communication follows a tiered cadence (weekly PM/PdM syncs, monthly stakeholder updates, ad-hoc escalations) using standardized templates for weekly status, incident updates, and escalation paths — from team-level triage all the way to sponsor-level escalation for business-impacting issues. A single source of truth (the project README or release doc) is maintained so all stakeholders have consistent, up-to-date information.

**Quality assurance and continuous improvement** are embedded throughout the lifecycle rather than bolted on at the end. The engineering workflow mandates unit tests, integration tests, end-to-end smoke tests for critical flows, and security scanning in CI. Releases — categorized as Patch, Minor, or Major — require all acceptance criteria met, passing CI, rollback plans, and staged deployment before production. After every sprint, release, or incident, the team holds a timeboxed retrospective (45–75 min) to capture what went well, what could improve, and 2–3 prioritized action items with owners and due dates. Those action items feed directly back into the project backlog, creating a feedback loop that drives iterative, evidence-based improvement across the organization.

---

## Quick Summary of Project Management Processes

| Phase | Key Activities |
|---|---|
| **Initiation** | Capture problem, stakeholders, one-pager, and go/no-go decision |
| **Planning** | Prioritize backlog, estimate, define Definition of Done, and map releases/milestones |
| **Execution & Tracking** | Daily standups, project board workflow, PR conventions, and CI checks |
| **Release & Deployment** | Pre-release checks, staging verification, release notes, and rollback playbook |
| **Retrospective & Continuous Improvement** | Regular retros, action items, and tracking improvements |
| **Risk & Communication** | Maintain a risk register, weekly stakeholder updates, and clear escalation paths |

---

## Links to Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risks & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

---

## How to Use

- Keep all process documents in `docs/` and update this README when adding or renaming documents.
- Use the [`.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template to propose changes to these docs.
