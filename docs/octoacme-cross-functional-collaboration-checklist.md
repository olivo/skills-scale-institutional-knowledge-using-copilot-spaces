# OctoAcme — Cross-Functional Collaboration Checklist

## Purpose
Ensure all roles are engaged, accountable, and communicating effectively throughout the project lifecycle.

## Pre-Project Checklist (Initiation)
- [ ] Identify and assign representatives for each role: Dev Lead, Product Manager, UX Designer, Data Analyst, QA Lead, Release Manager
- [ ] Schedule project kickoff with all roles
- [ ] Share project one-pager with all roles for review
- [ ] Confirm team capacity and availability for entire project timeline
- [ ] Establish weekly or bi-weekly sync cadence

## Kickoff Meeting Checklist
- [ ] Review and align on problem statement and success metrics
- [ ] Define user personas and key user journeys (with UX input)
- [ ] Identify data tracking requirements and KPIs (with Data Analyst input)
- [ ] Map dependencies between roles (handoff points, blockers)
- [ ] Define communication channels (Slack, email, meetings)
- [ ] Confirm timeline and release date
- [ ] Establish escalation path for blockers

## Planning Phase Checklist
- [ ] Backlog items include functional, UX, data, and accessibility criteria
- [ ] Design dependencies documented (e.g., "Requires design review before dev start")
- [ ] Data tracking events defined and documented
- [ ] Release plan created with Release Manager
- [ ] Testing strategy aligned between QA and Developers
- [ ] All roles confirm they can meet timelines

## Execution Phase Checklist (Weekly)
- [ ] Standups include all key roles or documented async updates
- [ ] Design reviews completed on schedule (no dev blockers on design)
- [ ] Data instrumentation on track (no testing blockers on tracking)
- [ ] Risk register reviewed and escalations addressed
- [ ] Blockers identified and escalated quickly (same day if critical)
- [ ] Communication on schedule (no surprises for stakeholders)

## Pre-Release Checklist (1–2 weeks before)
- [ ] Release Manager confirms release date and scope with all teams
- [ ] All acceptance criteria met (functional, UX, data, accessibility)
- [ ] QA testing plan finalized and communicated
- [ ] Release notes drafted (with Product and UX input)
- [ ] Data Analyst confirms tracking implementation and validation
- [ ] Rollback plan documented
- [ ] Stakeholders and support teams briefed on release

## Release Readiness Checklist (Day before)
- [ ] All code merged, tested, and approved
- [ ] UX design changes verified in staging
- [ ] Data tracking verified in staging
- [ ] Smoke test plan reviewed and ready
- [ ] Release notes final and reviewed
- [ ] Communication plan ready (announcement, known issues, docs)
- [ ] Rollback plan confirmed with Release Manager and Ops
- [ ] On-call support confirmed for immediate post-release

## Post-Release Checklist (24–48 hours after)
- [ ] Deployment successful with no critical issues
- [ ] Data tracking verified (events are flowing correctly)
- [ ] Smoke tests passed; no unexpected issues reported
- [ ] Data Analyst shares early impact metrics
- [ ] Incident response (if needed) completed and documented
- [ ] Stakeholders and support teams confirm no major issues

## Retrospective Checklist
- [ ] All roles participated in retrospective
- [ ] What went well captured
- [ ] What could improve captured (include cross-functional feedback)
- [ ] Action items assigned with clear owners and due dates
- [ ] Follow-up on previous action items from prior retrospectives
- [ ] Celebrate wins with the team

## Role-Specific Handoff Checklist

### Design → Development
- [ ] Design specs complete and detailed
- [ ] Figma/design tool access for all developers
- [ ] Design review meeting held to clarify questions
- [ ] Dev confirms feasibility; design documents trade-offs if any
- [ ] Acceptance criteria for UX quality documented

### Development → QA
- [ ] Feature complete and code reviewed
- [ ] PR description includes link to acceptance criteria
- [ ] Data tracking events documented and implemented
- [ ] QA environment accessible and feature testable
- [ ] Test plan reviewed and agreed with QA lead

### QA → Release Manager
- [ ] All acceptance criteria met and tested
- [ ] Defects resolved or documented as known issues
- [ ] Release notes validated for accuracy
- [ ] Smoke tests defined and staged
- [ ] Release Manager confirms go/no-go decision

### Release Manager → Stakeholders
- [ ] Release notes shared 24–48 hours before
- [ ] Known issues and workarounds clearly communicated
- [ ] Deployment window and rollback plan shared
- [ ] Support team briefed on changes
- [ ] Post-release communication plan shared

## Common Cross-Functional Pitfalls to Avoid
- ❌ Missing design reviews before dev starts (causes rework)
- ❌ Not defining data tracking requirements upfront (causes post-release scrambling)
- ❌ QA discovering acceptance criteria for the first time during testing (causes delays)
- ❌ Release date set without Release Manager input (causes rushed or failed deployments)
- ❌ No escalation process for blockers (causes silent delays)
- ❌ Poor documentation of decisions and trade-offs (causes confusion later)
- ❌ Standups without visibility into cross-team dependencies (misses blocking issues)

## Communication Expectations
- **Response Time:** Cross-team questions answered within 4–8 business hours
- **Escalations:** Blockers flagged immediately; escalated within 1 business day if unresolved
- **Status Updates:** Weekly async or sync depending on project cadence
- **Decisions:** Documented in a central location (project README, decision log, or issue comments)
- **Retrospectives:** Scheduled within 1 week of release; action items tracked