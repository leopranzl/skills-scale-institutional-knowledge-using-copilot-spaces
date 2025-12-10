# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

## How to use this document

Consult these persona definitions when:
- Starting a new project to assign roles and responsibilities
- Onboarding new team members to clarify expectations
- Resolving confusion about handoffs or decision rights
- Creating project plans and RACI matrices

**How to assign roles:** Review the persona descriptions below and match them to team members based on project needs. A single person may hold multiple roles on smaller projects, while larger projects benefit from dedicated role owners. Use the [role-responsibility template](templates/role-responsibility-template.md) to document role assignments for your specific project.

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

## Stakeholder Engagement Lead

### Role Summary
Stakeholder Engagement Leads manage communications and expectations with external and internal stakeholders, ensuring their needs are surfaced and addressed throughout the project lifecycle.

### Responsibilities
- Identify and map all key stakeholders and their interests
- Facilitate stakeholder meetings and gather feedback
- Communicate project updates, risks, and decisions to stakeholders
- Ensure stakeholder requirements are represented in planning
- Manage escalations and maintain stakeholder satisfaction

### Interactions
- **With Project Managers:** Weekly alignment on status, risks, and stakeholder concerns; collaborate on communication plans
- **With Product Managers:** Monthly roadmap reviews; validate priorities against stakeholder needs
- **With Developers:** Relay technical questions or constraints from stakeholders; facilitate technical demos
- **Trigger points:** Project kickoff, milestone reviews, major decisions, issue escalations

### Example Deliverables
- Stakeholder map and engagement plan
- Meeting notes and action items from stakeholder sessions
- Stakeholder communication updates (newsletters, briefings)
- Feedback summary reports

### Impact on Project Outcomes
Effective stakeholder engagement increases buy-in, reduces surprises, and ensures project direction aligns with business needs, leading to smoother approvals and adoption.

---

## Change Manager

### Role Summary
Change Managers oversee the process of rolling out project changes, coordinate change impact assessments, communicate updates, and track adoption to ensure successful transitions.

### Responsibilities
- Develop change management strategy and adoption plans
- Conduct impact assessments for proposed changes
- Create and deliver training and communication materials
- Monitor adoption metrics and address resistance
- Coordinate with teams affected by changes

### Interactions
- **With Project Managers:** Daily during release phases; align on deployment schedules and readiness
- **With Product Managers:** Bi-weekly reviews of feature rollout plans and user impact
- **With Developers:** Coordinate on feature flags, rollback procedures, and technical documentation
- **With Onboarding Coordinators:** Share training materials and update onboarding content for new workflows
- **Trigger points:** New feature releases, process changes, tool migrations, organizational restructures

### Example Deliverables
- Change impact assessments
- Adoption and training plans
- Communication timelines and templates
- Post-implementation adoption reports

### Impact on Project Outcomes
Strong change management reduces disruption, accelerates adoption, and minimizes productivity loss during transitions, ensuring project benefits are realized.

---

## Risk Champion

### Role Summary
Risk Champions champion risk identification, escalation, and mitigation across the project team, fostering a healthy risk culture where concerns are raised early and addressed proactively.

### Responsibilities
- Facilitate risk identification workshops and reviews
- Maintain and update the risk register
- Ensure risks have clear owners and mitigation plans
- Escalate high-impact risks to leadership
- Promote risk awareness and encourage team members to surface concerns

### Interactions
- **With Project Managers:** Weekly risk review sessions; collaborate on mitigation strategies
- **With Developers:** Ad-hoc technical risk discussions; validate technical debt and architecture risks
- **With Stakeholder Engagement Leads:** Monthly stakeholder risk briefings; align on communication of major risks
- **Trigger points:** Project initiation, sprint planning, major technical decisions, external dependency changes

### Example Deliverables
- Risk register with impact/probability assessments
- Risk mitigation plans and status updates
- Risk trend reports and dashboards
- Lessons learned documentation on realized risks

### Impact on Project Outcomes
Proactive risk management reduces project failures, prevents costly surprises, and builds team confidence through transparent issue handling.

---

## Data Steward

### Role Summary
Data Stewards maintain data integrity, access protocols, and compliance for all project documentation and data assets, ensuring information is accurate, secure, and accessible to authorized users.

### Responsibilities
- Define and enforce data quality standards
- Manage access controls and permissions for project data
- Ensure compliance with data governance policies and regulations
- Maintain documentation repositories and versioning
- Conduct data audits and quality checks

### Interactions
- **With Project Managers:** Monthly reviews of documentation completeness and organization
- **With Developers:** As-needed support for data access, API documentation, and data model reviews
- **With Product Managers:** Quarterly alignment on data requirements and privacy considerations
- **Trigger points:** Project initiation, new data sources, compliance audits, access requests

### Example Deliverables
- Data governance guidelines
- Access control matrices
- Data quality reports
- Documentation standards and templates

### Impact on Project Outcomes
Effective data stewardship prevents data breaches, ensures regulatory compliance, improves decision-making quality, and reduces time wasted searching for or correcting information.

---

## Onboarding Coordinator

### Role Summary
Onboarding Coordinators design and run onboarding for new team members, streamline knowledge transfer, and update orientation materials to match current processes and documentation.

### Responsibilities
- Create and maintain onboarding checklists and materials
- Facilitate new team member orientation sessions
- Coordinate access provisioning and tool setup
- Gather feedback to improve onboarding experience
- Update onboarding content as processes evolve

### Interactions
- **With Project Managers:** At project start and when new members join; align on role assignments and timelines
- **With Developers:** First week of new developer joins; coordinate pair programming and code reviews
- **With Change Managers:** Quarterly updates to incorporate new processes or tools into onboarding
- **With Data Stewards:** Initial access setup; ensure new members understand data policies
- **Trigger points:** New team member starts, project team expansion, process documentation updates

### Example Deliverables
- [Onboarding checklists](templates/onboarding-checklist.md) tailored to roles
- Orientation schedules and meeting agendas
- Welcome guides and quick-start documentation
- Onboarding feedback summaries and improvement plans

### Impact on Project Outcomes
Well-executed onboarding reduces time-to-productivity, improves team cohesion, and ensures new members understand processes and expectations from day one.

---

## RACI Mapping Recommendations

**What is RACI?** RACI is a responsibility assignment matrix that clarifies roles for activities:
- **R**esponsible: Does the work
- **A**ccountable: Ultimately answerable for completion
- **C**onsulted: Provides input before decisions/actions
- **I**nformed: Kept updated on progress

**When to use RACI:** Create RACI matrices for complex projects, cross-functional activities, or when role confusion exists. Update RACI during planning and reference during execution to resolve ambiguity.

### Example RACI: Project Kickoff Meeting

| Activity | Project Manager | Product Manager | Developer | Stakeholder Engagement Lead | Change Manager | Risk Champion |
|----------|----------------|-----------------|-----------|----------------------------|----------------|---------------|
| Schedule kickoff meeting | R/A | C | I | C | I | I |
| Define project goals and scope | C | R/A | C | C | I | I |
| Identify stakeholders | C | C | I | R/A | I | I |
| Present technical approach | C | C | R/A | I | I | C |
| Create initial risk register | C | C | C | I | I | R/A |
| Document decisions and next steps | R/A | C | I | C | I | I |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

