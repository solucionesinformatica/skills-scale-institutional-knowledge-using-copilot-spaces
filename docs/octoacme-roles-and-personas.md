# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. Roles may be combined or shared on smaller teams, but ownership for each responsibility should remain clear.

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

## Delivery Facilitator (Scrum Master)

### Role Summary
The Delivery Facilitator supports the team’s working agreements and flow by facilitating delivery ceremonies and helping resolve impediments. This role complements, rather than replaces, the Project Manager’s accountability for plans, risks, and stakeholder coordination.

### Responsibilities
- Facilitate standups, iteration planning, reviews, and retrospectives as agreed by the team
- Help surface and coordinate removal of delivery impediments
- Make workflow bottlenecks and team capacity visible
- Encourage continuous improvement and follow through on agreed actions

### Goals
- Support a sustainable, predictable delivery flow
- Ensure blockers and improvement actions have clear owners
- Help the team spend meetings on decisions and coordination

### Typical Communication
- Team ceremonies and project-board updates
- Blocker and dependency discussions with the Project Manager
- Retrospective follow-up with the team

### Interactions with Existing Roles
- Partners with the Project Manager on delivery health, dependencies, and escalation; the Project Manager remains accountable for the project plan and status.
- Works with the Product Manager to ensure planned work is understood and ready, without taking over product prioritization.
- Helps Developers and QA/Testing raise impediments and coordinate collaboration.
- Shares relevant progress and risks with Stakeholders through the agreed communication path.

---

## UX/Design Lead

### Role Summary
The UX/Design Lead guides research-informed interaction and visual design so that solutions are usable, accessible, and consistent.

### Responsibilities
- Lead or coordinate user research, journey mapping, and interaction design
- Define design artifacts and accessibility expectations for planned work
- Maintain consistency with applicable design systems and patterns
- Validate designs with users and incorporate feedback

### Goals
- Make product experiences useful, understandable, and inclusive
- Reduce avoidable usability issues and rework
- Ensure design decisions support intended product outcomes

### Typical Communication
- Design reviews and research readouts
- Product discovery and backlog refinement
- Design specifications and implementation reviews with engineering

### Interactions with Existing Roles
- Partners with the Product Manager to connect user needs, product outcomes, and acceptance criteria.
- Works with Developers to assess feasibility, clarify designs, and review implementation trade-offs.
- Collaborates with QA/Testing on usability and accessibility checks that can be included in acceptance and test plans.
- Keeps the Project Manager informed of research, design dependencies, and decisions affecting milestones; shares validated findings with Stakeholders as appropriate.

---

## Security Lead

### Role Summary
The Security Lead provides security expertise throughout planning, implementation, and release, and coordinates security review and remediation with the appropriate teams.

### Responsibilities
- Identify security requirements, threats, and applicable controls
- Advise on secure design and implementation practices
- Coordinate security reviews, findings, and remediation priorities
- Follow the security incident process and notify the Security on-call when required

### Goals
- Reduce security risk while enabling delivery
- Make security ownership and remediation expectations explicit
- Ensure security considerations are included in release readiness

### Typical Communication
- Threat and design reviews with Developers
- Security findings and remediation tracking
- Risk and release-readiness updates with project leads

### Interactions with Existing Roles
- Advises the Product Manager on security implications and trade-offs so product decisions account for risk.
- Partners with Developers to review designs and agree on practical remediation.
- Coordinates with QA/Testing on security validation and evidence; automated scanning remains part of CI where configured.
- Works with the Project Manager to record risks, owners, mitigations, and escalations, and informs Stakeholders through approved incident or status channels.

---

## Data Analyst

### Role Summary
The Data Analyst helps teams define, interpret, and communicate evidence about product usage and project outcomes.

### Responsibilities
- Translate product goals into measurable indicators and instrumentation needs
- Analyze usage, quality, and delivery data and explain relevant limitations
- Build or maintain dashboards and provide regular outcome readouts
- Protect data quality and follow applicable privacy and access requirements

### Goals
- Enable evidence-informed prioritization and iteration
- Make success measures understandable and actionable
- Identify changes in outcomes early enough for the team to respond

