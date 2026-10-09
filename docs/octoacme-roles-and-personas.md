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
QA/Testing Leads own the quality strategy and ensure that features meet acceptance criteria and quality standards before release. They collaborate with developers and product managers to define testable requirements and maintain quality gates throughout the project lifecycle.

### Responsibilities
- Define test strategy and acceptance criteria alignment
- Create and maintain test plans and test cases
- Automate quality checks in CI/CD pipelines
- Perform exploratory testing and user acceptance testing (UAT)
- Report quality metrics and defect trends
- Validate that Definition of Done includes quality criteria
- Coordinate with stakeholders on quality expectations

### Goals
- Catch defects early and prevent production issues
- Enable rapid, confident releases
- Maintain high quality standards consistently
- Build quality assurance into every iteration

### Interaction with Other Personas
- Developers: Works with Developers to understand implementation details, identify test coverage gaps, and validate test-driven development practices
- Product Managers: Collaborates on acceptance criteria refinement and success metrics to ensure quality aligns with business objectives
- Project Managers: Partners on quality gates and release readiness checklists
- Technical Lead/Architect: Aligns test strategy with architectural decisions and technical requirements
- Stakeholders/Sponsors: Provides quality status and risk reports to inform go/no-go decisions

### Typical Communication
- Sprint planning and retrospectives (quality feedback)
- Test status reports and defect reviews
- Release readiness checklists and quality scorecards
- Test automation and quality metrics dashboards

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate agile ceremonies, remove process blockers, coach the team on agile practices, and maintain team health and psychological safety. They serve as servant leaders focused on team enablement and continuous improvement.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Remove impediments and process blockers
- Coach team members on agile principles and practices
- Maintain sprint cadence and team velocity tracking
- Foster psychological safety and open communication
- Help resolve conflicts and support team dynamics
- Protect the team from interruptions and scope creep

### Goals
- Enable consistent, predictable team delivery
- Improve team collaboration and communication
- Support continuous learning and adaptation
- Maintain sustainable pace and prevent burnout

### Interaction with Other Personas
- Developers: Coaches on agile practices, facilitates ceremonies, and removes blockers impacting delivery
- Product Managers: Partners on sprint planning and backlog refinement to balance scope with team capacity
- Project Managers: Collaborates on timelines and milestone planning while protecting team focus
- All Personas: Facilitates effective communication and alignment across all roles

### Typical Communication
- Sprint ceremonies and team standups
- One-on-one coaching sessions
- Retrospective action items and team health surveys
- Velocity and burndown tracking

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architectural guidance, review technical designs, and ensure code quality and scalability. They mentor developers and help identify technical risks early, establishing coding standards and best practices that support sustainable, long-term product development.

### Responsibilities
- Review architectural designs and pull requests for technical soundness
- Establish coding standards and best practices
- Identify and mitigate technical risks and technical debt
- Guide technology choices and design trade-offs
- Mentor and coach developers on technical skills
- Lead design reviews and technical spike investigations
- Collaborate on infrastructure and scalability requirements

### Goals
- Ensure sustainable, scalable technical solutions
- Reduce technical debt and maintenance costs
- Build team capability and technical knowledge sharing
- Enable high-quality code delivery at scale

### Interaction with Other Personas
- Developers: Guides on technical implementation, architecture decisions, and code quality; mentors on best practices
- Product Managers: Partners on feasibility assessments and technical trade-offs impacting scope and timelines
- Project Managers: Identifies technical risks and dependencies for project planning and risk mitigation
- Operations/DevOps: Collaborates on deployability, scalability requirements, and infrastructure decisions
- Security/Compliance Officer: Works together on security architecture and technical compliance requirements

### Typical Communication
- Technical design reviews and architecture discussions
- Code review feedback and technical mentoring
- Technical risk register updates and architectural decision records (ADRs)
- Infrastructure and scalability planning sessions

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, strategic direction, and governance for projects. They approve scope and budget, communicate project importance to upper management, and make go/no-go decisions that align projects with organizational strategy and priorities.

### Responsibilities
- Provide business context and strategic alignment
- Approve project scope, budget, and resource allocation
- Make go/no-go decisions for major phases or changes
- Communicate project status to upper management
- Escalate and resolve business-level blockers
- Validate that project outcomes align with business objectives
- Provide feedback on deliverables and user value

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment with organizational strategy
- Make informed decisions based on clear trade-offs
- Manage stakeholder expectations and business risk

