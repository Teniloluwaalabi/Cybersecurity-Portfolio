# 02 – Incident Classification

## Incident ID

**FINS-IR-001**

## Incident Type

**Phishing / Credential Compromise**

## Initial Severity

**High**

## Priority

**P1 – Urgent**

---

## 1. Incident Classification

The incident is classified as a **phishing-related credential compromise** because an employee entered their credentials into a suspected fraudulent website and suspicious authentication activity was subsequently detected.

The compromise is considered **suspected rather than confirmed** until investigation establishes whether unauthorized access actually occurred.

---

## 2. Severity Assessment

Severity is based on the potential effect of the incident on:

* Confidentiality
* Integrity
* Availability
* Business operations
* Customer trust

| Factor              | Assessment       | Rationale                                                                                             |
| ------------------- | ---------------- | ----------------------------------------------------------------------------------------------------- |
| Confidentiality     | High             | Compromised credentials could provide unauthorized access to sensitive information                    |
| Integrity           | Medium           | An attacker could potentially modify account or system information                                    |
| Availability        | Medium           | Containment activities could temporarily restrict access                                              |
| Business Operations | High             | Investigation and containment could disrupt normal operations                                         |
| Customer Impact     | Potentially High | The affected account may have access to systems containing sensitive business or customer information |

### Overall Severity: **High**

The incident is classified as High because the compromised credentials could potentially provide access to sensitive organizational resources.

---

## 3. Priority Assessment

The incident is assigned **P1 – Urgent** because immediate action is required to determine whether unauthorized access is occurring and prevent further compromise.

Priority factors include:

* Suspected credential compromise
* Suspicious authentication activity
* Potential access to internal systems
* Possibility of continued unauthorized access
* Potential exposure of sensitive information

---

## 4. Classification Criteria

The following classification model is used for this exercise:

| Severity | Description                                                                   |
| -------- | ----------------------------------------------------------------------------- |
| Critical | Confirmed or suspected incident with severe organizational or customer impact |
| High     | Significant potential impact requiring urgent investigation and response      |
| Medium   | Limited or contained impact requiring timely investigation                    |
| Low      | Minimal impact with limited security implications                             |

Under this model, the current incident meets the **High** severity threshold.

---

## 5. Escalation Requirements

Because this is a High-severity incident, the response should be escalated to the appropriate security and management personnel.

The response team should consider escalation if:

* Unauthorized access is confirmed
* Sensitive information is accessed
* Additional accounts are compromised
* The attacker maintains access
* Evidence indicates lateral movement
* Customer-facing systems are affected
* Regulatory or contractual obligations may be triggered

---

## 6. Classification Decision

**Incident:** FINS-IR-001
**Category:** Phishing / Credential Compromise
**Severity:** High
**Priority:** P1 – Urgent
**Status:** Under Investigation

The incident should proceed to the **Detection and Analysis** stage.

The classification may be revised if new evidence changes the assessed scope or impact.

---

## 7. Next Response Stage

The next stage is **Detection and Analysis**, where investigators will examine available evidence to determine what happened, what systems were accessed, and whether unauthorized activity occurred.
