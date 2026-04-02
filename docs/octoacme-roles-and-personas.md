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
- Collaborate with UX Designers on implementation feasibility
- Work with Release Managers on deployment readiness

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Interactions with Other Roles
- **Product Managers:** Clarify acceptance criteria and priorities; discuss technical trade-offs
- **Project Managers:** Report blockers and progress; estimate and plan work
- **UX Designers:** Pair on implementation approach; validate design feasibility; review code for design fidelity
- **Data Analysts:** Collaborate on event tracking and data instrumentation implementation
- **Release Managers:** Confirm deployment readiness; coordinate release timing
- **QA/Testing:** Review test plans; resolve issues collaboratively

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed
- UX pairing sessions during implementation
- Release planning meetings

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Work with Data Analysts to define and track KPIs
- Partner with UX Designers on user validation
- Support Release Managers with launch planning and communications

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Interactions with Other Roles
- **Project Managers:** Align on scope, timeline, and dependencies; facilitate cross-team coordination
- **Developers:** Clarify requirements; discuss technical feasibility and trade-offs
- **UX Designers:** Collaborate on user research; validate designs against product goals
- **Data Analysts:** Define success metrics and KPIs; review data findings to inform decisions
- **Release Managers:** Plan release timing and messaging; communicate feature value to stakeholders
- **QA/Testing:** Clarify acceptance criteria; ensure quality standards

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs
- Data review sessions with Data Analysts
- Release readiness reviews

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
- Facilitate collaboration between all roles (Dev, Product, UX, Data, Release)
- Escalate blockers and maintain risk register

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders
- Enable effective cross-functional collaboration

### Interactions with Other Roles
- **Product Managers:** Partner on scope, timeline, and stakeholder alignment
- **Developers:** Track progress; identify and escalate blockers
- **UX Designers:** Monitor design review dependencies; communicate timeline impacts
- **Data Analysts:** Report on project health metrics; identify data-driven risks
- **Release Managers:** Coordinate release dates with project timeline; manage dependencies
- **QA/Testing:** Ensure quality schedule is factored into timeline

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation
- Cross-functional sync meetings
- Escalation paths for blockers

---

## User Experience Designers (UX/Design)

### Role Summary
User Experience Designers lead user research, create designs, and advocate for user-centric solutions. They ensure the product is intuitive, accessible, and aligned with user needs.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Advocate for user-centric design decisions in trade-off discussions
- Collaborate with Developers on implementation feasibility
- Define accessibility and usability requirements
- Provide design feedback and direction during development
- Participate in QA acceptance testing for user experience

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support burden
- Ensure product meets user needs and expectations
- Advocate for usability in cross-functional trade-offs

### Interactions with Other Roles
- **Product Managers:** Align on user research findings and design direction; validate designs against product goals
- **Developers:** Pair on implementation approach; review code for design fidelity; troubleshoot feasibility questions
- **Project Managers:** Communicate timeline impacts for design reviews; flag user research dependencies
- **QA/Testing:** Define and validate acceptance criteria for user experience; collaborate on usability testing
- **Data Analysts:** Use metrics to inform design improvements; track user experience KPIs

### Typical Communication
- Design review sessions (weekly or bi-weekly)
- User research findings presentations
- Design specification documents and prototypes
- Slack/channel for quick design questions
- Usability testing reports and recommendations

---

## Data Analysts

### Role Summary
Data Analysts gather, analyze, and communicate data-driven insights. They enable teams to make informed decisions through metrics, dashboards, and actionable recommendations.

### Responsibilities
- Define Key Performance Indicators (KPIs) aligned with project success metrics
- Design and implement data collection and tracking
- Analyze product and project metrics to inform decision-making
- Create dashboards and reports for stakeholders
- Identify trends, anomalies, and optimization opportunities
- Support hypothesis testing and A/B experiments
- Help QA teams validate data collection accuracy

### Goals
- Provide clear, actionable data insights
- Enable data-driven decision-making
- Measure project and product impact
- Identify optimization opportunities through metrics

### Interactions with Other Roles
- **Product Managers:** Define success metrics and KPIs; present findings to support prioritization decisions
- **Developers:** Collaborate on event tracking implementation; validate data accuracy; support data instrumentation
- **Project Managers:** Report on project health metrics (velocity, burn-down); flag data-driven risks
- **QA/Testing:** Validate event tracking accuracy; ensure data collection completeness
- **Release Managers:** Provide pre/post-release impact metrics
- **UX Designers:** Use metrics to inform design improvements; track user experience KPIs

### Typical Communication
- Weekly metric reviews and dashboards
- Data findings presentations (monthly or milestone-based)
- KPI definition workshops during planning
- Slack/email for data questions and ad-hoc analysis requests
- Post-release metrics and impact reports

---

## Release Managers

