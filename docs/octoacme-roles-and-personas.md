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

## Release Manager

### Role Summary
Release Managers coordinate the release process, ensuring release checklists are followed and communicating release status to stakeholders. They manage release cycles from planning through deployment and post-release validation.

### Responsibilities
- Coordinate the end-to-end release process
- Ensure release checklists and quality gates are followed
- Communicate release status, timelines, and risks to stakeholders
- Manage release schedules and version numbering
- Coordinate rollback procedures when necessary

### Goals
- Deliver releases on schedule with minimal incidents
- Maintain clear visibility into release status across teams
- Reduce deployment risk through standardized processes

### Typical Communication
- Release planning meetings with PM, QA, and DevOps
- Release status updates to stakeholders
- Post-release announcements and documentation
- Coordination with support teams for release awareness

### Interactions with Other Roles
- Works closely with **Project Managers** to align release timing with project milestones
- Collaborates with **QA Lead** to ensure quality gates are met before release
- Partners with **DevOps Engineers** for deployment automation and monitoring
- Coordinates with **Product Managers** for release notes and feature communication

---

## QA Lead

### Role Summary
QA Leads own the overall quality strategy, coordinate test activities, ensure test coverage, and drive bug triage. They champion quality throughout the development lifecycle.

### Responsibilities
- Define and maintain the quality assurance strategy
- Coordinate test planning, execution, and reporting
- Drive bug triage and prioritization
- Ensure adequate test coverage across features
- Establish and maintain testing standards and best practices

### Goals
- Deliver high-quality products with minimal defects
- Reduce time to identify and resolve quality issues
- Build a culture of quality ownership across the team

### Typical Communication
- Test planning sessions with Developers and Product Managers
- Bug triage meetings with the development team
- Quality status reports to Project Managers
- Acceptance criteria reviews with Product Managers

### Interactions with Other Roles
- Collaborates with **Developers** to define acceptance criteria and test scope
- Works with **Product Managers** to validate features meet user expectations
- Partners with **Release Managers** to ensure quality gates before deployment
- Coordinates with **DevOps Engineers** on CI/CD test automation

---

## UX Designer

### Role Summary
UX Designers translate business needs into usable interfaces, championing user research, usability testing, and accessibility best practices. They ensure products are intuitive and meet user needs.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Collaborate on user experience and interaction design
- Champion accessibility standards and inclusive design
- Iterate on designs based on user feedback and data

### Goals
- Deliver intuitive, accessible user experiences
- Increase user satisfaction and reduce friction
- Ensure design consistency across products

### Typical Communication
- Design reviews with Product Managers and Developers
- User research findings presentations
- Design documentation and specification handoffs
- Usability testing sessions and feedback reports

### Interactions with Other Roles
- Works with **Product Managers** to understand user needs and business goals
- Collaborates with **Developers** on design implementation and feasibility
- Partners with **QA Lead** on usability testing and accessibility validation
- Coordinates with **Customer Success Managers** on user feedback insights

---

## DevOps Engineer

### Role Summary
DevOps Engineers design and maintain CI/CD pipelines, automation tools, and monitor infrastructure health. They enable reliable, efficient software delivery through automation and operational excellence.

### Responsibilities
- Design, build, and maintain CI/CD pipelines
- Automate deployment and infrastructure provisioning
- Monitor system health, performance, and reliability
- Manage infrastructure as code and configuration
- Support incident response and operational troubleshooting

### Goals
- Enable fast, reliable, and repeatable deployments
- Minimize downtime and improve system reliability
- Reduce manual operational overhead through automation

### Typical Communication
- Infrastructure and deployment discussions with Developers
- Incident response coordination with on-call teams
- Pipeline and automation updates to engineering teams
- Capacity planning with Project Managers

### Interactions with Other Roles
- Works with **Developers** on build pipelines and deployment automation
- Collaborates with **QA Lead** on test automation in CI/CD
- Partners with **Release Managers** for deployment execution and monitoring
- Coordinates with **Security Champions** on infrastructure security controls

---

## Security Champion

### Role Summary
Security Champions advocate for secure development practices, threat modeling, and security reviews. They guide teams on security requirements and integrate security into the development lifecycle.

### Responsibilities
- Advocate for secure coding practices within the team
- Conduct or facilitate threat modeling sessions
- Review code and architecture for security concerns
- Guide teams on security requirements and compliance
- Support security incident response and remediation

### Goals
- Embed security into the development lifecycle
- Reduce security vulnerabilities in shipped code
- Build security awareness and culture within teams

### Typical Communication
- Security review sessions with Developers
- Threat modeling workshops with the team
- Security findings and remediation guidance
- Incident response coordination with security teams

### Interactions with Other Roles
- Works with **Developers** to implement secure coding practices
- Collaborates with **DevOps Engineers** on infrastructure security
- Partners with **QA Lead** on security testing and validation
- Coordinates with **Project Managers** on security requirements and timelines

---

## Project Sponsor

### Role Summary
Project Sponsors provide executive sponsorship, remove escalated roadblocks, and champion the project vision. They ensure alignment with organizational strategy and provide resources and authority.

### Responsibilities
- Provide executive oversight and sponsorship
- Remove escalated blockers and make key decisions
- Champion the project vision and value
- Ensure alignment with organizational goals and priorities
- Approve major scope changes and resource allocations

### Goals
- Ensure project success and strategic alignment
- Remove barriers to team progress
- Maintain visibility into project health and outcomes

### Typical Communication
- Monthly executive briefings and status updates
- Escalation reviews and decision-making sessions
- Strategic alignment discussions with leadership
- Milestone reviews with Project Managers

### Interactions with Other Roles
- Works with **Project Managers** on project direction and escalations
- Collaborates with **Product Managers** to align on product vision and priorities
- Engages with **stakeholders** for organizational buy-in
- Provides guidance to **Release Managers** on release priorities

---

## Customer Success Manager

### Role Summary
Customer Success Managers advocate for end users, capture feedback, and translate insights into tangible improvements. They ensure customers achieve their goals and drive satisfaction post-release.

### Responsibilities
- Advocate for customer needs and success
- Capture and communicate customer feedback
- Coordinate post-release support and success activities
- Monitor customer satisfaction and adoption metrics
- Translate customer insights into product improvements

### Goals
- Maximize customer satisfaction and retention
- Ensure customers achieve desired outcomes
- Drive continuous improvement based on customer feedback

### Typical Communication
- Customer feedback reports to Product teams
- Success metrics reviews with stakeholders
- Post-release coordination with Support and Engineering
- Customer success stories and case study documentation

### Interactions with Other Roles
- Works with **Product Managers** to communicate customer needs and priorities
- Collaborates with **Support** teams on customer issue resolution
- Partners with **UX Designers** on customer experience insights
- Coordinates with **Release Managers** on customer-facing release communication

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

