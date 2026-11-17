# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles describe responsibilities, not necessarily separate people; one person may hold multiple roles depending on the project. Teams should explicitly agree who is accountable for decisions when responsibilities overlap.

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

## Project Sponsor / Executive Sponsor

### Role Summary
The sponsor owns the business case and provides strategic direction, organizational support, and resources for the project.

### Responsibilities
- Confirm the project's strategic outcomes and continued justification
- Secure or escalate resources and resolve high-level priority conflicts
- Make or obtain decisions beyond the project team's authority
- Review significant changes, risks, and progress against business outcomes

### Goals
- Ensure the project remains valuable and supported
- Resolve escalations promptly and enable delivery

### Typical Communication
- Milestone reviews and concise status reports
- Escalation briefings and decision requests

### Interactions with Existing Roles
- Partners with the Product Manager to align product outcomes and the business case
- Receives delivery status and escalations from the Project Manager
- Supports Developers by helping resolve organizational impediments, without directing day-to-day technical work

### Decision / Accountability Boundaries
Accountable for sponsorship, strategic alignment, and decisions escalated to the sponsor; the Product Manager remains responsible for product priorities, while the Project Manager coordinates delivery and escalations.

---

## Business Analyst

### Role Summary
The Business Analyst translates business needs into clear requirements, rules, workflows, and acceptance criteria.

### Responsibilities
- Elicit, analyze, document, and validate requirements
- Identify gaps, assumptions, and impacts across processes
- Maintain traceability between needs, requirements, and validation

### Goals
- Make needs understandable and testable
- Reduce ambiguity and avoid preventable rework

### Typical Communication
- Workshops and interviews with stakeholders
- Requirements, workflow diagrams, and clarification notes

### Interactions with Existing Roles
- Works with the Product Manager to refine needs and acceptance criteria while the Product Manager owns product priorities
- Clarifies requirements for Developers and coordinates with QA/test engineers to ensure they can be validated
- Shares dependencies and unresolved questions with the Project Manager for planning and tracking

### Decision / Accountability Boundaries
Recommends and documents requirements; business and product decision authority remains with the designated stakeholder or Product Manager.

---

## UX/UI Designer or User Researcher

### Role Summary
This role investigates user needs and designs or evaluates usable, accessible experiences.

### Responsibilities
- Plan and conduct user research or usability evaluations
- Create interaction flows, prototypes, and design specifications
- Identify usability and accessibility considerations

### Goals
- Ensure solutions address user needs and are understandable and accessible

### Typical Communication
- Research findings, design reviews, prototypes, and usability reports

### Interactions with Existing Roles
- Partners with the Product Manager to connect user evidence to product outcomes and priorities
- Collaborates with Developers and the Technical Lead to assess feasibility and implement designs accessibly
- Coordinates research or design review timing with the Project Manager

### Decision / Accountability Boundaries
Provides user-centered evidence and design recommendations; the Product Manager owns product priorities, and implementation decisions are made with engineering.

---

## QA / Test Engineer

### Role Summary
The QA/Test Engineer helps the team prevent and detect defects and assess whether delivered work meets its quality and acceptance expectations.

### Responsibilities
- Define appropriate test approaches and maintain test cases or automation
- Execute tests, report defects, and communicate residual quality risks
- Verify acceptance criteria and support release-readiness assessment

### Goals
- Provide reliable evidence about product quality and risk
- Detect issues early and support dependable releases

### Typical Communication
- Test plans, defect reports, test results, and readiness summaries

### Interactions with Existing Roles
- Works with Developers to reproduce defects, verify fixes, and improve testability
- Clarifies expected behavior and acceptance criteria with the Product Manager and Business Analyst
- Shares quality risks and test progress with the Project Manager for status and release coordination

### Decision / Accountability Boundaries
Provides quality evidence and recommendations; the designated product or release decision-maker accepts residual risk and makes the release decision.

---

## Technical Lead / Architect

### Role Summary
The Technical Lead or Architect guides technical design and engineering decisions so the solution meets functional and quality needs.

