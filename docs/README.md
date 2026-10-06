# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management playbook — your centralized resource for scalable, iterative processes that power our cross-functional projects.

## Overview

This directory contains the complete set of project management processes used by OctoAcme. Our approach prioritizes customer value, clear ownership, and data-informed decisions while fostering psychological safety and team feedback.

Whether you're a new team member, starting a project, or seeking guidance during execution, you'll find practical workflows, checklists, and templates here.

## Core Principles

- Customer-first: prioritize customer value and usability in every decision
- Iterative delivery: ship small, testable increments rather than big-bang releases
- Clear ownership: every project has named PM and Product Lead roles
- Data-informed: measure impact and iterate based on evidence and feedback
- Psychological safety: encourage candid feedback, learning, and continuous improvement

## Project Lifecycle

OctoAcme projects follow this phased approach:

1. Initiation — validate business need, align stakeholders, establish success metrics
2. Planning — break work into shippable increments, identify risks and dependencies
3. Execution — build, test, review, and track progress toward milestones
4. Release — deploy to production with verified quality and rollback readiness
5. Retrospective — capture learnings and convert them into actionable improvements

## Quick Navigation

| Document | Purpose | Use When |
|----------|---------|----------|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme approach, roles, and key artifacts | You're new to the team or need process orientation |
| [Project Initiation Guide](octoacme-project-initiation.md) | Define initial steps to validate and authorize work | A new project idea or feature proposal is ready to explore |
| [Project Planning](octoacme-project-planning.md) | Turn an approved initiative into an actionable plan and backlog | Your project is approved and you're ready to plan execution |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Manage day-to-day execution and track progress toward milestones | You're actively delivering work on a project |
| [Risks & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies | You need to escalate blockers or update stakeholders |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardize how features are released to production safely | Your feature is ready to deploy or you need a release plan |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into improvements | A sprint, release, or milestone has completed |
| [Roles & Personas](octoacme-roles-and-personas.md) | Define typical roles, responsibilities, and communication patterns | You need clarity on team structure or role expectations |

## Getting Started

### For New Team Members
1. Read [Project Management Overview](octoacme-project-management-overview.md) to understand our principles and roles
2. Review [Roles & Personas](octoacme-roles-and-personas.md) to understand how teams are structured
3. Bookmark this README for quick reference during your first project

### For Project Leads & Managers
Follow this sequence for a new project:
1. [Project Initiation Guide](octoacme-project-initiation.md) — align stakeholders and validate the problem
2. [Project Planning](octoacme-project-planning.md) — create backlog and timeline
3. [Execution & Tracking](octoacme-execution-and-tracking.md) — run standups and track progress
4. [Risks & Communication](octoacme-risks-and-communication.md) — manage blockers and stakeholder updates
5. [Release & Deployment Guide](octoacme-release-and-deployment.md) — prepare and deploy
6. [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — capture learnings

### For Developers
- Start with [Execution & Tracking](octoacme-execution-and-tracking.md) to understand our PR and CI workflows
- Review [Project Planning](octoacme-project-planning.md) to understand acceptance criteria and backlog structure
- Check [Release & Deployment Guide](octoacme-release-and-deployment.md) before shipping to production

## Key Concepts

### Project One-pager
Every project starts with a lightweight one-pager that defines:
- Problem statement — what are we solving?
- Goal (SMART) — what outcome are we driving?
- Success metrics — how do we measure success?
- Stakeholders — who needs to align?
- Timeline and milestones — what's our delivery schedule?
- Risks and dependencies — what could block us?
- Team and roles — who's responsible?

See [Project Initiation Guide](octoacme-project-initiation.md) for the template.

### Definition of Done (DoD)
Every project team agrees on a Definition of Done that includes:
- Acceptance criteria met
- Tests written and passing
- Code reviewed and approved
- Documentation complete
- Deployment-ready

See [Project Planning](octoacme-project-planning.md) for guidance.

### Risk Register
Risks are tracked continuously in a simple register:
- ID, Description, Impact, Likelihood, Owner, Mitigation, Status

Risks are reviewed in weekly syncs and escalated when needed. See [Risks & Communication](octoacme-risks-and-communication.md) for escalation paths.

### Roles

Three core roles power OctoAcme projects:

- Project Manager (PM) — coordinates delivery, manages schedules, and communicates with stakeholders
- Product Manager (PdM) — defines outcomes, prioritizes backlog, and measures success
- Delivery team — developers, QA, and specialists who design, build, test, and ship

See [Roles & Personas](octoacme-roles-and-personas.md) for detailed responsibilities.

## Communication Cadence

- Daily standup (15 minutes) — progress, blockers, dependencies
- Weekly PM + PdM sync — plan, risk review, stakeholder updates
- Weekly delivery standup (if team > 4) — track progress and unblock work
- Sprint or milestone demo — show progress and gather feedback
- Monthly stakeholder update — summary, metrics, next steps
- Post-release retrospective — learnings and action items

## How to Use These Docs

1. Link docs in your project README — copy the relevant sections into your project's README to ground your team in shared language
2. Customize for your team — these are templates; adapt them to your team's context and constraints
3. Add to `.copilot/` for Copilot Spaces — if using Copilot Spaces, attach these docs as context for specialized guidance
4. Iterate and improve — use the issue template in `.github/ISSUE_TEMPLATE/` to suggest improvements or new content

## Process Improvement

Have an idea to improve these processes? Found a gap or unclear section?

Use the process improvement issue template in [`.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to:
- suggest new content or sections
- flag unclear guidance
- propose examples or case studies
- share team feedback

All improvements are tracked and discussed collaboratively.

## Questions?

- Process question? Check the specific document or ask your Product Lead or Project Manager
- Want to improve a doc? Open an issue using the process improvement template
- Need examples? Check your project's README for customized guidance and case studies

---

Maintained by OctoAcme project management stakeholders.
