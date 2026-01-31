# Ticket 05 — SharePoint/OneDrive Permission Issue

## User Reported Issue
“I get an access denied/request access message when opening a SharePoint or OneDrive link.”

## Initial Hypothesis
- User not explicitly granted access to resource
- Incorrect sharing scope (link restricted to existing users)
- SharePoint / OneDrive permissions mismatch

## Investigation Steps
1. Back in the admin account
2. Right-click folder → Manage access
3. Observe:
  - Chris User Two not listed
  - No direct permissions

## Root Cause
User was not explicitly granted permissions to the shared OneDrive folder. 
The sharing link was restricted to users with existing access, preventing access.

## Resolution
Granted direct permissions to the user via OneDrive folder sharing.
Verified access by successful file open.

## Verification
User successfully accessed the shared folder and file after the permission update.

## Notes
Prefer direct user or group permissions over link-based sharing for controlled access.
