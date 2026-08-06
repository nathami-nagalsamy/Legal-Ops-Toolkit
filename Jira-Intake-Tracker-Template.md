# Legal Intake Tracker (Jira Structure)

Tracks legal requests from submission through resolution — built to
monitor volume, turnaround time, and ownership across a legal team.

| Field | Purpose |
|---|---|
| Request ID | Unique ticket number |
| Requestor / Department | Who submitted it |
| Request Type | NDA, Vendor Agreement, Employment, Finance, etc. |
| Date Submitted | Intake timestamp |
| Assigned Attorney | Ownership |
| Priority | Standard / Urgent |
| Status | Intake → In Review → Approval → Executed |
| Days Open | Auto-calculated aging |
| Resolution Date | When closed |

## Example Row
| REQ-1042 | Sales Team | Vendor Agreement | 2026-01-15 | N. Nagalsamy | Standard | In Review | 4 | — |
