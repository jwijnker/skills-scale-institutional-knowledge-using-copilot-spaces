# OctoAcme Project Management Documentation

Welcome to OctoAcme's centralized project management knowledge base. This directory contains the processes, templates, and guidance we use to deliver projects successfully. Use this README as the starting point to learn our approach, find role-specific guidance, and navigate into the detailed process documents.

## Our Approach
OctoAcme follows a structured project lifecycle founded on these core principles:
- Customer-first: Prioritize customer value and usability
- Iterative delivery: Deliver small, testable increments
- Clear ownership: Each project has named owners and accountability
- Data-informed decisions: Measure impact and iterate based on evidence
- Psychological safety: Encourage feedback and continuous learning

## Project Lifecycle Phases

### 1. Initiation
Validate the business need, identify stakeholders, and decide go/no-go for planning.
- Deliverables: Project One-pager, stakeholder list, high-level timeline
- See: ./octoacme-project-initiation.md

### 2. Planning
Turn approved initiatives into actionable plans and prioritized backlogs.
- Deliverables: Prioritized backlog with acceptance criteria, risk register, release plan
- See: ./octoacme-project-planning.md

### 3. Execution & Tracking
Manage day-to-day delivery, track progress, and maintain quality standards.
- Key activities: Daily standups, sprint delivery, CI-driven quality gates
- See: ./octoacme-execution-and-tracking.md

### 4. Release & Deployment
Standardize how we release features to production with reduced risk.
- Key activities: Pre-release verification, staged deploys, rollback procedures
- See: ./octoacme-release-and-deployment.md

### 5. Retrospective & Continuous Improvement
Capture learnings and convert them into actionable improvements.
- Key activities: Sprint retrospectives, action item tracking, process refinement
- See: ./octoacme-retrospective-and-continuous-improvement.md

## Brief overview of OctoAcme project management processes
OctoAcme runs projects with a clear, staged lifecycle that begins with a lightweight initiation and moves through planning, execution, release, and retrospective. Projects start by producing a Project One-pager to capture the problem, goals, success metrics, stakeholders, and an initial timeline; that one-pager gates planning. During planning the team breaks approved initiatives into prioritized backlog items with acceptance criteria, estimates, and a Definition of Done to ensure readiness for implementation.

Day-to-day execution is coordinated on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and emphasizes small, focused pull requests with linked issues and automated CI checks before review. Roles are explicit: Product Managers define outcomes and success metrics, Project Managers coordinate delivery and risk, Developers implement and test, and QA validates acceptance criteria. Each project has named ownership (PM and Product Lead) and artifacts such as a roadmap, release plan, and risk register are kept in the repository to maintain transparency and accountability.

Communication is structured and frequent: short daily standups for progress and blockers, a weekly delivery sync to highlight progress and risks, regular demos at the end of sprints or milestones, and monthly stakeholder updates. Escalation paths are defined (team → PM → Product Lead → Sponsor) and communication templates are provided for weekly status and incident updates to keep stakeholders informed with a single source of truth.

Quality assurance is integrated into the workflow: CI must run automated tests, linting, and security scans before review, and unit, integration, and end-to-end smoke tests are required where applicable. Pull requests should be small, include acceptance criteria, and require at least one approval before merging (or per team policy). Release checklists and an incident playbook (including rollback and blameless retrospectives) ensure predictable, low-risk deployments and continuous improvement.

## Core documentation (links)
- Project Management Overview — ./octoacme-project-management-overview.md
- Initiation Guide — ./octoacme-project-initiation.md
- Planning — ./octoacme-project-planning.md
- Execution & Tracking — ./octoacme-execution-and-tracking.md
- Release & Deployment — ./octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement — ./octoacme-retrospective-and-continuous-improvement.md
- Risk Management & Communication — ./octoacme-risks-and-communication.md
- Roles & Personas — ./octoacme-roles-and-personas.md

## Quick links by role
- Project Managers: Start with the Project Management Overview, then Planning and Risk Management
- Product Managers: Focus on Initiation and Planning to define scope and success metrics
- Developers: Reference Execution & Tracking for workflow and quality standards
- All team members: Read Roles & Personas to understand responsibilities and communication expectations

## Using these docs
- Keep project charters, plans, and runbooks updated in each project repository
- Reference these docs during project kickoffs, planning sessions, and retrospectives
- For process improvements or documentation updates, use the Issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml
