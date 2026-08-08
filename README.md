# Awesome-Workforce-Identity-Cloud

## Top Workforce Identity Cloud Tools Ecosystem

**Curated List of SaaS/Commercial Products & Open-Source GitHub Projects**  
*Focused on Workforce IAM, SSO, Directory Services, MFA, User Provisioning & Access Management*  
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Workforce Identity**. These tools provide centralized identity and access management for employees and workforce users — covering single sign-on (SSO), multi-factor authentication (MFA), user lifecycle management, directory services, federation, and policy-based access control.

**Examples** include Okta Workforce Identity, Microsoft Entra ID, JumpCloud, Rippling Identity, OneLogin, Ping Identity, IBM Security Verify, Cisco Duo, Google Cloud Identity, and Keycloak (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted workforce identity and access management — ideal for organizations that want full data ownership, no per-user licensing, air-gapped deployments, and freedom from vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing | Free Tier Limit |
|---------|-------------|---------|-----------------|
| **[Okta Workforce Identity](https://www.okta.com/)** | Leading cloud identity platform for workforce SSO, MFA, lifecycle management, adaptive access, and extensive application integrations. | Per User / Per Month | Developer Plan only (No production free tier) |
| **[Microsoft Entra ID](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)** | Enterprise identity and access management tightly integrated with Microsoft 365 and Azure, offering SSO, conditional access, identity governance, and hybrid directory capabilities. | Included w/ MS subs / Premium tiers | 50,000 resources (default limit) |
| **[JumpCloud](https://jumpcloud.com/)** | Cloud directory platform combining identity, device management, and access control for modern, heterogeneous environments. | Per User / Per Month | None (30-day trial only) |
| **[Rippling Identity](https://www.rippling.com/)** | Identity and access capabilities embedded within the broader Rippling workforce platform, linking HR data to provisioning and access. | Custom Quote | None |
| **[OneLogin](https://www.onelogin.com/)** | Commercial platform covering SSO, MFA, directory services, passwordless authentication, and zero-trust access. | Per User / Per Month | Developer trial |
| **[Ping Identity](https://www.pingidentity.com/)** | Enterprise commercial platform covering SSO, MFA, directory services, passwordless authentication, and zero-trust access. | Custom Quote | None |
| **[IBM Security Verify](https://www.ibm.com/products/verify-identity)** | Commercial identity platform covering SSO, MFA, directory services, passwordless authentication. | Tiered Pricing | Developer Edition available |
| **[Cisco Duo](https://duo.com/)** | Security platform covering SSO, MFA, directory services, passwordless authentication, and zero-trust access for workforce users. | Per User / Per Month | Up to 10 users (Legacy Free edition) |
| **[Google Cloud Identity](https://cloud.google.com/identity)** | Commercial platform covering SSO, MFA, directory services, passwordless authentication, and zero-trust access for workforce users. | Per User / Per Month (Premium) | Up to 50 users (Free edition) |
| **[Keycloak Cloud / managed offerings](https://www.keycloak.org/)** | Hosted or commercially supported deployments of the leading open-source identity provider for teams that prefer not to self-host. | Varies by Provider | Varies by Provider |

## Open-Source GitHub Projects

- **[Keycloak](https://github.com/keycloak/keycloak)**  
  The most widely adopted open-source identity and access management solution. Provides SSO (OIDC, SAML), user federation (LDAP/AD), identity brokering, fine-grained authorization, MFA/WebAuthn, and extensive admin capabilities. Apache 2.0 licensed and CNCF-related.

- **[Authentik](https://github.com/goauthentik/authentik)**  
  Modern, flexible open-source identity provider with excellent admin UX, customizable Flows, SSO (OIDC/SAML), MFA, LDAP outposts, proxy authentication, and strong self-hosted ergonomics.

- **[Zitadel](https://github.com/zitadel/zitadel)**  
  Cloud-native open-source IAM/CIAM platform with built-in multi-tenancy (Organizations), OIDC/SAML, MFA, audit logging, and strong support for B2B and workforce scenarios.

- **[Authelia](https://github.com/authelia/authelia)**  
  Lightweight open-source authentication and authorization server focused on SSO + MFA via reverse-proxy forward-auth. Popular for securing internal applications and self-hosted stacks.

- **[FreeIPA](https://www.freeipa.org/)**  
  Open-source identity management system providing centralized Linux user, group, host, and service identity along with policy and certificate management (upstream of Red Hat IdM).

- **[Ory](https://github.com/ory)** (Kratos, Hydra, Oathkeeper, Keto)  
  Modular, API-first open-source identity and access control components for building headless or highly customized authentication and authorization systems.

- **[Gluu / Janssen Project](https://github.com/JanssenProject)**  
  Open-source digital identity platform focused on SSO, strong authentication, and enterprise federation capabilities.

- **[Casdoor](https://github.com/casdoor/casdoor)**, **[Logto](https://github.com/logto-io/logto)**, **[Kanidm](https://github.com/kanidm/kanidm)**, **[WSO2 Identity Server](https://github.com/wso2/product-is)**  
  Additional capable open-source identity platforms offering UI-first IAM, modern authentication, simple secure identity management, and enterprise-grade features respectively.

### Additional Strong Open-Source Options

- privacyIDEA and related open-source OTP/token servers for specialized MFA.
- Teleport, Pomerium, and other identity-aware access proxies that complement core IAM.
- LDAP/AD alternatives and directory services that integrate with the platforms above.
- Many community plugins, themes, and protocol bridges for Keycloak, Authentik, and Zitadel.

**Frameworks for building custom systems**: For full-featured enterprise workforce IAM start with **Keycloak**. Choose **Authentik** for a modern admin experience and flexible flows, **Zitadel** when multi-tenancy and cloud-native design matter, and **Authelia** for lightweight reverse-proxy protection of internal apps. Combine with FreeIPA or existing directories for Linux/infrastructure identity, and layer MFA/passwordless as needed.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/commercial or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Identity systems are security-critical. Self-hosted open-source IAM requires careful hardening, regular updates, high availability design, backup/recovery planning, and proper key/certificate management. Review current license terms (some projects use open-core models) and evaluate protocol coverage (SAML depth, SCIM, LDAP federation) against your application estate.
- Always test authentication flows, session handling, and recovery processes thoroughly before production cutover.

---

**Made for identity architects, security teams, and organizations seeking sovereign, self-hosted workforce identity.**  
Let's make identity and access management more open, transparent, and under your control.
