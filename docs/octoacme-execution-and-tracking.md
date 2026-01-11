# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — facilitated by Scrum Master, focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone — showcase completed work to stakeholders
- Sprint retrospectives — facilitated by Scrum Master to capture learnings and improvements

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI (monitored by Security Lead)
- Manual QA for feature acceptance when needed
- UX validation and usability testing coordinated with UX Designer
- Accessibility testing for UI changes

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- **Level 1**: Team-level triage in daily standup facilitated by Scrum Master
- **Level 2**: Scrum Master and PM escalate to Product Lead and dependent teams
- **Level 3**: Sponsor-level escalation for business-impacting issues
- **Security escalations**: Security Lead coordinates with Security on-call for security incidents

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Security scanning enabled and monitored by Security Lead
- [ ] Regular demos scheduled with stakeholder calendar invites
- [ ] Risk register updated weekly by PM
- [ ] Sprint ceremonies facilitated by Scrum Master (standup, planning, retro, demo)
- [ ] UX Designer reviews and validates UI implementations
- [ ] Release Manager notified of deployment target dates
