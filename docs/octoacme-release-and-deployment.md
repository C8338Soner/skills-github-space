# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- **QA Signoff**: All tests passed and quality verified by QA Engineer
- **Security Verification**: Security Lead approves security scan results
- **DevOps Readiness**: Infrastructure and deployment automation verified
- Release notes drafted (with input from Product Manager and Customer Success)
- Rollback / mitigation plan documented
- Smoke tests prepared
- **Customer Success Briefing**: Support team informed of changes and potential issues

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] **DevOps Engineer** coordinates deployment execution
- [ ] Deploy to production (automated pipeline preferred)
- [ ] **QA Engineer** runs post-deploy smoke tests
- [ ] Run post-deploy verifications
- [ ] **Security Lead** verifies security controls are functioning
- [ ] **Customer Success** announces release to stakeholders and support
- [ ] Monitor system health and user feedback

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call (DevOps Engineer and Security Lead if security-related)
  - Rollback to last known-good release if necessary (coordinated by DevOps Engineer)
  - Triage root cause and capture action items
  - **Customer Success** communicates status to affected customers
  - **Security Lead** coordinates if incident has security implications
  - Post-incident blameless retrospective with all involved roles

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
