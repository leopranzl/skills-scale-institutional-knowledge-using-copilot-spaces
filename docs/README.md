# OctoAcme — Project Management Overview

Purpose
- Provide a concise entry point to how OctoAcme runs projects so new teammates can quickly understand approach, roles, and key artifacts.

High-level lifecycle
- Initiation: define the problem, stakeholders, and success metrics.
- Planning: build the backlog, estimate work, and map milestones.
- Execution: implement, test, review, and iterate.
- Release: deploy, verify, and announce.
- Close & Retrospective: capture learnings and turn them into action items.

Team rhythm
- Daily standups for progress and blockers.
- Weekly delivery/PM syncs for progress, risks, and dependencies.
- Sprint/milestone demos and periodic stakeholder updates.

Workflows
- Use the project board with columns: Backlog, Ready, In Progress, In Review, QA, Done.
- PR expectations: small PRs when possible, include issue link and acceptance criteria, pass CI and security checks, require at least one approval before merging.

Quality & testing
- Unit and integration tests for new logic; E2E smoke tests for critical flows; manual QA as needed; security scanning in CI.

Reporting & metrics
- Track velocity and burndown; monitor project success metrics from the one-pager; use dashboards for key signals.

Blocker escalation
- Level 1: team triage in standup.
- Level 2: PM escalates to Product Lead and dependent teams.
- Level 3: Sponsor-level escalation for business-impacting issues.

How to use these docs
- This README is a short summary. Consult the full process docs in this folder for details: octoacme-project-management-overview.md, octoacme-project-initiation.md, octoacme-project-planning.md, octoacme-execution-and-tracking.md, octoacme-risks-and-communication.md, octoacme-release-and-deployment.md, octoacme-retrospective-and-continuous-improvement.md, octoacme-roles-and-personas.md
