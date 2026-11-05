# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles may be combined on smaller projects, but accountability for each responsibility should remain clear. The Project Manager coordinates delivery and communication; specialist roles own their respective decisions and expertise.

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

### Interactions with Other Roles
- Work with the Product Manager to clarify requirements and acceptance criteria.
- Coordinate implementation, estimates, technical risks, and dependencies with the Technical Lead and Project Manager.
- Collaborate with QA/Test on testability, defects, and validation; partner with UX on feasible, usable designs.
- Consult the Security/Privacy Partner and DevOps/Platform or Release Engineer when changes affect security, privacy, infrastructure, or deployment.

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

### Interactions with Other Roles
- Align outcomes, scope, and priority with the Business Sponsor and Subject-Matter Experts.
- Partner with UX/User Research on user needs and with QA/Test on acceptance criteria and validation.
- Make product trade-offs with input from Developers, the Technical Lead, and Security/Privacy Partner.
- Coordinate sequencing and stakeholder updates with the Project Manager; use delivery and quality evidence to assess outcomes.

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

### Interactions with Other Roles
- Coordinate plans, dependencies, and decisions with the Product Manager, Technical Lead, and delivery team.
- Track specialist risks and readiness from QA/Test, Security/Privacy, UX, and DevOps/Release partners without taking over their expert decisions.
- Escalate decisions beyond the team's authority to the Sponsor and communicate impacts to stakeholders.

---

## QA / Testing

### Role Summary
QA/Testing validates that deliverables meet acceptance criteria and quality expectations. A QA/Test Lead may coordinate the test approach; on smaller teams, these responsibilities can be shared among QA and Developers.

### Responsibilities
- Define and coordinate an appropriate test approach, including risk-based, integration, and end-to-end testing as applicable
- Review acceptance criteria for testability and identify coverage gaps
- Coordinate defect triage and communicate quality risks and validation results
- Support release readiness with evidence from testing

### Goals
- Find important defects early and provide reliable evidence of product quality
- Ensure critical user flows and agreed acceptance criteria are validated

### Interactions with Other Roles
- Work with the Product Manager to understand acceptance expectations and with Developers to build testable features and resolve defects.
- Coordinate test timing, dependencies, and status with the Project Manager.
- Partner with UX on usability validation and with DevOps/Release on test environments and smoke tests.
- Raise security or privacy concerns to the Security/Privacy Partner and involve stakeholders in acceptance decisions when appropriate.

---

## UX / UI Designer or User Researcher

### Role Summary
UX/UI Designers and User Researchers bring user needs and evidence into product decisions and shape usable, accessible experiences.

### Responsibilities
- Plan or conduct appropriate user research and synthesize findings
- Create and validate user flows, interaction designs, and prototypes
- Identify usability and accessibility considerations and assumptions
- Share design guidance and research evidence with the delivery team

### Goals
- Help ensure solutions address real user needs and are understandable and usable
- Reduce avoidable usability risks through early feedback and iteration

### Interactions with Other Roles
- Partner with the Product Manager to connect research and design decisions to outcomes and priorities.
- Collaborate with Developers and the Technical Lead on feasibility and implementation trade-offs.
- Work with QA/Test to include usability and accessibility considerations in validation.
- Share findings with stakeholders and coordinate research activities and dependencies with the Project Manager.

---

## Technical Lead / Architect

### Role Summary
The Technical Lead or Architect guides technical design and integration decisions so the solution is maintainable, reliable, and aligned with agreed technical constraints.

### Responsibilities
- Guide architecture, interfaces, and technical design decisions
- Support estimation and identify technical dependencies and risks
- Promote maintainability, reliability, and appropriate engineering practices
- Explain technical options, trade-offs, and impacts to the team

### Goals
- Enable a coherent and supportable technical solution
- Surface technical risks and integration needs early

### Interactions with Other Roles
- Collaborate with Developers on design, implementation, estimates, and technical risks.
- Explain options and trade-offs to the Product Manager and Project Manager so product and delivery decisions are informed.
- Coordinate security requirements with the Security/Privacy Partner and operational needs with the DevOps/Platform or Release Engineer.
- Work with QA/Test on testability and integration coverage.

