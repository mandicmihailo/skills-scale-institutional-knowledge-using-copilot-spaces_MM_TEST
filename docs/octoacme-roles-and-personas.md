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

## Project Sponsors / Executives

### Role Summary
Project Sponsors represent the organization’s investment in a project. They provide strategic direction, secure support, and make or escalate decisions that exceed the project team’s authority.

### Responsibilities
- Own and communicate the project’s business case and organizational priority
- Secure executive support and resolve resource constraints beyond the team’s control
- Approve major changes to funding, scope, or strategic direction within their authority
- Make timely decisions on escalations raised by the Project Manager

### Goals
- Ensure the project remains aligned with organizational strategy
- Enable the team to make progress by resolving high-impact blockers
- Realize the intended business outcomes

### Typical Communication
- Governance and steering discussions
- Major decision and escalation briefings
- Business-case and outcome reviews

### Interactions and Handoffs
- Align with the Product Manager on strategic outcomes and priority.
- Partner with the Project Manager on governance, escalations, and organizational support; the Project Manager remains responsible for day-to-day coordination and reporting.
- Rely on the Business Owner / Subject-Matter Expert for domain impact and on the Technical Lead for feasibility when considering major changes.

---

## Business Owners / Subject-Matter Experts

### Role Summary
Business Owners and Subject-Matter Experts provide operational and domain expertise. They clarify business rules and validate that proposed solutions meet real user and business needs.

### Responsibilities
- Explain domain context, workflows, constraints, and business rules
- Review requirements and clarify questions from the team
- Validate deliverables against business needs and provide timely feedback
- Identify business impacts, dependencies, and risks

### Goals
- Ensure the solution works for its intended users and business context
- Reduce rework caused by misunderstood requirements or workflows
- Support informed, timely product and project decisions

### Typical Communication
- Requirements and workflow reviews
- Demonstrations, acceptance discussions, and domain Q&A
- Business-impact and readiness assessments

### Interactions and Handoffs
- Work with the Product Manager to refine user needs, value, and acceptance criteria; the Product Manager remains accountable for product priorities.
- Answer Developers’ domain questions and review implementations against business rules.
- Coordinate with the Project Manager on review availability, decisions, dependencies, and business-side risks.
- Consult the Operations / Service Owner when validating operational workflows and support needs.

---

## Technical Leads / Architects

### Role Summary
Technical Leads and Architects guide technical direction and help the team make sound engineering decisions. They advise on feasibility and technical risk without replacing the Developers’ ownership of implementation.

### Responsibilities
- Define or guide architecture, technical standards, and engineering trade-offs
- Identify technical dependencies, constraints, and risks, and recommend mitigations
- Support estimation, technical planning, and quality practices
- Facilitate technical decisions and communicate their impact

### Goals
- Enable a coherent, secure, reliable, and maintainable solution
- Address technical risks and dependencies early
- Keep technical decisions aligned with product goals and delivery constraints

### Typical Communication
- Architecture and design reviews
- Technical plans, decision records, and risk discussions
- Estimation and dependency reviews with the delivery team

### Interactions and Handoffs
- Guide Developers through design and implementation and support code and design reviews; Developers retain responsibility for building and testing their work.
- Advise the Product Manager on feasibility and technical trade-offs so priorities and scope are informed.
- Give the Project Manager visibility into technical dependencies, estimates, and risks for plans and status reporting.
- Coordinate with the Quality Assurance / Test Lead on testability and with the Operations / Service Owner on reliability and operability.

---

## Quality Assurance / Test Leads

### Role Summary
Quality Assurance and Test Leads coordinate the approach to verifying that deliverables meet requirements and quality expectations. They make quality status and risk visible to the team.

### Responsibilities
- Define appropriate test coverage and verification activities
- Coordinate testing, track defects, and communicate quality risks
- Confirm that acceptance criteria are testable and that results are documented
- Assess verification status and provide evidence for release-readiness decisions

### Goals
- Detect defects and gaps early
- Provide confidence that deliverables meet agreed expectations
- Make quality risks visible before they affect users or delivery commitments

### Typical Communication
- Test plans, results, and defect reports
- Acceptance-criteria reviews and demonstrations
- Quality and readiness updates

### Interactions and Handoffs
- Collaborate with Developers on testability, automated checks, and defect resolution; Developers remain responsible for testing their implementation.
- Work with the Product Manager and Business Owner / Subject-Matter Expert to clarify and verify acceptance criteria.
- Report quality progress, blockers, and residual risks to the Project Manager for delivery tracking.
- Share verification evidence and unresolved risks with the Operations / Service Owner as part of release readiness.

---

## Operations / Service Owners

### Role Summary
Operations and Service Owners represent the teams responsible for running and supporting a delivered service. They define operational expectations and help ensure releases can be supported reliably.

### Responsibilities
- Define monitoring, support, reliability, and service-readiness needs
- Identify operational constraints, dependencies, and risks
- Participate in release planning and prepare support handoffs
- Clarify ownership and procedures for service incidents and ongoing operations

### Goals
- Ensure services are observable, reliable, and supportable
- Make operational impacts and readiness gaps visible before release
- Enable a clear transition from project delivery to ongoing service ownership

### Typical Communication
- Operational-readiness and release reviews
- Monitoring, support, and incident-response documentation
- Service health and handoff discussions

### Interactions and Handoffs
- Collaborate with Developers and the Technical Lead on monitoring, deployment, reliability, and operability requirements.
- Align with the Product Manager on service outcomes and user impact.
- Work with the Project Manager to track readiness dependencies, coordinate handoffs, and communicate operational risks.
- Review verification results with the Quality Assurance / Test Lead and confirm that support teams have the information needed for release.

---

## Assigning and combining roles

Projects may combine these personas or adapt them to fit their size and context. When one person holds multiple roles, make the responsibilities, decision authority, and handoffs explicit so that essential reviews and approvals are still covered.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
