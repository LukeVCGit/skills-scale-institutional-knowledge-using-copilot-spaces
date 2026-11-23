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

### Interactions with Other Roles
- Work with Product Managers to clarify outcomes and acceptance criteria.
- Work with Project Managers to communicate estimates, dependencies, and delivery risks.
- Collaborate with UX/Design, QA/Testing, Security/Compliance, DevOps/Release, and Data/Analytics roles on implementation, validation, operability, and measurement.

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
- Work with Business Analysts to refine needs and acceptance criteria.
- Partner with UX/Design and Customer Support to understand customer needs.
- Align scope and sequencing with Project Managers and Delivery Facilitators.
- Use Data/Analytics guidance to define and review success metrics.

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
- Coordinate scope, schedule, and delivery risks with Product Managers and Developers.
- Work with the Delivery Facilitator on team flow and impediment escalation.
- Include Business Analysts, UX/Design, QA/Testing, DevOps/Release, Security/Compliance, Customer Support, and Data/Analytics in relevant decisions and readiness reviews.

---

## Business Analysts

### Role Summary
Business Analysts translate stakeholder needs into clear, testable requirements and help maintain traceability from business goals to delivered outcomes.

### Responsibilities
- Gather and clarify business requirements
- Define or refine acceptance criteria
- Map processes, dependencies, and edge cases
- Validate that proposed solutions meet stakeholder needs
- Support requirements traceability and backlog refinement

### Goals
- Reduce ambiguity in requirements
- Ensure stakeholders agree on scope and expected outcomes
- Improve testability and delivery alignment

### Typical Communication
- Discovery and requirement workshops
- Backlog refinement and acceptance-criteria reviews
- Stakeholder walkthroughs and decision logs

### Interactions with Other Roles
- Partner with Product Managers to translate outcomes and priorities into actionable requirements.
- Collaborate with Developers and QA/Testing on feasibility, implementation detail, and test coverage.
- Work with stakeholders to resolve questions and confirm acceptance expectations.
- Coordinate with UX/Design when requirements include user workflows or usability constraints.

---

## UX/Design Lead

### Role Summary
The UX/Design Lead advocates for customer usability and represents design research and interaction decisions throughout delivery.

### Responsibilities
- Conduct or support user research
- Create and review interaction designs and prototypes
- Establish usability and accessibility requirements
- Validate design decisions with users and stakeholders
- Collaborate on design acceptance criteria

### Goals
- Improve usability and accessibility
- Reduce rework through early design validation
- Maintain a consistent customer experience

### Typical Communication
- Design reviews and research readouts
- Prototyping and usability-test sessions
- Backlog and acceptance-criteria refinement

### Interactions with Other Roles
- Partner with Product Managers on customer outcomes and feature priorities.
- Work with Business Analysts to shape workflows and requirements.
- Collaborate with Developers on feasible implementation and design constraints.
- Coordinate with QA/Testing on usability and accessibility acceptance.
- Present findings to stakeholders and incorporate their feedback.

---

## Scrum Master / Delivery Facilitator

### Role Summary
The Scrum Master or Delivery Facilitator helps delivery teams improve flow, run effective ceremonies, and identify and remove impediments.

### Responsibilities
- Facilitate agreed ceremonies and planning sessions
- Coach teams on effective delivery practices
- Identify, remove, or escalate team impediments
- Promote psychological safety and continuous improvement
- Help the team maintain a sustainable and predictable cadence

### Goals
- Improve delivery flow and team collaboration
- Reduce avoidable blockers and meeting overhead
- Build consistent, repeatable team practices

### Typical Communication
- Daily standups, planning, reviews, and retrospectives
- Team impedance and dependency discussions
- Action tracking and improvement follow-up

### Interactions with Other Roles
- Work with Project Managers on planning, status, risks, and delivery dependencies.
- Partner with Product Managers and Developers to keep priorities and capacity visible.
- Support QA/Testing and other delivery roles in resolving process bottlenecks.
- Escalate cross-team or organizational impediments through the established project-management escalation path.

---

