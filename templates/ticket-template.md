# Ticket Template — Microsoft 365 Access Issue

> Use this template to document Microsoft 365 access-related incidents in a consistent, repeatable format.

---

## Ticket Summary
**Ticket ID:**  
**Issue Type:** (Access / Authentication / Licensing / Client / Permissions)  
**Priority:** (Low / Medium / High)  
**Status:** (Open / Resolved / Escalated)

---

## User Reported Issue
- Description of the issue as reported by the user
- Exact error message or symptom (if provided)
- Application(s) affected (Outlook, Teams, SharePoint, OneDrive, etc.)
- Scope:
  - Single user
  - Multiple users

---

## Environment
- Tenant Type: (Lab / Developer tenant / Simulated)
- Identity Platform: Microsoft Entra ID
- Application(s) Involved:
- Client Type:
  - Web
  - Desktop
- Device / OS (if relevant):

---

## Initial Hypothesis
Based on the reported issue, potential causes include:
- 
- 
- 

---

## Investigation Steps
Document actions taken in chronological order.

1. Step performed  
   - What was checked  
   - Where (Admin Center, Entra ID, Sign-in logs, etc.)  
   - Result

2. Step performed  
   - Findings  
   - Supporting evidence (screenshots/logs)

3. Additional investigation (if required)

---

## Evidence Reviewed
- Entra ID sign-in logs
- License assignment / service plans
- MFA configuration
- Conditional Access policies
- Client behavior (web vs desktop)
- Other relevant logs or settings

---

## Root Cause
Clearly state the underlying cause of the issue.

> Example:  
> The user account did not have the required Microsoft 365 service plan enabled, preventing access to Microsoft Teams.

---

## Resolution
Describe the corrective action taken:
- Configuration change
- License assignment
- MFA reset
- Client remediation
- Policy adjustment

---

## Verification
- How access was tested and confirmed
- Application functionality restored
- No additional errors observed

---

## Escalation (if applicable)
- Was escalation required?
- Who/what team would this be escalated to?
- Reason for escalation

---

## Prevention / Recommendations
- Documentation updates
- User guidance
- Policy or configuration improvements
- Monitoring considerations

---

## Lessons Learned
- What this issue reinforced or improved in your troubleshooting process
- What you would check earlier next time
