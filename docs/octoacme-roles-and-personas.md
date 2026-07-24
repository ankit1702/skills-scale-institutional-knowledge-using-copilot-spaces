# Roles and Personas

> (This file has been updated to add a new section "Operational Personas" — additions begin below.)

<!-- Existing role definitions should remain above. The following section adds operational personas to improve day-to-day clarity and handoffs. -->

## Operational Personas

This section adds operational personas that support the high-level roles already defined in this document. Each persona has a one-paragraph overview, 3–5 key responsibilities, primary interactions, and suggested acceptance criteria for key activities.

### Project Coordinator

Overview: The Project Coordinator supports the Project Manager by maintaining project schedules, tracking action items, and coordinating logistics so the core team can focus on delivery.

Responsibilities:
- Maintain and update the project schedule and trackers.
- Track and follow up on action items from meetings.
- Coordinate meeting logistics, notes, and distribution of decisions.
- Maintain a central list of blockers and escalate to the Project Manager.

Primary interactions:
- Project Manager — daily sync on actions and escalations.
- Delivery Team — collects status updates and dependencies.
- Stakeholder Liaison — schedules stakeholder reviews and demos.

Acceptance criteria:
- Action tracker is updated within 24 hours of meetings.
- Blockers are logged and acknowledged by an owner within one business day.
- Meeting notes and decisions are distributed within 48 hours.

---

### Delivery Lead

Overview: The Delivery Lead oversees the execution of a specific workstream, ensures dependencies are tracked, and coordinates with engineering and QA to unblock progress.

Responsibilities:
- Drive delivery activities for an assigned workstream.
- Track dependencies and ensure handoffs are planned.
- Coordinate resource allocation and escalate resource conflicts.
- Confirm readiness for acceptance and release activities.

Primary interactions:
- Engineering Lead — coordinate implementation and technical choices.
- Project Manager — align on scope, timelines, and risks.
- Quality Advocate / QA — ensure acceptance criteria and testing plans are in place.

Acceptance criteria:
- Delivery milestones are met according to the plan or documented with approved change requests.
- Dependencies have owners and mitigation plans.
- Acceptance criteria for features are defined before handoff to QA.

---

### Quality Advocate

Overview: The Quality Advocate ensures that quality criteria are defined, tested, and validated throughout the delivery process to reduce regressions and improve customer outcomes.

Responsibilities:
- Define and maintain quality criteria and testing checklists.
- Coordinate acceptance testing and track test coverage for releases.
- Flag and track quality regressions and ensure triage.
- Collaborate with engineering to promote test automation where appropriate.

Primary interactions:
- QA Engineers — test planning and execution.
- Delivery Lead — acceptance gates and test signoffs.
- Release Manager — pre-release quality checks.

Acceptance criteria:
- Test checklist is complete for each release and signed off by Quality Advocate.
- Critical regressions are triaged within the agreed SLA.
- Acceptance tests for new features are documented and executed.

---

### Risk Owner

Overview: The Risk Owner is accountable for the lifecycle of one or more identified risks, maintaining mitigation plans and driving escalations when thresholds are met.

Responsibilities:
- Maintain the risk register entries they own.
- Update risk status and mitigation plans regularly.
- Trigger escalations when risk thresholds or time-based triggers are met.
- Coordinate cross-team actions to reduce or accept risk.

Primary interactions:
- Project Manager — risk reporting, status, and mitigation recommendations.
- Stakeholder Liaison — communicate impact to stakeholders as required.
- Leadership — escalate risks that require decision or additional funding.

Acceptance criteria:
- Risk entries have a clear owner, mitigation actions, and status updates at each checkpoint.
- Escalations follow the documented escalation path when thresholds are exceeded.

---

### Stakeholder Liaison

Overview: The Stakeholder Liaison maintains stakeholder relationships, coordinates communications, and ensures stakeholder feedback is gathered and actioned.

Responsibilities:
- Maintain a stakeholder roster and communication plan.
- Schedule and facilitate stakeholder demos and reviews.
- Consolidate stakeholder feedback into actionable items.
- Ensure stakeholder expectations are aligned with delivery timelines.

Primary interactions:
- Project Manager — prioritization of stakeholder asks and clarifications.
- Product Owner — clarify requirements and feedback.
- Project Coordinator — schedule stakeholder meetings.

Acceptance criteria:
- Stakeholder communication plan exists and is followed for major milestones.
- Feedback is captured and linked to action items with owners.

---

### Change Manager

Overview: The Change Manager owns the change control process, documenting scope changes, coordinating approvals, and ensuring changes are reflected in release plans and communications.

Responsibilities:
- Document and log change requests with impact analysis.
- Coordinate approval flows with Product, PMO, and stakeholders.
- Update release plans and communicate approved changes.
- Track implementation of approved changes and verify closure.

Primary interactions:
- Product Owner — scope decisions and impact discussions.
- Project Manager — impact analysis and schedule updates.
- Release Manager — incorporate approved changes into release cadence.

Acceptance criteria:
- Change requests include impact, estimated effort, and approval status.
- Approved changes are scheduled and communicated ahead of releases.

---

## Suggested placement and cross-linking

Add these personas as subsections under a new top-level section "Operational Personas" in docs/octoacme-roles-and-personas.md. Cross-link any related high-level roles (e.g., Project Manager, Product Owner, Engineering Lead) to avoid duplication and clarify boundaries.

When adding, ensure each persona has:
- One-paragraph overview
- 3–5 clear responsibilities
- Primary interactions (who they coordinate with and why)
- Suggested acceptance criteria for key outcomes

These operational personas are intended to complement—not replace—existing role definitions. They surface the day-to-day responsibilities and handoffs that often cause ambiguity in cross-functional projects.
