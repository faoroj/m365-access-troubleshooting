# Ticket 04 — Password Reset Required/Credential Issue

## User Reported Issue
User reports they cannot sign in to Microsoft 365. The password is believed to be correct, but access is denied, or they are stuck in a password reset loop.

## Initial Hypothesis
- Expired or incorrect credentials
- Password reset requirement is preventing authentication
- User is unable to complete the password change process

## Investigation Steps
1. Reviewed the user report indicating the inability to sign in.
2. Verified user account was enabled and licensed.
3. Reviewed Entra ID sign-in logs and observed password-related authentication failures.
4. Confirmed the account was configured to require a password change at next sign-in.

## Root Cause
The user account was configured to require a password change at the next sign-in, preventing successful authentication until credentials were updated.

## Resolution
-Reset password again
-Provide a new temporary password
-Allow password update to complete successfully

## Verification
Confirmed successful sign-in after password reset and credential update.
