# OctoAcme Project Management Docs

## Overview

This README serves as the main entry point for all OctoAcme project management process documentation. It provides a summary of our project management approach and links to detailed guides. Use this index to navigate to the specific process documents you need for your project work.

## Project Management Processes Summary

OctoAcme follows a structured, customer-first approach to project management that emphasizes iterative delivery, clear ownership, and data-informed decision-making.

### Project Lifecycle & Core Workflows

OctoAcme follows a five-phase project lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. The **Initiation** phase begins with a lightweight Project One-pager that confirms business need, identifies stakeholders, and establishes measurable success metrics. Once approved, the team moves into **Planning**, where work is broken into shippable increments with clear acceptance criteria, dependencies are mapped, and a release timeline is established. **Execution** emphasizes iterative delivery through a structured daily rhythm: 15-minute standups focus on progress and blockers, work progresses through a project board (Backlog → Ready → In Progress → In Review → QA → Done), and pull requests follow strict conventions with automated testing and linting before merging. The **Release** phase requires pre-release verification including passing CI/security scans, smoke tests, and a documented rollback plan. Finally, teams conduct retrospectives to capture learnings and convert them into actionable improvements tracked in the backlog.

### Roles, Responsibilities & Communication

OctoAcme defines clear role ownership to ensure accountability and reduce single-person dependencies:

- **Project Managers** coordinate delivery, manage schedules and risks, and facilitate cross-team communication
- **Product Managers** define what should be built, prioritize the roadmap, and measure outcomes through data-driven decisions
- **Developers** implement features, write tests, participate in design reviews, and identify technical risks
- **QA/Testing** teams validate quality and acceptance criteria
- **Stakeholders** provide inputs and approvals

The communication cadence is designed for alignment and transparency: weekly syncs between PM and Product Manager, twice-weekly standups for delivery teams, and monthly stakeholder updates. Risk escalation follows a three-level path: team-level triage in daily standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues.

### Quality Assurance & Risk Management

Quality is woven throughout execution with multiple checkpoints: unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, and security scanning in CI. Manual QA validates feature acceptance when needed. Small pull requests (≤400 lines) with clear issue links and acceptance criteria make reviews more manageable, requiring at least one approval before merging.

OctoAcme maintains a Risk Register that tracks risk ID, description, impact, likelihood, owner, and mitigation plans—reviewed weekly during syncs. The team also emphasizes a culture of psychological safety and continuous improvement: retrospectives are conducted after each sprint or release with 2–3 prioritized action items to avoid overload, and improvements are measured for impact.

### Documentation & Single Source of Truth

All key artifacts—Project Charter/One-pager, Roadmap, Sprint Backlog, Risk Register, and Retrospective notes—are maintained in the project repository. Process-specific documents are stored in `.copilot/` to serve as persistent context for team members and new onboarding. Status is communicated via a simple template covering progress, next steps, risks, blockers, and decisions needed. This approach centralizes institutional knowledge, reduces onboarding time, and ensures consistent, repeatable project execution across the organization.

---

## Links to Process Docs

Navigate to the detailed process guides below:

- **[Project Management Overview](./octoacme-project-management-overview.md)** — Introduction to OctoAcme's project approach, core roles, key artifacts, and lifecycle overview
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- **[Project Planning](./octoacme-project-planning.md)** — Turn an approved initiative into an actionable plan and backlog for delivery
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Guidance for managing day-to-day execution and tracking progress toward project milestones
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — How to identify, manage, and communicate risks and dependencies
- **[Release & Deployment](./octoacme-release-and-deployment.md)** — Standardized process for releasing features to production
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements
- **[Roles and Personas](./octoacme-roles-and-personas.md)** — Definitions of typical roles and responsibilities used in OctoAcme projects

---

## Quick Start

**New to OctoAcme?** Start here:
1. Read the [Project Management Overview](./octoacme-project-management-overview.md) to understand our principles and key artifacts
2. Review the [Roles and Personas](./octoacme-roles-and-personas.md) to understand your role and responsibilities
3. Follow the [Project Initiation Guide](./octoacme-project-initiation.md) when starting a new project

**Executing a project?** Follow this sequence:
1. [Project Initiation](./octoacme-project-initiation.md) → [Planning](./octoacme-project-planning.md) → [Execution & Tracking](./octoacme-execution-and-tracking.md) → [Release & Deployment](./octoacme-release-and-deployment.md) → [Retrospective](./octoacme-retrospective-and-continuous-improvement.md)
2. Use [Risk Management & Communication](./octoacme-risks-and-communication.md) throughout all phases

---

## Contributing to Process Docs

To request updates, clarifications, or new content in the OctoAcme process documentation, use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.