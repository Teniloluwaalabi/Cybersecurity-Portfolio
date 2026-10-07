# 03 – Incident Response Team

## Incident ID

**FINS-IR-001**

## Purpose

This document defines the roles and responsibilities involved in responding to the suspected phishing-related credential compromise at FinTrust Financial Services Ltd.

The response structure is designed to establish clear ownership, support timely decision-making, and prevent confusion during the investigation.

---

## 1. Incident Response Structure

The response team consists of the following functional roles:

| Role                              | Primary Responsibility                                             |
| --------------------------------- | ------------------------------------------------------------------ |
| Incident Response Lead            | Coordinates the overall response                                   |
| Security Analyst                  | Investigates alerts, logs, and indicators                          |
| IT / Identity Administrator       | Secures affected accounts and systems                              |
| Management Representative         | Makes business-impact and escalation decisions                     |
| Legal / Compliance Representative | Assesses legal, regulatory, and contractual considerations         |
| Communications Representative     | Coordinates approved internal and external communications          |
| Affected Employee                 | Provides information about the phishing event and account activity |

---

## 2. Incident Response Lead

The Incident Response Lead coordinates the response from detection through recovery.

### Responsibilities

* Coordinate investigation activities
* Assign response tasks
* Maintain awareness of incident status
* Ensure actions are documented
* Coordinate communication between response teams
* Escalate significant developments
* Approve progression between response stages
* Coordinate the final incident review

The Incident Response Lead serves as the central point of coordination during the incident.

---

## 3. Security Analyst

The Security Analyst performs the primary technical investigation.

### Responsibilities

* Review security alerts
* Analyze authentication activity
* Review relevant logs
* Identify indicators of compromise
* Determine potentially affected systems
* Establish the incident timeline
* Document investigation findings
* Provide technical recommendations to the response lead

The Security Analyst should preserve relevant evidence and avoid making unsupported conclusions during the investigation.

---

## 4. IT / Identity Administrator

The IT or Identity Administrator is responsible for protecting affected accounts and systems.

### Responsibilities

* Restrict or disable the affected account when authorized
* Reset compromised credentials
* Review authentication settings
* Revoke active sessions where appropriate
* Verify MFA configuration
* Review access permissions
* Support restoration of normal account access
* Implement required technical changes

Actions should be coordinated with the Incident Response Lead and documented.

---

## 5. Management Representative

Management provides business oversight and decision-making support.

### Responsibilities

* Assess business impact
* Approve significant operational decisions
* Support resource allocation
* Determine whether senior leadership should be notified
* Support decisions involving customer-facing services
* Review major response risks

Management should rely on documented findings from the response team when making decisions.

---

## 6. Legal / Compliance Representative

The Legal or Compliance Representative evaluates whether the incident may create legal, regulatory, contractual, or reporting obligations.

### Responsibilities

* Assess potential compliance implications
* Review contractual notification requirements
* Advise on required documentation
* Determine whether additional legal review is necessary
* Coordinate with relevant stakeholders when notification requirements are identified

This role does not determine technical severity but provides guidance on legal and compliance considerations.

---

## 7. Communications Representative

The Communications Representative coordinates approved communications related to the incident.

### Responsibilities

* Prepare internal communications
* Coordinate approved external communications
* Ensure messaging is consistent and accurate
* Prevent unauthorized disclosure of incident information
* Maintain records of significant communications

Communications should be based on confirmed information and approved through the appropriate organizational process.

---

## 8. Affected Employee

The affected employee provides information that may help establish how the incident occurred.

### Responsibilities

* Report the suspicious email
* Provide relevant information about the phishing message
* Identify actions taken after receiving the message
* Cooperate with the investigation
* Follow security instructions from the response team

The affected employee should not attempt to independently investigate or delete potentially relevant information unless instructed to do so.

---

## 9. Responsibility Matrix

| Activity                   | IR Lead | Security | IT/IAM | Management | Legal/Compliance | Communications |
| -------------------------- | ------- | -------- | ------ | ---------- | ---------------- | -------------- |
| Incident coordination      | A       | C        | C      | I          | I                | I              |
| Technical investigation    | A       | R        | C      | I          | I                | I              |
| Account containment        | A       | C        | R      | I          | I                | I              |
| Evidence documentation     | A       | R        | C      | I          | C                | I              |
| Business impact assessment | C       | C        | C      | A/R        | C                | I              |
| Compliance assessment      | C       | C        | I      | C          | A/R              | I              |
| Internal communications    | A       | C        | I      | C          | C                | R              |
| External communications    | A       | C        | I      | A          | C                | R              |
| Recovery coordination      | A       | C        | R      | C          | I                | I              |
| Lessons learned            | A/R     | R        | C      | C          | C                | C              |

**R = Responsible**
**A = Accountable**
**C = Consulted**
**I = Informed**

---

## 10. Escalation

The Incident Response Lead should escalate the incident when:

* Unauthorized access is confirmed
* Sensitive information may have been accessed
* Additional accounts are compromised
* The incident expands beyond the original scope
* Customer-facing systems are affected
* Regulatory or contractual obligations may apply
* The incident creates significant business disruption

---

## 11. Next Response Stage

With response responsibilities established, the next stage is **Detection and Analysis**.

The Security Analyst and Incident Response Lead will review available evidence to determine the actual scope and impact of the suspected compromise.
