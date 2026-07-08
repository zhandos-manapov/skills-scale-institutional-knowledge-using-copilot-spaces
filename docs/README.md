# OctoAcme Project Management Docs

This directory contains OctoAcme's core project management process documents and a concise summary for quick onboarding and discoverability.

## Overview
OctoAcme follows a lightweight, iterative project management approach that moves work through five stages: Initiation, Planning, Execution & Tracking, Release & Deployment, and Retrospective & Continuous Improvement. Initiation captures the problem, desired outcomes, stakeholders, and a Project One-pager to validate and authorize work. Planning breaks approved initiatives into prioritized backlog items with clear acceptance criteria, estimates, and a risk register to surface dependencies early.

Execution follows a predictable team rhythm: daily standups for immediate coordination and blocker triage, a weekly delivery sync for progress and risks, and regular demos or reviews at the end of sprints or milestones. Work is tracked on a project board (Backlog → Ready → In Progress → In Review → QA → Done), and Pull Requests should be small, include issue links and acceptance criteria, run CI/tests/linting prior to review, and require at least one approval. Escalation paths exist (team → PM → Product Lead → Sponsor) and security incidents follow a dedicated runbook.

Quality assurance is enforced through CI pipelines (unit, integration, and security scanning), end-to-end smoke tests for critical flows, and manual QA where needed. Pre-release gating requires passing CI, documented rollback plans, release notes, and post-deploy verification. Retrospectives after sprints, releases, or incidents capture action items with owners and due dates; action items are tracked and measured to drive continuous improvement.

## Docs index
- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md

## Suggested next steps
- Commit this file to the branch add-process-docs-readme and open a pull request that references issue #2.
- Add @zhandos-manapov as a reviewer on the PR.