## Release and DevOps Manager

### Role Summary
The Release and DevOps Manager owns release coordination and supports reliable, observable delivery through automation and operational readiness.

### Responsibilities
- Plan and coordinate release activities
- Maintain deployment and rollback readiness
- Automate or improve build and deployment pipelines
- Define release verification and observability checks
- Coordinate incidents and post-release follow-up

### Goals
- Improve release reliability and repeatability
- Reduce deployment risk and recovery time
- Ensure operational readiness before and after release

### Typical Communication
- Release readiness reviews and deployment plans
- CI/CD pipeline and observability reports
- Deployment, rollback, and incident coordination

### Interactions with Other Roles
- Work with Developers on deployable components and operational requirements.
- Coordinate release gates with QA/Testing and Project Managers.
- Partner with Security/Compliance on release controls and evidence.
- Work with Customer Support on release communications and known issues.
- Share production signals with Data/Analytics and relevant stakeholders.

---

## Security and Compliance Lead

### Role Summary
The Security and Compliance Lead identifies applicable security and compliance requirements and helps ensure controls are considered throughout delivery.

### Responsibilities
- Identify security and compliance requirements
- Review designs, threats, and implementation risks
- Coordinate security testing and evidence collection
- Advise on mitigations and approval decisions
- Support incident response and audit needs

### Goals
- Reduce security and compliance risk
- Build control requirements into delivery rather than deferring them
- Improve the quality of approval and audit evidence

### Typical Communication
- Security and compliance reviews
- Risk and control tracking
- Release-readiness and incident coordination

### Interactions with Other Roles
- Advise Product Managers and Business Analysts on applicable constraints and trade-offs.
- Collaborate with Developers on secure design and remediation.
- Work with QA/Testing on security test coverage and control validation.
- Coordinate with Release/DevOps Managers on release evidence and rollback controls.
- Report material risks and approvals to Project Managers and stakeholders.

---

## Customer Support Lead

### Role Summary
The Customer Support Lead represents customer-facing operations, supportability needs, and recurring customer feedback throughout the project lifecycle.

### Responsibilities
- Capture support needs and frequent customer issues
- Validate support workflows and documentation
- Participate in release readiness and known-issue reviews
- Triage recurring defects and customer-impact trends
- Provide post-release customer and support feedback

### Goals
- Improve customer support readiness
- Reduce avoidable customer-impacting issues
- Create an effective feedback loop from production to delivery teams

### Typical Communication
- Support-readiness reviews
- Known-issue and release-communication updates
- Customer-impact and defect trend reviews

### Interactions with Other Roles
- Share customer feedback and support trends with Product Managers and stakeholders.
- Work with Developers and QA/Testing on defect reproduction, support scenarios, and fixes.
- Collaborate with UX/Design on usability and documentation concerns.
- Coordinate release communications and known issues with Release/DevOps Managers and Project Managers.

---

## Data and Analytics Lead

### Role Summary
The Data and Analytics Lead defines how project outcomes will be measured and ensures that instrumentation and reporting support evidence-based decisions.

### Responsibilities
- Define success metrics and measurement plans
- Specify instrumentation and data-quality requirements
- Review dashboards, experiment plans, and results
- Interpret outcomes and communicate findings
- Identify metric or telemetry gaps

### Goals
- Ensure outcomes are measurable and observable
- Improve the accuracy and usefulness of project reporting
- Support evidence-based decisions after release

### Typical Communication
- Metrics and measurement-plan reviews
- Dashboard and experiment analysis
- Outcome reports for delivery and stakeholder reviews

### Interactions with Other Roles
- Partner with Product Managers and stakeholders to define relevant success metrics.
- Work with Developers and Release/DevOps Managers on instrumentation and observability.
- Coordinate acceptance and validation of analytics with QA/Testing.
- Help Project Managers assess progress and material outcome trends.
- Bring customer or usage findings to UX/Design and Customer Support for further action.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Teams may combine personas when roles and responsibilities are shared; the Project Manager and Product Manager remain responsible for keeping ownership, approvals, and escalations clear.
