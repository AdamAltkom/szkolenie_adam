# OctoAcme Project Management Docs

This README is the central entry point for OctoAcme's program and process documentation. It provides quick links to detailed process guides and a concise summary of the project's management approach so team members can discover and apply core practices quickly.

## Quick links

- [Project Management Overview](docs/octoacme-project-management-overview.md)
- [Project Initiation Guide](docs/octoacme-project-initiation.md)
- [Project Planning](docs/octoacme-project-planning.md)
- [Execution & Tracking](docs/octoacme-execution-and-tracking.md)
- [Risk Management & Communication](docs/octoacme-risks-and-communication.md)
- [Release & Deployment Guide](docs/octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](docs/octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](docs/octoacme-roles-and-personas.md)

## Summary of OctoAcme project management processes

OctoAcme follows an iterative, evidence-driven approach that moves work through clear stages from initiation to close. Initiation captures the problem, success metrics, stakeholders, and an initial risk list in a short Project One-pager; a go/no‑go decision is made once objectives and stakeholder alignment are confirmed. Planning turns approved initiatives into a prioritized backlog with estimates, a Definition of Done, and a release plan supported by timeboxed kickoffs and planning sessions.

Day‑to‑day delivery uses a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) combined with a disciplined Pull Request process: keep PRs small, include links and acceptance criteria, run CI (tests, linting, security scans) before requesting review, and require approvals per team policy. Team cadence includes daily standups for blockers, a weekly delivery sync for progress and risks, and demos at sprint or milestone completion to validate outcomes.

Roles are explicit: Project Managers coordinate delivery and communication, Product Managers own outcomes and prioritization, Developers implement and test, QA validates acceptance criteria, and Stakeholders provide inputs and approvals. Communication emphasizes a single source of truth (project README or release docs), regular stakeholder updates, and defined escalation paths (team → PM → Product Lead → Sponsor), with a specific runbook for security incidents.

Quality and risk management are integrated across stages: developers write unit and integration tests, critical flows have smoke or end‑to‑end checks, manual QA is applied when needed, and security scanning runs in CI. Releases follow a checklist (acceptance criteria met, passing CI and security checks, release notes, rollback plan) with an automated pipeline preferred and a documented incident/rollback playbook. Retrospectives produce a small set of prioritized action items that are tracked into the backlog to drive continuous improvement.

## How to propose edits

To suggest changes or add new process content, use the "Add Content to Project Management Process Docs" issue template (GitHub: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml). Link or paste proposed content in the issue body and include acceptance criteria or stakeholder review notes as needed.
