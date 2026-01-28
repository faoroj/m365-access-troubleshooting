# Microsoft 365 Access Troubleshooting Checklist

This checklist outlines a structured workflow for diagnosing and resolving common Microsoft 365 access issues. It is designed to mirror real-world IT Analyst ticket triage and investigation practices.

---

## 1. Confirm Scope
- What application is affected?
  - Outlook
  - Microsoft Teams
  - SharePoint / OneDrive
- What exact error message is displayed?
- Is the issue affecting:
  - A single user
  - Multiple users
- Did the issue start recently or after a known change?

---

## 2. Identity Basics
- Is the user account enabled in Entra ID?
- Is the account locked or flagged for sign-in risk?
- Has the user been forced to reset their password?
- Are there recent failed sign-in attempts?

---

## 3. Licensing
- Is the correct Microsoft 365 license assigned?
- Is the required service plan enabled for the affected application?
- Has the license been recently added or changed?
- Has sufficient time passed for license changes to propagate?

---

## 4. Multi-Factor Authentication (MFA)
- Is MFA enabled for the user?
- Is at least one MFA method properly registered?
- Are there MFA-related failures in Entra ID sign-in logs?
- Is the user stuck in an MFA registration or authentication loop?

---

## 5. Conditional Access / Security Defaults
- Is Conditional Access blocking the sign-in?
- Does the policy require:
  - A compliant device
  - A trusted location
  - A specific MFA method
- Are Security Defaults enforcing additional requirements?
- Is the policy behavior expected or misconfigured?

---

## 6. Client / Device Factors
- Does the issue occur in:
  - Web browser
  - Desktop application
- Does web access succeed while the desktop client fails?
- Has the user signed out and back in?
- Has the application cache or credentials been cleared?
- Is the device up to date and compliant (if applicable)?

---

## 7. Resolution and Documentation
- What was the root cause of the issue?
- What action resolved the problem?
- How was successful access verified?
- Is escalation required?
- Are preventive steps needed?
  - User guidance
  - Internal documentation update
  - Policy or configuration change

---

## Notes
This checklist is used in conjunction with documented ticket investigations to ensure consistent, repeatable troubleshooting and clear documentation.
