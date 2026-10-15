# Fernando Huizar

System Administrator moving into Identity and Access Management. I build identity labs end to end: HR data in, accounts and access out, and checks that prove nothing drifted.

SC-300 · Okta Certified Professional · CompTIA Security+

## Latest

| Project | Proof | What it solves | Stack |
|---|---|---|---|
| [Havlund Pharma: HR-driven identity lifecycle](https://github.com/FernandoHuizar/havlund-identity-lifecycle) | Code, screenshots, problem log | A pharma company where HR is the source of truth. Joiners, movers, leavers, contractor end dates and rehires flow from HR to Okta, Active Directory and Entra ID. A drift check compares all three with HR and flags leavers with access, separation of duties conflicts and accounts with no owner. Tested on purpose: 3 problems made by hand gave 8 findings, all caught. | Python, PowerShell, Okta API, Microsoft Graph, AD, Entra Cloud Sync |

## Identity labs

| Lab | Proof | What it shows | Stack |
|---|---|---|---|
| [SCIM Provisioning Lab](https://github.com/FernandoHuizar/scim-provisioning-lab) | Code, screenshots | A SCIM 2.0 server I wrote, connected to a live Okta tenant for automatic create and deactivate | Node.js, SCIM 2.0, Okta |
| [Okta SSO and MFA Lab](https://github.com/FernandoHuizar/Okta-SSO-MFA-Lab) | Screenshots | SAML 2.0 and OIDC apps, sign-on policies, 5 troubleshooting cases I reproduced | Okta, SAML, OIDC, MFA |
| [Enterprise App Provisioning Lab](https://github.com/FernandoHuizar/Enterprise-App-Provisioning-Lab) | Screenshots | Entra provisioning to ServiceNow, and why I switched away from a broken Salesforce integration | Entra ID, ServiceNow |
| [PIM and Access Reviews Lab](https://github.com/FernandoHuizar/PIM-Access-Reviews-Lab) | Screenshots | Just-in-time admin roles, a 30-user access review with real removals, separation of duties | Entra ID, PIM, Access Reviews |
| [Hybrid Identity and AD Lab](https://github.com/FernandoHuizar/Hybrid-Identity-AD-Lab) | Screenshots | Active Directory synced to Entra with Entra Connect, group-based access structure | AD, Entra Connect, PowerShell |

The labs marked Screenshots are portal walkthroughs from earlier in my learning. I'm replacing them one by one with full builds like Havlund.

## Building next

1. **App onboarding at Havlund:** taking an app from request to production in Okta with SSO, SCIM provisioning by group, an MFA policy and a help desk runbook
2. **Privileged access at Havlund:** vaulting the shared admin and service accounts in Delinea Secret Server, with check-out approval, automatic password rotation and an audit trail

## Connect

[LinkedIn](https://www.linkedin.com/in/fernandohuizarit)
