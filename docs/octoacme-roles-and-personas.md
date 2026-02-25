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

## QA / Testing

### Role Summary
QA Engineers validate that features meet acceptance criteria, quality standards, and user expectations before release.

### Responsibilities
- Define and execute test plans and test cases
- Validate acceptance criteria for each feature or fix
- Report defects, verify fixes, and track quality metrics
- Run regression, integration, and smoke test suites
- Participate in sprint planning to identify testability concerns early

### Goals
- Ensure production releases are stable and reliable
- Reduce post-release defects and customer-reported issues
- Support a fast feedback loop between developers and quality validation

### Typical Communication
- Sprint planning and daily standups
- Defect reports and test result summaries
- Sign-off communication before release

---

## Release Manager

### Role Summary
Release Managers oversee release planning, scheduling, compliance, and communication with stakeholders. They coordinate across teams to ensure smooth, low-risk deployments.

### Responsibilities
- Plan and manage release schedules and deployment windows
- Coordinate with Developers and QA to confirm release readiness
- Ensure pre-release requirements (tests, security scans, rollback plans) are met
- Communicate release status and timelines to stakeholders and support teams
- Oversee post-release verification and handle go/no-go decisions

### Goals
- Minimize release risk and deployment failures
- Ensure smooth, predictable deployments with full stakeholder visibility
- Maintain a reliable release cadence aligned with project milestones

### Typical Communication
- Release readiness reviews with QA, Developers, and Project Manager
- Stakeholder notifications before and after deployments
- Incident communication and rollback coordination if needed

### Interaction Points
- Works closely with **Project Manager** on scheduling and milestone alignment
- Coordinates with **Developers** on deployment readiness and hotfix prioritization
- Partners with **QA** for sign-off before production releases
- Notifies **Customer Support Advocate** and stakeholders of upcoming releases

---

## UX Designer / Researcher

### Role Summary
UX Designers and Researchers design user experiences and conduct user research to ensure the product is usable, valuable, and aligned with customer needs.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Design wireframes, prototypes, and interface specifications
- Collaborate with Product Managers on acceptance criteria and feature definition
- Validate proposed solutions against real user needs and behaviors
- Provide design guidance throughout development and review

### Goals
- Ensure products are intuitive, accessible, and satisfying to use
- Reduce support burden and onboarding friction through good design
- Bridge customer needs and technical implementation

### Typical Communication
- Design reviews and prototype walkthroughs with Developers and Product Manager
- Research findings shared with Product Manager and stakeholders
- Feedback loops with QA to validate UI against design specifications

### Interaction Points
- Collaborates closely with **Product Manager** on problem framing and feature prioritization
- Works with **Developers** to ensure design feasibility and consistent implementation
- Partners with **QA** to verify UI acceptance criteria
- Surfaces user insights to inform **Customer Support Advocate** escalations

---

## Customer Support Advocate

### Role Summary
Customer Support Advocates bring end-user perspectives into the project, escalating support trends and pain points to help the team build products that meet real customer needs.

### Responsibilities
- Escalate recurring support trends and customer pain points to the product team
- Flag usability or reliability issues identified through support interactions
- Participate in sprint retrospectives to share customer impact insights
- Feed customer feedback into planning and backlog prioritization
- Help validate release communications and self-service documentation

### Goals
- Ensure the product meets real customer needs and reduces support volume
- Increase customer satisfaction through better product design and communication
- Provide the team with a direct channel to customer experience data

### Typical Communication
- Reports to **Product Manager** with aggregated support trends and escalations
- Participates in planning meetings and retrospectives
- Collaborates on release notes and customer-facing communications

### Interaction Points
- Reports insights to **Product Manager** for backlog prioritization
- Coordinates with **Release Manager** on customer communications for upcoming releases
- Collaborates with **UX Designer/Researcher** to validate design decisions against real usage patterns
- Engages with **Project Manager** during retrospectives to surface recurring issues

---

## Security Lead

### Role Summary
Security Leads advise on security best practices, manage threat readiness, and ensure the team follows secure development and incident response processes.

### Responsibilities
- Conduct threat modeling and security risk assessments
- Perform or coordinate security code reviews for sensitive changes
- Define and maintain the security incident response plan
- Provide compliance guidance and enforce security standards in CI/CD pipelines
- Advise on secure architecture and data handling practices

### Goals
- Minimize security vulnerabilities and exposure across the product
- Maintain customer trust through proactive security practices
- Support rapid and effective incident response when security issues arise

### Typical Communication
- Security review sessions with Developers during design and implementation
- Incident briefings and post-incident retrospectives with Project Manager and on-call teams
- Compliance updates to stakeholders when required

### Interaction Points
- Works directly with **Developers** on secure coding practices and code reviews
- Coordinates with **Project Manager** for security risk tracking and escalation
- Engages with on-call and incident response teams during security incidents
- Advises **Release Manager** on security requirements before deployments

---

## Data Analyst / Scientist

### Role Summary
Data Analysts and Scientists track usage metrics, generate insights, and support data-driven decision-making throughout the project lifecycle.

### Responsibilities
- Define, track, and report on project and product success metrics
- Generate dashboards, reports, and trend analyses for the team and stakeholders
- Identify patterns in usage, performance, and customer behavior data
- Support post-release analysis to measure feature impact
- Collaborate on experiment design and A/B test analysis

### Goals
- Provide data-driven insights that improve product and delivery decisions
- Measure and communicate the impact of project outcomes
- Enable the team to iterate with confidence based on evidence

### Typical Communication
- Regular metric reports and dashboards shared with Product Manager and Project Manager
- Post-release impact summaries following deployments
- Ad-hoc analysis in response to stakeholder or team requests

### Interaction Points
- Collaborates with **Product Manager** on success metric definition and roadmap validation
- Reports key signals to **Project Manager** for status updates and risk monitoring
- Shares post-release findings with **Release Manager** and stakeholders
- May surface data trends relevant to **Customer Support Advocate** escalations

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

