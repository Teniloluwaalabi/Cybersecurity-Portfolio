# 07 – Incident Communications Plan

## Incident ID

**FINS-IR-001**

## Purpose

This document defines how information about the suspected phishing-related credential compromise should be communicated during the incident.

The objective is to ensure that the right stakeholders receive accurate information at the appropriate time while protecting sensitive incident details.

---

## 1. Communication Principles

Incident communications should be:

* Accurate
* Timely
* Relevant
* Consistent
* Appropriately authorized
* Limited to information necessary for the recipient

The response team should avoid speculation and clearly distinguish confirmed findings from information that remains under investigation.

---

## 2. Internal Stakeholders

| Stakeholder            | Information Required                             | Timing                           |
| ---------------------- | ------------------------------------------------ | -------------------------------- |
| Incident Response Team | Technical findings and response actions          | Throughout incident              |
| IT / Identity Team     | Account and access-related findings              | Immediately when relevant        |
| Management             | Business impact and response status              | At significant milestones        |
| Legal / Compliance     | Potential regulatory or contractual implications | When relevant                    |
| Affected Employee      | Required actions and account status              | As needed                        |
| Senior Leadership      | Significant business or security impact          | When escalation criteria are met |

---

## 3. Communication Responsibilities

### Incident Response Lead

Responsible for coordinating incident-related communication and ensuring that significant updates are documented.

### Security Analyst

Provides technical findings and investigation updates to the response team.

### IT / Identity Administrator

Communicates account and access-related actions to the appropriate response personnel.

### Management Representative

Provides business-level decisions and approves significant operational actions where required.

### Legal / Compliance Representative

Provides guidance concerning legal, regulatory, contractual, or notification considerations.

### Communications Representative

Coordinates approved organizational messaging and ensures that communications follow established processes.

---

## 4. Incident Status Updates

Status updates should communicate:

* Current incident status
* Confirmed findings
* Actions completed
* Actions currently underway
* Potential business impact
* Outstanding investigation questions
* Required decisions
* Next response milestone

Updates should avoid including unnecessary sensitive information.

---

## 5. Example Internal Status Update

**Incident ID:** FINS-IR-001
**Status:** Containment in Progress
**Severity:** High
**Priority:** P1 – Urgent

A suspected phishing-related credential compromise involving an employee account has been identified.

The affected account has been placed under containment while authentication activity and related systems are being investigated.

At this stage:

* Credential compromise is suspected.
* Suspicious authentication activity has been identified.
* The investigation is ongoing.
* No confirmed customer data exposure has been established.
* Relevant security information is being reviewed.

Further updates will be provided as significant findings become available.

---

## 6. External Communications

External communication should only occur when authorized by the appropriate organizational stakeholders.

Potential external stakeholders may include:

* Customers
* Business partners
* Service providers
* Regulators
* Contractual partners

Whether notification is required depends on the confirmed facts, applicable obligations, and guidance from the organization's legal and compliance functions.

No external notification should be assumed solely because an incident has been detected.

---

## 7. Customer Communication Considerations

If investigation confirms that customer information was accessed or exposed, the organization should evaluate whether customer notification is appropriate.

Any customer-facing communication should:

* Provide confirmed information
* Explain relevant actions taken
* Avoid unnecessary technical detail
* Provide appropriate guidance to affected customers
* Follow applicable legal and regulatory requirements

---

## 8. Escalation Triggers

Communication should be escalated when:

* Unauthorized access is confirmed
* Sensitive information may have been accessed
* Additional accounts become affected
* Customer-facing systems are impacted
* The incident expands beyond its original scope
* Regulatory or contractual notification requirements may apply
* Significant business disruption occurs

---

## 9. Communication Record

Significant incident communications should be recorded.

| Time | Recipient/Group        | Communication                  | Sender  | Status    |
| ---- | ---------------------- | ------------------------------ | ------- | --------- |
| T+0  | Incident Response Team | Initial incident notification  | IR Lead | Completed |
| T+1  | IT / Identity Team     | Account containment request    | IR Lead | Completed |
| T+2  | Management             | Initial business impact update | IR Lead | Pending   |
| T+3  | Legal / Compliance     | Potential compliance review    | IR Lead | Pending   |
| T+4  | Relevant stakeholders  | Investigation update           | IR Lead | Pending   |

The actual timestamps would be populated as the incident progresses.

---

## 10. Communication Outcome

The communication process should ensure that:

**Technical teams receive actionable information → Management understands business impact → Compliance stakeholders can assess obligations → Approved communications reach affected parties when necessary.**

This supports coordinated incident response while reducing the risk of inaccurate or unauthorized disclosure.

---

## 11. Next Response Stage

The next document will establish the **Incident Timeline**, providing a chronological record of the suspected phishing event and the organization's response activities.