### Responsibilities
- Facilitate architecture and design decisions and document significant trade-offs
- Guide engineering standards, technical quality, and integration approach
- Identify technical risks, dependencies, and estimates

### Goals
- Enable a secure, reliable, maintainable solution that can evolve

### Typical Communication
- Design proposals, technical reviews, estimates, and risk updates

### Interactions with Existing Roles
- Guides and supports Developers without replacing their implementation responsibilities
- Works with the Product Manager to explain technical trade-offs that affect scope or outcomes
- Provides the Project Manager with technical dependencies, risks, and estimates for planning

### Decision / Accountability Boundaries
Owns or facilitates technical recommendations within delegated engineering authority; product scope remains with the Product Manager and delivery coordination with the Project Manager.

---

## Operations / Release Engineer

### Role Summary
This role prepares and coordinates deployment and operational readiness so changes can be released and supported reliably.

### Responsibilities
- Plan deployment, rollback, monitoring, and operational handoffs
- Identify reliability, capacity, and support readiness needs
- Coordinate release procedures and document operational guidance

### Goals
- Make releases safe, observable, and supportable

### Typical Communication
- Release plans, runbooks, readiness checks, and operational alerts

### Interactions with Existing Roles
- Coordinates deployment requirements and handoffs with Developers and QA/Test Engineers
- Advises the Product Manager on operational impacts relevant to product or release decisions
- Aligns release timing, dependencies, and communications with the Project Manager

### Decision / Accountability Boundaries
Advises on operational readiness and executes or coordinates assigned release activities; release approval belongs to the explicitly designated decision-maker.

---

## Security / Privacy Specialist

### Role Summary
The Security/Privacy Specialist helps identify and address security, privacy, and compliance risks in the solution and its delivery.

### Responsibilities
- Define or clarify applicable security and privacy requirements
- Assess risks and recommend controls, reviews, or mitigations
- Advise on secure handling of data and relevant incident or compliance processes

### Goals
- Integrate security and privacy into project decisions and delivery
- Reduce exposure to avoidable security, privacy, and compliance risks

### Typical Communication
- Risk assessments, review findings, control recommendations, and decision records

### Interactions with Existing Roles
- Works with Product Managers to incorporate relevant requirements into product scope and acceptance criteria
- Advises Developers and the Technical Lead on secure design and implementation
- Communicates material risks, dependencies, and review needs to the Project Manager for tracking and escalation

### Decision / Accountability Boundaries
Provides specialist advice and documents findings; designated organizational authorities decide risk acceptance and required approvals.

---

## Business Stakeholder / Subject-Matter Expert

### Role Summary
A Business Stakeholder or Subject-Matter Expert provides domain knowledge, validates business needs, and contributes to decisions within their authority.

### Responsibilities
- Explain business processes, constraints, and domain terminology
- Review requirements and validate whether deliverables address business needs
- Provide timely feedback and identify impacts to affected groups

### Goals
- Ensure project decisions reflect accurate domain context and stakeholder needs

### Typical Communication
- Interviews, workshops, reviews, and documented feedback or approvals

### Interactions with Existing Roles
- Works with the Product Manager to explain value, constraints, and user or business needs
- Partners with the Business Analyst to clarify and validate requirements
- Coordinates review timing and communicates impacts or decisions with the Project Manager
- Answers Developers' domain questions through agreed channels

### Decision / Accountability Boundaries
Provides domain input and makes decisions only when explicitly delegated; product prioritization remains with the Product Manager and delivery coordination with the Project Manager.

---

## Cross-Role Collaboration and Accountability

For example, a stakeholder explains a business need to the Product Manager and Business Analyst; they clarify and document it for the Developers, while the QA/Test Engineer helps make acceptance criteria verifiable. The Technical Lead advises on feasibility and risks, and the Project Manager tracks dependencies and coordinates reviews. The sponsor resolves escalated business or resource decisions. Before release, Operations/Release and Security/Privacy specialists advise on readiness and risks. The team should record who owns each decision and escalation so recommendations, approvals, and delivery coordination are not confused.

Not every project needs a separate person for every role. Assign roles according to project size, risk, and expertise available, and explicitly document any combined responsibilities or decision-making authority.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
