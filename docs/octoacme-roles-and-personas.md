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

## Additional Personas

### Technical Lead

#### Role Summary
Technical Leads architect technical approaches, guide implementation strategy, and mentor engineers. They own technical debt prioritization and ensure solutions are scalable, maintainable, and aligned with long-term product direction.

#### Responsibilities
- Design technical architecture and implementation strategies
- Make informed tradeoffs between speed, scalability, and maintainability
- Mentor and support developers in solving complex technical problems
- Identify and prioritize technical debt
- Escalate cross-team technical dependencies and integration challenges
- Conduct design reviews and provide technical guidance

#### Goals
- Enable fast, confident feature delivery with high quality
- Reduce technical risk and improve system resilience
- Foster a culture of technical excellence and continuous learning

#### Typical Communication
- Technical design documents and architecture reviews
- Code review guidance and mentoring feedback
- Weekly sync with Product Manager and Project Manager on technical risks
- Sprint planning participation for estimation and feasibility assessment

#### Key Interactions
- **With Developers**: Provides architectural guidance, mentorship, and design review
- **With Product Managers**: Translates requirements into technical designs; communicates feasibility and tradeoffs
- **With Project Managers**: Flags technical dependencies and risks; assists in timeline estimation
- **When to Engage**: Planning phase (architecture), pre-release (technical readiness), incident response (post-mortems)

---

### UX Researcher & Designer

#### Role Summary
UX Researchers and Designers drive user-centered design through research, prototyping, and usability validation. They define user flows, acceptance criteria for usability, and provide design assets and accessibility guidance to ensure products are intuitive and accessible.

#### Responsibilities
- Conduct user research and synthesize insights
- Define user flows and interaction patterns
- Create design mockups, prototypes, and specifications
- Ensure accessibility compliance and inclusive design
- Define usability acceptance criteria
- Validate design solutions through user testing and feedback

#### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce usability issues and support burden through research-backed design
- Improve user adoption and satisfaction metrics

#### Typical Communication
- Design specifications and user flow documents
- Usability test reports and user feedback summaries
- Sprint planning participation for design acceptance criteria
- Collaboration in demo/review sessions for design feedback

#### Key Interactions
- **With Product Managers**: Validates solutions through research; collaborates on user stories and acceptance criteria
- **With Developers**: Provides design assets and interaction specifications; participates in sprint planning
- **With QA/Testers**: Defines usability test plans and acceptance criteria
- **When to Engage**: Planning phase (user research), design phase (mockups), pre-release (usability testing)

---

### Release & Build Engineer

#### Role Summary
Release and Build Engineers maintain CI/CD pipelines, own release packaging, and coordinate deployments. They ensure smooth, reliable releases and own the rollback plan and pre-release smoke testing strategy.

#### Responsibilities
- Maintain and improve CI/CD pipelines and automation
- Own release packaging and versioning strategy
- Coordinate and execute deployments to staging and production
- Run pre-release smoke tests and validate deployment readiness
- Document and execute rollback procedures
- Monitor deployment health and troubleshoot release issues
- Collaborate on post-release verification and monitoring

#### Goals
- Enable fast, reliable, low-risk deployments
- Reduce deployment errors and time-to-recovery for incidents
- Improve team confidence in release processes

#### Typical Communication
- Release checklists and deployment runbooks
- CI/CD pipeline status and improvement proposals
- Pre-release readiness reports and smoke test results
- Post-deployment health dashboards

#### Key Interactions
- **With Developers**: Validates code is release-ready; advises on CI/CD best practices
- **With QA/Testers**: Coordinates smoke tests and pre-release verification
- **With Project Manager & Product Manager**: Informs release timing and deployment windows; communicates deployment status
- **When to Engage**: Pre-release (smoke tests, rollback planning), release day (deployment execution), post-release (health monitoring)

---

### Data Analyst & Measurement Owner

#### Role Summary
Data Analysts and Measurement Owners define success metrics, instrument events, and verify data quality. They produce reports and dashboards for post-release analysis and support data-driven decision-making throughout the project lifecycle.

#### Responsibilities
- Define success metrics and KPIs aligned with project goals
- Design data instrumentation and event tracking
- Ensure data quality, accuracy, and completeness
- Build dashboards and reports for stakeholders
- Analyze post-release impact and provide insights
- Support retrospectives with quantitative data on outcomes
- Collaborate on metric interpretation and decision-making

