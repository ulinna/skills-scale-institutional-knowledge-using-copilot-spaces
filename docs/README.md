# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management framework. This documentation centralizes the core processes, roles, and artifacts used to plan, deliver, and improve cross-functional projects.

OctoAcme follows a structured lifecycle that begins with initiation, moves into planning, then execution, release, and retrospective improvement. The team starts by validating the business need, defining success metrics, and aligning stakeholders around a clear project one-pager. Once approved, work is broken into backlog items, milestones, and dependencies with explicit acceptance criteria and Definition of Done. During execution, teams use regular communication rhythms, project tracking, and escalation paths to keep delivery moving and quickly surface blockers. At the end of each cycle, retrospectives capture learning and convert it into concrete actions that improve how the team works.

## Project lifecycle

### 1. Initiation
- [Project Initiation Guide](octoacme-project-initiation.md)
- Validate the business problem, identify stakeholders, define success metrics, and decide whether the initiative is ready to move into planning.

### 2. Planning
- [Project Planning](octoacme-project-planning.md)
- Turn approved initiatives into an actionable backlog, define scope, estimate effort, identify dependencies, and agree on release milestones.

### 3. Execution & Tracking
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- Run day-to-day delivery with standups, issue tracking, quality checks, and escalation paths for blockers or dependencies.

### 4. Release & Deployment
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- Standardize release readiness, deployment checks, smoke testing, rollback planning, and stakeholder communication.

### 5. Retrospective & Continuous Improvement
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- Capture lessons learned, assign owners for action items, and embed improvements into the project workflow.

## Supporting reference guides
- [Project Management Overview](octoacme-project-management-overview.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)

## Key principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Key roles and artifacts

### Common roles
- Project Manager (PM): coordinates schedules, dependencies, risks, and communication.
- Product Manager / Product Lead: defines outcomes, prioritizes the backlog, and measures success.
- Developers: build, test, and deliver software features.
- QA / Testing: validate acceptance criteria and quality standards.
- Stakeholders: provide input, priorities, and approvals.

### Core artifacts
- Project One-pager / charter
- Roadmap and release plan
- Sprint or iteration backlog
- Acceptance criteria and Definition of Done
- Risk register
- Retrospective notes and action items

## Communication and quality practices

OctoAcme emphasizes regular communication and shared accountability. Teams use standups, weekly delivery syncs, milestone reviews, and stakeholder updates to keep work visible and aligned. Escalation paths ensure that blockers move quickly from the team level to project leadership and, when needed, executive sponsors. Communication templates help teams share progress, risks, next steps, and incident status consistently across functions.

Quality is treated as a core delivery practice rather than a final checkpoint. The process requires CI validation, unit and integration testing, smoke testing for critical flows, security scanning, and manual QA when needed. Pull requests should be small and reviewable, include issue links and acceptance criteria, and receive approval before merge. Release readiness checks, rollback plans, and post-deployment verification further reduce risk and improve operational confidence.

## How to use these docs in a project
1. Start with the [Project Management Overview](octoacme-project-management-overview.md) and the [Project Initiation Guide](octoacme-project-initiation.md).
2. Keep the project one-pager and key artifacts in the project repository.
3. Use the relevant lifecycle guide during each phase of the work.
4. Apply templates and checklists from the process docs to maintain consistency.
5. Add project-specific customizations to the repo or `.copilot/` directory as needed.

These documents are intended to help teams stay aligned, reduce ambiguity, and maintain a consistent, repeatable delivery rhythm across projects.
