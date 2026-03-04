# OctoAcme Project Management Docs

This README centralizes knowledge about how OctoAcme manages projects and links to all detailed process documents.

## Summary of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The methodology spans five key phases: Initiation, Planning, Execution, Release, and Closure &amp; Retrospectives. During initiation, teams validate business needs and align stakeholders around a lightweight Project One-pager that defines the problem, goals, success metrics, and resource needs. Once approved, the planning phase breaks work into shippable increments, establishes acceptance criteria, estimates scope, and creates a prioritized backlog with identified dependencies and risks. This structured foundation ensures that all teams—developers, product managers, project managers, and QA—have clarity on objectives before execution begins.

Execution at OctoAcme is driven by a consistent team rhythm and clear workflows. Daily standups (15 minutes) focus on progress and blockers, while weekly delivery syncs track milestones and flag risks. Teams use GitHub Projects with a standardized workflow (Backlog → Ready → In Progress → In Review → QA → Done), maintain small pull requests (≤400 lines when possible), and require automated CI testing and at least one approval before merging. Quality is non-negotiable: the team implements unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and security scanning in CI, with manual QA for feature acceptance as needed. Risk management is built into the process through a maintained Risk Register and a three-level escalation path: team-level triage → PM escalation to Product Lead → sponsor-level involvement for business-impacting issues.

Communication and transparency are central to OctoAcme's success. A weekly sync between the Project Manager and Product Manager ensures alignment, while twice-weekly standups keep the delivery team synchronized. Status updates follow a consistent template covering progress, next steps, risks, and decisions needed, and stakeholders receive regular updates on a monthly basis (or more frequently for high-visibility initiatives). After each sprint, release, or milestone, teams conduct structured retrospectives (45–75 minutes) to capture learnings, identify improvements, and track action items with clear owners and due dates. This continuous improvement culture is reinforced by measuring the impact of process changes and celebrating small wins. When releases occur, OctoAcme enforces pre-release checklists ensuring acceptance criteria are met, CI passes, security scans complete, rollback plans exist, and smoke tests are prepared—reducing deployment risk and enabling reliable, observable product delivery.

### Process Docs:
- <a href="octoacme-project-management-overview.md">Project Management Overview</a>
- <a href="octoacme-project-initiation.md">Project Initiation Guide</a>
- <a href="octoacme-project-planning.md">Project Planning</a>
- <a href="octoacme-execution-and-tracking.md">Execution &amp; Tracking</a>
- <a href="octoacme-risks-and-communication.md">Risk Management &amp; Communication</a>
- <a href="octoacme-release-and-deployment.md">Release &amp; Deployment Guide</a>
- <a href="octoacme-retrospective-and-continuous-improvement.md">Retrospective &amp; Continuous Improvement</a>
- <a href="octoacme-roles-and-personas.md">Roles and Personas</a>
