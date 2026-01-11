# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- Release Manager owns release communication to all affected teams
- Security Lead communicates security posture and compliance status

## Role Accountability Matrix
To clarify cross-functional handoffs and decision rights (RACI model):

**Abbreviations:** PM = Project Manager, PdM = Product Manager, SM = Scrum Master

| Activity | Responsible | Accountable | Consulted | Informed |
|----------|-------------|-------------|-----------|----------|
| Sprint Planning | Scrum Master | Product Manager | Developers, UX Designer | Project Manager, Stakeholders |
| Design Direction | UX Designer | Product Manager | Developers, Project Manager | Stakeholders |
| Release Deployment | Release Manager | Project Manager | Developers, Security Lead | Stakeholders |
| Security Review | Security Lead | Project Manager | Developers, Product Manager | Stakeholders |
| Backlog Prioritization | Product Manager | Product Manager | Scrum Master, Project Manager | Developers, Stakeholders |
| Risk Identification | Team Members | Project Manager | Scrum Master | Stakeholders |

**Note:** In the RACI model, a single role can be both Responsible and Accountable when they have sole ownership of an activity (e.g., Product Manager for Backlog Prioritization).

*This matrix addresses accountability gaps identified in issue #4.*

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- **Standard escalation**: Team-level -> Scrum Master -> PM -> Product Lead -> Sponsor
- **Security incidents**: Security Lead -> Security on-call -> Security incident runbook
- **Release issues**: Release Manager -> PM -> Product Lead (with parallel notification to Security Lead if security-related)
- **Cross-team dependencies**: Scrum Master coordinates with peer Scrum Masters, escalates to PMs if unresolved
