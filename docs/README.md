# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a customer-first, iterative delivery approach to project management. This documentation centralizes our processes, roles, and best practices to enable consistent, repeatable project execution across the organization.

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Named Project Manager and Product Lead per project
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Process Documents

| Document | Purpose | Key Topics |
|----------|---------|------------|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to OctoAcme approach, roles, artifacts, and lifecycle | Core roles, key artifacts, lifecycle phases, communication cadence |
| [Project Initiation](octoacme-project-initiation.md) | Validate and authorize new work, align stakeholders | One-pager template, decision gates, checklist |
| [Project Planning](octoacme-project-planning.md) | Turn approved initiatives into actionable plans | Backlog prioritization, estimation, risk management |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day execution and progress tracking | Team rhythm, workflows, quality & testing, metrics |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks | Risk register, escalation paths, communication templates |
| [Release & Deployment](octoacme-release-and-deployment.md) | Standardize release and deployment processes | Release types, pre-release requirements, deployment checklist |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and drive improvements | Retrospective structure, action item tracking |
| [Roles & Personas](octoacme-roles-and-personas.md) | Define typical roles and responsibilities | Developers, Product Managers, Project Managers |

## Process Summary

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear accountability. The framework consists of five primary phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. During initiation, teams validate business need and align stakeholders around a lightweight Project One-pager that captures the problem statement, measurable success metrics, and initial timeline. This gate-based approach ensures that only well-scoped work proceeds to planning, where teams break down deliverables into shippable increments, estimate scope, and establish a prioritized backlog with clear acceptance criteria and dependencies. This deliberate upfront work reduces rework and misalignment downstream.

Execution and delivery are coordinated through a predictable **communication rhythm** and well-defined **roles**. Project Managers (PMs) coordinate schedules, risks, and cross-team dependencies, while Product Managers (PdMs) own prioritization and success metrics, and Developers implement features while collaborating on design and testability. The team operates through daily standups (15 min), weekly delivery syncs, and demo/review sessions, using GitHub Projects as the central source of truth with columns for Backlog, Ready, In Progress, In Review, QA, and Done. Small, focused pull requests (≤400 lines when possible) with linked issues and acceptance criteria move through automated CI checks and peer review before merging, ensuring quality gates are met early and often.

Quality assurance and risk management are embedded throughout the lifecycle rather than siloed at the end. Teams implement unit tests, integration tests, and end-to-end smoke tests for critical flows, alongside security scanning in CI and manual QA for feature acceptance. Risk identification begins during planning and continues through execution via a Risk Register that tracks impact, likelihood, owner, and mitigation plans; blockers are escalated through defined levels (team triage → PM escalation → sponsor level) during weekly syncs. Before any release—whether patch, minor, or major—teams verify that acceptance criteria are met, CI passes, rollback plans exist, and smoke tests run successfully on staging.

Finally, OctoAcme institutionalizes learning through **retrospectives** and **continuous improvement** after each sprint, release, or milestone. Teams capture what went well, what could improve, and assign 2–3 prioritized action items with clear owners and due dates, feeding validated improvements back into the process docs. This combination of structured workflows, transparent communication, quality-first practices, and collaborative learning creates a repeatable, scalable approach that reduces single-person dependency, accelerates onboarding, and enables consistent project execution across the organization.

## Quick Reference

### Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risk, communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

### Communication Cadence

- **Daily standups** (15 min) — focus on progress, blockers, dependencies
- **Weekly PM + PdM sync** — alignment and prioritization
- **Weekly delivery sync** — progress updates and flagged risks
- **Monthly stakeholder updates** — status and announcements
- **Ad-hoc escalations** — as needed for blockers or decisions

### Project Lifecycle

1. **Initiation**: Problem statement, stakeholders, high-level timeline
2. **Planning**: Scope, resources, milestones, dependencies, backlog prioritization
3. **Execution**: Build, test, review, iterate with regular demos
4. **Release**: Deploy, verify, announce
5. **Retrospective**: Capture learnings and next steps

### Key Artifacts

- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## How to Use These Docs

- Keep the Project Charter updated in the project repo
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to use them as context
- Reference specific sections when onboarding new team members
- Use the issue template in `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to propose updates to process documentation
