# Microsoft Entra ID: Enterprise Architecture & Governance

A hands-on portfolio focused on designing, implementing, securing, and governing enterprise identity solutions with Microsoft Entra ID.

This is a standalone advanced learning track, separate from the existing Identity and Access Administrator labs repository.

## Learning objectives

- Enterprise application architecture and SAML SSO
- App registrations, OAuth 2.0, and OpenID Connect
- SCIM provisioning and identity lifecycle management
- Application objects, service principals, and workload identities
- Microsoft Graph API permissions and consent governance
- Application credential and secret lifecycle management
- Conditional Access architecture and troubleshooting
- Privileged Identity Management (PIM)
- Identity Governance and access reviews
- Cross-tenant access and B2B collaboration
- Cross-tenant synchronization
- Enterprise identity architecture and security design

## Lab roadmap

| Lab | Topic | Status |
|---:|---|---|
| 1 | [Enterprise Application SSO Architecture](Lab-01-Enterprise-Application-SSO/README.md) | Not started |
| 2 | [App Registrations, OAuth 2.0 and OIDC](Lab-02-App-Registration-OIDC-OAuth/README.md) | Not started |
| 3 | [SCIM Automated User Provisioning](Lab-03-SCIM-Provisioning/README.md) | Not started |
| 4 | [Service Principals and Workload Identities](Lab-04-Service-Principals-Workload-Identities/README.md) | Not started |
| 5 | [Microsoft Graph API Permissions and Consent Governance](Lab-05-Graph-API-Permissions/README.md) | Not started |
| 6 | [Application Credential and Secret Governance](Lab-06-App-Credential-Governance/README.md) | Not started |
| 7 | [Enterprise Conditional Access Architecture](Lab-07-Conditional-Access-Architecture/README.md) | Not started |
| 8 | [Privileged Identity Management (PIM)](Lab-08-PIM-Privileged-Identity-Management/README.md) | Not started |
| 9 | [Identity Governance and Access Reviews](Lab-09-Identity-Governance-Access-Reviews/README.md) | Not started |
| 10 | [Cross-Tenant Access and B2B Collaboration](Lab-10-Cross-Tenant-Access-B2B/README.md) | Not started |
| 11 | [Cross-Tenant Synchronization](Lab-11-Cross-Tenant-Synchronization/README.md) | Not started |
| 12 | [Enterprise Identity Architecture Capstone](Lab-12-Enterprise-Identity-Capstone/README.md) | Not started |

## Standard lab structure

Each lab will document the scenario, requirements, architecture, implementation, positive and negative testing, troubleshooting, security assessment, evidence, and lessons learned.

Suggested folder contents:

```text
Lab-XX-Topic/
├── README.md
├── Architecture/
├── Screenshots/
├── Configuration/
├── Scripts/
├── Troubleshooting.md
└── Security-Assessment.md
```

## Repository guidance

- Use non-production test tenants and test identities.
- Verify licensing and feature prerequisites before each lab.
- Never commit passwords, client secrets, private keys, access tokens, or sensitive logs.
- Use least-privilege permissions and document role assignments.
- Redact tenant and user information from screenshots when appropriate.
- Mark a lab Completed only after implementation, validation, troubleshooting, documentation, and evidence are finished.

## Project tracking

See [Progress.md](Progress.md) for the current status of all 12 labs. See the `docs/` directory for design principles, licensing prerequisites, and evidence standards.

**Scope:** Labs 1–12. All labs begin as Not started; no implementation results are claimed until verified.
