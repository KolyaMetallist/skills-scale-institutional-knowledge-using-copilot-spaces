# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Delivery Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Cross-Functional & Operational Roles

### Technical Program Manager (TPM)

#### Role Summary
Technical Program Managers coordinate technical cross-team efforts, own schedules for multi-team milestones, and drive removal of engineering-level blockers. They bridge product delivery and technical execution across organizational boundaries.

#### Responsibilities
- Align technical dependencies across teams and engineering groups
- Track milestone-level risks, technical debt, and mitigation plans
- Facilitate technical design reviews and integration discussions
- Remove blockers at the engineering and architecture level
- Maintain roadmap visibility across multiple technical teams

#### Goals
- Accelerate multi-team delivery by reducing coordination overhead
- Ensure technical feasibility of product roadmaps
- Improve architectural alignment and reduce rework

#### Interactions
- Works with PM and Product Manager to translate roadmap milestones into coordinated engineering work
- Collaborates with Developers and Engineering Leads on technical design and dependencies
- Escalates architectural or cross-team blockers to Engineering Leadership and Product Lead
- Coordinates with Release Engineer on multi-team release coordination

#### Typical Communication
- Technical dependency mapping and cross-team planning
- Architecture review notes and design decisions
- Engineering leadership syncs and milestone tracking

---

### Release Engineer / DevOps

#### Role Summary
Release Engineers own release pipelines, deployment automation, and release readiness validation. They ensure reliable, repeatable deployments and rapid incident response.

#### Responsibilities
- Design, build, and maintain CI/CD pipelines and deployment automation
- Define and enforce release checklists (smoke tests, rollback procedures, security scans)
- Coordinate with on-call and infrastructure teams for production changes
- Implement observability and monitoring for release health
- Conduct runbook reviews and deployment rehearsals

#### Goals
- Enable safe, frequent releases with minimal manual effort
- Reduce mean time to recovery (MTTR) during incidents
- Maintain high deployment reliability and observability

#### Interactions
- Works with Developers to ensure code meets deployment readiness standards
- Collaborates with QA to define and validate smoke tests
- Works with PM to confirm release readiness and validate deployment windows
- Provides rollback and mitigation guidance to PM and on-call during incidents
- Coordinates with Security Engineer to ensure security scanning passes before production

#### Typical Communication
- Release checklists and deployment logs
- Incident runbooks and post-incident reviews
- CI/CD pipeline updates and infrastructure changes

---

### UX Researcher / Designer

#### Role Summary
UX Researchers and Designers ensure user research, design validation, and accessibility are incorporated into feature decisions. They advocate for usability and user-centered design throughout delivery.

#### Responsibilities
- Conduct lightweight research and usability testing for high-impact features
- Provide design artifacts, wireframes, and acceptance criteria related to usability
- Advocate for accessibility, inclusive design, and user-centered decisions
- Validate designs through user testing before handoff to development
- Document design patterns and component libraries for consistency

#### Goals
- Ensure delivered features meet user needs and usability standards
- Reduce design rework and user-facing bugs
- Build accessible, delightful products

#### Interactions
- Collaborates with Product Manager on defining success metrics and acceptance criteria
- Partners with Developers during implementation to clarify design intent
- Shares research findings and design recommendations with QA to inform test cases
- Works with Support Liaison to ensure design decisions support customer success
- Provides design feedback to Product Manager on roadmap prioritization

#### Typical Communication
- Design specifications and usability test reports
- Research findings and user insights
- Design review comments and accessibility audit results

---

### Security Engineer

#### Role Summary
Security Engineers provide security review, threat modeling, and approval for production changes. They embed security into the development lifecycle and incident response.

#### Responsibilities
- Conduct security reviews for new features, architecture changes, and dependencies
- Define required security tests, scans, and controls for releases
- Triage and prioritize security findings with engineering teams
- Participate in threat modeling for high-risk features
- Lead security incident response and post-incident reviews

#### Goals
- Prevent security incidents and data breaches
- Embed security into the development process rather than as an afterthought
- Maintain compliance with regulatory and organizational security policies

#### Interactions
- Works with Developers to review code and architecture for security vulnerabilities
- Collaborates with Release Engineer to ensure required security scans pass before production
- Advises PM and Product Manager on security risks and mitigation timelines
- Escalates critical security findings to leadership and incident response team
- Partners with Architects on security design decisions

#### Typical Communication
- Security review comments and threat models
- Vulnerability reports and remediation timelines
- Security incident summaries and post-incident action items

---

### Data Engineer / Analytics Owner

#### Role Summary
Data Engineers and Analytics Owners own data pipelines, instrumentation, and analytics requirements for product features. They ensure data quality and enable data-driven decisions.

#### Responsibilities
- Define events, metrics, and instrumentation required for success measurement
- Design and maintain data pipelines and ETL processes
- Ensure data quality, availability, and accessibility for dashboards and experiments
- Implement or coordinate instrumentation changes in products and services
- Support A/B testing and analytics for feature validation

