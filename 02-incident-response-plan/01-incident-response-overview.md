# 01 – Incident Response Case Overview

## Incident ID

**FINS-IR-001**

## Incident Title

**Suspected Employee Credential Compromise Through Phishing**

## Incident Status

**Under Investigation**

## Incident Type

**Phishing / Account Compromise**

## Severity

**High**

---

## 1. Incident Description

FinTrust Financial Services Ltd. detected suspicious authentication activity involving an employee account.

The activity occurred shortly after the employee received a phishing email requesting account verification through a linked website.

The employee followed the link and entered their credentials. The website was later identified as potentially fraudulent.

Shortly afterward, authentication activity inconsistent with the employee's normal access pattern was detected.

The incident is therefore being treated as a **suspected credential compromise** pending investigation.

---

## 2. Affected Asset

### Primary Asset

**Employee Account**

The affected account provides access to internal business resources and systems.

### Potentially Affected Systems

The investigation will determine whether the compromised credentials were used to access:

* Corporate email
* Internal applications
* Cloud services
* Customer-related systems
* Other business resources

At this stage, unauthorized access to these systems has **not been confirmed**.

---

## 3. Initial Indicators

The following indicators prompted the investigation:

| Indicator              | Observation                                                            |
| ---------------------- | ---------------------------------------------------------------------- |
| Phishing email         | Employee received a suspicious account-verification message            |
| Credential submission  | Employee entered credentials into the linked website                   |
| Unusual authentication | Login activity differed from the employee's normal pattern             |
| Unexpected location    | Authentication originated from an unusual location                     |
| Timing                 | Suspicious authentication occurred shortly after credential submission |

These indicators provide sufficient justification for treating the event as a potential security incident.

---

## 4. Initial Scope

The initial investigation will focus on:

* The affected employee account
* Authentication logs
* Email records
* Cloud-service access logs
* Systems accessed by the account
* Recent account activity
* Potentially affected information
* Similar suspicious activity involving other accounts

The scope will be expanded if evidence indicates that additional accounts or systems may be affected.

---

## 5. Initial Business Impact Assessment

At the beginning of the investigation, the potential impacts include:

### Confidentiality

Unauthorized access could expose internal or sensitive information.

### Integrity

A compromised account could potentially be used to modify information or account settings.

### Availability

The organization may need to temporarily restrict access to affected accounts or systems during containment.

### Business Operations

Security teams and affected employees may need to spend time investigating and responding to the incident.

### Reputation

A confirmed compromise could affect customer confidence in the organization's ability to protect information.

---

## 6. Immediate Investigation Questions

The response team should establish:

1. Was the employee account actually compromised?
2. When did the suspicious activity begin?
3. What IP addresses or locations were associated with the activity?
4. Which systems were accessed?
5. Were any sensitive resources accessed?
6. Were any account settings changed?
7. Did the attacker attempt to access additional accounts?
8. Are other employees targeted by the same phishing campaign?
9. Is there evidence of continued unauthorized access?
10. What actions are required to contain the incident?

---

## 7. Evidence to Review

The investigation should review available security information, including:

* Authentication logs
* Identity and access management records
* Email security logs
* Endpoint security alerts
* Cloud access logs
* Application access logs
* Account activity
* Relevant security alerts

Evidence should be documented carefully throughout the investigation.

---

## 8. Initial Response Decision

Based on the available indicators, the incident should remain classified as a **High-severity suspected credential compromise** while investigation continues.

The priority is to:

1. Protect the affected account.
2. Determine whether unauthorized access occurred.
3. Establish the scope of the incident.
4. Prevent additional compromise.
5. Preserve relevant investigation information.

Further response decisions will depend on evidence collected during the detection and analysis phase.

---

## 9. Next Response Stage

The next stage of the investigation is **Incident Classification**, where the response team will formally assess the incident category, severity, priority, and potential business impact.
