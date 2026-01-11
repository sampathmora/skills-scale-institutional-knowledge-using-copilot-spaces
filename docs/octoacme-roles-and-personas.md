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
Scrum Masters facilitate agile ceremonies, remove impediments, and coach teams on agile practices. They ensure the team follows agreed processes and continuously improves delivery flow.

### Responsibilities
- Facilitate sprint planning, daily standups, retrospectives, and demos
- Remove blockers and impediments that slow team progress
- Coach team members on agile principles and self-organization
- Shield the team from distractions and context-switching
- Track and communicate team velocity and capacity
- Foster psychological safety and continuous improvement culture

### Goals
- Maximize team throughput and minimize waste
- Reduce cycle time and improve predictability
- Build a self-organizing, high-performing team
- Create transparency in progress and impediments

### Typical Communication
- Facilitate daily standups and agile ceremonies
- Provide team metrics and velocity reports
- Escalate impediments to PM and stakeholders
- Coordinate with other Scrum Masters on dependencies

### Cross-functional Interactions
- **Project Managers**: Collaborate on timeline alignment, risk escalation, and cross-team dependencies
- **Developers**: Remove impediments, facilitate technical discussions, protect focus time
- **Product Managers**: Align on backlog priorities, clarify acceptance criteria, manage scope changes
- **UX Designers**: Coordinate design readiness and integrate feedback into sprint planning

---

## UX Designer

### Role Summary
UX Designers create user-centered designs that balance user needs, business goals, and technical feasibility. They conduct research, design interfaces, and validate solutions through testing.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and high-fidelity designs
- Define interaction patterns and visual design systems
- Collaborate with Product Managers on feature requirements
- Work with Developers to ensure design feasibility and implementation fidelity
- Validate designs through user feedback and analytics

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and increase engagement
- Maintain design consistency across product surfaces
- Balance user needs with business and technical constraints

### Typical Communication
- Design reviews and critique sessions
- User research findings and insights presentations
- Design specs and handoff documentation
- Usability test results and recommendations

### Cross-functional Interactions
- **Product Managers**: Collaborate on feature definition, user needs, and success metrics
- **Developers**: Provide design specs, review implementations, discuss technical constraints
- **Scrum Master**: Coordinate design readiness for sprint planning, communicate design blockers
- **QA/Testing**: Define acceptance criteria for UI/UX quality, participate in UAT

---

## Release Manager

### Role Summary
Release Managers coordinate and execute software releases across environments. They ensure releases are properly planned, tested, and deployed with minimal risk and clear communication.

### Responsibilities
- Coordinate release planning and scheduling across teams
- Manage release branches, versioning, and build pipelines
- Ensure pre-release requirements are met (tests, docs, approvals)
- Execute deployment procedures and post-deployment verification
- Maintain release notes and change documentation
- Coordinate rollback procedures when issues arise
- Track release metrics and identify process improvements

### Goals
- Deliver reliable, low-risk releases on schedule
- Minimize production incidents and deployment downtime
- Maintain clear visibility into release status and readiness
- Continuously improve release processes and automation

### Typical Communication
- Release readiness reviews with stakeholders
- Deployment notifications and status updates
- Post-release reports and metrics
- Incident coordination during deployment issues

### Cross-functional Interactions
- **Project Managers**: Align release schedules with project milestones and communicate risks
- **Developers**: Coordinate code freeze, review PRs for release readiness, manage hotfixes
- **QA/Testing**: Ensure testing completion, coordinate smoke tests and UAT signoff
- **Security Lead**: Verify security scans pass, coordinate security-related deployments
- **Product Managers**: Validate feature completeness, coordinate release communications

---

## Security Lead

### Role Summary
Security Leads ensure security is integrated throughout the development lifecycle. They identify vulnerabilities, define security requirements, and guide teams on secure coding practices.

### Responsibilities
- Conduct threat modeling and security reviews
- Define security requirements and acceptance criteria
- Review code and architecture for security vulnerabilities
- Manage security scanning tools and vulnerability remediation
- Respond to security incidents and coordinate fixes
- Provide security training and guidance to development teams
- Track and communicate security risks to stakeholders

### Goals
- Prevent security vulnerabilities in production
- Ensure compliance with security policies and standards
- Build security awareness across the organization
- Minimize mean-time-to-remediation for security issues

### Typical Communication
- Security review reports and threat models
- Vulnerability assessments and remediation plans
- Security incident response updates
- Security training sessions and guidelines

### Cross-functional Interactions
- **Developers**: Review code for security issues, provide secure coding guidance, pair on fixes
- **Project Managers**: Communicate security risks, negotiate security debt prioritization
- **Release Manager**: Review release security posture, approve/block deployments based on security
- **QA/Testing**: Define security test cases, coordinate penetration testing
- **Product Managers**: Advise on security implications of features, influence backlog prioritization

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Related Documentation
For more information on how these roles interact in practice, see:
- [Project Planning Guide](octoacme-project-planning.md) - Planning activities involving Scrum Master and UX Designer
- [Execution and Tracking Guide](octoacme-execution-and-tracking.md) - Day-to-day coordination with Scrum Master
- [Release and Deployment Guide](octoacme-release-and-deployment.md) - Release Manager coordination
- [Risk Management and Communication Guide](octoacme-risks-and-communication.md) - Security Lead escalation paths

*These role expansions address gaps identified in issue #4 regarding accountability, onboarding clarity, and role definitions.*

