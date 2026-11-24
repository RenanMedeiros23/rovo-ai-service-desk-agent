# SLA Monitoring and Risk Assessment

## SLA Objectives

- Monitor Time to First Response.
- Monitor Time to Resolution.
- Identify incidents at risk of SLA breaches.
- Recommend preventive actions and escalation.

## Risk Classification

| SLA Time Consumed | Risk Level |
|---|---|
| Below 70% | Normal |
| 70% to below 90% | Warning |
| 90% to below 100% | Critical |
| 100% or above without fulfillment | Breach risk — verify Jira status |

## Recommended Actions

### Normal
Continue monitoring and incident investigation.

### Warning
Notify the responsible agent and review the remaining time.

### Critical
Recommend immediate escalation and notify the appropriate stakeholders.

### Breached
Document the SLA breach, notify the responsible team, and continue working toward service restoration.

## Operational Rules

- Respect configured SLA calendars and business hours.
- Consider SLA start, pause, and stop conditions.
- Distinguish first-response SLAs from resolution SLAs.
- Use actual SLA data from Jira Service Management when available.
- Never invent SLA targets or remaining time.
- Never promise an unconfirmed resolution deadline.
- Request missing information when SLA data is unavailable.
- Require human approval before modifying tickets or sending notifications.

## Expected Output

- Incident ID
- SLA type
- SLA target
- Remaining time
- Current SLA status
- Risk level
- Recommended action
