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

## Technical Lead

### Role Summary
Technical Leads provide technical direction, make architecture decisions, and guide implementation quality. They ensure major design changes are reviewed and technical debt is tracked with clear remediation plans.

### Responsibilities
- Define and communicate technical direction for the team
- Review architecture and major design changes
- Partner with Developers on implementation approaches
- Track and prioritize technical debt with delivery timelines
- Identify and escalate cross-team technical dependencies

### Goals
- Maintain architectural integrity and scalability
- Balance delivery speed with long-term maintainability
- Reduce risk from unmanaged technical debt

### Typical Communication
- Technical design reviews and architecture decision records
- Feasibility and trade-off discussions with PM and Product
- Dependency escalation updates with Project Managers

### Interaction with Existing Roles
- Works closely with Developers on design and implementation details
- Advises Product Managers and Project Managers on feasibility and trade-offs
- Escalates cross-team technical dependencies to Project Managers for coordination

---

## Release Manager

### Role Summary
Release Managers coordinate release windows and readiness activities. They own release checklists, deployment runbooks, rollback plans, and release communications.

### Responsibilities
- Plan and coordinate release windows with participating teams
- Maintain deployment runbooks and rollback procedures
- Ensure release checklist completion and sign-offs
- Coordinate go/no-go decisions with stakeholders
- Communicate release status and outcomes

### Goals
- Deliver predictable, low-risk releases
- Minimize release-related incidents and rollbacks
- Maintain clear and timely communication throughout release cycles

### Typical Communication
- Release readiness meetings and go/no-go updates
- Deployment checklist tracking and handoff notes
- Release status updates to project and product stakeholders

### Interaction with Existing Roles
- Coordinates schedules and acceptance criteria with Developers, QA/Testing, SRE, and Product Managers
- Aligns with Project Managers on release timing and dependencies
- Shares release status, risks, and completion outcomes with Project Managers

---

## Site Reliability Engineer (SRE) / Operations Owner

### Role Summary
SREs and Operations Owners are responsible for production reliability and service operations. They manage runbooks, monitoring, alerting, on-call processes, and capacity planning.

### Responsibilities
- Define and maintain production runbooks and incident procedures
- Build and tune monitoring, alerts, and service health indicators
- Manage on-call readiness and operational handoffs
- Plan for capacity, performance, and reliability targets
- Drive operational improvements from incidents and trends

### Goals
- Improve system reliability and uptime
- Reduce mean time to detect and resolve incidents
- Ensure environments are operationally consistent and supportable

### Typical Communication
- Incident updates, post-incident reviews, and action item tracking
- Reliability reviews and operational risk briefings
- Environment readiness and observability alignment sessions

### Interaction with Existing Roles
- Collaborates with Developers on observability instrumentation and operational readiness
- Enables QA/Testing through staging environment parity and reliability checks
- Advises Project Managers on operational risks and mitigation plans

---

## Security Lead / Security Representative

### Role Summary
Security Leads provide security governance across the delivery lifecycle. They drive threat modeling, security reviews, vulnerability triage, and compliance alignment.

### Responsibilities
- Conduct threat modeling for new features and architecture changes
- Perform security reviews for designs and implementations
- Triage vulnerabilities and track remediation timelines
- Ensure required security scans and compliance controls are addressed
- Escalate critical risks and mitigation plans to delivery leadership

### Goals
- Reduce security risk in released solutions
- Ensure timely remediation of high-priority vulnerabilities
- Maintain compliance with organizational and regulatory requirements

### Typical Communication
- Security review notes and risk assessment summaries
- Vulnerability triage updates and remediation tracking
- Compliance status and mitigation timeline reports

### Interaction with Existing Roles
- Conducts security reviews with Developers and the Technical Lead
- Collaborates with Project Managers on risk prioritization and scheduling
- Informs Project Managers of security risks and mitigation timelines

---

## UX / Design Lead

### Role Summary
UX and Design Leads ensure solutions are usable, accessible, and consistent with user needs. They run user research, conduct design reviews, and provide implementation-ready design artifacts.

### Responsibilities
- Lead user research and synthesize usability insights
- Produce and maintain design artifacts for handoff
- Conduct accessibility checks and design quality reviews
- Validate implemented experiences against intended design outcomes
- Refine interaction patterns based on feedback and testing

### Goals
- Improve user satisfaction and task completion success
- Ensure accessibility and design consistency
- Reduce rework caused by unclear or incomplete design handoffs

### Typical Communication
- Design review sessions and usability findings readouts
- Handoff documentation and acceptance criteria alignment
- UI/UX fidelity feedback during implementation and QA

### Interaction with Existing Roles
- Partners with Product Managers to define user needs and acceptance criteria
- Collaborates with Developers during implementation to preserve UX intent
- Works with QA/Testing to validate UI/UX fidelity and accessibility outcomes

---

## Data Analyst / Measurement Owner

### Role Summary
Data Analysts and Measurement Owners define how success is measured and reported. They create metrics frameworks, dashboards, and analyses that inform decisions and prioritization.

### Responsibilities
- Define success metrics and measurement frameworks
- Specify instrumentation and telemetry requirements
- Build dashboards and recurring performance reports
- Analyze feature impact and operational outcomes
- Communicate insights to guide roadmap and execution decisions

### Goals
- Ensure decisions are grounded in reliable data
- Improve visibility into product and delivery outcomes
- Close measurement gaps through effective instrumentation

### Typical Communication
- Metrics definitions and dashboard reviews
- Impact analysis summaries and stakeholder reports
- Telemetry requirement alignment with engineering teams