#### Goals
- Enable clear measurement of project impact and ROI
- Support data-driven prioritization and iteration decisions
- Reduce guesswork and improve confidence in outcomes

#### Typical Communication
- Success metric definitions and data instrumentation plans
- Pre-release and post-release dashboards and reports
- Analysis of user behavior and feature adoption
- Recommendations for optimization based on data

#### Key Interactions
- **With Product Managers**: Defines KPIs and success criteria; provides insights on user behavior and feature impact
- **With Developers**: Advises on data instrumentation and event design; reviews implementation for accuracy
- **With Project Manager**: Supports milestone reporting with quantitative data
- **When to Engage**: Planning phase (metric definition), pre-release (instrumentation), post-release (analysis and reporting)

---

### Security Liaison

#### Role Summary
Security Liaisons run threat assessments, ensure security checks and remediation, and coordinate security scanning and fixes. They own security risk identification and mitigation to protect customer data and system integrity.

#### Responsibilities
- Conduct threat assessments and security reviews
- Ensure security scanning and vulnerability management
- Collaborate on security issue triage and prioritization
- Coordinate security fixes and patch management
- Provide security guidance on architecture and design decisions
- Communicate security risks and mitigations to stakeholders
- Support incident response for security issues

#### Goals
- Minimize security vulnerabilities and risk exposure
- Build security into the development process from the start
- Ensure compliance and maintain customer trust

#### Typical Communication
- Threat assessment reports and security review findings
- Vulnerability and remediation tracking
- Security risk summaries in status reports
- Pre-release security checklist and sign-off

#### Key Interactions
- **With Developers & Technical Lead**: Works on security fixes; provides secure coding guidance
- **With Project Manager & Product Manager**: Escalates security risks and timeline impacts
- **When to Engage**: Planning phase (threat assessment), development (code review), pre-release (security sign-off), incident response

---

### Delivery Lead (Execution Coordinator)

#### Role Summary
Delivery Leads focus on day-to-day execution coordination, unblocking teams, and monitoring sprint health. They work closely with the Project Manager to operationalize the plan and ensure consistent forward progress.

#### Responsibilities
- Coordinate day-to-day delivery tasks and standups
- Identify and unblock team blockers rapidly
- Monitor sprint health, velocity, and progress toward milestones
- Escalate risks and dependencies to stakeholders
- Ensure project board and tracking systems reflect current status
- Facilitate sprint ceremonies and retrospectives
- Track and report on delivery metrics and team capacity

#### Goals
- Keep teams unblocked and moving at sustainable velocity
- Detect and surface risks early
- Maintain transparency and accountability in execution

#### Typical Communication
- Daily standup facilitation and blocker resolution
- Sprint health reports and velocity tracking
- Risk and blocker escalations
- Project board updates and progress summaries

#### Key Interactions
- **With Project Manager & Product Manager**: Surfaces blockers and risks; operationalizes the plan day-to-day
- **With Development Team**: Facilitates standups; unblocks and removes obstacles
- **When to Engage**: Throughout execution phase; critical for sprint ceremonies and risk escalation

---

### Business Owner & Sponsor

#### Role Summary
Business Owners and Sponsors own business outcomes and drive prioritization and funding decisions. They are engaged for go/no-go decisions and provide strategic direction and stakeholder alignment.

#### Responsibilities
- Define business objectives and success outcomes
- Prioritize work based on business impact and ROI
- Provide funding and resource approvals
- Make go/no-go decisions at key gates
- Engage stakeholders and secure alignment
- Review milestone progress and outcomes
- Escalate strategic blockers and risks

#### Goals
- Maximize business value and ROI from project investments
- Ensure strategic alignment and stakeholder support
- Make informed decisions on project continuations and pivots

#### Typical Communication
- Milestone review briefings and decision presentations
- Business case and ROI analysis
- Stakeholder updates and alignment communications
- Go/no-go decision documentation

#### Key Interactions
- **With Product Manager & Project Manager**: Reviews progress; makes prioritization and funding decisions
- **When to Engage**: Initiation (go/no-go), major milestones (reviews and decisions), risks requiring executive attention

---

## How These Personas Are Used

- Use these persona definitions to frame scenarios and interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference personas in other process docs (planning, execution, release) to clarify responsibilities and handoffs.
- When onboarding to a project, identify which personas are active and ensure each has a named owner.
- Use persona interaction tables to clarify dependencies and communication flows across complex projects.

