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
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, customers)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- **Customer Success**: Primary liaison for customer-facing communications
- **Security Lead**: Communicates security-related risks and incidents
- **DevOps Engineer**: Provides infrastructure status and deployment updates

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication (coordinated by DevOps Engineer or Security Lead):
- Triage summary
- Actions being taken
- Expected timeline
- Impact assessment
- Post-incident blameless retrospective scheduled

Customer Impact Communication (led by Customer Success):
- Issue description in customer-friendly language
- Affected features or services
- Workarounds (if available)
- Expected resolution timeline
- How to get support

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security Lead immediately
- For infrastructure or deployment issues, escalate to DevOps Engineer
- For customer-impacting issues, notify Customer Success for user communication
- For critical quality issues, involve QA Engineer in triage and resolution planning
