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

## Scrum Master

### Role Summary
The Scrum Master coaches the team on Agile practices, facilitates Scrum ceremonies, and removes impediments that slow delivery. They are a servant-leader, not a traditional manager.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove blockers and dependencies
- Shield the team from external distractions during a sprint
- Coach team members and stakeholders on Agile principles
- Track team velocity and support continuous improvement

### Goals
- Keep the team focused and unblocked
- Improve team health, predictability, and delivery cadence
- Foster a culture of transparency, inspection, and adaptation

### Typical Communication
- Daily standup facilitator
- Retrospective notes and action items
- Impediment log updates in the project board

### Works closely with
- **Project Manager** — aligns on schedule, risk, and stakeholder communication
- **Product Manager** — ensures backlog is ready and prioritized before each sprint
- **Developers** — removes blockers and facilitates self-organisation
- **Business Analyst** — confirms user stories meet the Definition of Ready before sprint intake

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and the delivery team. They elicit, document, and validate requirements to ensure the right solution is built.

### Responsibilities
- Elicit and document business requirements and user stories
- Facilitate requirements workshops with stakeholders
- Translate business needs into clear acceptance criteria
- Maintain the requirements traceability matrix
- Support UAT (User Acceptance Testing) with stakeholders

### Goals
- Ensure the team builds what stakeholders actually need
- Reduce rework caused by ambiguous or missing requirements
- Maintain a shared, up-to-date view of scope

### Typical Communication
- Requirements workshops and story-writing sessions
- User story cards and acceptance criteria updates in the backlog
- Change request documentation

### Works closely with
- **Product Manager** — aligns requirements to product vision and prioritisation decisions
- **Developers** — clarifies acceptance criteria and answers questions during implementation
- **UX Designer** — translates functional requirements into user-centred design briefs
- **QA / Testing** — ensures acceptance criteria are testable and complete
- **Stakeholders** — primary liaison for requirements gathering and sign-off

---

## UX Designer

### Role Summary
UX Designers create user interfaces and experiences that are intuitive, accessible, and aligned with user needs. They use research and rapid iteration to validate design decisions.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Create wireframes, prototypes, and high-fidelity mockups
- Define and maintain the design system and style guide
- Iterate designs based on user feedback and stakeholder review
- Ensure accessibility standards (WCAG) are met

### Goals
- Deliver experiences that are easy to use and delightful
- Reduce support and usability issues through proactive research
- Align design decisions with product goals and technical constraints

### Typical Communication
- Design reviews and critique sessions
- Prototype walkthroughs with stakeholders and Developers
- Design handoff notes in the project board or Figma/design tool

### Works closely with
- **Product Manager** — aligns designs with product strategy and feature prioritisation
- **Developers** — provides design specs and clarifies interactions during implementation
- **Business Analyst** — reviews requirements to inform user-centred design decisions
- **Customer Support Representative** — incorporates end-user pain points into design iterations

---

## Customer Support Representative

### Role Summary
Customer Support Representatives are the primary interface with end users. They handle questions, document pain points, and channel real-world feedback back to the delivery team.

### Responsibilities
- Respond to end-user enquiries and resolve issues within SLA
- Document and categorise recurring pain points and feature requests
- Escalate critical bugs or incidents to the development team
- Participate in UAT to validate that fixes address reported issues
- Maintain the customer-facing knowledge base

### Goals
- Resolve user issues quickly and with high satisfaction scores
- Ensure the voice of the customer is heard during planning and prioritisation
- Reduce recurring support volume through proactive product improvements

### Typical Communication
- Support ticket summaries shared in sprint reviews or team Slack channels
- Bug reports and feature requests added to the backlog
- Regular feedback digests sent to Product Manager

### Works closely with
- **Product Manager** — relays customer feedback to inform backlog prioritisation
- **Developers** — escalates bugs and validates fixes
- **UX Designer** — surfaces usability pain points that inform design improvements
- **Project Manager** — flags customer-impacting risks during delivery

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain the infrastructure, CI/CD pipelines, and tooling that enable teams to deliver software reliably and at pace. They bridge development and operations.

### Responsibilities
- Design, build, and maintain CI/CD pipelines (build, test, deploy)
- Manage cloud infrastructure and environment configuration
- Monitor system reliability, performance, and security posture
- Automate infrastructure provisioning (IaC)
- Lead incident response for platform and infrastructure issues
- Enforce security and compliance controls in the pipeline

### Goals
- Achieve fast, reliable, and repeatable deployments
- Maximise system availability and minimise mean time to recovery (MTTR)
- Reduce manual toil through automation

### Typical Communication
- Runbooks and incident post-mortems
- CI/CD pipeline status alerts and monitoring dashboards
- Infrastructure change requests and approval workflows

### Works closely with
- **Developers** — collaborates on build configurations, environment requirements, and deployment readiness
- **Project Manager** — communicates deployment schedules, environment availability, and release blockers
- **QA / Testing** — provides stable test environments and integrates test automation into the pipeline
- **Scrum Master** — surfaces infrastructure blockers during standups

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Use the [Roles & Responsibilities Checklist](./octoacme-roles-and-responsibilities-checklist.md) at project kickoff to assign ownership across all active roles.

