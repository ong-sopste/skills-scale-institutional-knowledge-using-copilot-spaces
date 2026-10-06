# OctoAcme Project Management Documentation

## Overview

This directory contains the complete **OctoAcme project management playbook**—a collection of lightweight, iterative processes for running cross-functional projects. Our approach prioritizes customer value, clear ownership, and data-informed decision-making while encouraging team feedback and psychological safety.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Quick Links

| Document | Purpose | When to Use |
|----------|---------|-------------|
| [Project Management Overview](octoacme-project-management-overview.md) | High-level introduction to OctoAcme approach, roles, and key artifacts | New team members, project kickoff |
| [Project Initiation Guide](octoacme-project-initiation.md) | Define initial steps to validate and authorize work | When a new project idea is ready to explore |
| [Project Planning](octoacme-project-planning.md) | Turn an approved initiative into an actionable plan and backlog | After project is approved, before execution |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Manage day-to-day execution and track progress | During active project delivery |
| [Risks & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies | Throughout project lifecycle |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardize how features are released to production | Before releasing to production |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and convert them into improvements | After each sprint, release, or milestone |
| [Roles & Personas](octoacme-roles-and-personas.md) | Define typical roles and responsibilities | Reference for understanding team structure |

## Getting Started

### For New Team Members
1. Start with [Project Management Overview](octoacme-project-management-overview.md) to understand OctoAcme's approach and core roles
2. Review [Roles & Personas](octoacme-roles-and-personas.md) to understand your role and responsibilities
3. Bookmark this README for quick reference throughout your projects

### For Project Managers
1. Start a new project by following the [Initiation Guide](octoacme-project-initiation.md)
2. Move into planning with [Project Planning](octoacme-project-planning.md)
3. Manage execution using [Execution & Tracking](octoacme-execution-and-tracking.md)
4. Communicate risks with [Risks & Communication](octoacme-risks-and-communication.md)
5. Close out with [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

### For Product Managers
1. Refer to [Project Management Overview](octoacme-project-management-overview.md) for your role and responsibilities
2. Use [Project Initiation Guide](octoacme-project-initiation.md) to define success metrics
3. Collaborate with PMs during [Project Planning](octoacme-project-planning.md)
4. Measure outcomes as described in [Execution & Tracking](octoacme-execution-and-tracking.md)

### For Developers
1. Review [Roles & Personas](octoacme-roles-and-personas.md) to understand your responsibilities
2. Participate in [Execution & Tracking](octoacme-execution-and-tracking.md) activities
3. Contribute to [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) sessions

## Project Lifecycle Overview

The OctoAcme approach follows a structured but flexible lifecycle:

```
Initiation → Planning → Execution → Release → Retrospective
```

### 1. **Initiation** ([Project Initiation Guide](octoacme-project-initiation.md))
   - Confirm business need and measurable outcomes
   - Identify stakeholders and champions
   - Define success criteria and timeline
   - Decision gate: Approve to move into planning

### 2. **Planning** ([Project Planning](octoacme-project-planning.md))
   - Break work into shippable increments
   - Create prioritized backlog with acceptance criteria
   - Identify dependencies and risks
   - Define Definition of Done

### 3. **Execution** ([Execution & Tracking](octoacme-execution-and-tracking.md))
   - Daily standups and weekly syncs
   - Use project board to track progress
   - Run automated tests and quality checks
   - Manage risks and dependencies ([Risks & Communication](octoacme-risks-and-communication.md))

### 4. **Release** ([Release & Deployment Guide](octoacme-release-and-deployment.md))
   - Verify all acceptance criteria met
   - Pass CI and security scans
   - Deploy to production with rollback plan
   - Announce release to stakeholders

### 5. **Retrospective** ([Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md))
   - Capture learnings and improvements
   - Convert action items into backlog
   - Celebrate successes and iterate

## Key Artifacts

Each project should maintain:

- **Project Charter / One-pager** (from [Project Initiation Guide](octoacme-project-initiation.md))
- **Roadmap and Release Plan** (from [Project Planning](octoacme-project-planning.md))
- **Sprint/Iteration Backlog** (from [Project Planning](octoacme-project-planning.md))
- **Risk Register** (from [Risks & Communication](octoacme-risks-and-communication.md))
- **Retrospective notes and action items** (from [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md))

## Communication Cadence

Recommended meeting schedule:

- **Daily standups** (15 min) — Team-level progress and blockers
- **Weekly PM + PdM sync** — Strategy and prioritization
- **Twice-weekly team standups** — Delivery updates
- **Monthly stakeholder updates** — High-level progress and risks
- **Sprint/Milestone reviews and retrospectives** — End-of-cycle activities

## How to Use These Docs

1. **Keep docs updated**: Project artifacts referenced in these docs should be actively maintained in your project repository
2. **Use Copilot Spaces**: Add relevant docs to your `.copilot/` directory to ground Copilot in your project context
3. **Customize as needed**: These docs provide a baseline; adapt them to your team's needs and culture
4. **Contribute improvements**: See [Process Docs Contributing](#process-docs-contributing) below

## Process Docs Contributing

To request updates or additions to these process documents, [open an issue](../../issues/new/choose) using the **"Add Content to Project Management Process Docs"** issue template.

When proposing changes:
- Describe the gap or improvement needed
- Provide rationale and context
- Include suggested content if possible
- Ensure alignment with OctoAcme core principles

## Questions & Support

For questions about OctoAcme project management processes:
1. Check the relevant doc in this directory
2. Review [Project Management Overview](octoacme-project-management-overview.md) for role clarifications
3. Open an issue if you've identified a gap or improvement opportunity

---

**Last Updated**: October 2026  
**Maintained by**: OctoAcme Project Management Team
