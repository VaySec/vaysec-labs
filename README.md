# VaySec Security Labs

Hands-on cybersecurity labs covering Identity & Access Management, Microsoft Security, Data Protection, Security Operations, Security Architecture, GRC, and security automation.

The labs are designed for learning, experimentation, and demonstrating practical security capabilities in authorised lab environments.

---

## Lab Domains

### Identity & Access Management

Labs covering identity, authentication, authorisation, and access governance.

* [Entra ID](./iam/entra-id/)
* [Identity Governance](./iam/identity-governance/)
* [Authentication](./iam/authentication/)

Example topics:

* Microsoft Entra ID
* Users and groups
* App registrations
* Enterprise applications
* API permissions
* OAuth 2.0 / OIDC
* Conditional Access
* MFA
* Access Reviews
* Entitlement Management

---

### Microsoft Defender

Labs covering Microsoft Defender security capabilities.

* [Defender for Endpoint](./defender/defender-for-endpoint/)
* [Defender for Identity](./defender/defender-for-identity/)
* [Defender for Office 365](./defender/defender-for-office365/)
* [Defender for Cloud](./defender/defender-for-cloud/)
* [Defender for Cloud Apps](./defender/defender-for-cloud-apps/)

---

### Microsoft Purview

Labs covering data security, compliance, and information protection.

* [Data Loss Prevention](./purview/data-loss-prevention/)
* [Sensitivity Labels](./purview/sensitivity-labels/)
* [Insider Risk](./purview/insider-risk/)
* [Data Lifecycle Management](./purview/data-lifecycle/)
* [Audit](./purview/audit/)

Example topics:

* Sensitive Information Types
* DLP policies
* Credit card detection
* Sensitivity labels
* Microsoft Purview auditing
* Data protection controls

---

### Microsoft Sentinel

Labs covering security operations and SIEM capabilities.

* [Data Connectors](./sentinel/data-connectors/)
* [Analytics Rules](./sentinel/analytics-rules/)
* [Incidents](./sentinel/incidents/)
* [Workbooks](./sentinel/workbooks/)

Example topics:

* Log ingestion
* KQL
* Analytics rules
* Incident investigation
* Threat detection
* Security monitoring

---

### Security Architecture

Labs and reference implementations focused on security architecture and Zero Trust.

* [Zero Trust](./security-architecture/zero-trust/)
* [Identity Architecture](./security-architecture/identity-architecture/)
* [Cloud Security](./security-architecture/cloud-security/)
* [Reference Architectures](./security-architecture/reference-architectures/)

---

### Governance, Risk & Compliance

Labs covering security governance and common cybersecurity frameworks.

* [ISO 27001](./governance-risk-compliance/iso-27001/)
* [NIST Cybersecurity Framework](./governance-risk-compliance/nist-csf/)
* [Essential Eight](./governance-risk-compliance/essential-eight/)
* [Security Controls](./governance-risk-compliance/security-controls/)

---

### Automation

Scripts and examples for security automation.

* [PowerShell](./automation/powershell/)
* [Microsoft Graph](./automation/microsoft-graph/)
* [Azure CLI](./automation/azure-cli/)
* [Cloudflare](./automation/cloudflare/)

---

### Security Scenarios

End-to-end scenarios combining multiple security capabilities.

* [Identity Compromise](./scenarios/identity-compromise/)
* [Data Exfiltration](./scenarios/data-exfiltration/)
* [Insider Risk](./scenarios/insider-risk/)
* [Conditional Access](./scenarios/conditional-access/)

---

## Lab Format

Each lab is designed to be self-contained and normally includes:

```text
lab-name/
├── README.md
├── screenshots/
├── scripts/
└── sample-data/
```

The lab `README.md` provides:

1. Overview
2. Objectives
3. Prerequisites
4. Lab environment
5. Architecture
6. Step-by-step instructions
7. Expected results
8. Troubleshooting
9. Cleanup
10. References

---

## Lab Levels

Labs may be classified using the following levels:

| Level        | Description                                                 |
| ------------ | ----------------------------------------------------------- |
| Beginner     | Fundamental concepts and basic configuration                |
| Intermediate | Multi-step configuration and investigation                  |
| Advanced     | Complex configurations, integrations, or security scenarios |

---

## Prerequisites

Individual labs may require one or more of the following:

* Microsoft Entra ID tenant
* Microsoft 365 tenant
* Azure subscription
* Microsoft security product trial or appropriate licence
* Microsoft Graph access
* PowerShell
* Azure CLI
* Cloudflare account
* Other tools specified by the individual lab

Always review the prerequisites for the specific lab before starting.

---

## Security and Authorisation

These labs are intended for **authorised testing and educational purposes only**.

Do not use the lab instructions, scripts, configurations, or techniques against systems, accounts, tenants, applications, or networks without appropriate authorisation.

Do not place real credentials, secrets, customer information, production data, or other confidential information in this repository.

See [SECURITY.md](./SECURITY.md) for the repository security policy.

---

## Repository Structure

```text
vaysec-labs/
│
├── README.md
├── LICENSE
├── SECURITY.md
├── CONTRIBUTING.md
│
├── iam/
├── defender/
├── purview/
├── sentinel/
├── security-architecture/
├── governance-risk-compliance/
├── automation/
├── scenarios/
│
└── assets/
```

---

## Contributing

Contributions, corrections, improvements, and suggestions are welcome.

Before contributing, please review [CONTRIBUTING.md](./CONTRIBUTING.md).

---

## Licence

This repository is licensed under the [MIT License](./LICENSE), unless otherwise stated for a specific component or resource.

---

## About VaySec

VaySec publishes practical cybersecurity labs and reference material covering:

**Identity • Security • Compliance • Architecture**
