# 12 - Requirements Traceability Matrix

## 1. Purpose

The Requirements Traceability Matrix (RTM) provides end-to-end traceability between business requirements, functional requirements, user stories, acceptance criteria, and UAT scenarios.

The RTM helps ensure that approved requirements are implemented and validated before project completion.

---

## 2. Traceability Matrix

| Business Requirement | Functional Requirement | User Story | Acceptance Criteria | UAT |
|---|---|---|---|---|
| BR-01 Secure customer access | FR-01, FR-02, FR-03 | US-01 | AC-01, AC-02 | UAT-01, UAT-02 |
| BR-02 Knowledge base access | FR-04, FR-05, FR-06 | US-02 | AC-03, AC-04 | UAT-03 |
| BR-03 Support request creation | FR-07, FR-08, FR-09, FR-10 | US-03 | AC-05, AC-06, AC-07 | UAT-04, UAT-05 |
| BR-04 Request tracking | FR-11, FR-12 | US-04 | AC-08, AC-09 | UAT-06 |
| BR-05 Request history | FR-13 | US-05 | AC-10 | UAT-07 |
| BR-06 Customer notifications | FR-14, FR-15, FR-16 | US-06 | AC-11, AC-12 | UAT-08, UAT-09 |
| BR-07 System integration | FR-17, FR-18, FR-19 | US-07 | AC-13, AC-14 | UAT-10 |
| BR-08 Portal reporting | FR-20, FR-21, FR-22 | US-08 | AC-15, AC-16 | UAT-11 |
| BR-09 Access controls | FR-03 | US-09 | AC-17 | UAT-12 |
| BR-10 UAT validation | UAT Requirements | US-10 | AC-18 | UAT-01 to UAT-12 |

---

## 3. Traceability Flow

The project follows the following traceability lifecycle:

```text
Business Requirement
        ↓
Functional Requirement
        ↓
User Story
        ↓
Acceptance Criteria
        ↓
UAT Test Case
        ↓
Business Validation
        ↓
Requirement Sign-Off
4. Requirement Coverage
Area	Coverage
Business Requirements	100% mapped
Functional Requirements	Mapped to business needs
User Stories	Mapped to requirements
Acceptance Criteria	Defined for key functionality
UAT Scenarios	Linked to business requirements
Business Validation	Planned through UAT
5. Change Impact Analysis

When a requirement changes, the RTM can be used to identify affected areas.

For example, if the business introduces a new customer notification requirement, the BA can identify:

Affected business requirement
Functional requirements
User stories
Acceptance criteria
UAT scenarios
Training materials
Project documentation
Potential timeline impact

This allows the project team to understand the full impact of a requirement change.

6. BA Responsibilities

The Business Analyst is responsible for:

Maintaining requirement traceability.
Linking requirements to business objectives.
Ensuring requirements have acceptance criteria.
Supporting UAT coverage.
Identifying gaps in requirement coverage.
Performing change impact analysis.
Updating the RTM when requirements change.
Supporting final requirement validation.
7. RTM Benefits

The RTM helps the project team to:

Prevent missed requirements.
Improve requirement visibility.
Support testing coverage.
Manage requirement changes.
Identify gaps early.
Support stakeholder sign-off.
Demonstrate end-to-end requirement coverage.
