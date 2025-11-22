# OctoAcme Project Management Docs

Purpose
-------
This folder centralizes OctoAcme's project management processes and artifacts to improve discoverability, onboarding, and consistent execution. These docs describe how we initiate, plan, execute, release, manage risk, and learn from projects. They are intended as living guidance for teams using Copilot Spaces to capture and surface project artifacts.

Overview of Project Management Processes
---------------------------------------
- Initiation: Capture the problem, stakeholders, goals, and measurable success criteria in a concise Project One-pager to decide whether to proceed to planning.
- Planning: Turn approved initiatives into a prioritized, estimated backlog with a release plan, Definition of Done, and a basic risk register.
- Execution & Tracking: Deliver iteratively using small pull requests, CI checks, regular team rhythms (standups, weekly syncs, demos), and dashboards to measure progress.
- Release & Deployment: Follow pre-release checks (tests, security scans, rollback plan), staged deployments, and post-deploy verification, plus release notes and stakeholder communication.
- Risk Management & Communication: Maintain a simple risk register, review risks at cadence, and escalate blockers through defined paths.
- Retrospectives & Continuous Improvement: Run timeboxed retros, convert actions into tracked backlog items, and measure improvements over time.

Docs Index
----------
- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md

How to use these docs
---------------------
- Store project-specific artifacts (one-pagers, release plans, risk registers) in the project repo under docs/ or in `.copilot/` to make them available to Copilot Spaces.
- Link the project README to the canonical one-pager and release notes so stakeholders have a single source of truth.
- Keep the risk register and retrospective actions up to date and surface important changes in weekly syncs.

Acceptance Criteria
-------------------
- [ ] Content aligns with existing process docs
- [ ] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)
