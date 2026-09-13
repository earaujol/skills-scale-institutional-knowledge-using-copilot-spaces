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
- Work closely with **Technical Lead** for design guidance and architecture decisions
- Collaborate with **QA/Testing Lead** during sprint planning and acceptance criteria definition
- Report technical risks to **Project Manager** and **Technical Lead** for mitigation planning
- Receive requirements and priority guidance from **Product Manager** and **Stakeholder/Sponsor**

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
- Align with **Stakeholder/Sponsor** on strategy, budget, and business priorities
- Coordinate with **Project Manager** on delivery timelines and milestones
- Work with **Technical Lead** on feasibility and technical trade-offs
- Collaborate with **QA/Testing Lead** on acceptance criteria and quality metrics
- Guide **Developers** on feature specifications and success metrics

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
- Escalate blockers and risks identified by the **Technical Lead**, **QA/Testing Lead**, and **Developers**
- Report progress and risks to **Stakeholder/Sponsor**
- Coordinate schedules and dependencies with **Scrum Master/Delivery Coach**
- Align with **Product Manager** on scope and priorities
- Facilitate communication between **Security & Compliance Officer** and delivery team

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architectural oversight, design guidance, and technical risk assessment. They ensure solutions are scalable, maintainable, and aligned with long-term technical strategy.

### Responsibilities
- Review technical designs and propose architectural solutions
- Identify technical risks and propose mitigations
- Mentor developers and guide best practices
- Own integration points across multiple components
- Advise on technology choices and trade-offs
- Collaborate with **Security & Compliance Officer** on security architecture

### Goals
- Deliver technically sound, scalable solutions
- Reduce technical debt and maintenance burden
- Enable knowledge transfer and team capability growth

### Typical Communication
- Design review meetings and architecture discussions
- Code review comments and technical guidance
- Risk register updates (technical risks)
- Technical documentation and decision logs

### Interactions with Other Roles
- Guide **Developers** on architecture, design patterns, and best practices
- Support **Product Manager** and **Project Manager** with technical feasibility assessments
- Work with **QA/Testing Lead** to define testability and performance requirements
- Advise **Project Manager** on technical risks and mitigation strategies
- Consult with **Subject Matter Expert (SME)** on domain-specific technical challenges
- Collaborate with **Security & Compliance Officer** on security requirements and architecture

---

## QA/Testing Lead

### Role Summary
QA and Testing Leads own the quality strategy, test planning, and acceptance criteria validation. They ensure features meet quality standards before release.

### Responsibilities
- Define test strategy and acceptance criteria clarity
- Plan and execute manual and automated testing
- Identify defects and coordinate resolution
- Validate release readiness against quality gates
- Provide feedback on testability and design
- Track quality metrics and testing coverage

### Goals
- Deliver high-quality, defect-free features
- Reduce production incidents and user-impacting bugs
- Improve test coverage and automation

### Typical Communication
- Test planning sessions and kickoffs
- Defect reports and quality dashboards
- Acceptance sign-off before release
- Quality gate reviews with delivery team

### Interactions with Other Roles
- Collaborate with **Developers** on acceptance criteria definition and test case planning
- Work with **Technical Lead** on testability requirements and automation strategy
- Align with **Product Manager** on acceptance criteria and success metrics
- Report quality status to **Project Manager** for release readiness assessment
- Coordinate with **Stakeholder/Sponsor** on release approval and quality expectations
- Validate **Subject Matter Expert (SME)** business scenario requirements through testing

---

## Stakeholder / Sponsor

### Role Summary
Sponsors and key stakeholders represent business interests, approve budgets and scope, and make strategic decisions. They are the ultimate authority on priority and go/no-go decisions.

### Responsibilities
- Approve project charter and scope
- Allocate budget and resources
- Make escalated priority and trade-off decisions
- Provide executive visibility and reporting
- Validate business outcomes and success metrics
- Approve release and deployment decisions

### Goals
- Deliver business value and ROI
- Reduce risk of project misalignment or failure
- Ensure accountability to organizational strategy

