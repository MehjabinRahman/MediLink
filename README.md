# MediLink — Software Engineering Management in Practice

## Project Overview

MediLink is a fictional Canadian appointment-management platform for medical and dental clinics. The platform allows patients to book and cancel appointments, receive automated reminders, and manage their appointments. Clinic employees use an administrative interface to manage schedules.

This project simulates a software engineering development cycle focused on improving team coordination, workflow efficiency, software quality, and engineering management practices.

## Project Objectives

The main objectives of this project are to:

- Establish a structured GitHub development workflow.
- Manage a realistic backlog of software development tasks.
- Define clear responsibilities and priorities.
- Improve team communication and collaboration.
- Apply code review and verification practices.
- Identify workflow bottlenecks and technical dependencies.
- Encourage independent problem-solving and shared responsibility.
- Support continuous process improvement.

## Team Structure

The team consists of three members:

**Member 1 — Engineering Manager / Team Lead and Developer**
- Coordinates the development workflow.
- Manages task assignments and priorities.
- Monitors blockers and facilitates reviews.
- Contributes to technical and maintenance work.

**Member 2 — Appointments Developer**
- Works on appointment-management enhancements.
- Handles patient-facing functionality.
- Participates in testing and peer reviews.

**Member 3 — Notifications Developer**
- Works on reminder reliability.
- Investigates simulated defects.
- Develops notification-related test scenarios.
- Participates in technical reviews.

Detailed responsibilities are documented in `TEAM_RESPONSIBILITIES.md`.

## Development Workflow

The team follows a six-stage GitHub workflow:

**Backlog → Ready → In Progress → Code Review → Verification → Done**

- **Backlog:** Work items awaiting refinement.
- **Ready:** Tasks with confirmed requirements, priorities, and owners.
- **In Progress:** Tasks currently being worked on.
- **Code Review:** Work awaiting peer review.
- **Verification:** Work undergoing testing or acceptance checks.
- **Done:** Tasks that satisfy the Definition of Done.

### Work in Progress Limit

The team uses a WIP limit of **two active tasks** in the In Progress stage.

This limit is intended to reduce context switching, encourage task completion, and maintain capacity for code reviews and production support.

## Release Backlog

The simulated release contains eight planned work items:

- **ML-01:** Add Cancellation Confirmation Receipt
- **ML-02:** Filter Clinic Appointments by Status
- **ML-03:** Correct Stale Cancellation Status in Clinic View (Simulated Defect)
- **ML-04:** Check Appointment Status Before Reminder Dispatch
- **ML-05:** Add Cancellation/Reminder Integration Test Cases
- **ML-06:** Update Notification Support Runbook
- **ML-07:** Standardize Issue Acceptance-Criteria Template
- **ML-08:** Define Appointment-State Transition Test Matrix

Each GitHub issue includes a description, acceptance criteria, assigned owner, priority, and verification requirements.

## Quality Assurance

The team follows a shared Definition of Done to ensure that work items undergo appropriate review and verification before completion.

Quality practices include:

- Acceptance-criteria verification.
- Peer review.
- Testing or documented simulation checks.
- Review feedback resolution.
- Documentation updates.
- Privacy and security considerations.

The complete checklist is available in `DEFINITION_OF_DONE.md`.

## Team Communication

The team uses GitHub Discussions for asynchronous coordination.

Each member provides at least three daily updates containing:

- Completed work
- Planned work
- Blockers or assistance needed

GitHub Issues are used for task-specific discussions, while pull requests or documented review activities support peer feedback.

Urgent production incidents and significant unresolved blockers may require synchronous team discussions.

## Workflow Monitoring and Improvement

The team examines workflow activity to identify potential issues involving:

- Review delays
- Incomplete requirements
- Blocked work
- Technical dependencies
- Excessive work in progress
- Verification problems

Observations are evaluated using evidence, possible explanations, information still needed, and proposed responses.

The findings support engineering-management decisions and process improvement activities.

## Project Scope

This repository is used for an academic software engineering management simulation.

The assignment does not require implementation of a complete MediLink application. The repository contains project-management artifacts, GitHub issues, development plans, and review or verification evidence produced during the simulated cycle.

Simulated scenarios and results will be identified as such. No real patient information is used.

## Project Documentation

- `TEAM_RESPONSIBILITIES.md` — Team roles and responsibilities
- `DEFINITION_OF_DONE.md` — Quality checklist and completion criteria
- `DEVELOPMENT_PLAN.md` — Development cycle plan
- `WORKFLOW_OBSERVATIONS.md` — Evidence-based workflow observations

These files are maintained as they are created and updated during the development cycle.


