# OctoAcme Project Management Documentation

## Overview
OctoAcme follows a structured, iterative project management approach focused on delivering customer value through small, testable increments. Initiatives begin with a lightweight Project One-pager to define the problem, measurable success metrics, stakeholders, and a high-level timeline. From there, approved work moves into planning where the team breaks scope into shippable backlog items with acceptance criteria, estimates effort, and documents key dependencies and risks.

## Core Workflows
Core workflows center on a project board and a disciplined pull request process. Work is tracked on a Kanban-style board (Backlog → Ready → In Progress → In Review → QA → Done) and PRs are kept small, linked to issues with acceptance criteria, and must pass CI (tests, linting, security scans) before review. Releases follow a checklist-driven process — staging verification, smoke tests, release notes, and rollback plans — to reduce deployment risk and ensure observability.

## Roles & Communication
Roles and responsibilities are explicit: Product Managers define outcomes and success metrics; Project Managers coordinate delivery, schedules, and risk; Developers implement and test; and QA validates acceptance criteria. Day-to-day coordination uses short standups for progress and blockers, weekly delivery syncs to surface risks and cross-team dependencies, and demos at the end of sprints or milestones. A clear escalation path (team → PM → Product Lead → Sponsor) and communication templates (weekly status, incident summaries) ensure consistent stakeholder updates.

## Quality Assurance & Continuous Improvement
Quality assurance and continuous improvement are core practices. Developers are expected to provide unit and integration tests while CI enforces automated checks and security scans. Critical flows use smoke and end-to-end tests prior to release. Retrospectives after sprints, releases, or incidents capture action items that feed back into the backlog for continuous improvement and to reduce single-person knowledge dependencies.

## Quick Links
- Getting Started / Overview
  - octoacme-project-management-overview.md
- Project Phases
  - octoacme-project-initiation.md
  - octoacme-project-planning.md
  - octoacme-execution-and-tracking.md
  - octoacme-release-and-deployment.md
  - octoacme-retrospective-and-continuous-improvement.md
- Cross-cutting
  - octoacme-risks-and-communication.md
  - octoacme-roles-and-personas.md

## Project Lifecycle (at a glance)
1. Initiation — validate problem and align stakeholders (one-pager)
2. Planning — prioritize backlog, estimate, define DoD and test approach
3. Execution — implement, test, review, and track on the project board
4. Release — deploy with staging verification, smoke tests, and rollbacks
5. Close & Improve — run retrospectives, capture action items, and iterate

## Key Artifacts
- Project One-pager / Charter
- Roadmap & Release Plan
- Sprint/Iteration Backlog with acceptance criteria
- Definition of Done (DoD)
- Risk Register
- Retrospective notes and action items

## Getting Started
1. New to OctoAcme? Start with octoacme-project-management-overview.md to understand principles and roles.
2. Starting a new initiative? Complete the Project One-pager (see octoacme-project-initiation.md) and follow the initiation checklist.
3. In planning or execution? Use the planning and execution guides for backlog, DoD, PR conventions, and risk handling.
4. Need to update these docs? Use the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/ to propose changes.

## Feedback & Contributions
These docs are living artifacts. If you find gaps or have improvements, open an issue (use the provided template) or submit a pull request.
