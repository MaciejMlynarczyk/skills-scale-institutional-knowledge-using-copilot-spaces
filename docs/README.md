# OctoAcme Project Management Processes

OctoAcme runs projects through a lightweight lifecycle: **initiation → planning → execution/tracking → release/deployment → retrospective/continuous improvement**. Work starts with a one-pager that defines the problem, SMART goal, success metrics, stakeholders, timeline, and early risks, then moves into planning once outcomes and ownership are clear. Planning focuses on a prioritized backlog, clear acceptance criteria, dependencies, release milestones, and a Definition of Done so execution begins with shared expectations.

Delivery roles are explicit to keep accountability clear. The **Project Manager (PM)** coordinates planning, risk management, timelines, and status communication; the **Product Manager (PdM)** owns outcomes, prioritization, and value measurement; **Developers** implement and review solutions with maintainability and testability in mind; **QA/Testing** validates feature behavior against acceptance criteria; and **Stakeholders** provide input, decisions, and approvals. Shared artifacts (project board, risk register, release notes, retrospective action items) keep everyone aligned.

Execution is managed through a consistent communication cadence and escalation path. Teams use project board states (Backlog, Ready, In Progress, In Review, QA, Done), daily standups to surface blockers, weekly delivery syncs for progress/risk review, and sprint or milestone demos for stakeholder visibility. Risks and dependencies are tracked continuously, with escalation flowing from team triage to PM/Product leadership and then sponsor-level escalation for business-critical issues.

Quality and release readiness are first-class expectations. OctoAcme emphasizes unit tests for new logic, integration testing where needed, end-to-end smoke checks for critical flows, CI checks (including security scanning), and targeted manual QA before release sign-off. Release readiness includes completed acceptance criteria, passing CI/security checks, release notes, rollback planning, staging validation, post-deploy verification, and follow-up retrospectives that produce owned, time-bound improvement actions.

## Detailed process documentation

- [Project management overview](./octoacme-project-management-overview.md)
- [Project initiation](./octoacme-project-initiation.md)
- [Project planning](./octoacme-project-planning.md)
- [Execution & tracking](./octoacme-execution-and-tracking.md)
- [Risk management & communication](./octoacme-risks-and-communication.md)
- [Release & deployment](./octoacme-release-and-deployment.md)
- [Retrospective & continuous improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & personas](./octoacme-roles-and-personas.md)
