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

## QA/Testing Lead

### Role Summary
QA and Testing professionals ensure that delivered features meet quality standards, acceptance criteria, and user expectations. They collaborate with developers and product managers to define test strategies and validate releases.

### Responsibilities
- Define test plans and QA approach for features and releases
- Execute manual and automated testing per acceptance criteria
- Identify and document defects with clear reproduction steps
- Collaborate on Definition of Done and test coverage requirements
- Execute smoke tests before production deployment
- Participate in release planning and post-release verification

### Goals
- Deliver high-quality, tested features to production
- Minimize defects reaching customers
- Reduce time-to-quality through efficient test strategies

### Typical Communication
- Sprint planning and review meetings
- Defect reports in issue tracking system
- Test progress updates in daily standups
- Release verification sign-off

### Interaction with Existing Roles
- **With Developers:** Collaborates on test coverage, acceptance criteria validation, and defect triage
- **With Product Managers:** Defines test strategies aligned with product goals and user acceptance criteria
- **With Project Managers:** Reports quality metrics and test readiness against release timelines

---

## UX/Design Lead

### Role Summary
Designers translate user needs and business goals into intuitive, usable interfaces. They work closely with product managers and developers to ensure solutions are both valuable and delightful.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Collaborate on acceptance criteria to ensure usability
- Review implementation against design specifications
- Iterate based on user feedback and testing results

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support costs
- Advocate for user needs in trade-off discussions

### Typical Communication
- Design reviews and critique sessions
- Acceptance criteria collaboration
- Usability testing results and insights
- Design handoff documentation

### Interaction with Existing Roles
- **With Developers:** Provides design specifications and reviews implementation for fidelity and usability
- **With Product Managers:** Collaborates on feature definitions, user research, and success metrics
- **With Project Managers:** Communicates design milestones and dependencies that impact project timelines

---

## Security/Compliance Officer

### Role Summary
Security professionals ensure that projects meet security standards, compliance requirements, and data protection regulations. They provide guidance on secure design and validate implementations against security policies.

### Responsibilities
- Review security requirements and threat models
- Conduct security reviews during planning and development
- Ensure security scanning is configured in CI/CD
- Validate compliance with internal policies and regulations
- Lead security incident response when needed
- Advise on secure coding practices and dependency management

### Goals
- Prevent security breaches and data exposure
- Ensure compliance with regulatory requirements
- Build security into development practices from the start

### Typical Communication
- Security reviews and design sessions
- Incident escalation and response
- Security scanning results and remediation tracking
- Compliance audit and validation

### Interaction with Existing Roles
- **With Developers:** Advises on secure coding practices and reviews security-critical implementations
- **With Product Managers:** Defines security requirements and validates compliance with business goals
- **With Project Managers:** Escalates security risks and ensures compliance checkpoints are built into project plans

---

## Product Lead

### Role Summary
Product Leads provide strategic oversight and decision authority for product-level initiatives. They align product strategy with business objectives and resolve trade-offs between product managers, engineering, and stakeholders.

### Responsibilities
- Approve project charters and strategic initiatives
- Escalate and resolve product-level trade-offs
- Provide strategic context and business priorities
- Unblock cross-team dependencies
- Guide product managers on strategic alignment

### Goals
- Ensure product strategy remains aligned with business goals
- Reduce decision-making bottlenecks through clear authority
- Guide portfolio-level prioritization

### Typical Communication
- Weekly PM sync and escalation discussions
- Project charter and roadmap reviews
- Stakeholder briefings and decisions
- Executive status updates

### Interaction with Existing Roles
- **With Product Managers:** Provides strategic guidance and approves roadmap direction
- **With Project Managers:** Escalates blockers and resolves resource conflicts across projects
- **With Developers:** Communicates strategic priorities and validates that technical decisions align with product vision

---

## Sponsor

### Role Summary
Sponsors are senior stakeholders who have business authority and investment in project success. They provide resources, remove organizational barriers, and ensure accountability to business goals.

### Responsibilities
- Authorize project funding and resources
- Escalate and resolve organizational blockers
- Validate that project outcomes deliver on business objectives
- Communicate project importance to the organization
- Review and approve major milestones and releases

### Goals
- Ensure projects deliver measurable business value
- Remove organizational barriers to success
- Maintain executive visibility and accountability

### Typical Communication
- Project approval and charter sign-off
- Milestone reviews and status escalations
- Risk and decision escalations
- Release announcements and stakeholder updates

### Interaction with Existing Roles
- **With Project Managers:** Removes organizational barriers and approves resource allocation
- **With Product Managers:** Validates business alignment and approves strategic initiatives
- **With Product Leads:** Provides executive oversight and authority for portfolio decisions

---

## DevOps/On-Call Engineer

### Role Summary
DevOps and On-Call engineers enable reliable deployments, maintain production systems, and respond to incidents. They collaborate with developers on deployment automation, monitoring, and incident response.

### Responsibilities
- Design and maintain CI/CD pipelines
- Plan and execute deployments to production
- Monitor system health and performance
- Respond to production incidents and troubleshoot issues
- Automate infrastructure and operational tasks
- Document runbooks and incident playbooks

### Goals
- Enable fast, reliable deployments with minimal risk
- Maintain high system availability and performance
- Reduce mean-time-to-recovery (MTTR) for incidents

### Typical Communication
- Deployment coordination and execution
- Incident response and post-mortems
- Monitoring and alerting configuration
- Runbook and playbook documentation
- Release readiness reviews

### Interaction with Existing Roles
- **With Developers:** Collaborates on CI/CD configuration, deployment automation, and troubleshooting production issues
- **With Project Managers:** Coordinates deployment windows and validates production readiness for releases
- **With QA/Testing Lead:** Executes smoke tests and validates production environment post-deployment

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
