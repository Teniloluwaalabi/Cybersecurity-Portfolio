# 04 – Detection and Analysis

## Incident ID

**FINS-IR-001**

## Investigation Stage

**Detection and Analysis**

---

## 1. Investigation Objective

The purpose of this stage is to determine whether the suspected phishing event resulted in unauthorized access, establish the scope of the incident, and identify any systems or information that may have been affected.

The investigation should be evidence-based. Suspicious activity should be documented before conclusions are made.

---

## 2. Initial Evidence

The investigation begins with the following known information:

| Evidence                | Finding                                                     |
| ----------------------- | ----------------------------------------------------------- |
| Phishing email          | Employee received a suspicious account-verification message |
| Credential submission   | Employee entered credentials into the linked website        |
| Authentication activity | Unusual login activity occurred afterward                   |
| Login location          | Activity originated from an unexpected location             |
| Timing                  | Suspicious authentication followed the phishing event       |
| Account                 | One employee account is currently suspected to be affected  |

At this stage, unauthorized access to internal systems has **not been confirmed**.

---

## 3. Investigation Questions

The response team should answer the following questions:

1. When was the phishing email received?
2. When did the employee interact with the message?
3. When were credentials submitted?
4. When did suspicious authentication begin?
5. What IP addresses were associated with the activity?
6. What geographic locations were associated with the logins?
7. Which applications or systems were accessed?
8. Were successful logins recorded?
9. Were there failed login attempts before or after the successful login?
10. Were account settings changed?
11. Was MFA enabled and did any MFA events occur?
12. Was sensitive information accessed?
13. Did the account attempt to access other systems?
14. Are other employees receiving similar phishing messages?

---

## 4. Evidence Sources

The following sources should be reviewed where available:

### Identity and Authentication Logs

Review:

* Successful login events
* Failed authentication attempts
* Login locations
* IP addresses
* Device information
* MFA events
* Session activity

### Email Security Logs

Review:

* Sender information
* Message timestamps
* Links contained in the email
* Delivery records
* Similar messages sent to other employees

### Endpoint Security Information

Review:

* Security alerts
* Suspicious processes
* Browser activity where available
* Malware detections
* Endpoint communication with suspicious destinations

### Cloud and Application Logs

Review:

* Account access
* File or resource access
* Administrative actions
* Permission changes
* Unusual application activity

---

## 5. Example Investigation Findings

For this portfolio exercise, the investigation produces the following hypothetical findings:

| Finding                                   | Assessment          |
| ----------------------------------------- | ------------------- |
| Employee received phishing email          | Confirmed           |
| Employee submitted credentials            | Confirmed           |
| Unusual authentication occurred afterward | Confirmed           |
| Authentication from unexpected location   | Confirmed           |
| Unauthorized account access               | Suspected           |
| Access to sensitive information           | Not yet confirmed   |
| Additional compromised accounts           | Not identified      |
| Continued attacker activity               | Under investigation |

These findings indicate that the account should be treated as potentially compromised while investigation continues.

---

## 6. Preliminary Timeline

The initial sequence of events is:

**Event 1:** Employee receives suspicious email.

**Event 2:** Employee follows the link contained in the message.

**Event 3:** Employee enters credentials into the suspected phishing website.

**Event 4:** Unusual authentication activity is detected.

**Event 5:** Security team begins investigation.

**Event 6:** Incident is classified as High severity and P1 priority.

**Event 7:** Response team begins containment planning.

The detailed timeline will be documented separately in the **Incident Timeline** section.

---

## 7. Indicators of Potential Compromise

The following indicators require further investigation:

* Unexpected authentication location
* Unusual login timing
* Authentication activity following credential submission
* Potentially unfamiliar device or session
* Phishing infrastructure associated with the original email

These indicators do not independently prove compromise but collectively justify treating the account as potentially compromised.

---

## 8. Scope Assessment

The current scope is limited to:

* One employee account
* The associated authentication activity
* The suspected phishing email
* Systems accessible through the affected account

No evidence has yet established compromise of additional accounts or systems.

The investigation should continue until sufficient evidence exists to determine whether the incident is isolated or part of a broader campaign.

---

## 9. Analysis Conclusion

The available evidence establishes a credible relationship between the phishing event and subsequent suspicious authentication activity.

The employee account should therefore be treated as **potentially compromised**.

However, the investigation has not established that sensitive information was accessed or that additional systems were compromised.

The incident should proceed to **Containment** while investigation continues.

---

## 10. Next Response Stage

The next stage is **Containment**.

The response team must take appropriate steps to prevent further unauthorized access while preserving relevant investigation information.