#### Goals
- Enable real-time visibility into product and business metrics
- Provide reliable data infrastructure for decision-making
- Reduce time from hypothesis to validated learning

#### Interactions
- Collaborates with Product Manager to define success metrics and measure impact
- Works with Developers to implement event tracking and instrumentation
- Partners with Release Engineer on data pipeline deployments
- Provides dashboards and reports to PM for progress tracking and outcome measurement
- Supports UX Researcher with usage analytics and user behavior data

#### Typical Communication
- Metric definitions and instrumentation specifications
- Data pipeline documentation and SLAs
- Dashboard updates and analytics reports

---

### Support Liaison / Customer Success Representative

#### Role Summary
Support Liaisons represent customer and support perspectives to the delivery team. They validate runbook readiness, escalation paths, and ensure supportability before and after release.

#### Responsibilities
- Surface common customer issues, themes, and pain points to the team
- Validate support documentation, runbooks, and escalation paths pre-release
- Act as a primary contact for post-release customer impact and triage
- Identify support-related gaps in product features and documentation
- Collaborate on training and enablement for support teams

#### Goals
- Reduce support burden through better product design and documentation
- Improve customer satisfaction and issue resolution time
- Prevent customer-impacting incidents through early identification

#### Interactions
- Works with PM and QA to ensure new features are supportable
- Collaborates with Product Manager on feature design for support efficiency
- Partners with Release Engineer on runbook and escalation validation
- Escalates high-severity customer-impacting issues to PM and on-call
- Provides customer feedback to Product Manager for backlog prioritization
- Works with UX Researcher to validate documentation and help content

#### Typical Communication
- Support readiness checklists and runbook reviews
- Customer issue summaries and trend reports
- Post-release customer impact assessments

---

### Product Marketing Manager (PMM)

#### Role Summary
Product Marketing Managers coordinate launch messaging, positioning, and go-to-market readiness. They ensure customers and stakeholders understand the value of new features.

#### Responsibilities
- Prepare release announcements, feature positioning, and customer-facing documentation
- Coordinate launch timing and go-to-market strategy with stakeholders
- Collect and synthesize market feedback post-release
- Create training and enablement materials for customers and internal teams
- Monitor competitive positioning and market trends

#### Goals
- Maximize customer awareness and adoption of new features
- Ensure go-to-market alignment with product capabilities
- Build customer understanding of value and use cases

#### Interactions
- Works with Product Manager and PM to align messaging and release schedule
- Collaborates with Support Liaison to prepare customer-facing guides and FAQs
- Partners with UX Researcher on messaging around usability improvements
- Coordinates with Data Engineer on usage metrics and adoption tracking
- Provides market feedback to Product Manager for roadmap prioritization

#### Typical Communication
- Release announcements and customer-facing messaging
- Go-to-market plans and launch calendars
- Customer feedback summaries and adoption metrics

---

### Business Analyst (BA)

#### Role Summary
Business Analysts clarify requirements, document process flows and acceptance criteria, and ensure downstream reporting and compliance needs are captured. They bridge business and technical perspectives.

#### Responsibilities
- Translate stakeholder needs and business requirements into clear backlog items
- Document acceptance criteria, process flows, and data requirements
- Prepare diagrams and specifications for complex features and integrations
- Liaise with Finance, Legal, and Compliance teams for regulatory requirements
- Validate that implemented solutions meet business objectives

#### Goals
- Reduce ambiguity and rework from unclear requirements
- Ensure compliance with regulatory and governance requirements
- Enable clear acceptance and success measurement

#### Interactions
- Works closely with Product Manager and PM during planning and requirements gathering
- Collaborates with Developers to clarify technical requirements and edge cases
- Coordinates with Data Engineer on business metrics and reporting needs
- Partners with Security Engineer on compliance and data governance requirements
- Validates with stakeholders that delivered solutions meet business needs

#### Typical Communication
- Requirements documentation and process flow diagrams
- Acceptance criteria and success metrics
- Compliance and regulatory requirement summaries

---

## How to use these personas

### In Project Planning
- Identify which roles are needed for your project during the **Initiation** and **Planning** phases
- Assign explicit owners for each critical activity (release, security, data, support)
- Reference the "Interactions" section to understand handoff points and dependencies

### In Execution & Standup
- Use persona definitions to clarify who should be involved in decisions
- Reference "Typical Communication" to set appropriate touchpoints
- Escalate decisions to the right persona when blockers arise

### In Retrospectives
- Review whether the right personas were involved at key milestones
- Identify gaps (e.g., "We needed a Security Engineer but didn't have one")
- Adjust team composition for future projects based on learnings

### For Onboarding
- Share this document with new team members to explain roles and responsibilities
- Use each persona prompt to shape role-specific guidance in Copilot Spaces
- Reference interactions to help people understand their cross-functional dependencies
