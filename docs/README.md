# OctoAcme Project Management Docs

This README provides a concise index and summary of OctoAcme's project management processes. It lives in docs/README.md and should be kept up to date as process documents change.

OctoAcme’s project management approach is structured around lightweight, repeatable artifacts and a clear lifecycle from initiation through close. Projects begin with a Project One-pager that captures the problem statement, success metrics, stakeholders, timeline, and initial risks. The planning phase turns approved initiatives into a prioritized backlog with clear acceptance criteria, estimates, a Definition of Done, and a release plan. Core artifacts include the one-pager, roadmap/release plan, sprint backlog, risk register, and retrospective notes — all stored in the repository to serve as the single source of truth.

Work is executed through a predictable delivery workflow: a project board with columns (Backlog → Ready → In Progress → In Review → QA → Done), timeboxed sprints or iterations, and a pull request process that favors small PRs, links PRs to issues with acceptance criteria, runs CI (tests, linting, security scans), and requires at least one approval before merging. Release and deployment are governed by pre-release checks (passing CI, release notes, rollback plans), staging smoke tests, automated pipelines where possible, and a documented rollback/incident playbook.

Communication and escalation are explicit and regular: daily standups for blockers and progress, weekly delivery syncs and PM+PdM alignment meetings, demos at the end of sprints, and monthly stakeholder updates. Risks and dependencies are tracked in a simple risk register and reviewed in weekly syncs, with defined escalation paths (team → PM → Product Lead → Sponsor) and a separate security incident runbook when applicable.

Quality assurance is integrated across development and release: developers write unit and integration tests, critical flows have end-to-end smoke tests, and CI includes automated security scanning. Manual QA is used for feature acceptance when needed, and the Definition of Done plus acceptance criteria guide release readiness. Continuous improvement is supported through regular retrospectives that surface 2–3 prioritized action items which are tracked back into the backlog with owners and due dates.

## Docs (relative links)

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## Suggested ownership & maintenance

- File location: docs/README.md
- Owner: Project Manager or documentation owner
- Review cadence: Quarterly or when major process changes occur

