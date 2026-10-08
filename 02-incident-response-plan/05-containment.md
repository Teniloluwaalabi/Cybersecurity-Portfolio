# 05 – Containment

## Incident ID

**FINS-IR-001**

## Response Stage

**Containment**

## Objective

The objective of containment is to prevent further unauthorized access while preserving relevant information needed for the investigation.

Because the employee account is suspected to be compromised, containment should prioritize the affected identity and any systems that may have been accessed.

---

## 1. Immediate Containment Actions

### 1.1 Restrict the Affected Account

Temporarily suspend or restrict the affected employee account to prevent additional unauthorized authentication.

### 1.2 Revoke Active Sessions

Terminate active sessions associated with the affected account where appropriate.

This reduces the possibility that an attacker could continue using an already-authenticated session.

### 1.3 Reset Credentials

Reset the affected account's credentials through the organization's approved identity-management process.

### 1.4 Review MFA

Verify that multi-factor authentication remains correctly configured and investigate any unexpected MFA activity.

### 1.5 Restrict Suspicious Access

Block or restrict suspicious authentication sources where sufficient evidence exists to justify the action.

---

## 2. Investigation Preservation

Containment actions should not unnecessarily destroy evidence.

Before or during containment, the response team should document:

* Relevant authentication events
* Suspicious IP addresses
* Login timestamps
* Device information
* Account activity
* Security alerts
* Relevant email information
* Actions taken during containment

All significant actions should be recorded in the incident log.

---

## 3. Short-Term Containment

The following short-term actions should be completed as soon as practical:

| Action                    | Purpose                                     |
| ------------------------- | ------------------------------------------- |
| Restrict affected account | Prevent further unauthorized access         |
| Revoke active sessions    | Remove potentially compromised sessions     |
| Reset credentials         | Invalidate exposed credentials              |
| Review MFA                | Identify suspicious authentication activity |
| Review recent access      | Determine potential exposure                |
| Monitor account activity  | Detect continued attempts                   |
| Preserve relevant logs    | Support investigation                       |

---

## 4. Extended Containment

If investigation identifies additional affected systems or accounts, the response team should consider:

* Restricting additional compromised accounts
* Increasing authentication monitoring
* Blocking confirmed malicious infrastructure
* Restricting access to affected applications
* Isolating affected endpoints where appropriate
* Reviewing privileged access
* Expanding the investigation to related accounts

Additional containment should be based on evidence rather than assumptions.

---

## 5. Business Considerations

Containment actions can affect normal business operations.

For example, temporarily disabling an employee account may prevent the employee from accessing business applications.

The Incident Response Lead and Management Representative should therefore balance:

**Security Risk**

against

**Operational Impact**

The organization should prioritize preventing further compromise while restoring legitimate access as soon as it is safe to do so.

---

## 6. Containment Verification

After containment actions are completed, the response team should verify:

* The affected account can no longer authenticate using compromised credentials.
* Active sessions have been revoked where required.
* MFA configuration is secure.
* Suspicious authentication activity has stopped or significantly decreased.
* No additional affected accounts have been identified.
* Relevant evidence has been preserved.
* Monitoring remains active.

---

## 7. Containment Status

**Status: Containment Actions Initiated**

The affected account is treated as potentially compromised and appropriate access restrictions are being applied.

The incident should remain under investigation until the response team determines whether unauthorized access occurred and whether additional systems or accounts were affected.

---

## 8. Next Response Stage

Once containment is verified, the response moves to **Eradication and Recovery**.

The objective will be to remove the underlying cause of the compromise, address affected credentials and security weaknesses, and safely restore normal operations.