### Interaction with Existing Roles
- Partners with Product Managers to define and track success metrics
- Reports outcome trends and insights to Project Managers and stakeholders
- Advises Developers on telemetry requirements and instrumentation quality

---

## Business Analyst / Requirements Owner

### Role Summary
Business Analysts and Requirements Owners translate stakeholder needs into clear, actionable requirements. They maintain traceability from goals to implementation and acceptance criteria.

### Responsibilities
- Elicit and document detailed functional and non-functional requirements
- Define acceptance criteria, edge cases, and business rules
- Maintain traceability between requirements, delivery items, and outcomes
- Support backlog refinement and requirement prioritization
- Clarify implementation questions during delivery

### Goals
- Reduce ambiguity in requirements and acceptance criteria
- Improve delivery predictability through well-defined scope
- Ensure stakeholder intent is accurately reflected in implementation

### Typical Communication
- Backlog grooming and requirements walkthrough sessions
- Requirement updates with traceability notes
- Clarification responses for delivery and testing teams

### Interaction with Existing Roles
- Works closely with Product Managers and Project Managers on backlog refinement and prioritization
- Coordinates with Developers to resolve requirement and edge-case questions
- Aligns with QA/Testing on testable acceptance criteria

---

## Customer Success / Support Liaison

### Role Summary
Customer Success and Support Liaisons represent customer operational needs and post-release feedback. They surface recurring support trends, coordinate rollout messaging, and feed insights into planning.

### Responsibilities
- Collect and synthesize recurring customer support issues
- Represent customer operational concerns in planning and release decisions
- Coordinate beta, rollout, and support readiness communications
- Escalate customer-impacting incidents and adoption risks
- Track feedback themes for continuous improvement

### Goals
- Improve customer adoption and satisfaction during releases
- Reduce repeat support issues through earlier feedback loops
- Ensure customer communications are timely and actionable

### Typical Communication
- Support trend summaries and incident impact reports
- Customer readiness and rollout communication plans
- Feedback loops into planning and retrospective discussions

### Interaction with Existing Roles
- Feeds customer feedback and incidents to Project Managers and Product Managers
- Coordinates rollout and support communications with Release Managers
- Shares recurring operational pain points with Developers for product improvements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions across product, delivery, operations, and support workflows in the Skills Exercise.
- Each persona can be used as a role-specific Copilot Spaces prompt to simulate planning, execution, release, and retrospective collaboration.
- Cross-functional interactions in this document can be used to model ownership boundaries, escalation paths, and decision handoffs.

---

## Role Interaction Matrix

| Role | Initiation | Planning | Execution | Release | Retrospective |
| --- | --- | --- | --- | --- | --- |
| Developers | Collaborate with Product Managers and Technical Lead on feasibility | Estimate work with Project Managers and Business Analyst | Implement features with Technical Lead, UX/Design Lead, and Security Lead | Support Release Manager and SRE during deployment | Review outcomes with Project Managers and Data Analyst |
| Product Managers | Define initial outcomes with Project Managers and Customer Success/Support Liaison | Prioritize scope with Business Analyst, Technical Lead, and Data Analyst | Clarify priorities with Developers and UX/Design Lead | Confirm acceptance criteria with Release Manager and QA/Testing | Assess impact with Data Analyst and Project Managers |
| Project Managers | Establish scope, risks, and cadence with Product Managers and Technical Lead | Coordinate timelines and dependencies with all roles | Manage delivery risks and cross-team communication | Track release status with Release Manager and SRE | Facilitate retrospectives and improvement actions |
| Technical Lead | Review architecture options with Developers and Product Managers | Guide design trade-offs with Business Analyst and Security Lead | Support implementation reviews with Developers | Advise Release Manager and SRE on technical risk | Identify technical debt follow-ups with Project Managers |
| Release Manager | Gather release constraints from Project Managers and SRE | Build release plan with Developers, QA/Testing, and Product Managers | Track release readiness and checklist completion | Lead go/no-go, deployment communication, and rollback decisions | Share release outcomes and improvements with Project Managers |
| Site Reliability Engineer (SRE) / Operations Owner | Define operational constraints with Technical Lead and Project Managers | Align monitoring and runbook requirements with Developers | Monitor reliability and support incident response with Developers | Partner with Release Manager on deployment safety and rollback readiness | Drive reliability improvements with Developers and Project Managers |
| Security Lead / Security Representative | Highlight security/compliance constraints with Product Managers and Technical Lead | Perform threat modeling with Developers and Business Analyst | Triage vulnerabilities and validate controls with Developers | Verify security gates with Release Manager and SRE | Report risk trends and remediation progress to Project Managers |
| UX / Design Lead | Bring user research insights to Product Managers | Define UX requirements with Business Analyst and Product Managers | Review implementation fidelity with Developers and QA/Testing | Validate release-ready experience with Product Managers | Provide usability insights for improvement planning |
| Data Analyst / Measurement Owner | Propose baseline metrics with Product Managers | Define instrumentation requirements with Developers and Business Analyst | Validate telemetry and publish progress dashboards | Report release impact with Product Managers and Customer Success/Support Liaison | Present outcome analysis for retrospective decisions |
| Business Analyst / Requirements Owner | Capture stakeholder needs with Product Managers and Customer Success/Support Liaison | Define detailed requirements and edge cases with Project Managers | Clarify implementation details for Developers and QA/Testing | Confirm requirement coverage with Release Manager | Update requirement traceability with Project Managers |
| Customer Success / Support Liaison | Share customer pain points with Product Managers and Project Managers | Align rollout/support needs with Release Manager and Business Analyst | Surface recurring issues to Developers and Product Managers | Coordinate customer communications with Release Manager | Feed support trends into retrospective actions with Data Analyst |
