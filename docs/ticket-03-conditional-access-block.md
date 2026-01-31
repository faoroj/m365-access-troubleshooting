# Ticket 03 — Conditional Access Block

## User Reported Issue
User reports being blocked from accessing Microsoft Teams after a successful login.

## Initial Hypothesis
- Conditional Access policy blocking access
- MFA requirement not satisfied
- Licensing or service plan issue

## Investigation Steps
1. Confirmed the user account was enabled and licensed for Microsoft Teams.
2. Attempted user sign-in and observed access blocked by organizational policy.
3. Reviewed Microsoft Entra ID sign-in logs for the affected user.
4. Identified a Conditional Access policy blocking Microsoft Teams access.
5. Verified the specific policy name and block action applied to the user.

## Root Cause
Conditional Access policy is blocking Microsoft Teams for the user.

## Resolution
Modified the Conditional Access policy to exclude the affected user while preserving the policy for other users. This restored access without disabling security controls.

## Verification
Confirmed successful Microsoft Teams access after policy exclusion, and validated sign-in logs showed no further Conditional Access blocks.
