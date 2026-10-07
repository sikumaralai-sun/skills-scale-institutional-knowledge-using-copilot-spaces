# OctoAcme Project Management Docs

## Welcome

This directory contains the complete OctoAcme project management playbook, designed to help teams execute projects consistently, transparently, and with measurable outcomes.

## Quick Start

- **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md)
- **Planning a project?** Reference the [Project Planning Guide](octoacme-project-planning.md)
- **Need to understand roles?** See [Roles & Personas](octoacme-roles-and-personas.md)

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead roles
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Overview

OctoAcme's project management approach is built around a clear lifecycle: initiation, planning, execution, release, and close-out. Every new effort begins with a validated business need, a project one-pager, stakeholder alignment, and a decision gate before moving into planning. Once approved, the team turns the initiative into a prioritized backlog, estimates effort, defines milestones, and clarifies the definition of done. This makes work actionable and ensures progress is tied to specific outcomes, dependencies, and risks rather than ad hoc execution.

The operating model is grounded in defined roles and responsibilities. Product leaders define outcomes and prioritize backlog, while project managers coordinate schedules, communications, dependencies, and risk management. Developers build, test, and maintain quality, QA partners validate acceptance criteria and critical flows, and stakeholders provide input, approval, and ongoing business context. This shared system avoids ambiguity and supports predictable delivery across cross-functional teams.

Communication is a core practice. OctoAcme uses standard cadences such as daily standups, weekly delivery syncs, sprint demos, and regular stakeholder updates to keep teams aligned and surface issues early. Status is communicated through a single source of truth such as the project README or release doc, while risks and dependencies are tracked in a risk register and escalated through defined paths from team triage to PM, product lead, and sponsor when needed.

Quality assurance is built into the full lifecycle rather than treated as a final step. The program requires unit and integration testing, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA when needed before release. Work moves forward only when it meets clear acceptance criteria and the team's definition of done. Releases are governed by checklists covering pre-deployment validation, deployment execution, post-deploy verification, and rollback planning. Learning is captured through retrospectives and continuous improvement actions, ensuring each project improves both the product and the team's process.

## Project Lifecycle Documentation

### 1. Initiation Phase

[Project Initiation Guide](octoacme-project-initiation.md) — Define the initial problem statement, validate business need, identify stakeholders, and make a go/no-go decision to enter planning. Deliverables include a project one-pager, stakeholder list, high-level timeline, and resource needs.

### 2. Planning Phase

[Project Planning](octoacme-project-planning.md) — Break work into shippable increments, create a prioritized backlog with acceptance criteria, estimate scope, define the Definition of Done, identify dependencies, and create a release plan and milestone map.

### 3. Execution Phase

[Execution & Tracking](octoacme-execution-and-tracking.md) — Manage day-to-day execution with daily standups, weekly delivery syncs, and demo/review cycles. Use project boards, follow PR workflows, enforce quality standards with testing and security scanning, and escalate blockers through defined paths.

### 4. Release Phase

[Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardize how features are released to production. Define pre-release requirements, follow a deployment checklist, run smoke tests, and have a rollback and incident playbook ready.

### 5. Retrospective Phase

[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings after each sprint, release, or milestone. Document what went well, what could be improved, and convert insights into actionable improvement items tracked with owners and due dates.

## Cross-Cutting Concerns

[Risk Management & Communication](octoacme-risks-and-communication.md) — Maintain a risk register, assess impact and likelihood, manage mitigation plans, and communicate with stakeholders through standard templates. Define escalation paths for team-level, PM, product lead, and sponsor issues.

## Reference

[Roles & Personas](octoacme-roles-and-personas.md) — Detailed definitions and responsibilities for key roles: Project Managers (coordination and risk), Product Managers (outcomes and prioritization), Developers (implementation and quality), QA/Testing (validation), and Stakeholders (inputs and approvals).

## How to Use These Docs

- Each document is self-contained but interconnected; use the links above to navigate between related processes
- Process updates and new content should be submitted as issues using the [Add Content to Process Docs template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)
- Add relevant docs to Copilot Spaces by linking them in `.copilot/` configuration to provide context-specific guidance
- Keep the Project Charter or README updated in each project repository as a living artifact
- Review these docs during project kickoffs and team onboarding

## Contributing

If you have feedback, suggestions, or want to propose updates to these process docs, please open an issue using the [Add Content to Process Docs template](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml). All improvements are welcome as we continue to refine OctoAcme's practices.
