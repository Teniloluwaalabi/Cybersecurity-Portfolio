# 06 – Eradication and Recovery

## Incident ID

**FINS-IR-001**

## Response Stage

**Eradication and Recovery**

## Objective

The objective of this stage is to remove the conditions that allowed the suspected compromise to occur, eliminate unauthorized access, and safely restore normal operations.

Eradication should only begin after sufficient evidence has been collected and containment has been verified.

---

## 1. Eradication Actions

### 1.1 Remove Compromised Credentials

The affected credentials should be permanently invalidated and replaced through the organization's approved identity-management process.

### 1.2 Review Account Configuration

The response team should review the affected account for:

* Unexpected permission changes
* Unauthorized MFA changes
* Suspicious recovery methods
* Unrecognized sessions
* Unexpected application access
* Other account configuration changes

Any unauthorized changes should be removed.

### 1.3 Remove Unauthorized Access

Any unauthorized sessions, access tokens, or other identified mechanisms that could allow continued access should be revoked.

### 1.4 Investigate Related Systems

Systems accessed by the affected account should be reviewed for evidence of unauthorized activity.

If additional compromise is identified, the affected systems should be handled according to the organization's incident-response procedures.

---

## 2. Addressing the Root Cause

The immediate technical issue is suspected credential compromise through phishing.

The organization should therefore address both the compromised account and the underlying security weakness.

Recommended improvements include:

* Strengthening phishing awareness training
* Improving email filtering
* Reinforcing MFA adoption
* Reviewing authentication monitoring
* Improving suspicious-login detection
* Conducting targeted security awareness exercises

---

## 3. Recovery Actions

Once eradication is complete, normal operations can begin to resume.

Recovery activities include:

1. Confirm that unauthorized access has been removed.
2. Confirm that the affected account is secure.
3. Restore legitimate employee access.
4. Verify MFA configuration.
5. Review relevant systems for abnormal activity.
6. Continue enhanced monitoring.
7. Confirm that required security controls are functioning.
8. Document the recovery process.

---

## 4. Recovery Verification

Before considering the incident resolved, the response team should verify:

| Verification                        | Status   |
| ----------------------------------- | -------- |
| Compromised credentials invalidated | Required |
| Unauthorized sessions revoked       | Required |
| MFA configuration reviewed          | Required |
| Account permissions reviewed        | Required |
| Related systems investigated        | Required |
| Suspicious activity monitored       | Required |
| Legitimate access restored          | Required |
| Security controls reviewed          | Required |

The incident should not be formally closed until the response team has sufficient evidence that the threat has been addressed.

---

## 5. Enhanced Monitoring

Following recovery, the affected account and related systems should receive increased monitoring for a defined period.

Monitoring should focus on:

* Unusual authentication
* Repeated failed login attempts
* Unexpected locations
* New devices
* Unusual application access
* Suspicious account changes
* Similar phishing activity

The purpose is to identify any continued or recurring suspicious activity.

---

## 6. Return to Normal Operations

Normal operations may resume when:

* The affected account is secure.
* Unauthorized access has been removed.
* Investigation has reached an appropriate conclusion.
* Required recovery actions are complete.
* Security monitoring is active.
* Relevant stakeholders have been informed.
* No unresolved critical indicators remain.

---

## 7. Recovery Outcome

For this exercise, the expected recovery outcome is:

**Account secured → Unauthorized access removed → Systems reviewed → Legitimate access restored → Enhanced monitoring activated**

The incident can then progress to the **Lessons Learned** phase after the required documentation and communications have been completed.

---

## 8. Next Response Stage

The next stage is **Communications and Incident Notification**.

The organization must ensure that appropriate stakeholders receive accurate and timely information while avoiding unnecessary disclosure of sensitive incident details.
