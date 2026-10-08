# Final Incident Report – FinTrust Financial Services Ltd.

## Incident ID

**FINS-IR-001**

## Incident Title

**Suspected Employee Credential Compromise Through Phishing**

## Incident Type

**Phishing / Account Compromise**

## Severity

**High**

## Priority

**P1 – Urgent**

## Status

**Closed**

## Prepared By

**Teniloluwa Alabi**

## Purpose

**Cybersecurity Portfolio / Educational Exercise**

---

## 1. Executive Summary

FinTrust Financial Services Ltd. identified a suspected phishing attack involving an employee account.

The incident began when an employee interacted with a fraudulent phishing communication and potentially submitted their credentials. Subsequent investigation identified unusual authentication activity and an unexpected login location, creating a risk of unauthorized access.

The incident was classified as **High severity / P1 priority** because compromised credentials could potentially provide access to business systems and sensitive information.

The response team initiated containment by restricting the affected account, revoking active sessions, resetting credentials, reviewing authentication controls, and investigating related activity.

The investigation and recovery process followed a structured incident-response lifecycle:

**Detection & Analysis → Containment → Eradication → Recovery → Lessons Learned**

No specific customer data compromise was confirmed within the scope of this simulated exercise.

---

## 2. Incident Overview

### Affected Asset

**Employee Account**

### Potentially Affected Systems

* Corporate email
* Internal business applications
* Cloud services
* Customer-related systems
* Other business resources accessible through the compromised account

### Initial Indicators

* Suspicious phishing email
* Credential submission
* Unusual authentication activity
* Unexpected login location
* Potential unauthorized account access

---

## 3. Incident Classification

| Category              | Assessment                                 |
| --------------------- | ------------------------------------------ |
| Incident Type         | Phishing / Credential Compromise           |
| Severity              | High                                       |
| Priority              | P1 – Urgent                                |
| Status                | Closed                                     |
| Primary Asset         | Employee Account                           |
| Primary Attack Vector | Phishing                                   |
| Potential Impact      | Unauthorized access / information exposure |

The incident was escalated because compromised credentials could potentially allow unauthorized access to business resources.

---

## 4. Detection and Analysis

The investigation focused on determining whether the employee account had been compromised and whether unauthorized activity had occurred.

### Evidence Sources Reviewed

* Authentication logs
* Identity and access management records
* Email security records
* Endpoint security information
* Cloud application logs
* Business application activity

### Investigation Findings

The simulated investigation identified:

* Phishing email confirmed
* Credential submission confirmed
* Unusual authentication activity confirmed
* Unexpected login location confirmed
* Unauthorized access suspected
* Sensitive information compromise not confirmed
* Additional compromised accounts not identified
* Continued attacker activity remained under investigation during the initial response

The account was therefore treated as potentially compromised.

---

## 5. Containment

The following containment actions were initiated:

* Restricted the affected account
* Revoked active sessions
* Reset credentials
* Reviewed MFA configuration
* Restricted suspicious access
* Preserved relevant investigation information
* Reviewed related account activity

The objective was to prevent continued unauthorized access while allowing the investigation to continue.

---

## 6. Eradication

Eradication activities focused on removing conditions that could allow continued unauthorized access.

Actions included:

* Replacing potentially compromised credentials
* Reviewing account configuration
* Removing unauthorized access where identified
* Reviewing related systems
* Investigating potential additional access
* Reviewing authentication controls

The likely root cause was successful phishing and social engineering.

---

## 7. Recovery

Recovery activities included:

* Verifying account security
* Confirming appropriate access permissions
* Restoring legitimate access
* Applying enhanced monitoring
* Reviewing authentication activity
* Monitoring for additional suspicious behavior

Normal operations could resume after the account and associated access controls were verified.

---

## 8. Incident Timeline

