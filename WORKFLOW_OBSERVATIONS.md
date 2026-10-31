# MediLink — Workflow Observations 

**Project:** MediLink Release Cycle  
**Observation Period:** [Start Date] to [End Date]  
**Team Members:** Mehjabin Rahman Mowrin, Rim Belabbas, Yessir Khelifi  
**GitHub Project:** [Insert GitHub Project URL]

## Purpose

This document records workflow observations from the MediLink simulated development cycle. The team examines GitHub issues, Project Board status changes, daily updates, and pull requests or documented peer reviews.

Each observation follows the required structure: **Evidence → Possible Explanation → Information Still Needed → Proposed Response**.

The goal is to identify workflow problems, investigate their possible causes, and recommend improvements without unfairly evaluating individual developer performance.

## Observation 1 — Code Review Delays

### Evidence

- **Related Issue:** [Insert GitHub issue link]
- **Pull Request or Review Record:** [Insert link]
- **Date Entered Code Review:** [Date]
- **Date First Reviewed:** [Date]
- **Review Waiting Time:** [Actual duration]
- **Observed Activity:** [Describe what occurred]

### Possible Explanation

Code review delays may result from limited reviewer availability, competing priorities, unclear review responsibilities, or incomplete handoffs. These factors can cause work items to remain in Code Review longer than expected.

### Information Still Needed

- Was a reviewer assigned when the task entered Code Review?
- Did the reviewer have competing responsibilities?
- Was sufficient information available to complete the review?
- Was the delay an isolated event or a recurring problem?

### Proposed Response

Assign a reviewer when an issue enters Code Review and monitor pending reviews through asynchronous daily updates. Review turnaround time should be measured to determine whether the proposed approach improves workflow efficiency.

## Observation 2 — Incomplete Requirements

### Evidence

- **Related Issue:** [Insert GitHub issue link]
- **Clarification Comment:** [Insert link]
- **Date Identified:** [Date]
- **Missing or Unclear Requirement:** [Describe]
- **Workflow Impact:** [Actual delay, revision, or rework]

### Possible Explanation

Some work items may enter development before their requirements, dependencies, or acceptance criteria are sufficiently clarified. This can lead to additional questions, changes during development, and avoidable rework.

However, the team should also consider whether new requirements or edge cases emerged after development started.

### Information Still Needed

- Were the missing details available during initial planning?
- Were acceptance criteria sufficiently specific?
- Did the requirements change after development started?
- Did the ambiguity cause actual delay or rework?

### Proposed Response

Introduce a Ready-stage checklist requiring every work item to have a clear description, assigned owner, priority, acceptance criteria, relevant dependencies, and verification method before development begins.

## Observation 3 — Blocked Work and Technical Dependencies

### Evidence

- **Affected Issue:** [Insert GitHub issue link]
- **Related Dependency:** [Insert issue or PR link]
- **Date Blocker Identified:** [Date]
- **Date Resolved:** [Date, if applicable]
- **Impact on Progress:** [Describe actual impact]

**Potential issue to investigate:** ML-05 — Cancellation/Reminder Integration Test Cases may depend on the reminder dispatch validation behavior defined in ML-04.

This should only be reported as an actual blocker if the team encounters and documents the dependency.

### Possible Explanation

Blocked work may occur when dependent tasks, interface definitions, or technical decisions are incomplete. Dependencies that are not identified during planning can prevent developers from progressing with implementation or verification.

### Information Still Needed

- Which specific dependency prevented progress?
- Who was responsible for resolving it?
- Could independent work continue while the blocker remained unresolved?
- Was the dependency identified during backlog planning?

### Proposed Response

Identify technical dependencies during backlog refinement and document them in the relevant GitHub issues. Use the `blocked` label when an issue cannot progress and record the assistance required.

For significant unresolved blockers, arrange a short synchronous discussion to coordinate the next steps.

## Individual Issues vs. Team/Process Issues

Workflow delays should not automatically be considered individual performance problems. For example, a developer's task may remain in Code Review because of limited reviewer availability, unclear responsibilities, or competing priorities.

Such delays may indicate a team-level process issue rather than poor individual performance. The Engineering Manager should examine the evidence, consider the surrounding circumstances, and identify possible underlying causes before proposing improvements.

**Example from Our Development Cycle:** [Insert a genuine observation and relevant GitHub evidence demonstrating the distinction.]

## Consolidated Workflow Findings

The following findings will be completed after reviewing the team's actual GitHub activity.

**Finding 1:** [Describe the first observed problem and evidence.]

**Finding 2:** [Describe the second observed problem and evidence.]

**Finding 3:** [Describe the third observed problem and evidence.]

**Most Significant Process Problem:** [Identify the problem supported by the strongest evidence.]

**Reason for Prioritization:** [Explain its impact on the workflow.]

**Proposed Improvement Experiment for Part H:** [Identify a small, measurable process change for the team to evaluate.]

## Evidence Checklist

- [ ] Three actual workflow observations have been documented.
- [ ] Each observation includes supporting GitHub evidence.
- [ ] Possible explanations have been identified.
- [ ] Additional information needed for investigation is documented.
- [ ] Proposed responses are included.
- [ ] At least one observation distinguishes individual and team/process problems.
- [ ] Screenshots show relevant issue comments, reviews, or blockers.
- [ ] Findings are supported by real evidence rather than assumptions.

## Conclusion

The workflow observation process is intended to help the MediLink team identify opportunities to improve task coordination, requirement clarity, review practices, and dependency management.

The final observations and proposed improvements will be based on evidence gathered during the simulated development cycle. These findings will also help the team select a suitable process improvement experiment for Part H.
