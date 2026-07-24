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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas

### Release Manager
- Role summary: Coordinates and owns release readiness and rollout.
- Key responsibilities:
  - Schedule deployment windows and coordinate cross-team activities for release.
  - Verify release readiness (merged PRs, passing CI, release notes, rollback plan).
  - Maintain and own rollback/mitigation plans for releases.
- Primary interactions:
  - Works with PM, DevOps/SRE, QA, and Product during release planning and execution.

### DevOps / SRE
- Role summary: Ensure system reliability, CI/CD, and operational readiness.
- Key responsibilities:
  - Maintain and improve CI/CD pipelines and deployment automation.
  - Own monitoring, alerting, runbooks, and incident response tooling.
  - Support deployability and performance tuning.
- Primary interactions:
  - Partners with Developers for deployability, Release Manager for rollouts, and Support during incidents.

### Security Engineer / Security Reviewer
- Role summary: Assess and approve security posture for changes and designs.
- Key responsibilities:
  - Conduct threat modeling and security reviews for proposed features.
  - Run and validate security scans and remediation steps.
  - Approve security-related changes and flag high-risk items.
- Primary interactions:
  - Collaborates with Developers and PM to include security requirements in acceptance criteria and escalates to Product Lead for high-risk issues.

### UX Researcher / Design Lead
- Role summary: Validate user-facing decisions through research and design best practices.
- Key responsibilities:
  - Lead user research and usability testing.
  - Ensure accessibility and UX acceptance criteria are captured.
  - Provide design assets and guidance to Development and QA.
- Primary interactions:
  - Works with Product Managers to refine success metrics and acceptance criteria.

### Data Analyst / Metrics Owner
- Role summary: Define and validate success metrics and measurement plans.
- Key responsibilities:
  - Create instrumentation plans and dashboards for feature metrics.
  - Analyze post-release data and provide insights to Product and PM.
  - Ensure metrics are reliable and tracked over time.
- Primary interactions:
  - Partners with Product Managers to define success metrics and with Developers/DevOps for instrumentation.

### Support Lead / Customer Operations Liaison
- Role summary: Represent customer impact and manage operational customer feedback.
- Key responsibilities:
  - Triage customer-reported issues and communicate severity/impact.
  - Feed critical problems back into the backlog and help prioritize hotfixes.
  - Coordinate customer communications during incidents and releases.
- Primary interactions:
  - Coordinates with PM, Developers, and Release Manager during incidents and communications.

### Technical Writer / Documentation Owner
- Role summary: Maintain clear, accurate user-facing and internal documentation.
- Key responsibilities:
  - Produce and update release notes, runbooks, and user documentation.
  - Ensure documentation is part of the Definition of Done for features.
  - Help onboard new team members with up-to-date guides.
- Primary interactions:
  - Works with Developers, PM, and Release Manager to produce accurate release notes and process documentation.

### Legal / Compliance Liaison (when applicable)
- Role summary: Advise on regulatory and contractual constraints.
- Key responsibilities:
  - Review compliance and legal implications of features and communications.
  - Approve externally facing language and contractual materials when needed.
  - Advise on required controls or processes for regulated features.
- Primary interactions:
  - Engages with Product and PM during planning for features that trigger compliance reviews.

For each persona we suggest including:
- 1-line role summary
- 3–5 key responsibilities
- Primary interactions (who they work with and when)

This makes responsibilities explicit, reduces handoff ambiguity, and improves accountability for cross-cutting activities (release, security, observability, UX, and support).
