# Ticket 01 — Microsoft 365 License Assignment Issue

## User Reported Issue
User reports inability to access Microsoft Teams.

## Initial Hypothesis
- License not assigned
- Service plan disabled

## Investigation Steps
1. User report claims inability to access Microsoft Teams.
2. Verified the account is enabled, and no administrative roles have been assigned.
3. Confirmed user is part of the IT-Test-Users security group.
4. Checked licensing status in Microsoft 365 Admin Center:
5. Checked service plan to ensure Teams is included.
6. Verified successful Microsoft Teams sign-in via Entra ID sign-in logs after license assignment.

## Root Cause
The user account is not assigned a Microsoft 365 license and will not be able to access services without one.

## Resolution
Assigned the appropriate Microsoft 365 license (Office 365 E5) to the user and verified that the Microsoft Teams service plan was enabled.

## Verification
User access to Microsoft Teams was successfully restored. The user was able to sign in to and access the application without errors after the license was assigned.

## Notes
License assignment may require several minutes until it is successful.
