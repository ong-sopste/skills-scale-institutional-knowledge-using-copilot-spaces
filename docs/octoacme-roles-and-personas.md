# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA / Testing Lead

### Role Summary
QA and Testing Leads ensure product quality by validating features against acceptance criteria and identifying risks before release. They work closely with developers and product stakeholders to make sure the work is ready for deployment.

### Responsibilities
- Design and execute test plans, including unit, integration, end-to-end, and security checks
- Validate that features meet acceptance criteria and release readiness requirements
- Execute smoke tests before production deployments
- Report and triage defects with clear reproduction steps
- Collaborate with developers on testability, automation, and defect resolution
- Document testing coverage and quality trends for release decisions

### Goals
- Catch quality issues early and reduce regressions
- Ensure features are production-ready before release
- Support fast, confident delivery without sacrificing quality

### Typical Communication
- Planning reviews for test strategy and acceptance criteria alignment
- Defect reports and quality status updates in standups
- Pre-release validation and sign-off with engineering and PM leads

### Interaction with Existing Roles
- Works with Developers to review defects, testability, and automation opportunities
- Partners with Project Managers to report quality status, release risk, and readiness
- Supports Product Managers by validating whether delivered work meets stated customer and business outcomes

---

## Security Lead / Security Champion

### Role Summary
Security Leads protect the project by ensuring secure design decisions, vulnerability awareness, and compliance with organizational security practices. They partner across teams to reduce risk before and during release.

### Responsibilities
- Review architecture and design decisions for security implications
- Ensure security scanning and vulnerability checks are included in CI/CD workflows
- Support security testing, threat assessment, and remediation planning
- Coordinate incident response activities and mitigation follow-up
- Advise teams on secure coding practices and policy compliance
- Maintain the project’s security escalation and response guidance

### Goals
- Minimize security vulnerabilities and production incidents
- Enable secure, compliant releases
- Build a culture of proactive risk awareness across the team

### Typical Communication
- Security reviews during planning and design discussions
- Findings from CI/CD and vulnerability scans
- Incident communication and post-incident follow-up with project leadership

### Interaction with Existing Roles
- Collaborates with Developers to review risky code paths and recommended mitigations
- Advises Product Managers and Project Managers on security risk, release timing, and escalation needs
- Works with Stakeholders and Sponsors when security requirements affect timelines or governance

---

## Engineering Lead / Tech Lead

### Role Summary
Engineering Leads provide technical direction, help break work into shippable increments, and coordinate cross-team dependencies. They balance technical quality with delivery needs and support the team’s execution.

### Responsibilities
- Provide technical estimates and feasibility assessments
- Identify technical risks, dependencies, and integration points
- Mentor developers and help maintain code quality standards
- Coordinate with other engineering teams on shared dependencies and releases
- Participate in architecture, design, and review discussions
- Help the team prioritize work against capacity and technical constraints

### Goals
- Deliver technically sound, scalable, maintainable solutions
- Reduce cycle time and avoid unnecessary technical debt
- Help the team make effective trade-offs between speed, quality, and risk

### Typical Communication
- Architecture and technical planning discussions
- Dependency updates and risk tracking in project syncs
- Review of delivery readiness and technical trade-offs with PMs and product leads

### Interaction with Existing Roles
- Aligns with Product Managers on feasibility, sequencing, and scope trade-offs
- Partners with Project Managers to surface delivery risks, dependencies, and timelines
- Supports Developers by guiding technical decision-making and establishing standards

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors represent business priorities, leadership interests, and strategic needs. They approve major project decisions and ensure work remains aligned to organizational goals.

### Responsibilities
- Define business requirements and success metrics
- Approve project charter, scope decisions, and major milestones
- Provide strategic direction and prioritization guidance
- Review release readiness and business impact
- Escalate cross-functional blockers or organizational constraints
- Receive and act on status updates, risk communications, and decisions

### Goals
- Ensure initiatives deliver measurable business value
- Maintain alignment with broader organizational priorities
- Enable timely decisions and clear accountability for outcomes

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Major approvals and decision checkpoints
- Briefings on risk, blockers, and delivery status

### Interaction with Existing Roles
- Works with Product Managers to confirm business value and prioritization
- Collaborates with Project Managers on updates, risks, and key decisions
- Reviews the work of Engineering and QA leads to confirm readiness for launch and adoption

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps and Infrastructure Engineers maintain the systems that support reliable, safe, repeatable delivery. They create the operational foundation for deployment, monitoring, and recovery.

### Responsibilities
- Design and maintain CI/CD pipelines and release automation
- Configure infrastructure for environments, services, and deployment workflows
- Implement monitoring, logging, and observability practices
- Enable safe deployments, rollback procedures, and operational recovery
- Maintain runbooks and operational guidance for common issues
- Coordinate with delivery teams on infrastructure requirements and dependencies

### Goals
- Enable fast, reliable, and repeatable deployments
- Reduce downtime and operational incidents
- Improve visibility into system health and release risk

### Typical Communication
- Pipeline and environment health updates
- Infrastructure requirements during planning and rollout coordination
- Incident response and post-deploy verification with technical owners

### Interaction with Existing Roles
- Supports Developers by providing automation, environments, and deployment reliability
- Partners with Project Managers on milestone readiness and operational risk
- Works with Security Leads to ensure secure and compliant deployment practices

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together, these personas clarify accountability, cross-role communication, and delivery ownership across the full project lifecycle.

