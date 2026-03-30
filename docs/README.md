# OctoAcme Project Management Processes

Welcome to the OctoAcme project management documentation. This folder contains the core process guides that define how OctoAcme teams plan, execute, and deliver software. Whether you're a new team member onboarding or an experienced contributor looking for a refresher, start here to understand OctoAcme's approach to delivering customer value iteratively with clear ownership and data-informed decision-making.

## Overview & Lifecycle

OctoAcme follows a structured five-phase project lifecycle designed to deliver customer value iteratively while maintaining clear ownership and data-driven decision-making. The process begins with **Initiation**, where teams validate business needs and align stakeholders around a lightweight Project One-pager defining the problem, goals, and success metrics. Once approved, projects move to **Planning**, where work is broken into shippable increments with clear acceptance criteria, dependencies are mapped, and release timelines are established. The **Execution** phase emphasizes daily standups, weekly delivery syncs, and a pull request workflow with automated testing and at least one approval before merge. **Release & Deployment** follows a standardized checklist including pre-release verification, smoke testing, and post-deploy monitoring, with documented rollback procedures for incident management. Each project concludes with a **Close & Retrospective** phase to capture learnings and convert them into actionable improvements.

## Core Roles & Communication

OctoAcme operates with clearly defined roles that ensure accountability and collaboration. **Project Managers (PM)** coordinate delivery, manage risks, and facilitate communication across stakeholders. **Product Managers (PdM)** own the vision, prioritize the backlog, and measure outcomes through success metrics. **Developers** implement features while writing tests, participating in reviews, and identifying technical risks. **QA Engineers** validate quality gates, run acceptance tests, and ensure releases meet standards before they ship. The organization emphasizes psychological safety and iterative feedback, supported by a regular communication cadence: weekly PM–Product Lead syncs, twice-weekly team standups, and monthly stakeholder updates. Risk escalation follows a structured path from team-level triage to PM to Product Lead to Sponsor-level escalation for business-impacting issues.

## Quality Assurance & Continuous Improvement

Quality is embedded throughout the OctoAcme process through multiple layers: unit and integration tests for new logic, end-to-end smoke tests before release, security scanning in CI, and manual QA for feature acceptance when needed. The project board uses standardized columns — Backlog, Ready, In Progress, In Review, QA, Done — to maintain visibility and enforce quality gates. Small PRs (≤ 400 lines when possible) with clear issue links and acceptance criteria facilitate faster reviews and reduce risk. After each sprint, release, or significant milestone, teams conduct retrospectives to capture learnings and convert them into actionable improvements tracked in the project backlog — reinforcing a culture of continuous iteration and measurement-driven decision-making grounded in the key principles of **customer-first** thinking, **iterative delivery**, **clear ownership**, **data-informed decisions**, and **psychological safety**.

## Documentation

| Document | Description |
|---|---|
| [Project Management Overview](./octoacme-project-management-overview.md) | High-level overview of OctoAcme's project management philosophy and guiding principles |
| [Project Initiation Guide](./octoacme-project-initiation.md) | How to validate business needs, create the Project One-pager, and gain stakeholder alignment |
| [Project Planning](./octoacme-project-planning.md) | Breaking work into shippable increments, mapping dependencies, and building the backlog |
| [Execution & Tracking](./octoacme-execution-and-tracking.md) | Daily standups, weekly syncs, PR workflow, automated testing, and quality gates |
| [Release & Deployment](./octoacme-release-and-deployment.md) | Standardized release checklist, smoke testing, post-deploy monitoring, and rollback procedures |
| [Risks & Communication](./octoacme-risks-and-communication.md) | Escalation paths, stakeholder communication, and the risk register |
| [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Capturing learnings and converting them into actionable improvements |
| [Roles & Personas](./octoacme-roles-and-personas.md) | Detailed responsibilities for Developers, Product Managers, and Project Managers |