### Interaction with Other Personas
- Project Managers: Receives status updates and risk reports; provides strategic guidance and approvals
- Product Managers: Partners on business requirements, success metrics, and prioritization
- All Delivery Team Members: Provides business context and feedback on progress toward outcomes

### Typical Communication
- Monthly or milestone-based stakeholder updates
- Go/no-go decision meetings
- Business outcome validation and feedback sessions
- Executive status briefings

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers ensure that projects meet security requirements, regulatory standards, and organizational policies. They conduct security reviews, manage compliance risks, and coordinate security scanning to protect the organization and its customers.

### Responsibilities
- Define security requirements and compliance standards
- Conduct security architecture and code reviews
- Manage security scanning and vulnerability assessments
- Ensure GDPR, SOC 2, or other regulatory compliance
- Coordinate incident response and security incident handling
- Create and maintain security documentation and runbooks
- Provide security training and awareness for the team

### Goals
- Prevent security breaches and data loss
- Maintain regulatory compliance and reduce legal risk
- Build a security-conscious culture across teams
- Enable secure delivery without slowing innovation

### Interaction with Other Personas
- Developers: Reviews code for security vulnerabilities; provides security training and secure coding guidance
- Technical Lead/Architect: Collaborates on security architecture and threat modeling
- Project Managers: Identifies security risks and compliance gates for project planning
- Operations/DevOps: Partners on infrastructure security and secure deployment practices
- QA/Testing Lead: Coordinates security testing and vulnerability verification

### Typical Communication
- Security architecture reviews and threat assessments
- Security scanning reports and vulnerability management
- Compliance audit and regulatory update briefings
- Security incident response and post-mortem meetings

---

## Operations / DevOps

### Role Summary
Operations and DevOps teams manage infrastructure, deployment pipelines, monitoring, and incident response. They enable reliable, scalable, and secure production environments while providing the tooling and support necessary for rapid, confident feature delivery.

### Responsibilities
- Design and manage cloud infrastructure and deployment pipelines
- Automate testing, building, and deployment processes (CI/CD)
- Monitor application performance and infrastructure health
- Manage incident response and production support
- Coordinate rollbacks and disaster recovery
- Optimize cost and performance of infrastructure
- Provide observability tools and logging for troubleshooting

### Goals
- Enable rapid, reliable deployments
- Maintain high availability and system performance
- Reduce mean time to resolution (MTTR) for incidents
- Support infrastructure scalability and cost efficiency

### Interaction with Other Personas
- Developers: Provides deployment automation, infrastructure access, and production support; collaborates on observability requirements
- Technical Lead/Architect: Partners on infrastructure design, scalability, and reliability requirements
- Project Managers: Coordinates deployment windows and production readiness
- QA/Testing Lead: Works together on staging environments and pre-production validation
- Security/Compliance Officer: Collaborates on infrastructure security and compliance controls

### Typical Communication
- Deployment planning and release coordination
- Incident response and post-incident reviews
- Infrastructure and performance optimization discussions
- Monitoring and alerting strategy sessions

---

## UX / Design

### Role Summary
UX and Design professionals define user experience, create designs and prototypes, and validate usability. They ensure that features are intuitive, accessible, and aligned with user needs, while maintaining design consistency across the product.

### Responsibilities
- Conduct user research and gather user feedback
- Create wireframes, mockups, and prototypes
- Design user interfaces and interactions
- Ensure accessibility standards (WCAG) are met
- Validate usability through testing and user feedback
- Maintain design systems and component libraries
- Collaborate with developers on implementation details

### Goals
- Deliver intuitive, user-friendly features
- Ensure accessibility for all users
- Maintain design consistency and brand alignment
- Reduce user friction and support burden

### Interaction with Other Personas
- Product Managers: Partners on user needs assessment and feature prioritization
- Developers: Collaborates on design implementation, responsive design, and technical feasibility
- QA/Testing Lead: Works together on usability testing and accessibility validation
- Stakeholders/Sponsors: Presents design concepts and gathers feedback on user value
- Technical Lead/Architect: Aligns on technical feasibility and performance implications of designs

### Typical Communication
- Design reviews and feedback sessions
- Usability testing and user research findings
- Design system updates and component specifications
- Sprint planning for design-related tasks

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Cross-functional projects should reference these personas to clarify accountability and communication paths.
