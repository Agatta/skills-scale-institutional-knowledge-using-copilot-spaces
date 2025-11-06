# OctoAcme Project Management Docs

Welcome! This folder centralizes OctoAcme's project management processes and provides a comprehensive guide for managing cross-functional projects that deliver product features, services, or integrations.

## Summary of OctoAcme Project Management

OctoAcme uses an iterative, stakeholder-aligned approach focused on delivering customer value through clear ownership, data-informed decisions, and continuous improvement.

### Project Lifecycle

OctoAcme projects follow a structured lifecycle from conception to retrospective:

1. **Initiation** — Validate business need, align stakeholders, define success metrics, and create a project one-pager. Decision gate: approve to move into planning when success metrics are clear and team availability is confirmed.

2. **Planning** — Transform the approved initiative into an actionable plan by creating a prioritized backlog, estimating scope, defining Definition of Done, identifying dependencies, and establishing release milestones.

3. **Execution & Tracking** — Build, test, and iterate through daily standups, weekly syncs, and sprint reviews. Follow PR workflows with automated testing, maintain project board updates, and escalate blockers appropriately.

4. **Risk Management & Communication** — Maintain a risk register with impact/likelihood assessments, provide regular stakeholder updates, and follow escalation paths as needed.

5. **Release & Deployment** — Follow checklist-driven deployment process with pre-release requirements, smoke tests, rollback plans, and post-deploy verification. Use incident playbooks when issues arise.

6. **Retrospective & Continuous Improvement** — Capture learnings after sprints, releases, or milestones. Identify 2-3 action items with clear owners and track improvements in the backlog.

### Guiding Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

### Core Roles & Responsibilities

- **Project Manager (PM)**: Coordinates delivery, schedules, risks, and communications. Facilitates meetings, maintains project documentation, and manages dependencies.

- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, measures success. Owns product vision and makes data-driven prioritization decisions.

- **Developers**: Implement features, write tests, participate in code reviews, help estimate work, and identify technical risks.

- **QA/Testing**: Validate quality and acceptance criteria through unit, integration, and end-to-end testing.

- **Stakeholders**: Provide inputs, approvals, and feedback throughout the project lifecycle.

### Key Artifacts & Checklists

**Planning Artifacts:**
- Project Charter / One-pager (problem, goal, success metrics, stakeholders)
- Roadmap and Release Plan
- Sprint/Iteration Backlog with acceptance criteria
- Definition of Done
- Risk Register (ID, description, impact, likelihood, owner, mitigation)

**Execution Artifacts:**
- Project board with workflow states (Backlog, Ready, In Progress, In Review, QA, Done)
- Pull Request descriptions with issue links and acceptance criteria
- Weekly status updates (progress, next steps, risks/blockers, decisions needed)
- Metrics dashboards (velocity, burndown, success metrics)

**Release Artifacts:**
- Release notes (changes, migration steps, known issues)
- Deployment checklist
- Smoke test results
- Rollback/mitigation plans

**Retrospective Artifacts:**
- What went well / what could be improved
- Action items with owners and due dates
- Improvement tracking

### Communication Cadence

- **Daily standups** (15 min) — progress, blockers, dependencies
- **Weekly PM + PdM sync** — alignment on priorities and decisions
- **Weekly delivery sync** — demo progress and flag risks
- **Sprint/milestone demos** — review completed work
- **Monthly stakeholder updates** — strategic progress and roadmap
- **Retrospectives** — after sprints, releases, or major milestones (45-75 min)

## Process Documents

Explore detailed guidance for each phase and role:

- [Project Management Overview](octoacme-project-management-overview.md) — Principles, roles, lifecycle, and communication cadence
- [Project Initiation Guide](octoacme-project-initiation.md) — One-pager template, stakeholder alignment, and initiation checklist
- [Project Planning](octoacme-project-planning.md) — Backlog creation, estimation, Definition of Done, and release planning
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Team rhythm, workflows, quality standards, and blocker escalation
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Risk register, stakeholder communication, and escalation paths
- [Release & Deployment](octoacme-release-and-deployment.md) — Release types, deployment checklist, and rollback playbook
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Running retrospectives and tracking improvements
- [Roles & Personas](octoacme-roles-and-personas.md) — Detailed role definitions for developers, product managers, and project managers

## How to Use These Docs

- Keep the Project Charter updated in the project repository
- Add process-specific docs to `.copilot/` for Copilot Spaces context
- Reference these documents during project kickoffs and planning sessions
- Use the checklists to ensure consistent execution across projects
- Update and improve these processes based on retrospective learnings
