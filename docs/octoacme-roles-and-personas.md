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

## QA Engineer

### Role Summary
QA Engineers ensure end-to-end quality across the product lifecycle. They design test strategies, execute validation, and collaborate closely with Developers, Product Managers, and other stakeholders to prevent defects and verify acceptance criteria.

### Responsibilities
- Design and maintain test plans, test cases, and test automation
- Execute manual and automated testing (unit, integration, end-to-end)
- Validate acceptance criteria and Definition of Done before release
- Identify, document, and track defects through resolution
- Collaborate with Developers on testability and bug triage
- Participate in sprint planning to ensure testing is accounted for
- Provide quality metrics and testing status reports

### Goals
- Prevent defects from reaching production
- Maintain high test coverage and reliability
- Reduce time to find and fix issues
- Enable fast, confident releases

### Typical Communication
- Daily standups to report testing progress and blockers
- Sprint planning to estimate testing effort and identify risks
- Bug triage meetings with Developers
- Test signoff and quality reports to Project Managers and Product Managers

---

## UX Designer

### Role Summary
UX Designers research user needs, create prototypes, and define user experiences that are intuitive and effective. They work closely with Product Managers on requirements and with Developers on implementation feasibility and handoff.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define interaction patterns and information architecture
- Collaborate with Product Managers on user stories and requirements
- Work with Developers to ensure design feasibility and quality handoff
- Maintain design systems and component libraries
- Validate implemented designs match specifications

### Goals
- Deliver intuitive, accessible user experiences
- Validate designs with real user feedback
- Maintain design consistency across the product
- Reduce implementation rework through clear specifications

### Typical Communication
- Weekly syncs with Product Managers on roadmap and priorities
- Design reviews with Developers before implementation begins
- Handoff sessions to walk through designs and answer questions
- Usability testing sessions and research findings presentations
- Design critique sessions with other designers

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain CI/CD pipelines, automate processes, and ensure reliable infrastructure. They support incident response, enable fast deployments, and collaborate with Developers on deployment strategies and infrastructure needs.

### Responsibilities
- Design, implement, and maintain CI/CD pipelines
- Automate build, test, and deployment processes
- Manage infrastructure provisioning and configuration
- Monitor system health, performance, and availability
- Respond to and coordinate incident resolution
- Implement security scanning and compliance checks in pipelines
- Collaborate with Developers on deployment strategies (blue-green, canary, etc.)
- Document runbooks and operational procedures

### Goals
- Enable fast, reliable, automated deployments
- Minimize downtime and mean time to recovery
- Improve developer productivity through automation
- Maintain secure, scalable infrastructure

### Typical Communication
- Sprint planning to identify automation and infrastructure needs
- Deployment coordination with Project Managers and Developers
- Incident response coordination and postmortems
- Infrastructure handoff documentation for new services
- Weekly operational status and capacity reviews

---

## Customer Success / Support

### Role Summary
Customer Success and Support teams are the frontline for user feedback, bug reports, and feature requests. They triage issues, communicate with users, and provide critical insights to Product Managers and Developers about real-world usage and pain points.

### Responsibilities
- Respond to customer inquiries and support tickets
- Triage and escalate bugs to the development team
- Gather and synthesize user feedback and feature requests
- Create and maintain user-facing documentation and FAQs
- Communicate product updates and release notes to customers
- Track customer satisfaction metrics and trends
- Collaborate with Product Managers on prioritization based on user impact

### Goals
- Maximize customer satisfaction and retention
- Reduce time to resolution for customer issues
- Provide actionable insights to improve the product
- Ensure customers are informed of changes and new features

### Typical Communication
- Daily triage of support tickets and bug reports
- Weekly feedback sessions with Product Managers
- Release readiness reviews to understand what's changing
- Customer-facing communications about updates and known issues
- Escalation paths for critical customer-impacting issues

---

## Security Lead

### Role Summary
Security Leads ensure that security is built into every phase of the project lifecycle. They conduct security reviews, assess threats, implement mitigations, and facilitate incident response when security issues are discovered.

### Responsibilities
- Conduct security reviews of designs, code, and infrastructure
- Identify threats and vulnerabilities through threat modeling
- Define security requirements and acceptance criteria
- Review and approve security-sensitive changes
- Implement and maintain security scanning tools in CI/CD
- Coordinate security incident response and remediation
- Provide security training and guidance to the team
- Maintain security documentation and compliance records

### Goals
- Prevent security vulnerabilities from reaching production
- Minimize security incident impact and recovery time
- Build security awareness across the team
- Maintain compliance with security standards and regulations

### Typical Communication
- Security reviews during design and planning phases
- Code review comments on security-sensitive changes
- Incident response coordination for security issues
- Regular security status updates to stakeholders
- Threat modeling sessions with Developers and Architects

---

## Role Interactions and Collaboration

### Planning & Initiation Phase
- **Product Manager + UX Designer**: Define user needs and create initial designs
- **Product Manager + Project Manager**: Establish timeline, scope, and resource needs
- **Project Manager + All Roles**: Identify team composition and stakeholder communication plan
- **Security Lead + Product Manager**: Review security requirements early in planning

### Design & Specification Phase
- **UX Designer + Product Manager**: Validate designs against user needs and business goals
- **UX Designer + Developer**: Review design feasibility and implementation approach
- **Security Lead + UX Designer**: Review designs for security considerations (auth, data handling)
- **QA Engineer + Product Manager**: Clarify acceptance criteria and testing approach

### Development & Iteration Phase
- **Developer + UX Designer**: Design handoff and clarification sessions
- **Developer + QA Engineer**: Testability discussions and bug triage
- **Developer + DevOps Engineer**: Infrastructure needs and deployment strategy
- **Developer + Security Lead**: Security code reviews and vulnerability remediation
- **QA Engineer + Developer**: Daily coordination on testing progress and defect status

### Pre-Release Phase
- **QA Engineer + Project Manager**: Test completion and quality signoff
- **DevOps Engineer + Developer**: Deployment readiness verification
- **DevOps Engineer + Security Lead**: Security scanning and compliance checks
- **Product Manager + Customer Success**: Release notes and customer communication preparation
- **Project Manager + All Roles**: Final go/no-go decision and rollback planning

### Release & Deployment Phase
- **DevOps Engineer + Project Manager**: Coordinate deployment window and execution
- **DevOps Engineer + Developer**: Monitor deployment and verify success
- **QA Engineer + DevOps Engineer**: Post-deployment smoke testing
- **Customer Success + Product Manager**: Communicate release to customers
- **All Roles**: Incident response standby during deployment window

### Post-Release Phase
- **Customer Success + Product Manager**: Monitor user feedback and satisfaction
- **Customer Success + Developer**: Triage and escalate production issues
- **DevOps Engineer + All**: Monitor system health and performance
- **Project Manager + All Roles**: Retrospective to capture learnings

### Ongoing Collaboration
- **Security Lead**: Continuous monitoring of security alerts and vulnerability reports
- **DevOps Engineer**: Ongoing infrastructure maintenance and optimization
- **QA Engineer**: Maintenance of test automation and quality metrics
- **Customer Success**: Continuous collection and analysis of user feedback
- **All Roles**: Regular participation in standups, planning, and retrospectives

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

