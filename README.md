# GMGroup IAM Portfolio
# Grace George · MIS Graduate Student, UNLV · IAM Career Portfolio 2026

This repository contains hands-on Identity and Access Management (IAM) portfolio projects built to demonstrate real-world IAM skills to employers. Each project simulates a workflow commonly found in enterprise IAM job descriptions, built using industry-standard free tools.

# About me
I am a Management Information System/Cybersecurity graduate student at the University of Nevada, Las Vegas, pivoting into Identity and Access Management. 
My background includes IT support, digital forensics, and cybersecurity education through my platform CyberSis. 
I hold a Comptia Sec+ 701 and SC-300 (Microsoft Identity and Access Administrator) certification and am actively building hands-on IAM experience through these projects.

**Target roles:** 
IAM Analyst · Identity Security Engineer · Access Management Specialist


# Portfolio projects

| # | Project | Platform | Status |

| 1 | [Joiner-Mover-Leaver Workflow](./Project-1-JML) | Okta Workforce Identity | ✅ Complete 

| 2 | SSO + MFA Integration | Okta + Microsoft Entra ID | 🔄 In progress 

| 3 | RBAC Design + Entitlement Matrix | Google Sheets + Entra ID |  not started 

| 4 | Access Review + Certification Process | Microsoft Entra ID | not started

| 5 | Privileged Access + Least Privilege Audit | GCP + Microsoft Entra PIM | not started


# Project 1 — Joiner-Mover-Leaver Workflow

**Platform:** Okta Workforce Identity (free tier)  
**Company simulated:** GMGroup(Financial)  

### What I built
A complete identity lifecycle management workflow for a simulated financial services company, automating user provisioning and deprovisioning across three scenarios:

- **Joiner** — New hire Jill Joiner onboarded to Finance team. Okta automatically provisioned Slack and GitHub via group membership, zero manual app assignment
- **Mover** — Marcus transferred from IT to Finance. A single group change removed Google Workspace and added Slack automatically
- **Leaver** — Lena offboarded. Account deactivated, Upon deactivation, all active sessions are immediately terminated.
-  The Clear User Sessions option is used when an employee is currently logged in at time of offboarding but for the purpose of this project lena never had a user session,
-  so there was no session to revoke after deactivation.

# Key concepts demonstrated
- Group-based access control (RBAC via Okta groups)
- Automated provisioning and deprovisioning
- Least privilege — users only access apps their role requires
- Secure offboarding — immediate deactivation and session revocation
- Audit log preservation for compliance

# IAM skills
Okta, Identity lifecycle management, JML, RBAC, User provisioning, Deprovisioning, Least privilege, Access governance

# Tools and platforms used across this portfolio

# | Tool | Purpose |

| Okta Workforce Identity - User lifecycle, SSO, MFA, group management 
| Microsoft Entra ID - Conditional Access, PIM, access reviews, hybrid identity 
| Google Cloud Platform (GCP) - IAM roles, service accounts, workload identity federation 
| GitHub - Portfolio documentation and version control 
| draw.io | IAM architecture and workflow diagrams |

# Certifications
- Comptia Security +
- Microsoft SC-300 — Identity and Access Administrator (renewing)

# Contact
- LinkedIn: www.linkedin.com/in/george-moyin
- Platform: Instagram & Tiktok  - the_CyberSis — cybersecurity education for non-technical audiences

---
**This portfolio is actively being built. New projects added as done.**