### Typical Communication
- Metric definitions and analysis with Product Managers
- Dashboard and data-quality updates
- Findings shared at delivery reviews and stakeholder updates

### Interactions with Existing Roles
- Works with the Product Manager to define success metrics and interpret whether outcomes meet the intended goal.
- Collaborates with Developers on instrumentation and data quality, and with QA/Testing on validating event behavior and test data.
- Helps the Project Manager use agreed delivery and outcome signals in reports without substituting metrics for risk or dependency discussions.
- Presents relevant findings and caveats to Stakeholders in accessible language.

---

## Technical Writer

### Role Summary
The Technical Writer creates and maintains accurate user-facing and operational documentation that supports adoption, release, and ongoing use.

### Responsibilities
- Prepare user guides, release notes, onboarding materials, and relevant process documentation
- Gather and verify technical information with subject-matter experts
- Keep documentation aligned with product changes and release timing
- Apply clear, consistent language and accessible content practices

### Goals
- Help users and internal teams understand changes and complete tasks
- Reduce support burden caused by unclear or outdated instructions
- Make documentation a dependable part of delivery and release readiness

### Typical Communication
- Documentation reviews with Developers and Product Managers
- Release-note coordination with the Release Manager
- Content review and feedback from QA/Testing, Support, and Stakeholders

### Interactions with Existing Roles
- Partners with the Product Manager and UX/Design Lead on audience, terminology, and user needs.
- Works with Developers to verify implementation details and with QA/Testing to confirm that instructions match tested behavior.
- Coordinates publication timing and content needs with the Release Manager and Project Manager.
- Incorporates feedback from Support/Customer Representatives and Stakeholders, who help identify recurring questions and communication needs.

---

## Support/Customer Representative

### Role Summary
The Support/Customer Representative brings customer and operational feedback into project decisions and prepares support teams for changes.

### Responsibilities
- Summarize customer feedback, common questions, and operational pain points
- Route reproducible defects and emerging patterns to the responsible teams
- Identify support readiness needs, including FAQs and escalation guidance
- Provide post-release feedback on adoption and recurring issues

### Goals
- Ensure customer and support needs are considered throughout delivery
- Improve release readiness and the quality of customer communications
- Help teams detect and respond to customer-impacting issues

### Typical Communication
- Customer feedback summaries and support trends
- Readiness reviews with Product and Project Managers
- Release briefings and post-release issue reports

### Interactions with Existing Roles
- Shares customer evidence with the Product Manager to inform discovery, prioritization, and success measures.
- Works with Developers and QA/Testing to provide clear defect reports and validate customer-impacting fixes.
- Coordinates support readiness, rollout communication, and issue escalation with the Project Manager and Release Manager.
- Collaborates with the Technical Writer on FAQs and user guidance, and shares appropriate updates with Stakeholders.

---

## Release Manager

### Role Summary
The Release Manager coordinates release readiness, deployment communication, and the agreed release process across contributing teams. Technical deployment ownership may remain with engineering or operations teams.

### Responsibilities
- Coordinate release scope, schedule, readiness checks, and release communications
- Confirm that required acceptance, CI, security, and smoke-test evidence is available
- Track deployment dependencies and ensure rollback or mitigation plans are documented
- Coordinate post-deployment verification and capture release follow-up actions

### Goals
- Make releases predictable, observable, and well communicated
- Ensure teams understand readiness criteria and escalation paths
- Reduce avoidable release risk and confusion

### Typical Communication
- Release planning and readiness check-ins
- Deployment status and stakeholder announcements
- Post-deployment verification and follow-up

### Interactions with Existing Roles
- Works with the Project Manager on milestone timing, dependencies, and escalation, and with the Product Manager on release scope and customer-facing priorities.
- Coordinates with Developers on deployment readiness and rollback plans, and with QA/Testing on acceptance evidence and smoke tests.
- Consults the Security Lead on outstanding security findings and the Support/Customer Representative and Technical Writer on support materials and release notes.
- Provides Stakeholders with agreed release status and post-deployment outcomes.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- A person may hold more than one role on a small team; make ownership, decision authority, and handoffs explicit for each project.
