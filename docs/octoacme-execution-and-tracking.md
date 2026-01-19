# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)
  - **UX Design Verification**: For UI changes, include screenshots and verify against design specs
  - **Security Review**: Tag Security Lead for security-sensitive changes
- **Design Handoff**: UX Designer provides specifications, assets, and answers Developer questions
- **QA Handoff**: Developers notify QA Engineer when features are ready for testing
- **DevOps Coordination**: Developers work with DevOps Engineer on deployment automation and infrastructure changes

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI (coordinated by Security Lead and DevOps Engineer)
- Manual QA for feature acceptance when needed
- **QA Signoff**: QA Engineer must approve before release
- **Design QA**: UX Designer validates implementation matches design specifications
- **Automated Testing**: DevOps Engineer ensures CI pipeline runs all tests automatically

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Security scanning enabled in CI pipeline
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] UX design handoff completed for UI features
- [ ] QA testing coverage and signoff process established
- [ ] DevOps deployment automation configured
