# OctoAcme Project Management Docs

This folder contains OctoAcme’s program management processes and templates to help teams run projects consistently and predictably. The documents describe our end-to-end lifecycle — from lightweight initiation and planning, through execution and release, to retrospectives and continuous improvement — and provide role definitions, checklists, and communication templates to reduce friction and speed onboarding.

OctoAcme uses an iterative delivery model focused on small, testable increments, clear ownership, and evidence-driven decisions. Projects start with a one‑pager to align stakeholders and define success metrics, then move into planning where scope is broken into prioritized backlog items with acceptance criteria and a Definition of Done. During execution, teams follow a well-defined board and pull-request workflow, maintain a living risk register, and keep a regular communication cadence (daily standups, weekly PM+PdM syncs, demos and stakeholder updates). Releases follow pre-release gates (passing CI, security scans, smoke tests, draft release notes) and a deployment checklist with rollback and incident playbooks.

Key roles (Project Manager, Product Manager, Developers, QA, and Stakeholders) are defined to make responsibilities visible and reduce single-person dependencies. Communication strategies include templates for weekly status reports and incident notifications, a three-level escalation path for blockers, and a single source of truth (project README / release doc) for status. Quality assurance practices are embedded in the pipeline: unit and integration tests, end‑to‑end smoke tests for critical flows, CI security scanning, manual QA where needed, and acceptance gates before production deploys. Continuous improvement is enforced via regular retrospectives that convert learnings into prioritized, tracked action items in the backlog.

Process Docs Index
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

How to use these docs
- Keep the Project One-pager and process artifacts updated in the project repo.
- Use the checklists and templates in each doc for consistent execution.
- Add process-specific or project-specific context into `.copilot/` if you want Copilot Spaces to use them as context.
- File updates should follow the repo’s documentation contribution process (issue → PR → review).

Acceptance checklist for this README
- [ ] Summary aligns with existing process docs
- [ ] README improves discoverability and onboarding
- [ ] Links to each process document are correct
- [ ] Stakeholders have reviewed (if needed)

If anything in this README should be different (tone, phrasing, file name or location), tell me and I’ll update the content.
