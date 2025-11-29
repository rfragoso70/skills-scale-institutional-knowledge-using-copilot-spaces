# OctoAcme Project Management Docs

Welcome! This repository centralizes our project management processes used at OctoAcme to deliver product features, manage risks, and continuously improve our delivery.

## Summary of Project Management Processes

OctoAcme practices an iterative, customer-first approach to project delivery. Our methodology emphasizes clear ownership, data-informed decisions, and psychological safety to encourage feedback and learning.

### Key Workflows

- **Initiation**: Define clear problem statements, goals, stakeholders, and success metrics. Create a Project One-pager and validate business need before proceeding.
- **Planning**: Break work into shippable increments, estimate scope using T-shirt sizing or story points, and map out milestones with clear dependencies.
- **Execution & Tracking**: Use project boards (e.g., GitHub Projects), code reviews, and regular syncs to track progress. Follow small PR practices (≤400 lines) with CI validation.
- **Risk Management**: Maintain a risk register with impact, likelihood, owner, and mitigation plans. Review risks at weekly syncs.
- **Release & Deployment**: Follow standardized checklists for safe, reliable delivery to users. Include pre-release requirements, smoke tests, and rollback plans.
- **Retrospectives**: Reflect on each cycle to capture learnings and convert them into actionable improvements with clear owners and due dates.

### Personas & Roles

Our cross-functional teams include the following core roles:

| Role | Primary Responsibilities |
|------|-------------------------|
| **Project Manager (PM)** | Coordinates delivery, schedules, risk, and communications |
| **Product Manager (PdM)** | Defines outcomes, prioritizes backlog, and measures success |
| **Developers** | Implement features, collaborate on design, and maintain test coverage |
| **QA Lead** | Owns quality strategy, coordinates testing, and drives bug triage |
| **Release Manager** | Coordinates releases, ensures checklists are followed, communicates status |
| **UX Designer** | Translates needs into usable interfaces, champions user research |
| **DevOps Engineer** | Designs CI/CD pipelines, automates deployments, monitors infrastructure |
| **Security Champion** | Advocates secure practices, threat modeling, and security reviews |
| **Project Sponsor** | Provides executive sponsorship, removes blockers, champions vision |
| **Customer Success Manager** | Advocates for users, captures feedback, drives post-release success |
| **Stakeholders** | Provide inputs and approvals |

### Communication Strategies

- **Weekly sync** between PM and PdM for alignment
- **Twice-weekly standups** for the delivery team (or as agreed)
- **Monthly stakeholder updates** for broader visibility
- **Ad-hoc escalations** as needed, following defined escalation paths (Team → PM → Product Lead → Sponsor)

### Quality Assurance Practices

- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed
- Definition of Done (DoD) documented for each project

## Docs Index

Navigate to specific process documentation using the links below:

| Document | Description |
|----------|-------------|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to OctoAcme's project approach, principles, and artifacts |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate, authorize, and kick off new projects |
| [Project Planning](octoacme-project-planning.md) | Turn approved initiatives into actionable plans and backlogs |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day execution guidance, PR workflows, and progress tracking |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | Identify, manage, and communicate risks and dependencies |
| [Release & Deployment](octoacme-release-and-deployment.md) | Standardized release process and deployment checklists |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | Capture learnings and drive actionable improvements |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed role definitions for all team roles including Developers, Product Managers, Project Managers, Release Managers, QA Leads, UX Designers, DevOps Engineers, Security Champions, Project Sponsors, and Customer Success Managers |

## Contributing

All team members are encouraged to use, contribute to, and help improve these documents for stronger, more repeatable outcomes. Keep the Project Charter updated in the project repo and add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
