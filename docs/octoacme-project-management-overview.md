# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- **Project Manager (PM)**: coordinates delivery, schedules, risk, communications.
- **Product Manager (PdM)**: defines outcomes, prioritizes backlog, and measures success.
- **Scrum Master**: facilitates agile ceremonies, removes impediments, coaches on agile practices.
- **Developers**: implement features, collaborate on design and testability.
- **UX Designer**: creates user-centered designs, conducts research, validates solutions.
- **QA/Testing**: validate quality and acceptance criteria.
- **Release Manager**: coordinates releases, manages deployments, ensures release readiness.
- **Security Lead**: ensures security integration, identifies vulnerabilities, guides secure practices.
- **Stakeholders**: provide inputs and approvals.

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Lifecycle (high-level)
1. Initiation: problem statement, stakeholders, high-level timeline.
2. Planning: scope, resources, milestones, dependencies.
3. Execution: build, test, review, iterate.
4. Release: deploy, verify, announce.
5. Close & Retrospective: capture learnings and next steps.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.

## Onboarding New Team Members
To address onboarding clarity (per issue #4), new team members should:
1. Start with this overview document to understand the project management approach
2. Review [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) to understand their role and cross-functional interactions
3. Read the phase-specific docs relevant to their current work (planning, execution, release, etc.)
4. Shadow key ceremonies (standups, planning, retrospectives) for their first sprint
5. Review the project's Risk Register and current sprint backlog
6. Identify their onboarding buddy (typically assigned by Scrum Master or PM)
7. Complete role-specific onboarding activities:
   - **Developers**: Set up dev environment, review coding standards, understand PR workflow
   - **Scrum Masters**: Shadow existing ceremonies, review team metrics and velocity
   - **UX Designers**: Review design system, understand user research process
   - **Release Managers**: Learn release pipeline, review deployment runbooks
   - **Security Leads**: Review security policies, access scanning tools, understand incident response

*This onboarding guidance addresses clarity gaps identified in issue #4.*
