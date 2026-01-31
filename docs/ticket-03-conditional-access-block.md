# Ticket 03 — Conditional Access Block

## User Reported Issue
User reports being blocked from accessing Microsoft Teams after a successful login.

## Initial Hypothesis
- MFA not properly registered
- Authentication method unavailable
- MFA requirement enforced but not satisfied

## Investigation Steps
1. Reviewed user report indicating sign-in failure related to MFA prompts.
2. Verified user account status in Entra ID
3. Reviewed authentication methods for the user: no MFA methods registered
4. Analyzed Entra ID sign-in logs: Sign-in attempts interrupted, MFA requirement enforced but not completed

## Root Cause
Conditional Access policy is blocking Microsoft Teams for the user.

## Resolution
Modified the Conditional Access policy to exclude the affected user while preserving the policy for other users. This restored access without disabling security controls.

## Verification
Confirmed successful Microsoft Teams access after policy exclusion, and validated sign-in logs showed no further Conditional Access blocks.