### Typical Communication
- Project initiation and approval gates
- Monthly/quarterly executive updates
- Escalation of critical risks or trade-offs
- Post-release review and metrics reporting
- Release approval and go/no-go decisions

### Interactions with Other Roles
- Set strategic direction with **Product Manager** and review prioritization
- Approve project plans and timelines from **Project Manager**
- Review risk status from **Project Manager** for escalation decisions
- Make go/no-go decisions based on quality reports from **QA/Testing Lead**
- Approve security and compliance requirements from **Security & Compliance Officer**
- Review business outcomes and metrics with **Product Manager**

---

## Scrum Master / Delivery Coach

### Role Summary
Scrum Masters and Delivery Coaches facilitate team processes, remove blockers, and coach teams in iterative practices. They enable self-organization and continuous improvement within the team.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Identify and help remove blockers and impediments
- Coach the team on agile practices and ceremonies
- Track team velocity and iteration health
- Foster psychological safety and continuous improvement
- Escalate organizational blockers to **Project Manager**

### Goals
- Enable team self-organization and autonomy
- Reduce cycle time and improve predictability
- Build a high-performing, collaborative team culture

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective facilitation and action item tracking
- Blocker escalation and resolution coordination
- Team health and velocity metrics

### Interactions with Other Roles
- Support **Developers** by removing blockers and facilitating collaboration
- Coordinate with **Project Manager** to escalate organizational impediments
- Work with **Technical Lead** on technical debt and process improvements
- Collaborate with **QA/Testing Lead** to integrate testing into sprint cycles
- Coach all roles on agile practices and iterative delivery principles
- Report team health and velocity to **Project Manager**

---

## Security & Compliance Officer

### Role Summary
Security and Compliance Officers advise on security requirements, compliance gates, and risk mitigation. They ensure projects meet organizational security and regulatory standards.

### Responsibilities
- Define security requirements and compliance frameworks
- Review designs and implementations for security risks
- Establish security gates and compliance checkpoints
- Advise on incident response and security mitigations
- Track compliance metrics and audit readiness
- Collaborate with **Technical Lead** on security architecture

### Goals
- Protect organizational assets and customer data
- Ensure regulatory and compliance adherence
- Reduce security incidents and vulnerabilities
- Enable security by design in all projects

### Typical Communication
- Security architecture reviews and threat assessments
- Compliance checklist and gate reviews
- Incident response and mitigation guidance
- Security training and awareness communications

### Interactions with Other Roles
- Advise **Technical Lead** on security architecture and design patterns
- Collaborate with **Developers** on secure coding practices
- Provide compliance requirements to **Product Manager** for backlog prioritization
- Brief **Project Manager** on security risks and compliance gates
- Review **QA/Testing Lead** security test plans
- Escalate critical security issues to **Stakeholder/Sponsor** for approval

---

## Subject Matter Expert (SME)

### Role Summary
Subject Matter Experts bring deep domain knowledge and specialized expertise. They advise on business logic, technical complexities, and validate solutions align with domain requirements and best practices.

### Responsibilities
- Advise on domain-specific requirements and constraints
- Validate solution designs against domain best practices
- Provide specialized technical or business expertise
- Help clarify acceptance criteria and business scenarios
- Identify domain-specific risks and edge cases
- Support testing and validation of complex features

### Goals
- Ensure domain accuracy and regulatory compliance
- Reduce rework and misalignment with domain standards
- Accelerate learning and decision-making on specialized topics

### Typical Communication
- Design review consultations and advice
- Domain-specific requirement clarification
- Validation and testing support
- Subject matter expert guidance and mentoring

### Interactions with Other Roles
- Advise **Product Manager** on domain-specific features and prioritization
- Guide **Technical Lead** on domain constraints and technical trade-offs
- Support **Developers** with domain knowledge and implementation guidance
- Collaborate with **QA/Testing Lead** on domain-specific test scenarios
- Advise **Project Manager** on domain-specific risks and dependencies
- Work with **Stakeholder/Sponsor** on regulatory or domain compliance requirements

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The "Interactions with Other Roles" sections clarify how each role collaborates with others and where dependencies exist.
