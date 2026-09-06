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

## Additional Personas

The following personas are commonly involved in project delivery and should be documented so teams have clearer ownership and handoff expectations.

### Technical Program Manager (TPM)

Role Summary
- Coordinates cross-team technical dependencies and complex program-level schedules. Focuses on sequencing and technical risk management across multiple teams.

Responsibilities
- Map technical dependencies across teams and maintain cross-team schedules
- Facilitate architecture and design coordination for multi-team work
- Track and escalate cross-team risks and blockers
- Drive program-level planning ceremonies and syncs

Goals
- Reduce cross-team integration surprises
- Keep cross-functional delivery on schedule
- Surface technical trade-offs early

Typical Communication
- Program-level standups, dependency syncs, design syncs

Interaction with existing roles
- PM: coordinate scheduling and milestone alignment
- PdM: align on scope trade-offs and delivery priorities
- Engineering Lead / Devs: coordinate technical sequencing and design handoffs

---

### Engineering Lead / Tech Lead

Role Summary
- Owns technical design decisions, architecture alignment, and engineering quality within a team or component area.

Responsibilities
- Make and communicate design and architecture decisions
- Mentor developers and champion code quality and maintainability
- Represent technical risks in planning and prioritization
- Coordinate cross-team technical interfaces

Goals
- Ensure technical consistency and scalable design
- Reduce rework caused by architectural mismatch
- Raise engineering standards and practices

Typical Communication
- Design reviews, architecture discussions, technical grooming

Interaction with existing roles
- Developers: lead implementation approach and reviews
- QA: define test strategy for complex areas
- PM: communicate technical risk and effort implications

---

### UX Researcher / Designer

Role Summary
- Owns user research, interaction design, and accessibility to ensure features meet user needs.

Responsibilities
- Conduct research and usability testing
- Produce wireframes, prototypes, and design specs
- Define accessibility and usability acceptance criteria
- Partner on feature prioritization with product

Goals
- Increase usability and product-market fit
- Reduce design rework post-development

Typical Communication
- Design critiques, user research summaries, handoff docs

Interaction with existing roles
- PdM: align on requirements and success criteria
- Developers: provide design specs and implementation guidance
- QA: validate usability and accessibility in acceptance testing

---

### Release Manager

Role Summary
- Coordinates release planning, deployment windows, and release communications to reduce deployment risk.

Responsibilities
- Maintain release calendar and coordinate release windows
- Validate release readiness (release notes, rollback plans)
- Coordinate cross-team deployment steps and post-release verifications
- Lead communication for releases to stakeholders and support

Goals
- Reduce release incidents and rollback frequency
- Ensure predictable, well-communicated releases

Typical Communication
- Release planning meetings, release notes, post-release reviews

Interaction with existing roles
- PM: schedule and scope release windows
- SRE: coordinate deployment ops and verification
- Support: prepare post-release monitoring and customer communication

---

### Site Reliability Engineer (SRE) / Ops

Role Summary
- Responsible for production reliability, observability, runbook authoring, and post-deploy operational checks.

Responsibilities
- Define SLOs and monitor production health
- Create runbooks and incident response playbooks
- Support instrumentation and observability standards
- Assist in post-deploy verifications and scaling plans

Goals
- Maintain high availability and fast incident response
- Improve system observability and operability

Typical Communication
- On-call handoffs, reliability reviews, incident postmortems

Interaction with existing roles
- Developers: advise on instrumentation and reliability design
- Release Manager: coordinate deployment practices and rollbacks
- PM: report incident impact, collaborate on mitigations

---

### Support Lead / Customer Success

Role Summary
- Owns customer-facing communications, triages incoming production issues, and provides voice-of-customer feedback to product.

Responsibilities
- Triage and escalate customer-reported issues
- Communicate incident status and known workarounds to customers
- Aggregate customer feedback and surface priority items to product
- Participate in post-incident customer communications

Goals
- Reduce customer-impacting issues and improve response clarity
- Ensure customer feedback informs prioritization

Typical Communication
- Support tickets, incident updates, customer briefings

Interaction with existing roles
- PdM: feed customer insights into prioritization
- PM: escalate high-impact issues and coordinate responses
- SRE/Devs: work together on incident triage and resolution

---

### Data Analyst / Analytics Owner

Role Summary
- Owns measurement plans, telemetry design, and analysis to validate feature outcomes against success metrics.

Responsibilities
- Define key metrics and measurement plans for features
- Work with engineers to implement instrumentation
- Produce dashboards and reports for stakeholders
- Analyze experiments and feature impact

Goals
- Ensure features meet expected outcomes
- Provide data-driven recommendations for iteration

Typical Communication
- Metric definitions, dashboards, analytics deep-dives

Interaction with existing roles
- PdM: define success metrics and KPIs
- Developers: ensure proper instrumentation
- PM: provide reporting for status updates and retrospectives

---

### Security Engineer

Role Summary
- Reviews changes for security impact, performs threat modeling, and owns vulnerability triage.

Responsibilities
- Conduct security reviews for significant changes
- Maintain and enforce secure development practices
- Triage and remediate vulnerabilities and coordinate disclosures
- Provide guidance on authentication, data protection, and compliance

Goals
- Reduce security risk and ensure compliance
- Integrate security considerations early in the lifecycle

Typical Communication
- Security reviews, threat modeling sessions, patch coordination

Interaction with existing roles
- Developers: provide secure design guidance and fixes
- PM: log security risks in the risk register
- SRE: coordinate incident and vulnerability responses

---

### Business Analyst / Product Operations

Role Summary
- Documents complex requirements, manages process details, and helps coordinate stakeholder sign-offs for complex workflows.

Responsibilities
- Capture and formalize business requirements and acceptance criteria
- Coordinate reviews and sign-offs among stakeholders
- Maintain artifacts and process documentation for handoffs
- Support release readiness and operational readiness checks

Goals
- Reduce ambiguity in requirements and approvals
- Streamline stakeholder review and handoff processes

Typical Communication
- Requirements documents, stakeholder review sessions, operational readiness checks

Interaction with existing roles
- PdM: clarify scope and requirements
- PM: manage artifacts and coordinate handoffs
- Stakeholders: organize reviews and approvals

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
