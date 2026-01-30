# Microsoft 365 Access Troubleshooting  
**IT Analyst Portfolio Project**

> A collection of realistic IT Analyst-style ticket investigations focused on Microsoft 365 access issues  
> (licensing, MFA, Conditional Access, and client troubleshooting).

---

## Table of Contents
- [Overview](#overview)
- [Tools & Platforms](#tools--platforms)
- [Case Studies](#case-studies)
- [Repository Structure](#repository-structure)
- [Key Skills Demonstrated](#key-skills-demonstrated)
- [Notes](#notes)

---

## Overview
This repository documents hands-on troubleshooting workflows for common Microsoft 365 access problems.  
Each ticket includes:

- User-reported issue + symptoms  
- Investigation steps and evidence reviewed  
- Root cause analysis  
- Resolution steps  
- Verification and follow-up notes  

The goal is to demonstrate practical, job-relevant IT Analyst skills: structured troubleshooting, identity/access diagnosis, and clear documentation.

---

## Tools & Platforms
- **Microsoft 365 Admin Center**
- **Microsoft Entra ID Admin Center** (formerly Azure AD)
- **Entra ID Sign-in Logs**
- *(Optional, where applicable)* Microsoft Teams / Outlook clients, SharePoint / OneDrive admin settings

---

## Case Studies
| Ticket | Scenario | Primary Focus |
|------:|----------|---------------|
| 01 | License assignment issue | Licensing / service plans |
| 02 | MFA registration/authentication failure | MFA troubleshooting / sign-in logs |
| 03 | Conditional Access block | Policy impact / access controls |
| 04 | Teams/Outlook desktop client issue | Client vs web isolation / remediation |
| 05 | SharePoint/OneDrive permissions issue | Access/permissions / sharing |

> Ticket documentation is located in the `docs/` folder.

---

## Repository Structure
```text
m365-access-troubleshooting/
├─ README.md
├─ docs/
│  ├─ environment-setup.md
│  ├─ troubleshooting-checklist.md
│  ├─ ticket-01-license-issue.md
│  ├─ ticket-02-mfa-issue.md
│  ├─ ticket-03-conditional-access-block.md
│  ├─ ticket-04-teams-outlook-client-issue.md
│  └─ ticket-05-sharepoint-onedrive-permissions.md
├─ screenshots/
│  ├─ ticket-01/
│  ├─ ticket-02/
│  ├─ ticket-03/
│  ├─ ticket-04/
│  ├─  ticket-05/
│  └─ environment/
└─ templates/
   └─ ticket-template.md
