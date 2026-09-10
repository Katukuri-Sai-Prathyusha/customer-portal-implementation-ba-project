# 06 - RAID Log

## Project

Customer Portal Implementation & Digital Transformation

## 1. What is RAID?

RAID is used to track important project items throughout the project lifecycle.

- **R - Risks:** Potential events that may negatively affect the project.
- **A - Assumptions:** Conditions assumed to be true for project planning.
- **I - Issues:** Problems that have already occurred.
- **D - Dependencies:** External activities or deliverables required for project progress.

---

# 2. Risk Log

| ID | Risk | Probability | Impact | Mitigation | Owner | Status |
|---|---|---|---|---|---|---|
| R-01 | CRM integration may be delayed | Medium | High | Confirm integration dependencies early | Technical Lead | Open |
| R-02 | Requirements may change during development | Medium | High | Use formal change control | BA / PM | Open |
| R-03 | UAT may be delayed due to business user availability | Medium | High | Schedule UAT resources in advance | BA | Open |
| R-04 | Customer adoption may be lower than expected | Medium | High | Provide training and communication | Product | Open |
| R-05 | Security approval may take longer than planned | Low | High | Engage security team early | IT / Security | Open |
| R-06 | Data migration may contain incorrect information | Medium | High | Perform data validation and reconciliation | IT | Open |

---

# 3. Assumption Log

| ID | Assumption | Impact if Incorrect | Owner | Status |
|---|---|---|---|---|
| A-01 | Existing customer data is available for integration | High | IT | Open |
| A-02 | Business stakeholders will be available for workshops | Medium | PM | Open |
| A-03 | UAT users will be available during Week 10 | High | BA | Open |
| A-04 | Required infrastructure will be available before deployment | High | IT | Open |
| A-05 | Knowledge base content is ready for migration | Medium | Support | Open |
| A-06 | Security requirements can be completed within the planned timeline | High | Security | Open |

---

# 4. Issue Log

Issues represent problems that have already occurred.

| ID | Issue | Impact | Priority | Action | Owner | Status |
|---|---|---|---|---|---|---|
| I-01 | Sample knowledge articles contain incomplete information | Medium | Medium | Review and update content | Support | Open |
| I-02 | Some portal requirements require additional clarification | Medium | Medium | Conduct requirement workshop | BA | Open |
| I-03 | Integration field mapping requires business confirmation | High | High | Schedule mapping review | BA / IT | Open |

---

# 5. Dependency Log

| ID | Dependency | Dependency Type | Impact | Owner | Status |
|---|---|---|---|---|---|
| D-01 | CRM integration | Technical | High | IT | Open |
| D-02 | Customer database access | Technical | High | IT | Open |
| D-03 | Knowledge base content | Business | Medium | Support | Open |
| D-04 | Security approval | Governance | High | Security | Open |
| D-05 | UAT environment | Technical | High | QA / IT | Open |
| D-06 | Business user availability | Business | High | Business | Open |

---

# 6. RAID Review Process

The RAID log will be reviewed during regular project status meetings.

The Project Manager will:

- Review new risks and issues.
- Assign owners.
- Track mitigation actions.
- Monitor dependencies.
- Escalate high-impact items.
- Update item status.

The Business Analyst will support the RAID process by:

- Identifying requirement-related risks.
- Identifying requirement dependencies.
- Assessing business impact.
- Supporting issue clarification.
- Performing change impact analysis.
- Communicating requirement-related risks to stakeholders.

---

# 7. Escalation Criteria

An item should be escalated when:

- It has a high business impact.
- It threatens a major milestone.
- It affects project scope.
- It may cause significant timeline delays.
- It requires a decision from senior stakeholders.
- The assigned owner cannot resolve the item within the agreed timeframe.

---

# 8. RAID Status Definitions

| Status | Meaning |
|---|---|
| Open | Item requires action |
| In Progress | Action is currently being performed |
| Blocked | Progress cannot continue |
| Escalated | Item requires senior decision |
| Resolved | Action completed |
| Closed | Item formally completed |
