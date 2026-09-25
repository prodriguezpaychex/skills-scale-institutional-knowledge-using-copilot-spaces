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

---

## Executive Sponsors / Steering Committee Representatives

### Role Summary
Executive Sponsors provide strategic sponsorship, funding support, priority decisions, and escalation support for projects. A Steering Committee Representative performs these responsibilities on behalf of the group that governs the initiative.

### Responsibilities
- Confirm that the project supports organizational strategy and business outcomes
- Secure sponsorship, funding, and the resources needed to deliver the agreed scope
- Decide or sponsor decisions that exceed the delivery team's authority
- Resolve escalated scope, priority, and risk issues

### Goals
- Maintain strategic alignment and organizational support
- Remove obstacles that the delivery team cannot resolve
- Make timely decisions when trade-offs affect scope, schedule, funding, or risk

### Typical Communication
- Steering committee reviews and milestone briefings
- Executive status reports and escalation summaries
- Decision records for major trade-offs and risk acceptance

### Interactions with Existing Roles
- Partner with Project Managers on scope, schedule, resources, and major risk escalations
- Align with Product Managers on expected business outcomes and priority changes
- Support Developers by resolving organizational constraints rather than directing implementation details

---

## Business Owners / Domain Subject-Matter Experts

### Role Summary
Business Owners and domain subject-matter experts provide operational context and validate that the project solves the right business problem. They represent the people, policies, and workflows affected by the outcome.

### Responsibilities
- Explain domain processes, constraints, terminology, and dependencies
- Validate problem statements, requirements, and acceptance criteria
- Review delivered behavior against operational needs
- Identify business risks and recommend subject-matter experts for decisions

### Goals
- Ensure the solution is accurate, usable, and fit for its intended context
- Reduce ambiguity and rework caused by missing domain knowledge
- Support adoption by connecting project outcomes to real workflows

### Typical Communication
- Discovery workshops and requirements reviews
- Acceptance walkthroughs and decision records
- Status updates on domain dependencies and operational readiness

### Interactions with Existing Roles
- Work with Product Managers on discovery, prioritization, and outcome measures
- Clarify expected behavior with Developers and review acceptance evidence
- Provide Project Managers with domain dependencies, decisions, and stakeholder availability

---

## UX / Research Leads

### Role Summary
UX and Research Leads guide user research, workflow design, usability validation, and accessibility considerations. They help the team understand user needs before implementation and validate the experience after implementation.

### Responsibilities
- Plan and conduct research with representative users
- Translate findings into workflows, experience requirements, and design recommendations
- Validate usability and accessibility throughout delivery
- Document unresolved user needs, assumptions, and research risks

### Goals
- Improve user outcomes and product usability
- Reduce delivery risk caused by unvalidated assumptions
- Make accessibility and user feedback part of normal project decisions

### Typical Communication
- Research plans, findings, and design reviews
- Usability testing summaries and acceptance discussions
- Project planning updates for research and design milestones

### Interactions with Existing Roles
- Collaborate with Product Managers on customer problems, priorities, and success measures
- Work with Developers to make designs feasible and clarify interaction behavior
- Coordinate with Project Managers on research milestones, dependencies, and risks

---

## Quality / Test Leads

### Role Summary
Quality and Test Leads define the quality approach and coordinate the evidence needed to assess whether a project is ready to release. They make quality risks visible without taking ownership of implementation from Developers.

### Responsibilities
- Define test strategy, coverage expectations, and quality gates
- Coordinate functional, integration, regression, performance, and accessibility testing as needed
- Track defects, quality risks, and unresolved test gaps
- Advise on release readiness and go/no-go decisions

### Goals
- Provide reliable evidence that acceptance criteria and quality expectations are met
- Detect defects and risks early enough to address them economically
- Make residual quality risk explicit before release

### Typical Communication
- Test plans, results, and defect reports
- Quality reviews during planning and execution
- Release readiness assessments and risk summaries

### Interactions with Existing Roles
- Work with Developers on test automation, reproducibility, and defect resolution
- Align with Product Managers on acceptance expectations and user impact
- Coordinate with Project Managers on quality milestones and with Release / Deployment Managers on go/no-go recommendations

---

## Security, Privacy, and Compliance Partners

### Role Summary
Security, Privacy, and Compliance Partners identify control requirements and help the team manage technical, regulatory, and data protection risks. They provide specialized review and approval input where the project requires it.

### Responsibilities
- Identify applicable security, privacy, legal, and regulatory requirements
- Coordinate threat modeling, privacy reviews, control assessments, and evidence collection
- Document findings, exceptions, mitigations, and residual risk
- Define approval or release conditions for governed changes

