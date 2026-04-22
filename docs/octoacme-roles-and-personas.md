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

## UX Designers

### Role Summary
UX Designers shape user journeys, interaction patterns, and usability outcomes so delivery teams build experiences that are clear, accessible, and efficient.

### Responsibilities
- Translate user needs into wireframes, flows, and design specs
- Partner with Product Managers to refine requirements and acceptance criteria
- Support Developers with design clarification during implementation
- Validate usability through lightweight research and feedback loops
- Flag UX risks early (complexity, accessibility, inconsistent patterns)

### Goals
- Improve task success and user satisfaction
- Reduce usability defects discovered late in delivery
- Keep user experience consistent across releases

### Typical Communication
- Design reviews and async design comments
- Annotated mockups and interaction specifications
- Usability findings summaries shared with PdM/PM/Developers

### Interaction with Existing Roles
- **Developers:** clarify implementation details, review UI behavior, and confirm feasibility trade-offs
- **Product Managers:** align user outcomes, prioritize UX debt, and define measurable usability success criteria
- **Project Managers:** coordinate design milestones, identify delivery risks, and align review timing with sprint/release plans

---

## Security Champions

### Role Summary
Security Champions embed practical security practices into day-to-day delivery and ensure risks are surfaced early without blocking team velocity.

### Responsibilities
- Promote secure-by-default development and review habits
- Help triage security findings and prioritize remediation
- Maintain threat/risk inputs for planning and release readiness
- Coordinate with PM/PdM on security-related dependencies and decisions
- Support incident follow-up actions and prevention improvements

### Goals
- Reduce security vulnerabilities introduced during delivery
- Shorten time-to-triage and time-to-remediate security issues
- Increase team confidence in release safety

### Typical Communication
- Security checkpoints in planning and release reviews
- Risk register updates for high-priority security concerns
- Guidance in PR reviews or design discussions for sensitive changes

### Interaction with Existing Roles
- **Developers:** provide secure coding guidance, review risky changes, and help validate mitigations
- **Product Managers:** align security requirements with feature priorities and customer commitments
- **Project Managers:** maintain security risk visibility, escalation paths, and mitigation timelines

---

## Technical Writers

### Role Summary
Technical Writers ensure project and product documentation stays accurate, usable, and release-ready for both internal and external audiences.

### Responsibilities
- Draft and maintain process docs, release notes, and user guidance
- Standardize documentation structure and terminology
- Work with delivery teams to capture decisions and implementation details
- Identify documentation gaps that impact onboarding or support
- Ensure documentation updates are included in Definition of Done

### Goals
- Improve documentation clarity and discoverability
- Reduce repeated clarification requests from stakeholders and support teams
- Keep documentation synchronized with shipped behavior

### Typical Communication
- Documentation review checkpoints during sprint/release cycles
- Change summaries linked to PRs and release artifacts
- Feedback loops with PdM, PM, Developers, and Support

### Interaction with Existing Roles
- **Developers:** gather implementation details and examples for accurate technical content
- **Product Managers:** align messaging with user outcomes, feature scope, and known limitations
- **Project Managers:** coordinate documentation deliverables and publication timing within milestones

---

## Release Managers

### Role Summary
Release Managers coordinate release readiness and execution so deployments are predictable, well-communicated, and reversible when needed.

### Responsibilities
- Own release calendar, sequencing, and go/no-go coordination
- Verify release readiness checklist completion across teams
- Confirm rollback plans, communication plans, and stakeholder notifications
- Coordinate deployment windows and post-release verification
- Capture release-level follow-up actions and handoffs

### Goals
- Increase release predictability and reduce deployment risk
- Minimize release-related incidents and downtime
- Improve cross-functional alignment during launch windows

### Typical Communication
- Release readiness reviews and go/no-go updates
- Deployment timeline and status broadcasts
- Post-release summaries with outcomes and follow-up actions

### Interaction with Existing Roles
- **Developers:** validate technical readiness, deployment order, and rollback steps
- **Product Managers:** align release scope, customer impact, and launch communications
- **Project Managers:** align release milestones, dependencies, and stakeholder escalation paths

---

## Customer Support Liaisons

### Role Summary
Customer Support Liaisons connect delivery teams with frontline customer signals to improve prioritization, release readiness, and incident response.

### Responsibilities
- Aggregate support trends, recurring issues, and customer pain points
- Feed support insights into backlog refinement and risk discussions
- Validate support readiness (known issues, troubleshooting steps, comms)
- Coordinate customer-facing updates for incidents and major changes
- Track post-release support impact and feedback

### Goals
- Reduce avoidable support tickets after release
- Improve responsiveness to customer-impacting defects
- Strengthen feedback loops between customers and delivery teams

### Typical Communication
- Weekly summaries of top customer issues and escalation signals
- Release-impact notes for support teams before launch
- Incident communication coordination with PM/PdM stakeholders

### Interaction with Existing Roles
- **Developers:** share reproducible customer issues and verify fix behavior
- **Product Managers:** prioritize customer pain points and validate product trade-offs
- **Project Managers:** align support risks, communication cadence, and escalation workflows

---

## Interaction Map (Lifecycle Touchpoints)

| Lifecycle Phase | Primary Collaboration Touchpoints |
| --- | --- |
| Initiation | PdM + PM define scope; UX and Support Liaison provide early customer/usability signals; Security Champion flags high-level risk areas |
| Planning | PM/PdM/Developers align backlog; UX refines flows; Security Champion contributes risk and controls; Technical Writer plans documentation deliverables |
| Execution | Developers implement; UX and Security Champion support reviews; PM tracks risks/dependencies; Technical Writer captures updates; Support Liaison shares live customer trends |
| Release | Release Manager runs go/no-go; PM/PdM confirm scope and comms; Developers validate readiness; Technical Writer publishes release notes; Support Liaison prepares frontline guidance |
| Retrospective | PM facilitates learnings; PdM/Developers review outcomes; UX/Security/Support provide signal-based improvements; Technical Writer records agreed process updates |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