---

## DevOps / Platform or Release Engineer

### Role Summary
This role supports reliable build, deployment, runtime operations, and observability for the product or service.

### Responsibilities
- Advise on CI/CD pipelines, environments, configuration, and deployment practices
- Support monitoring, logging, observability, and operational readiness
- Prepare or advise on release, rollback, and mitigation procedures
- Identify platform constraints and operational risks

### Goals
- Make releases repeatable and observable
- Improve service reliability and safe recovery from deployment issues

### Interactions with Other Roles
- Work with Developers and the Technical Lead on platform requirements, pipelines, and runtime design.
- Coordinate test environments and smoke-test needs with QA/Test.
- Communicate deployment dependencies, readiness, and risks to the Project Manager; align release timing and scope with the Product Manager.
- Consult the Security/Privacy Partner on secure configuration and the Stakeholders or support teams on operational handoffs where relevant.

---

## Security / Privacy Partner

### Role Summary
The Security/Privacy Partner advises teams on security and privacy requirements, risks, and appropriate review or controls.

### Responsibilities
- Identify security and privacy considerations during initiation, planning, and design
- Advise on controls, threat or privacy reviews, and mitigation options
- Review relevant changes or evidence according to team policy
- Communicate findings, residual risks, and incident escalation needs

### Goals
- Address security and privacy risks early and proportionately
- Help teams meet applicable security and privacy expectations before release

### Interactions with Other Roles
- Work with the Product Manager and Stakeholders to clarify data sensitivity and requirements.
- Partner with Developers and the Technical Lead on secure design and mitigation implementation.
- Coordinate review timing and track risks with the Project Manager; share release-relevant findings with QA/Test and DevOps/Release.
- Follow the security incident runbook and notify Security on-call for security incidents, as specified by project process.

---

## Business Sponsor or Subject-Matter Expert

### Role Summary
The Business Sponsor provides strategic direction and resolves escalations beyond the team's authority. Subject-Matter Experts provide domain knowledge and help validate business rules and operational needs. These may be separate people.

### Responsibilities
- Explain business context, constraints, expected benefits, or specialized domain rules
- Provide timely input during initiation, planning, and validation
- Make or advise on decisions within their authority
- The Sponsor resolves escalations and supports alignment on business priority and resources

### Goals
- Ensure the initiative addresses an important business need and has appropriate sponsorship
- Help the team make accurate decisions grounded in domain knowledge

### Interactions with Other Roles
- Work with the Product Manager to clarify outcomes, priorities, and domain requirements.
- Provide decisions or escalation support to the Project Manager, who coordinates impacts to scope, schedule, risks, and communications.
- Share domain knowledge with Developers, UX, QA/Test, and the Technical Lead so requirements and validation reflect real constraints.
- Participate in stakeholder updates and milestone reviews as needed; the Sponsor does not replace the Product Manager's day-to-day product prioritization.

---

## Stakeholders

### Role Summary
Stakeholders are people or groups affected by, contributing to, or relying on project outcomes, such as customers, operations, sales, support, or dependent teams.

### Responsibilities
- Share needs, constraints, and relevant feedback
- Review updates or deliverables when their input or approval is needed
- Communicate impacts to their teams and raise concerns through agreed channels

### Goals
- Ensure relevant perspectives and downstream impacts are considered
- Support adoption and successful use of delivered outcomes

### Interactions with Other Roles
- The Project Manager coordinates stakeholder communication and identifies when input or decisions are needed.
- The Product Manager gathers stakeholder input to inform priorities and outcomes while retaining product prioritization accountability.
- The Sponsor resolves business escalations; Subject-Matter Experts provide focused domain guidance.
- The delivery team engages relevant stakeholders for design feedback, operational readiness, and acceptance as appropriate.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Adapt role assignments to project size: people may hold multiple roles, but clarify ownership, decision boundaries, and handoffs.
