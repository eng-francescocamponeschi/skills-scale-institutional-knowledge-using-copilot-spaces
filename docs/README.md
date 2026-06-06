# OctoAcme Project Management Docs

Welcome! This folder is the source of truth for how OctoAcme runs projects. Whether you're a new team member getting up to speed or an experienced contributor looking for a quick reference, start here.

## Overview

OctoAcme's project management approach is built around a clear lifecycle — **initiation → planning → execution → release → retrospective** — with customer value and iterative delivery at its core. Each project has named owners (a Project Manager (PM) and a Product Lead—often the Product Manager/PdM), a shared backlog, and defined acceptance criteria so the whole team stays aligned on what "done" means.

Well-defined roles keep accountability clear. **Project Managers (PMs)** coordinate delivery, schedules, risks, and communications. **Product Leads / Product Managers (PdM)** own the product vision, prioritize the backlog, and measure outcomes. **Developers** design, build, test, and review code while surfacing technical risks. **QA/Testing** validates acceptance criteria and quality. **Stakeholders** provide inputs and approvals at key lifecycle gates.

Communication runs on a regular cadence: weekly PM/PdM syncs, delivery team standups (daily or twice-weekly, as agreed), monthly stakeholder updates, and ad-hoc escalation through defined levels when blockers arise. Day-to-day work is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done), and progress is surfaced through weekly delivery syncs and sprint or milestone demos.

Quality assurance is baked into every stage. Small pull requests linked to issues, automated CI checks (linting, unit tests, integration tests, security scans), mandatory code review, and manual QA for feature acceptance are all standard practice. Releases require passing CI, completed acceptance criteria, drafted release notes, a rollback plan, and smoke tests before going live. Lessons captured in retrospectives become tracked action items that feed back into future planning.

---

## Documentation

| Document | Description |
|----------|-------------|
| [Project Management Overview](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, and lifecycle at a glance |
| [Project Initiation](octoacme-project-initiation.md) | How to confirm business need, define success criteria, and produce a project one-pager |
| [Project Planning](octoacme-project-planning.md) | Turning an initiative into an actionable backlog with milestones and a Definition of Done |
| [Execution and Tracking](octoacme-execution-and-tracking.md) | Running sprints, managing the board, and keeping stakeholders informed |
| [Risks and Communication](octoacme-risks-and-communication.md) | Risk register, escalation paths, and communication cadences |
| [Release and Deployment](octoacme-release-and-deployment.md) | Release readiness checklist, deployment steps, and smoke tests |
| [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Retrospective format, action item tracking, and how learnings feed back into planning |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed responsibilities and goals for each role on a project team |
