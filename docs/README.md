# OctoAcme — Project Management Processes (overview)

Purpose
- Centralized summary of OctoAcme project management practices. Use the linked process docs in this folder for full guidance.

Core principles
- Customer-first: prioritize customer value.
- Iterative delivery: deliver small, testable increments.
- Clear ownership and data-informed decisions.
- Psychological safety and continuous improvement.

Key artifacts (in docs/)
- Project One-pager (initiation)
- Release & Deployment guide
- Execution & Tracking checklist
- Risk Register & Communication templates
- Retrospectives and action-tracking

Team rhythm
- Daily standups (15 min) for progress & blockers
- Weekly delivery sync / PM+PdM alignment
- Sprint demos and retrospectives at milestone ends

Workflows (high-level)
- Project board with columns: Backlog → Ready → In Progress → In Review → QA → Done
- Small PRs when possible; include issue link, acceptance criteria
- CI must pass (tests, lint, security scans) before requesting reviews
- Require at least one approval per PR (team policy may vary)

Quality & release
- Unit and integration tests for new logic; smoke tests for critical flows
- Pre-release checklist: passing CI, release notes, rollback plan, and smoke tests
- Post-deploy verifications and incident playbook

Where to find more details
- See the full process docs in this folder:
  - octoacme-project-management-overview.md
  - octoacme-project-initiation.md
  - octoacme-project-planning.md
  - octoacme-execution-and-tracking.md
  - octoacme-risks-and-communication.md
  - octoacme-release-and-deployment.md
  - octoacme-retrospective-and-continuous-improvement.md
  - octoacme-roles-and-personas.md
