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

## QA / Testing Lead

### Role Summary
QA/Testing Leads own the quality strategy, test planning, and acceptance validation for projects. They collaborate with developers and product managers to ensure features meet acceptance criteria and quality standards before release.

### Responsibilities
- Define testing strategy (unit, integration, E2E, security tests)
- Create and maintain test plans aligned with acceptance criteria
- Conduct manual QA testing for feature acceptance
- Coordinate security scanning and vulnerability assessment
- Monitor test coverage and quality metrics
- Identify and triage quality issues and regressions
- Support smoke testing and post-deployment verification

### Goals
- Ensure features meet acceptance criteria and quality standards
- Reduce defects reaching production
- Enable confident, risk-reduced releases

### Interactions with Other Roles
- **Developers**: Review test plans, provide testing feedback, collaborate on test automation
- **Product Managers**: Validate acceptance criteria interpretation, clarify feature requirements
- **Project Managers**: Report quality metrics, flag schedule impacts of testing
- **Operations/Release Manager**: Conduct pre-release smoke tests, verify deployment quality

### Typical Communication
- Sprint planning and daily standups
- Quality metrics in weekly status reports
- Test plan documentation and test case reviews
- Post-release quality assessments

---

## Stakeholders / Sponsors

### Role Summary
Stakeholders and Sponsors are business leaders and decision-makers who authorize work, provide resources, and define strategic direction. They approve project charters, confirm priority, and receive regular status updates.

### Responsibilities
- Approve project initiation and funding
- Confirm priority and strategic alignment
- Provide business context and success metrics
- Escalate organizational blockers
- Review progress and approve major milestones
- Communicate outcomes and business impact

### Goals
- Ensure projects deliver measurable business value
- Maintain strategic alignment across the organization
- Reduce risk through informed decision-making

### Interactions with Other Roles
- **Project Managers**: Receive status updates, provide milestone approvals
- **Product Managers**: Define business priorities, confirm success metrics
- **Product Lead**: Escalate cross-project conflicts, approve strategic decisions

### Typical Communication
- Project approval gates and reviews
- Monthly stakeholder updates and demos
- Ad-hoc escalation for risks and blockers
- Business impact summaries and ROI tracking

---

## Product Lead

### Role Summary
Product Leads provide strategic product oversight, mentor Product Managers, and ensure cross-project alignment. They own product vision and priorities at scale.

### Responsibilities
- Mentor and guide Product Managers
- Ensure cross-project alignment and roadmap coherence
- Escalate and make decisions on prioritization conflicts
- Review and approve project charters and success metrics
- Communicate product strategy to stakeholders
- Monitor portfolio health and resource allocation

### Goals
- Maximize portfolio impact and customer value
- Build and maintain aligned team and stakeholder vision
- Make timely strategic decisions

### Interactions with Other Roles
- **Product Managers**: Mentor on prioritization, guide on roadmap strategy
- **Project Managers**: Review timelines for strategic fit, escalate resource conflicts
- **Stakeholders/Sponsors**: Communicate strategic vision, align on portfolio priorities
- **Technical Lead**: Ensure technical feasibility of strategic initiatives

### Typical Communication
- Weekly sync with PM and PdM leads
- Project charter reviews and approvals
- Escalation meetings for cross-project priorities
- Strategic roadmap updates

---

## Technical Lead / Architect

### Role Summary
Technical Leads and Architects own technical design decisions, system integration, and technical risk mitigation. They provide technical guidance to developers and ensure solutions meet scalability, performance, and reliability standards.

### Responsibilities
- Lead technical design and architecture decisions
- Identify technical risks and propose mitigations
- Mentor developers on technical best practices
- Review design proposals and code architecture
- Coordinate technical integration points across teams
- Ensure scalability, performance, and security standards

### Goals
- Deliver technically sound, maintainable solutions
- Reduce technical debt and complexity
- Build systems that scale with business needs

### Interactions with Other Roles
- **Developers**: Provide technical guidance, review code and design decisions
- **Project Managers**: Identify technical risks and dependencies, flag timeline impacts
- **Product Lead**: Advise on technical feasibility of strategic initiatives
- **QA/Testing Lead**: Define testing strategy for complex components

### Typical Communication
- Technical design reviews and architecture discussions
- Code reviews and mentoring
- Technical risk identification in planning and execution
- System integration planning meetings

---

## Operations / Release Manager

### Role Summary
Operations and Release Managers coordinate deployments, manage infrastructure, and oversee production monitoring. They own the release process and ensure smooth, low-risk deployments.

### Responsibilities
- Coordinate release planning and deployment scheduling
- Manage deployment infrastructure and environments
- Oversee pre-release verification and smoke testing
- Monitor production health post-deployment
- Manage rollback procedures and incident response
- Track deployment metrics and system observability
- Communicate deployment status to stakeholders

### Goals
- Execute safe, reliable, auditable releases
- Minimize production incidents and downtime
- Enable rapid incident response and recovery

### Interactions with Other Roles
- **Project Managers**: Coordinate release windows, report deployment status
- **Developers**: Provide deployment guidance, troubleshoot production issues
- **QA/Testing Lead**: Execute smoke tests, verify release quality
- **Stakeholders/Sponsors**: Communicate deployment status and business impact

### Typical Communication
- Release planning meetings and deployment windows
- Status updates during deployments
- Post-incident retrospectives and reports
- Production monitoring dashboards and alerts

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
