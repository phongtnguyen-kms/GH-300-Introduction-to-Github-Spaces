# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

## Why expanded personas matter
- Reduce ambiguity by making decision owners and handoffs explicit.
- Improve release readiness by involving quality, security, and operations earlier.
- Strengthen risk management with earlier visibility into dependency, compliance, and customer-impact risks.
- Improve onboarding by clarifying who to involve at each phase of planning, execution, release, and retrospective work.

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

## QA / Test Engineers

### Role Summary
QA / Test Engineers validate that delivered work meets acceptance criteria, quality standards, and release expectations.

### Responsibilities
- Define test strategy for new work and high-risk areas
- Validate acceptance criteria and regression coverage
- Report defects clearly with impact and reproduction details
- Partner with developers to improve testability and quality gates
- Support release readiness checks and post-release validation

### Goals
- Catch issues before release and reduce escaped defects
- Improve confidence in release quality and stability
- Keep quality signals visible to delivery and business teams

### Typical Communication
- Test plans and test result summaries
- Defect triage and quality risk updates
- Release readiness sign-off inputs

### Interaction with Existing Roles
- **Developers:** align on testability, automation coverage, and defect resolution.
- **Product Managers:** validate acceptance criteria and clarify expected behavior.
- **Project Managers:** communicate quality risks, triage priorities, and release readiness status.

---

## Technical Leads / Engineering Leads

### Role Summary
Technical Leads guide technical direction, architecture decisions, and engineering quality across contributors.

### Responsibilities
- Define implementation approach and architectural guardrails
- Identify technical dependencies and delivery risks early
- Support estimation with technical complexity context
- Mentor developers and enforce engineering standards
- Partner on incident follow-up and technical debt prioritization

### Goals
- Deliver scalable, maintainable solutions
- Reduce rework through early technical alignment
- Improve execution predictability for complex initiatives

### Typical Communication
- Technical design reviews and architecture notes
- Dependency/risk escalations and mitigation plans
- Engineering standards and review feedback

### Interaction with Existing Roles
- **Developers:** provide design guidance, code review support, and technical unblockers.
- **Product Managers:** shape scope trade-offs based on feasibility and risk.
- **Project Managers:** align sequencing, dependencies, and escalation paths for technical risks.

---

## Designers / UX Partners

### Role Summary
Designers / UX Partners define user flows and interaction patterns that improve usability, accessibility, and product clarity.

### Responsibilities
- Translate requirements into user flows and interface concepts
- Define UX acceptance inputs, including accessibility considerations
- Validate designs with feedback, testing, or research as needed
- Collaborate during implementation to preserve user intent
- Contribute to post-release usability learnings

### Goals
- Improve user success and adoption of delivered features
- Reduce ambiguity in product and engineering handoffs
- Ensure accessible and consistent user experiences

### Typical Communication
- Design reviews and annotated prototypes
- UX acceptance notes in specs and tickets
- Feedback summaries from usability validation

### Interaction with Existing Roles
- **Developers:** partner on implementation details and design feasibility.
- **Product Managers:** align on user problems, outcomes, and solution priorities.
- **Project Managers:** coordinate design dependencies and timeline impacts.

---

## Stakeholders / Sponsors

### Role Summary
Stakeholders / Sponsors provide business context, decision support, and approvals to keep project outcomes aligned with organizational priorities.

### Responsibilities
- Confirm goals, constraints, and expected business value
- Approve key milestones, scope changes, and go/no-go decisions
- Remove organizational blockers and support escalations
- Provide timely feedback on demos and progress updates
- Help align cross-team priorities when trade-offs are required

### Goals
- Ensure delivery stays aligned to strategic outcomes
- Improve decision speed for high-impact issues
- Increase accountability for value realization after release

### Typical Communication
- Milestone reviews and steering updates
- Decision logs for major scope or timeline changes
- Outcome reviews against success metrics

### Interaction with Existing Roles
- **Developers:** provide context on priority outcomes and constraints when needed.
- **Product Managers:** align on value, scope direction, and outcome measurement.
- **Project Managers:** receive status, risks, and escalation updates for decisions.

---

## Support / Operations Representatives

### Role Summary
Support / Operations Representatives ensure customer support readiness and operational stability before and after release.

### Responsibilities
- Surface operational constraints and support impact early
- Validate runbooks, alerting expectations, and escalation paths
- Prepare support teams with known issues and troubleshooting guidance
- Provide deployment readiness feedback for release planning
- Share customer-reported issues and trends for prioritization

### Goals
- Reduce production incidents and support escalations
- Improve handoffs from delivery to operations and support teams
- Shorten time-to-detect and time-to-recover when issues occur

### Typical Communication
- Launch readiness and runbook check-ins
- Support bulletins and known-issue updates
- Incident and post-release trend summaries

### Interaction with Existing Roles
- **Developers:** align on observability, runbooks, and operational fixes.
- **Product Managers:** share customer impact trends and support-driven insights.
- **Project Managers:** coordinate launch readiness, support staffing, and incident communication.

---

## Security / Compliance Partners

### Role Summary
Security / Compliance Partners help teams design and deliver changes that meet security and compliance expectations without avoidable delivery delays.

### Responsibilities
- Review security-sensitive designs and implementation plans
- Identify compliance requirements and approval dependencies
- Recommend mitigations for prioritized security risks
- Support threat modeling, security testing, and incident preparedness
- Track and communicate unresolved risks before release decisions

### Goals
- Reduce avoidable security and compliance incidents
- Shift risk identification earlier in the delivery lifecycle
- Improve confidence in go/no-go decisions for sensitive changes

### Typical Communication
- Security review notes and mitigation recommendations
- Compliance requirement checklists and approval status
- Risk exception documentation for unresolved findings

### Interaction with Existing Roles
- **Developers:** advise on secure implementation patterns and remediation.
- **Product Managers:** clarify scope impact when controls or reviews change timelines.
- **Project Managers:** align approval dependencies, risk escalation, and release readiness.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
