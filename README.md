# Fernando Huizar

System Administrator moving into Identity and Access Management. I build identity labs end to end: HR data in, accounts and access out, and checks that prove nothing drifted. Each repo shows the code, the problems I hit and how I fixed them.

SC-300 · Okta Certified Professional · CompTIA Security+

## Featured project

### [Havlund Pharma: HR-driven identity lifecycle](https://github.com/FernandoHuizar/havlund-identity-lifecycle)

A made-up pharma company where HR is the source of truth. A Python script reads the HR export and handles joiners, movers, leavers, contractor end dates and rehires in Okta. Okta provisions Active Directory, and Entra Cloud Sync carries it into Entra ID. A drift check compares all three systems with HR and flags leavers who still have access, separation of duties conflicts and accounts with no owner.

- Tested on purpose: 3 problems made by hand in AD gave 8 findings, each caught in both AD and Entra
- 9 real problems logged with cause, fix and lesson
- Python, PowerShell, Okta API, Microsoft Graph, Active Directory, Entra Cloud Sync

## Also built

| Project | What it shows | Proof |
|---|---|---|
| [SCIM Provisioning Lab](https://github.com/FernandoHuizar/scim-provisioning-lab) | A SCIM 2.0 server I wrote in Node.js, connected to a live Okta tenant for automatic create and deactivate | Code, screenshots |

## Building next

- **App onboarding in Okta:** taking an app from request to production with SAML or OIDC, SCIM provisioning, MFA policy and a runbook
- **Entra security:** Conditional Access, PIM and access reviews for the same Havlund Pharma company

## Connect

[LinkedIn](https://www.linkedin.com/in/fernandohuizarit)
