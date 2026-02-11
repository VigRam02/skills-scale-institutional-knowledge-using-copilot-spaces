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

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams, ensuring requirements are clearly defined, understood, and technically feasible. They serve as translators who capture business needs and transform them into actionable specifications for the development team.

### Responsibilities
- Gather, analyze, and document business requirements from stakeholders
- Create detailed user stories and acceptance criteria in collaboration with Product Managers
- Conduct requirements validation workshops with both business and technical teams
- Identify gaps, ambiguities, and risks in requirements before development begins
- Clarify technical implications of business requests and propose alternatives
- Participate in design reviews to ensure solutions meet business objectives
- Support UAT planning and facilitate testing with business stakeholders

### Goals
- Ensure shared understanding of requirements across all teams
- Reduce rework caused by incomplete or misunderstood requirements
- Enable faster, more accurate estimation and planning
- Bridge communication gaps between business and technology

### Typical Communication
- Requirements workshops and stakeholder interviews
- Written requirements specifications and user story documentation
- Collaboration with Product Managers on backlog refinement
- Design review sessions with Developers and Technical Leads
- UAT coordination and feedback synthesis

### Key Interactions
- **With Product Managers**: Refines and details product vision into implementable requirements
- **With Developers**: Clarifies acceptance criteria and answers technical feasibility questions
- **With Project Managers**: Provides requirements status and scope impact assessments
- **With QA Lead**: Collaborates on test case development and acceptance criteria validation

---

## QA Lead

### Role Summary
QA Leads own the quality assurance strategy and testing approach for projects. They establish quality standards, coordinate testing efforts across the team, and ensure products meet acceptance criteria and quality benchmarks before release.

### Responsibilities
- Define quality standards, test strategies, and testing approaches for projects
- Create and maintain test plans, test cases, and test coverage documentation
- Coordinate testing activities across manual testers, automation engineers, and developers
- Establish defect triage processes and manage defect lifecycle
- Track quality metrics, test coverage, and defect trends
- Conduct design reviews from a quality and testability perspective
- Plan and facilitate test environment setup and management
- Communicate test status, risks, and blockers to Project Managers and stakeholders

### Goals
- Ensure products meet defined quality standards before release
- Identify and prevent defects early in the development cycle
- Reduce post-release defects and support burden
- Build confidence in product quality across stakeholders

### Typical Communication
- Test plan and strategy documentation
- Daily/weekly test status reports and metrics
- Defect triage meetings and root cause analysis sessions
- Design review participation for testability assessment
- Release readiness sign-offs and quality gates

### Key Interactions
- **With Developers**: Partners on unit testing and test-driven development practices
- **With Business Analyst**: Collaborates on test case development from acceptance criteria
- **With Project Manager**: Reports quality status and identifies testing risks
- **With Deployment Coordinator**: Ensures release readiness criteria are met before deployment

---

## Deployment Coordinator

### Role Summary
Deployment Coordinators manage the release process and ensure smooth deployment of software to production environments. They coordinate across teams, verify readiness, and orchestrate the deployment timeline while managing risk and communication throughout the release cycle.

### Responsibilities
- Plan deployment schedules and timelines in coordination with Project Managers
- Create and maintain deployment checklists and runbooks
- Verify deployment readiness criteria are met (code quality, testing complete, documentation ready)
- Coordinate pre-deployment activities across teams (Change Manager, QA Lead, Operations)
- Execute or oversee deployment activities and manage rollback procedures if needed
- Communicate deployment status and schedule to all stakeholders
- Document deployment activities, issues, and resolutions for knowledge sharing
- Work with Operations teams to monitor post-deployment stability

### Goals
- Execute deployments on schedule with minimal risk and disruption
- Ensure smooth handoff from development to production
- Reduce deployment incidents and rollbacks
- Maintain clear communication and visibility throughout releases

### Typical Communication
- Deployment plans and readiness checklists
- Release notes and deployment communications to stakeholders
- Coordination meetings with development, QA, operations, and support teams
- Post-deployment status updates and incident reports
- Release retrospectives and lessons learned documentation

### Key Interactions
- **With Project Manager**: Coordinates deployment schedule and communicates timeline
- **With Change Manager**: Collaborates on change control and stakeholder communication
- **With QA Lead**: Verifies quality gates and release readiness sign-offs
- **With Developers**: Obtains deployment artifacts and technical implementation details

---

## Support Liaison

### Role Summary
Support Liaisons serve as the bridge between development teams and customer support, ensuring production issues are properly understood, routed, and resolved. They facilitate feedback loops that improve product quality and capture lessons learned to prevent future issues.

### Responsibilities
- Serve as primary contact between support teams and development teams
- Triage and prioritize production issues and customer escalations
- Ensure production defects are logged and tracked through resolution
- Facilitate root cause analysis sessions for production incidents
- Capture and communicate customer feedback and usage patterns
- Identify patterns in support tickets that indicate product improvements or documentation gaps
- Support post-release monitoring and customer success activities
- Document lessons learned from production issues to prevent recurrence

### Goals
- Reduce time-to-resolution for production issues
- Improve customer satisfaction through rapid issue triage and communication
- Identify and address product quality issues and documentation gaps
- Build knowledge that improves future product development and design

### Typical Communication
- Production incident reports and escalation notifications
- Root cause analysis and incident review documentation
- Customer feedback summaries and usage analytics
- Post-incident reviews and lessons learned sessions
- Product improvement recommendations to Product Managers

### Key Interactions
- **With Project Manager**: Escalates critical production issues and provides impact assessment
- **With Developers**: Facilitates debugging and provides reproduction details for issues
- **With Business Analyst**: Shares customer feedback that impacts requirements and use cases
- **With QA Lead**: Collaborates on regression testing for hotfixes and root causes

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the Role Interaction Matrix document for visual representation of how these personas collaborate across the project lifecycle.