| Stage                 | Key Event                                                            |
| --------------------- | -------------------------------------------------------------------- |
| Detection             | Suspicious phishing email identified                                 |
| Investigation         | Credential submission and unusual authentication activity identified |
| Classification        | Incident classified as High / P1                                     |
| Containment           | Account restricted and sessions revoked                              |
| Credential Protection | Credentials reset and MFA reviewed                                   |
| Investigation         | Authentication and security logs reviewed                            |
| Eradication           | Unauthorized access reviewed and removed where identified            |
| Recovery              | Account security verified and access restored                        |
| Monitoring            | Enhanced monitoring applied                                          |
| Review                | Lessons learned and improvement actions documented                   |

---

## 9. Communications

Incident communication followed the principles of:

* Accuracy
* Timeliness
* Relevance
* Consistency
* Authorization
* Need-to-know access

Key stakeholders included:

* Incident Response Lead
* Security Analyst
* IT / Identity Administration
* Management
* Legal / Compliance
* Communications
* Affected Employee
* Senior Leadership

External communication would only be considered if investigation findings established a requirement for notification.

---

## 10. Lessons Learned

The incident identified several security improvement opportunities.

### Security Awareness

Employees should receive regular phishing awareness training and simulated phishing exercises.

### Multi-Factor Authentication

MFA should be consistently enforced for corporate and high-risk accounts.

### Email Security

Email filtering and phishing detection should be strengthened.

### Authentication Monitoring

Unusual authentication patterns should generate timely security alerts.

### Incident Documentation

Incident activities, evidence, decisions, and communications should be documented consistently.

### Incident Response

The organization should regularly test and update its incident-response procedures.

---

## 11. Recommended Preventive Controls

| Control                     | Purpose                                        | Priority |
| --------------------------- | ---------------------------------------------- | -------- |
| Security Awareness Training | Reduce successful phishing attempts            | High     |
| Phishing Simulations        | Test employee readiness                        | High     |
| Multi-Factor Authentication | Reduce credential-based account compromise     | Critical |
| Email Security Controls     | Detect and block malicious messages            | High     |
| Authentication Monitoring   | Detect suspicious account activity             | High     |
| Least Privilege             | Limit potential impact of compromised accounts | High     |
| Access Reviews              | Identify unnecessary access                    | High     |
| Incident Response Exercises | Improve response readiness                     | Medium   |

---

## 12. Business Impact Assessment

A successful account compromise could potentially affect:

### Confidentiality

Unauthorized access could expose internal or customer-related information.

### Integrity

An attacker with sufficient access could potentially modify information or account settings.

### Availability

Security response actions could temporarily restrict access to affected systems or accounts.

### Operations

Investigation and containment could require security, IT, management, and compliance resources.

### Reputation

A confirmed security incident could affect customer trust and organizational reputation.

---

## 13. Risk Reduction

The response activities reduced the potential risk by:

* Restricting the potentially compromised account
* Invalidating active sessions
* Replacing credentials
* Reviewing MFA
* Investigating authentication activity
* Removing unauthorized access where identified
* Applying enhanced monitoring
* Identifying preventive security improvements

---

## 14. Final Assessment

The simulated incident demonstrated the importance of a structured incident-response process when responding to suspected credential compromise.

The response successfully progressed through detection, classification, containment, eradication, recovery, communication, and post-incident review.

The primary areas for improvement are:

1. Phishing awareness
2. MFA enforcement
3. Email security
4. Authentication monitoring
5. Incident documentation
6. Incident-response readiness

These improvements should form part of FinTrust's broader cybersecurity risk-management program.

---

## 15. Skills Demonstrated

This project demonstrates practical knowledge of:

* Incident response
* Incident classification
* Security investigation
* Evidence identification
* Incident containment
* Eradication and recovery
* Incident communication
* Incident timeline development
* Root cause analysis
* Security controls
* Risk management
* Security documentation
* GRC principles
* Business risk communication

---

## Disclaimer

This project is a **fictional cybersecurity portfolio exercise** created for educational and professional demonstration purposes.

It does not represent:

* A real security incident
* A real FinTrust organization
* A penetration test
* A forensic investigation
* A formal compliance audit
* A certified security assessment
* Professional cybersecurity work performed for a client

The project demonstrates the ability to structure and document an incident-response process using a realistic hypothetical scenario.
