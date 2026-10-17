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

I build personal labs that copy the real work of an IAM team: giving people the right access on day one, taking it away when they leave, and proving it matches HR. Fake people and made-up companies, real Okta, Active Directory and Entra ID.

## Certifications

| Certification | Issuer |
|---|---|
| SC-300: Identity and Access Administrator Associate | Microsoft |
| Okta Certified Professional | Okta |
| Security+ | CompTIA |

## Featured project

### [Havlund Pharma: HR-driven identity lifecycle](https://github.com/FernandoHuizar/havlund-identity-lifecycle)

**Problem:** new hires wait days for access, people who leave keep it too long, and nobody can easily show who has access to what.

**What I built:** HR changes flow automatically into Okta, Active Directory and Entra ID. A second script checks all three against HR and flags anything that doesn't match.

- 7 new hires set up with the right access in one run
- A leaver's access removed and account turned off in about 1 second, every step logged
- 3 problems I planted by hand gave 8 findings, all caught in both AD and Entra

<a href="https://github.com/FernandoHuizar/havlund-identity-lifecycle"><img src="https://github.com/FernandoHuizar/havlund-identity-lifecycle/raw/main/screenshots/08-drift-check-all-systems.png" width="600" alt="Drift check finding a leaver with access and a separation of duties conflict"></a>

Python · PowerShell · Okta API · Microsoft Graph · Entra Cloud Sync. Code, screenshots and a log of what broke and how I fixed it.

## Earlier labs

Screenshot-based labs from earlier in my learning. I'm replacing them one by one with full builds like Havlund.

- [SCIM Provisioning](https://github.com/FernandoHuizar/scim-provisioning-lab): a small server I wrote so Okta can create and turn off accounts in another app. Includes code.
- [Okta SSO and MFA](https://github.com/FernandoHuizar/Okta-SSO-MFA-Lab): single sign-on and MFA for 3 apps, plus 5 sign-in problems I reproduced and fixed.
- [Enterprise App Provisioning](https://github.com/FernandoHuizar/Enterprise-App-Provisioning-Lab): Entra creating accounts in ServiceNow automatically.
- [PIM and Access Reviews](https://github.com/FernandoHuizar/PIM-Access-Reviews-Lab): admin rights only when needed, and a 30-user access review with real removals.
- [Hybrid Identity and AD](https://github.com/FernandoHuizar/Hybrid-Identity-AD-Lab): Active Directory synced to Entra ID, with access given by group.

## Next

App onboarding at Havlund (single sign-on, automatic accounts, MFA policy, help desk runbook), then privileged access for shared admin accounts.

## Skills

| Area | Tools and concepts |
|---|---|
| **Identity & Access** | Okta · Microsoft Entra ID · Active Directory · SSO (SAML 2.0, OIDC) · MFA · SCIM · Joiner/Mover/Leaver · PIM · Access Reviews · Separation of Duties |
| **Automation** | Python · PowerShell · Okta API · Microsoft Graph API · n8n |
| **Endpoint & Security** | Intune · Hexnode MDM · Huntress EDR |
| **Platforms & Service** | Microsoft 365 · Google Workspace · ServiceNow · Git |