### Goals
- Protect customers, data, systems, and the organization
- Find control gaps early and avoid late approval surprises
- Enable informed decisions about risk acceptance and remediation

### Typical Communication
- Risk assessments, review findings, and remediation plans
- Security and privacy checkpoints during planning and execution
- Approval records and release conditions

### Interactions with Existing Roles
- Engage Project Managers early to schedule reviews and track risk mitigations
- Work with Developers on secure design, implementation controls, and evidence
- Advise Product Managers on customer and regulatory impacts and provide release input to Release / Deployment Managers

---

## Release / Deployment Managers and Site Reliability Engineers

### Role Summary
Release / Deployment Managers and Site Reliability Engineers coordinate the transition from completed work to a reliable production service. They focus on deployment sequencing, observability, rollback, and production verification.

### Responsibilities
- Define release plans, deployment sequencing, and rollback procedures
- Confirm observability, alerting, capacity, and production support readiness
- Coordinate deployment execution and post-deployment verification
- Capture operational risks, incidents, and follow-up actions

### Goals
- Release changes predictably and safely
- Minimize customer impact during deployment and recovery
- Ensure production behavior is visible and supportable

### Typical Communication
- Release checklists, runbooks, and deployment plans
- Go/no-go reviews and production verification updates
- Incident reviews and operational metrics

### Interactions with Existing Roles
- Connect Developers, Quality / Test Leads, and Security Partners to release readiness evidence
- Work with Project Managers on timing, dependencies, and escalation paths
- Share operational signals with Product Managers to inform outcomes and follow-up priorities

---

## Operations / Support and Customer Success Owners

### Role Summary
Operations, Support, and Customer Success Owners prepare the organization and customers for the delivered change. They own the service transition, support readiness, adoption feedback, and operational learning after release.

### Responsibilities
- Prepare support teams, customer communications, training, and operational runbooks
- Confirm service readiness, ownership, and escalation paths
- Monitor adoption, incidents, and recurring customer issues
- Feed post-release feedback into product and improvement planning

### Goals
- Make new capabilities supportable and understandable from day one
- Reduce avoidable customer disruption and support escalations
- Turn operational and customer feedback into measurable improvements

### Typical Communication
- Support readiness reviews and customer communication plans
- Runbooks, knowledge articles, and incident updates
- Adoption reports, customer feedback, and retrospective inputs

### Interactions with Existing Roles
- Partner with Release / Deployment Managers on handoff, rollback readiness, and production support
- Work with Developers on incident fixes and operational defects
- Share customer outcomes with Product Managers and transition milestones with Project Managers

---

## Program / Dependency Managers

### Role Summary
Program and Dependency Managers coordinate work across related projects. They make shared dependencies, portfolio constraints, sequencing decisions, and cross-project risks visible.

### Responsibilities
- Maintain cross-project dependency maps and commitment dates
- Identify conflicts in resources, sequencing, scope, and priorities
- Coordinate decisions that span multiple Project Managers or teams
- Escalate portfolio-level risks and recommend sequencing options

### Goals
- Keep related initiatives aligned and unblocked
- Reduce duplicate work and unexpected downstream impact
- Improve portfolio-level predictability and decision-making

### Typical Communication
- Dependency reviews and integrated delivery plans
- Cross-project risk and status reports
- Escalation briefs and portfolio decision records

### Interactions with Existing Roles
- Work with Project Managers to maintain dependency commitments and surface schedule risk
- Partner with Product Managers to resolve priority conflicts and coordinate outcomes
- Escalate cross-project trade-offs to Executive Sponsors when team-level decisions are insufficient

---

## Role Interaction Guide

The following handoffs clarify how the personas collaborate across the project lifecycle:

| Lifecycle activity | Primary accountability | Key contributors |
| --- | --- | --- |
| Initiation and outcomes | Product Manager and Project Manager | Executive Sponsor, Business Owner, UX / Research Lead |
| Planning and dependencies | Project Manager | Developers, Product Manager, Business Owner, Program / Dependency Manager |
| Risk and control review | Project Manager | Security, Privacy, and Compliance Partner; Quality / Test Lead; Executive Sponsor |
| Requirements and acceptance | Product Manager | Business Owner, UX / Research Lead, Developers, Quality / Test Lead |
| Release readiness | Release / Deployment Manager or Site Reliability Engineer | Developers, Quality / Test Lead, Security Partner, Operations / Support Owner, Project Manager |
| Production handoff and adoption | Operations / Support or Customer Success Owner | Release / Deployment Manager, Developers, Product Manager, Project Manager |
| Cross-project escalation | Executive Sponsor / Steering Committee | Project Manager, Product Manager, Program / Dependency Manager |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

