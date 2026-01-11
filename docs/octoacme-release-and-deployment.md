# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans (validated by Security Lead)
- Release notes drafted by Release Manager
- Rollback / mitigation plan documented
- Smoke tests prepared
- UX Designer sign-off on user-facing changes
- Security Lead approval for production deployment

## Deployment Checklist
**Release Manager coordinates the following steps:**
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Security Lead reviews staging security posture
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Monitor error rates and key metrics for first 30 minutes
- [ ] Announce release to stakeholders and support
- [ ] Update release documentation and knowledge base

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Release Manager triggers incident response and notifies on-call
  - Security Lead engaged immediately if incident is security-related, including:
    - Data breaches or unauthorized data access
    - Authentication or authorization failures
    - Vulnerability exploits or attacks
    - Security scanning failures or compliance violations
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items
  - Conduct blameless post-incident review facilitated by Scrum Master

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:
