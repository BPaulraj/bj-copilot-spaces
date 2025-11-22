# OctoAcme Project Management Docs

## Purpose

This documentation provides guidance on how OctoAcme runs cross-functional projects. These docs are designed to help new team members quickly understand our project management approach, roles, processes, and key artifacts. They serve as living reference materials that support the Copilot Space program by ensuring consistent, well-documented project practices.

## Overview of OctoAcme Project Management

OctoAcme follows a structured, iterative project management approach built on five core principles:

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments to enable rapid feedback
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and continuous learning

### Project Lifecycle

OctoAcme projects move through a clear lifecycle:

1. **Initiation**: Validate the business need, align stakeholders, define the problem statement, and create a project one-pager with success metrics and initial timeline
2. **Planning**: Break work into shippable increments, create a prioritized backlog with acceptance criteria, identify dependencies and risks, and establish a release plan
3. **Execution**: Build, test, and iterate using regular standups, PR workflows, continuous testing, and weekly risk reviews
4. **Release**: Deploy to production using a standardized checklist, run smoke tests, announce to stakeholders, and maintain rollback plans
5. **Retrospective**: Capture learnings, celebrate wins, identify improvements, and create actionable items for the next project

### Core Roles

- **Project Manager (PM)**: Coordinates delivery, schedules, risk management, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, collaborate on design, and ensure testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

### Communication & Risk Management

OctoAcme emphasizes consistent communication through weekly PM/PdM syncs, twice-weekly standups, and monthly stakeholder updates. Risks are tracked in a centralized Risk Register with clear ownership, mitigation plans, and regular reviews.

## Documentation Index

The following documents provide detailed guidance for each phase of the OctoAcme project management process:

- [**Project Management Overview**](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's project management principles, roles, lifecycle, and communication cadence
- [**Project Initiation**](octoacme-project-initiation.md) — How to validate ideas, align stakeholders, create a project one-pager, and decide go/no-go for planning
- [**Project Planning**](octoacme-project-planning.md) — Creating actionable plans, prioritized backlogs, release timelines, and Definition of Done
- [**Execution and Tracking**](octoacme-execution-and-tracking.md) — Day-to-day execution guidance including team rhythm, PR workflows, quality standards, and blocker escalation
- [**Risk Management & Communication**](octoacme-risks-and-communication.md) — How to identify, assess, and mitigate risks; stakeholder communication templates and escalation paths
- [**Release and Deployment**](octoacme-release-and-deployment.md) — Standardized release process including deployment checklists, rollback procedures, and release notes
- [**Retrospective and Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) — Running effective retrospectives, tracking action items, and fostering a culture of continuous improvement
- [**Roles and Personas**](octoacme-roles-and-personas.md) — Detailed definitions of Developer, Product Manager, and Project Manager roles with responsibilities and communication patterns

## How to Use These Docs

### For Project Teams

- **Keep project artifacts in your repo**: Store your Project Charter, one-pager, and project-specific plans in the `docs/` folder of your project repository
- **Reference these process docs**: Use these OctoAcme process docs as templates and guidelines when creating your project documentation
- **Adapt as needed**: These docs provide a framework; adjust them to fit your project's specific needs while maintaining the core principles

### For Copilot Spaces Integration

- **Surface docs to Copilot**: Add process-specific documentation to `.copilot/` directory if you want GitHub Copilot Spaces to use them as context for AI-assisted development
- **Keep docs updated**: Regularly review and update documentation to ensure Copilot provides accurate, current guidance
- **Use as context**: Reference these docs when asking Copilot for project management guidance, templates, or best practices

### Quick Start

1. Starting a new project? Begin with [Project Initiation](octoacme-project-initiation.md)
2. Need to plan your project? See [Project Planning](octoacme-project-planning.md)
3. Already executing? Check [Execution and Tracking](octoacme-execution-and-tracking.md)
4. Preparing for release? Review [Release and Deployment](octoacme-release-and-deployment.md)
5. After a milestone? Run a [Retrospective](octoacme-retrospective-and-continuous-improvement.md)

## Acceptance Criteria

- [x] docs/README.md added to repository and contains the required summary and index
- [x] All eight process documents linked with relative paths
- [x] Brief overview of project management processes included
- [x] "How to use these docs" section describes artifact storage and Copilot Spaces integration
- [x] Acceptance criteria checklist included in README

---

For questions or suggestions about these process docs, please reach out to your Project Manager or open an issue in this repository.
