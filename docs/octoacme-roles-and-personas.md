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
QA / Testing Leads define the quality strategy, test planning, and validation approach for the project. They work with product and engineering teams to confirm that features meet acceptance criteria and release readiness standards.

### Responsibilities
- Define the overall quality and test strategy for the project
- Review acceptance criteria and ensure they are testable
- Create and maintain automated and manual test plans
- Coordinate bug triage and issue prioritization with developers and PMs
- Validate release readiness and support regression testing for high-risk changes

### Goals
- Catch defects early and reduce production risk
- Improve release confidence and customer satisfaction
- Maintain a consistent quality bar across features and milestones

### Typical Communication
- Test planning and release readiness reviews
- Bug triage and regression check-ins
- Quality metrics and stakeholder summaries during sprint or release reviews

### How they interact with existing roles
- Work with Developers to validate implementation quality and prioritize defects
- Partner with Product Managers to confirm acceptance criteria and user impact
- Coordinate with Project Managers to align quality gates with delivery milestones
- Support DevOps / Release Engineers to verify deployment stability and smoke-test coverage

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters or Agile Coaches help the team work effectively, remove blockers, and improve delivery rhythm without taking ownership of product decisions. They support continuous improvement and healthy team collaboration.

### Responsibilities
- Facilitate Agile ceremonies such as standups, sprint planning, retrospectives, and reviews
- Help teams identify and resolve workflow bottlenecks and dependencies
- Coach teams on Agile practices, collaboration habits, and process improvement
- Track team health indicators and support sustainable delivery practices
- Partner with Project Managers to improve execution flow and decision-making

### Goals
- Improve team productivity and delivery consistency
- Strengthen collaboration, accountability, and continuous learning
- Reduce unnecessary friction in the delivery process

### Typical Communication
- Daily standups and sprint rituals
- Retrospective and process improvement discussions
- Team health and execution alignment conversations with PMs and leads

### How they interact with existing roles
- Support Developers by creating a smoother delivery flow and helping resolve process friction
- Partner with Project Managers to keep work moving and align execution with milestones
- Enable Product Managers to receive clear progress updates and flag blockers early
- Work closely with Technical Architects and DevOps leads to reduce coordination friction during delivery

---

## Technical Architect

### Role Summary
Technical Architects define the target system design, make strategic technical decisions, and help the team balance business needs with long-term maintainability and scalability.

### Responsibilities
- Define architecture principles and technical direction for the project
- Review and guide technical design decisions across components and integrations
- Identify major dependencies, architectural risks, and technical debt
- Support platform choices, scalability, and maintainability decisions
- Mentor developers and review design trade-offs before implementation is finalized

### Goals
- Build sustainable, scalable, and maintainable systems
- Reduce rework caused by poor design choices
- Improve alignment between product goals and engineering constraints

### Typical Communication
- Design reviews and technical decision discussions
- Architecture documentation and trade-off conversations
- Collaboration with PMs and Product Managers on feasibility and sequencing

### How they interact with existing roles
- Partner with Developers to guide implementation decisions and technical direction
- Work with Product Managers to understand business priorities and feasibility trade-offs
- Coordinate with Project Managers on dependencies, milestones, and risk exposure
- Provide guidance to QA and Security teams on architecture-related risk areas and validation needs

---

## DevOps / Release Engineer

### Role Summary
DevOps / Release Engineers manage the deployment pipeline, infrastructure, and release readiness process so teams can deliver changes safely and consistently.

### Responsibilities
- Build and maintain CI/CD pipelines and deployment automation
- Manage environments, release configuration, and rollback readiness
- Document deployment procedures and operational safeguards
- Support release planning, post-deployment verification, and incident response coordination
- Monitor deployment health and improve observability for production services

### Goals
- Enable fast, safe, and repeatable releases
- Minimize deployment failures and downtime
- Improve reliability and operational readiness

### Typical Communication
- Release planning and deployment readiness reviews
- Post-deploy verification and incident communication
- Infrastructure and environment updates with engineering and PM stakeholders

### How they interact with existing roles
- Partner with Developers to ensure code is deployable and release-ready
- Coordinate with Project Managers on deployment windows, risk, and stakeholder communication
- Work with QA / Testing Leads to validate smoke tests and release readiness
- Support Security Leads on secure configuration and production controls

---

## Security Lead

### Role Summary
Security Leads ensure that projects meet security standards, identify risk early, and integrate secure-by-design practices throughout the product lifecycle.

### Responsibilities
- Review architecture, features, and dependencies for security risks
- Support threat modeling and secure design reviews
- Define security requirements and review acceptance criteria for risky changes
- Coordinate security testing and triage vulnerabilities with engineering teams
- Escalate compliance or security concerns to stakeholders and incident response owners as needed

### Goals
- Reduce security risk before and during production release
- Align projects with security and compliance expectations
- Promote secure decision-making across the team

### Typical Communication
- Security review meetings and design walk-throughs
- Risk escalation and incident communication
- Collaboration with engineering, PM, and release stakeholders on control requirements

### How they interact with existing roles
- Work with Developers to ensure secure implementation and remediation plans
- Partner with Product Managers to prioritize risk-aware delivery trade-offs
- Coordinate with QA / Testing Leads on penetration, security, and regression testing
- Align with DevOps / Release Engineers to ensure secure deployment and production safeguards

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together, these roles define a balanced operating model that clarifies accountability, coordination, and decision-making across delivery teams.