### Role Summary
Release Managers coordinate release planning, execution, and communication. They ensure smooth, predictable deployments while managing risk and maintaining quality.

### Responsibilities
- Plan and schedule releases with all stakeholders
- Create release notes and communicate changes to stakeholders and users
- Prepare and validate deployment checklists
- Coordinate with Developers on deployment readiness
- Manage rollback plans and incident response
- Track and communicate release status
- Document lessons learned and post-release metrics

### Goals
- Execute predictable, low-risk releases
- Minimize downtime and post-release issues
- Maintain stakeholder confidence and transparency
- Enable rapid rollback if needed

### Interactions with Other Roles
- **Developers:** Verify feature/fix completion and deployment readiness; coordinate deployment windows
- **QA/Testing:** Confirm acceptance criteria met; collaborate on smoke test execution
- **Project Managers:** Coordinate release dates with project timeline; manage dependencies
- **Product Managers:** Draft release announcement and marketing message; validate release scope
- **Data Analysts:** Prepare pre/post-release metrics for impact assessment
- **Stakeholders:** Provide release summaries, known issues, and migration guidance

### Typical Communication
- Release planning meetings (1–2 weeks pre-release)
- Release readiness reviews (day before deployment)
- Release notes and announcement communications
- Post-release retrospectives and incident reports
- Rollback plan reviews

---

## Quality Assurance / Testing

### Role Summary
QA/Testing teams validate quality and ensure features meet acceptance criteria and quality standards before release. They partner with all roles to ensure shipping with confidence.

### Responsibilities
- Validate features against acceptance criteria
- Execute test plans and automation
- Identify and report defects
- Coordinate with Developers on issue resolution
- Validate data collection and tracking accuracy
- Participate in release readiness validation
- Support accessibility and security testing

### Goals
- Ensure product quality and reliability
- Reduce defects reaching production
- Support continuous improvement in product quality
- Enable confident releases

### Interactions with Other Roles
- **Developers:** Report issues; collaborate on reproduction and fixes; review test coverage
- **UX/Design:** Validate user experience design fidelity; conduct usability testing; verify accessibility
- **Product Managers:** Clarify acceptance criteria; validate product requirements
- **Data Analysts:** Validate event tracking accuracy; ensure data collection completeness
- **Release Managers:** Confirm release readiness; execute smoke tests; participate in rollback testing
- **Project Managers:** Report quality metrics; flag timeline risks related to testing

### Typical Communication
- Test reports and defect tracking
- Sprint QA kickoff meetings
- Release readiness reviews
- Ad-hoc quality discussions and pairing sessions
- Accessibility and security testing reports

---

## Cross-Functional Collaboration Guidelines

Effective project execution requires clear collaboration and accountability across all roles. Use the following guidelines to ensure aligned teams and predictable delivery.

### Decision Rights Framework
- **Product Direction & Prioritization:** Product Manager (with stakeholder input)
- **Technical Implementation & Architecture:** Dev Lead (with Design and PM input)
- **User Experience & Design:** UX Designer (with PM and Dev input)
- **Data & Metrics:** Data Analyst (with Product and Dev input)
- **Release Planning & Execution:** Release Manager (with Dev and QA input)
- **Project Timeline & Coordination:** Project Manager (with all team input)

### Recommended Collaboration Checkpoints
1. **Project Initiation:** All roles validate requirements, constraints, and dependencies
2. **Planning:** Define roles, handoff points, acceptance criteria, and communication cadence
3. **Mid-Milestone:** Cross-functional sync to address blockers and adjust course if needed
4. **Pre-Release:** Release Manager coordinates final readiness with all teams
5. **Post-Release:** Data Analyst shares impact metrics; team captures learnings in retrospective

### Communication Best Practices
- Use a single source of truth (project README, shared doc, or issue tracker)
- Escalate cross-team dependencies early (ideally during planning)
- Document decisions and rationale for future reference
- Schedule regular cross-functional syncs (weekly or bi-weekly minimum)
- Celebrate wins and share learnings in retrospectives
- Provide feedback to other roles within 4–8 business hours (target)
- Flag blockers immediately; escalate if unresolved within 1 business day

### Common Cross-Functional Pitfalls to Avoid
- ❌ Missing design reviews before dev starts → causes rework and delays
- ❌ Not defining data tracking requirements upfront → causes post-release scrambling
- ❌ QA discovering acceptance criteria for the first time during testing → causes delays
- ❌ Release date set without Release Manager input → causes rushed or failed deployments
- ❌ No escalation process for blockers → causes silent delays and surprises
- ❌ Poor documentation of decisions and trade-offs → causes confusion later
- ❌ Standups without visibility into cross-team dependencies → misses blocking issues

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the cross-functional collaboration guidelines when designing workflows or resolving role conflicts.
- Use the decision rights framework to clarify who owns which decision in your project.