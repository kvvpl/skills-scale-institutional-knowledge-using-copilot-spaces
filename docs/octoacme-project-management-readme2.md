# OctoAcme Project Management Documentation

This README is the entry point to OctoAcme's project management process documentation. It summarizes our approach to running projects and links to the detailed process documents in this folder so team members can quickly find templates, checklists, and role guidance.

OctoAcme follows a lightweight, iterative lifecycle: Initiation (one-pager, stakeholder alignment, go/no‑go), Planning (kickoff, prioritized backlog, estimates, Definition of Done, release plan), Execution (work on the project board, small PRs, CI and reviews), Release (deploy, smoke tests, announce), and Close & Retrospective (capture learnings and turn them into tracked action items). Work is organized on a project board with clear states (Backlog → Ready → In Progress → In Review → QA → Done) and a Pull Request workflow that enforces tests, small changes, and required approvals.

Roles are clearly assigned: Project Managers coordinate delivery, schedules, risks, and communications; Product Managers own outcomes, prioritization, and success metrics; Developers implement features and tests; QA validates acceptance criteria; stakeholders provide input and approvals. Decision gates (e.g., from Initiation to Planning) require clear success metrics and stakeholder alignment to reduce early ambiguity.

Communication and quality are built into the cadence and artifacts. Team rhythm includes daily standups, weekly delivery syncs, demos at sprint/milestone end, and monthly stakeholder updates. Risk management uses a lightweight risk register and escalation paths (team → PM → Product Lead → Sponsor). Quality practices include unit/integration tests, CI security scans, end-to-end smoke tests for critical flows, manual QA where needed, release checklists, and a rollback/incident playbook. Retrospectives drive continuous improvement by converting observations into tracked action items.

Process Documents
- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](docs/octoacme-roles-and-personas.md)

How to use this folder
- Keep your project one-pager, release notes, and process-specific artifacts in the project repo under docs/ or `.copilot/` so they are discoverable.
- Use the checklists in each document before changing a project phase (e.g., before releasing).
- Add new process improvements as PRs to these docs and track action items from retrospectives in the project backlog.
