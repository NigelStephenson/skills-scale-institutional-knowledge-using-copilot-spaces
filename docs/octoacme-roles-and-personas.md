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

### Interaction Points with Other Roles
- **Product Managers**: Clarify requirements, discuss technical trade-offs, estimate effort
- **Project Managers**: Update on progress and blockers, identify dependencies
- **QA Lead**: Collaborate on test automation, triage bugs, discuss quality standards
- **UX Designer**: Review design specifications, provide technical feasibility input, implement UI components
- **Release Manager**: Communicate deployment requirements, verify CI/CD status

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

### Interaction Points with Other Roles
- **Developers**: Define requirements, review technical proposals, validate solutions
- **Project Managers**: Align on roadmap timing, prioritize work, manage stakeholder expectations
- **QA Lead**: Review acceptance criteria, validate quality approach
- **UX Designer**: Collaborate on feature definition, review user research, validate design solutions
- **Support/Customer Success**: Review customer feedback and feature requests, prioritize improvements
- **Release Manager**: Align on release timing and feature readiness

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

### Interaction Points with Other Roles
- **Developers**: Track progress and blockers, coordinate dependencies
- **Product Managers**: Synchronize on roadmap, manage scope and timeline expectations
- **QA Lead**: Monitor quality metrics, coordinate test environment needs
- **Release Manager**: Align on project milestones and release schedules, manage release-related risks
- **UX Designer**: Coordinate design timelines, ensure design resources are available

---

## Release Manager

### Role Summary
Release Managers coordinate and oversee the release process from planning through deployment. They ensure releases are executed smoothly, safely, and on schedule while managing risk and coordinating across teams.

### Responsibilities
- Own the release schedule and coordinate release windows
- Manage release readiness reviews and sign-offs
- Coordinate deployment activities across environments
- Ensure release notes and documentation are complete
- Facilitate go/no-go decisions for production releases
- Coordinate rollback procedures when needed
- Track release metrics and identify process improvements

### Goals
- Deliver reliable, low-risk releases on schedule
- Minimize deployment-related incidents and downtime
- Maintain clear communication across all stakeholders
- Continuously improve release processes and automation

### Typical Communication
- Release planning meetings with PM, Product, and Engineering
- Pre-release readiness reviews with stakeholders
- Deployment status updates and post-release reports
- Release retrospectives and process improvement discussions

### Interaction Points with Other Roles
- **Developers**: Coordinate code freeze timing, verify CI/CD pipeline status, gather deployment requirements
- **Product Managers**: Align on feature readiness and release timing, coordinate release communications
- **Project Managers**: Synchronize on project milestones and dependencies, manage release-related risks
- **QA Lead**: Ensure testing completion and sign-off before release
- **Support/Customer Success**: Coordinate release communications and prepare support team

---

## QA Lead

### Role Summary
QA Leads define and implement quality assurance strategies, ensuring software meets functional and non-functional requirements. They coordinate testing efforts and advocate for quality throughout the development lifecycle.

### Responsibilities
- Define test strategy and maintain test plans
- Coordinate testing activities across unit, integration, and end-to-end tests
- Review acceptance criteria and provide quality perspective in planning
- Manage test automation frameworks and tools
- Sign off on release readiness from quality perspective
- Track quality metrics and identify testing gaps
- Mentor team on testing best practices

### Goals
- Prevent defects from reaching production
- Maintain high test coverage and automation rates
- Reduce mean time to detect and resolve issues
- Foster a culture of quality ownership across the team

### Typical Communication
- Test plan reviews and quality gate discussions
- Daily sync on test execution status and blockers
- Quality metrics reporting in sprint reviews
- Bug triage meetings and severity assessments

### Interaction Points with Other Roles
- **Developers**: Review acceptance criteria, pair on test automation, conduct bug triage
- **Product Managers**: Validate feature requirements, provide quality perspective on prioritization
- **Project Managers**: Report on quality metrics and risks, coordinate test environment needs
- **Release Manager**: Provide release readiness assessment and quality sign-off
- **UX Designer**: Test user flows and validate design implementation

---

## UX Designer

### Role Summary
UX Designers create user-centered design solutions that balance user needs, business goals, and technical constraints. They research, prototype, and validate designs to ensure products are intuitive and effective.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Define user flows and interaction patterns
- Maintain design systems and UI consistency
- Collaborate with Product and Engineering on feasibility
- Validate implementations match design intent
- Advocate for accessibility and inclusive design

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support requests
- Ensure design consistency across the product
- Base design decisions on user research and data

### Typical Communication
- Design reviews and critique sessions
- User research findings and usability test results
- Design handoff meetings with Developers
- Collaboration sessions with Product on feature scoping

### Interaction Points with Other Roles
- **Developers**: Provide design specifications, review implementations, clarify design intent
- **Product Managers**: Collaborate on feature definition, validate solutions with users, inform roadmap with research
- **QA Lead**: Coordinate on user flow testing and visual regression testing
- **Support/Customer Success**: Gather user feedback, understand pain points, validate design solutions

---

## Support/Customer Success Representative

### Role Summary
Support/Customer Success Representatives serve as the voice of the customer, helping users succeed with the product while gathering feedback to inform improvements. They ensure customer satisfaction and retention.

### Responsibilities
- Respond to customer inquiries and troubleshoot issues
- Document common issues and maintain knowledge base
- Escalate bugs and feature requests to Product and Engineering
- Onboard new customers and ensure adoption
- Track customer health metrics and identify at-risk accounts
- Gather and communicate customer feedback and pain points
- Advocate for customer needs in product discussions

### Goals
- Maximize customer satisfaction and retention
- Reduce time to resolution for customer issues
- Identify and communicate product improvement opportunities
- Enable customer self-service through documentation

### Typical Communication
- Daily ticket triage and customer communications
- Weekly sync with Product on common issues and requests
- Customer success updates and health reports
- Feedback sessions sharing user insights with Engineering

### Interaction Points with Other Roles
- **Developers**: Escalate bugs with reproduction steps, validate fixes in staging
- **Product Managers**: Provide customer feedback and feature requests, validate priority
- **Release Manager**: Receive release communications, prepare for customer questions
- **UX Designer**: Share user pain points and usability issues
- **QA Lead**: Provide real-world test scenarios and edge cases

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

