<div align="center">

# Fernando Huizar

*System Administrator · Identity & Access Management*

<a href="https://www.linkedin.com/in/fernandohuizarit"><img src="https://img.shields.io/badge/LinkedIn-fernandohuizarit-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>

<img src="https://img.shields.io/badge/Okta-007DC1?style=for-the-badge&logo=okta&logoColor=white" alt="Okta">
<img src="https://img.shields.io/badge/Microsoft_Entra_ID-0078D4?style=for-the-badge&logoColor=white" alt="Microsoft Entra ID">
<img src="https://img.shields.io/badge/Active_Directory-0078D4?style=for-the-badge&logoColor=white" alt="Active Directory">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/PowerShell-5391FE?style=for-the-badge&logoColor=white" alt="PowerShell">

</div>

---

> **Portfolio note**
>
> These are personal labs built to copy the real work of an IAM team: joiners, movers and leavers, access by role, provisioning, and checks that prove access matches HR.
>
> Each project starts from a business problem, runs on live tenants (Okta, Entra ID, Active Directory), and includes the code, the evidence, and a log of what broke and how I fixed it.

## 🎓 Certifications

| Certification | Issuer | Status |
|---|---|---|
| SC-300: Identity and Access Administrator Associate | Microsoft | ✅ Earned |
| Okta Certified Professional | Okta | ✅ Earned |
| Security+ | CompTIA | ✅ Earned |

## 🛠️ Skills

| Area | Tools and concepts |
|---|---|
| **Identity & Access** | Okta · Microsoft Entra ID · Active Directory · SSO (SAML 2.0, OIDC) · MFA · SCIM · Joiner/Mover/Leaver · PIM · Access Reviews · Separation of Duties |
| **Automation** | Python · PowerShell · Okta API · Microsoft Graph API · n8n |
| **Endpoint & Security** | Intune · Hexnode MDM · Huntress EDR |
| **Platforms & Service** | Microsoft 365 · Google Workspace · ServiceNow · Git |

## 🔐 Identity & Access Management

### Latest

| Project | Proof | Purpose | Stack | Status |
|---|---|---|---|---|
| [Havlund Pharma: HR-driven identity lifecycle](https://github.com/FernandoHuizar/havlund-identity-lifecycle) | Code, screenshots, problem log | HR is the source of truth. Joiners, movers, leavers, contractor end dates and rehires flow from HR to Okta, Active Directory and Entra ID. A drift check compares all three with HR and flags leavers with access, separation of duties conflicts and accounts with no owner. Tested on purpose: 3 problems made by hand gave 8 findings, all caught. | Python · PowerShell · Okta API · Microsoft Graph · AD · Entra Cloud Sync | ![Complete](https://img.shields.io/badge/Complete-2ea44f) |

### Roadmap

| Project | Purpose | Stack | Status |
|---|---|---|---|
| App onboarding at Havlund | Taking an app from request to production: SSO, SCIM provisioning by group, an MFA policy and a help desk runbook | Okta · SAML · OIDC · SCIM | ![Next](https://img.shields.io/badge/Next-dbab09) |
| Privileged access at Havlund | Vaulting the shared admin and service accounts with check-out approval, automatic password rotation and an audit trail | Delinea Secret Server · AD | ![Queued](https://img.shields.io/badge/Queued-8b949e) |

### Completed labs

| Lab | Proof | Purpose | Stack | Status |
|---|---|---|---|---|
| [SCIM Provisioning Lab](https://github.com/FernandoHuizar/scim-provisioning-lab) | Code, screenshots | A SCIM 2.0 server I wrote, connected to a live Okta tenant for automatic create and deactivate | Node.js · SCIM 2.0 · Okta | ![Complete](https://img.shields.io/badge/Complete-2ea44f) |
| [Okta SSO and MFA Lab](https://github.com/FernandoHuizar/Okta-SSO-MFA-Lab) | Screenshots | SAML 2.0 and OIDC apps, sign-on policies, 5 troubleshooting cases I reproduced | Okta · SAML · OIDC · MFA | ![Complete](https://img.shields.io/badge/Complete-2ea44f) |
| [Enterprise App Provisioning Lab](https://github.com/FernandoHuizar/Enterprise-App-Provisioning-Lab) | Screenshots | Entra provisioning to ServiceNow, and why I switched away from a broken Salesforce integration | Entra ID · ServiceNow | ![Complete](https://img.shields.io/badge/Complete-2ea44f) |
| [PIM and Access Reviews Lab](https://github.com/FernandoHuizar/PIM-Access-Reviews-Lab) | Screenshots | Just-in-time admin roles, a 30-user access review with real removals, separation of duties | Entra ID · PIM · Access Reviews | ![Complete](https://img.shields.io/badge/Complete-2ea44f) |
| [Hybrid Identity and AD Lab](https://github.com/FernandoHuizar/Hybrid-Identity-AD-Lab) | Screenshots | Active Directory synced to Entra with Entra Connect, group-based access structure | AD · Entra Connect · PowerShell | ![Complete](https://img.shields.io/badge/Complete-2ea44f) |

> **Focus area:** the full identity lifecycle across Okta, Active Directory and Entra ID, with HR as the source of truth and automation at each step. The screenshot labs are from earlier in my learning, and I'm replacing them one by one with full builds like Havlund.

## 📫 Connect

<a href="https://www.linkedin.com/in/fernandohuizarit"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
