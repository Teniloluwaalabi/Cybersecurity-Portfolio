# Control Assessment – FinTrust Financial Services Ltd.

## 1. Purpose

This document evaluates selected information-security controls within FinTrust Financial Services Ltd.

The assessment determines whether each control is **Effective, Partially Effective, Needs Improvement, or Not Implemented**, based on the fictional organization's current security posture.

> **Disclaimer:** This is a fictional cybersecurity portfolio exercise. The findings are hypothetical and do not represent a formal audit or certification assessment.

---

## 2. Control Assessment Summary

| Control Area | Control | Assessment | Risk |
|---|---|---|---|
| Asset Management | Maintain an inventory of critical information assets | Effective | Low |
| Access Control | Enforce least privilege | Partially Effective | High |
| Authentication | Multi-factor authentication | Partially Effective | Critical |
| Security Awareness | Employee security awareness training | Needs Improvement | High |
| Vulnerability Management | Regular patch management | Needs Improvement | High |
| Data Protection | Encryption of sensitive information | Partially Effective | High |
| Incident Response | Documented incident response procedures | Effective | Medium |
| Security Monitoring | Centralized security logging and monitoring | Needs Improvement | High |
| Third-Party Risk | Vendor security assessments | Needs Improvement | High |
| Business Continuity | Tested backup and recovery procedures | Partially Effective | High |
| Security Governance | Information-security policies | Partially Effective | Medium |

---

## 3. Detailed Control Assessment

### 3.1 Asset Management

**Control:** Maintain an inventory of critical information assets.

**Assessment:** Effective

FinTrust maintains an inventory covering important assets such as customer databases, banking applications, employee devices, cloud infrastructure, payment systems, and backup systems.

**Observation:**

The organization has established visibility into its major information assets.

**Recommendation:**

Review and update the asset inventory periodically and whenever significant systems or services are introduced or retired.

---

### 3.2 Access Control

**Control:** Enforce least privilege and conduct regular access reviews.

**Assessment:** Partially Effective

Access controls exist, but excessive privileges and inconsistent access reviews represent potential risks.

**Risk:**

Compromised or misused accounts could access more information than required for normal job responsibilities.

**Recommendation:**

- Conduct periodic access reviews.
- Remove unnecessary privileges.
- Apply least-privilege principles.
- Review privileged accounts more frequently.

---

### 3.3 Authentication

**Control:** Multi-factor authentication for employee and high-risk accounts.

**Assessment:** Partially Effective

MFA is available but requires broader and more consistent enforcement.

**Risk:**

Stolen credentials could potentially be used to gain unauthorized access.

**Recommendation:**

- Enforce MFA across corporate accounts.
- Prioritize privileged accounts.
- Monitor suspicious authentication activity.
- Review authentication exceptions regularly.

---

### 3.4 Security Awareness

**Control:** Employee security awareness and phishing training.

**Assessment:** Needs Improvement

The simulated phishing incident demonstrates that employees may remain vulnerable to social-engineering attacks.

**Risk:**

Successful phishing could result in credential compromise or unauthorized access.

**Recommendation:**

- Conduct regular security awareness training.
- Run controlled phishing simulations.
- Establish clear phishing-reporting procedures.
- Provide additional training based on identified weaknesses.

---

### 3.5 Vulnerability Management

**Control:** Regular identification and remediation of vulnerabilities.

**Assessment:** Needs Improvement

The previous risk assessment identified unpatched software as a significant security weakness.

**Risk:**

Unpatched systems may expose the organization to known security vulnerabilities.

**Recommendation:**

- Establish a documented patch-management process.
- Prioritize critical vulnerabilities.
- Track remediation deadlines.
- Maintain records of patching activities.

---

### 3.6 Data Protection

**Control:** Protect sensitive information through encryption and access restrictions.

**Assessment:** Partially Effective

Data-protection controls exist, but access management and encryption practices require continued monitoring.

**Risk:**

Unauthorized access could expose sensitive customer or financial information.

**Recommendation:**

- Encrypt sensitive information in storage and transit.
- Review access permissions regularly.
- Apply appropriate data-classification practices.
- Monitor access to sensitive information.

---

### 3.7 Incident Response

**Control:** Maintain documented incident-response procedures.

**Assessment:** Effective

FinTrust has a structured incident-response process covering detection, classification, containment, eradication, recovery, communication, and lessons learned.

**Observation:**

The incident-response plan provides a documented structure for managing security incidents.

**Recommendation:**

Conduct periodic tabletop exercises and update procedures based on lessons learned.

---

### 3.8 Security Monitoring

**Control:** Centralized logging and continuous security monitoring.

**Assessment:** Needs Improvement

Security logs are available from multiple systems, but monitoring and centralized analysis require improvement.

**Risk:**

Delayed detection could increase the impact of security incidents.

**Recommendation:**

- Centralize important security logs.
- Establish monitoring responsibilities.
- Create alerts for high-risk events.
- Define log-retention requirements.
- Review security alerts regularly.

---

### 3.9 Third-Party Risk

**Control:** Security assessment of vendors and service providers.

**Assessment:** Needs Improvement

Vendor security reviews are not consistently established across all third parties.

**Risk:**

A compromised or poorly secured third-party provider could introduce security risks to FinTrust.

**Recommendation:**

- Perform vendor security assessments.
- Classify vendors according to risk.
- Include security requirements in contracts.
- Conduct periodic vendor reviews.

---

### 3.10 Business Continuity

**Control:** Maintain and test backup and recovery procedures.

**Assessment:** Partially Effective

Backup capabilities exist, but regular testing and documented recovery procedures require improvement.

**Risk:**

A major security incident or system failure could disrupt critical business services.

**Recommendation:**

- Maintain encrypted backups.
- Test backups regularly.
- Document recovery procedures.
- Establish recovery priorities for critical systems.

---

### 3.11 Security Governance

**Control:** Maintain documented information-security policies and responsibilities.

**Assessment:** Partially Effective

Security policies and responsibilities exist but require regular review and stronger governance oversight.

**Risk:**

Unclear responsibilities or outdated policies may reduce the effectiveness of security controls.

**Recommendation:**

- Review policies periodically.
- Assign clear control owners.
- Establish management oversight.
- Track policy acknowledgements.
- Document exceptions and approvals.

---

## 4. Overall Control Assessment

The assessment indicates that FinTrust has several important security controls in place, but a number of controls require improvement.

The highest-priority areas are:

1. Multi-factor authentication
2. Security awareness
3. Vulnerability management
4. Security monitoring
5. Third-party risk management
6. Access control

These areas should receive priority during remediation planning.

---

## 5. Overall Assessment Rating

**Overall Control Maturity: Partially Effective**

The organization has established several foundational security controls, but improvements are required to achieve stronger and more consistent security governance.

---

## Skills Demonstrated

- Security control assessment
- Control effectiveness evaluation
- Risk identification
- GRC analysis
- Access control assessment
- Security governance
- Vulnerability management
- Third-party risk assessment
- Business continuity assessment
- Security monitoring assessment
