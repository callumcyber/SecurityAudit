<h1>Security Audit</h1>

### Conducting an Internal Security Audit: Botium Toys

*Google Cybersecurity Professional Certificate — Course 2 Portfolio Project*

## Overview

Botium Toys is a small U.S.-based toy retailer with a single physical location that
serves as its main office, storefront, and warehouse. As its online sales have grown to
attract customers across the U.S. and internationally, the IT department has come
under increasing pressure to support a growing web presence — while also staying
compliant with regulations tied to online payments and doing business in the European
Union.

The IT manager requested an internal audit to get a clear picture of the company's
security posture: what controls are already in place, where compliance gaps exist, and
what risks or fines the business could face as a result. This project picks up after the
IT manager had already applied the NIST Cybersecurity Framework (CSF) to define the
audit scope and goals, list the assets under IT's management, and produce an initial
risk assessment. My task was to review that report, then complete a controls and
compliance checklist and turn the findings into a set of actionable recommendations.

## Scope and Goals

**Scope:** The entire security program at Botium Toys — employee equipment and
devices, the internal network, and all managed systems.

**Goals:** Assess existing assets and complete a controls and compliance checklist to
determine which controls and compliance best practices need to be implemented to
improve Botium Toys' security posture.

## Assets Managed by IT

- On-premises equipment for in-office business needs
- Employee equipment: end-user devices, remote workstations, headsets, cables,
  keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products (sold on-site and online, stored in the adjoining warehouse)
- Systems, software, and services: accounting, telecommunication, database,
  security, ecommerce, and inventory management
- Internet access and internal network
- Data retention and storage
- Legacy system maintenance (end-of-life systems requiring manual monitoring)

## Risk Assessment

| | |
|---|---|
| **Risk description** | Inadequate asset management, missing controls, and gaps in compliance with U.S. and international regulations |
| **Control best practices (NIST CSF function)** | Identify — the organisation will need to dedicate resources to identify and classify assets, and determine the business-continuity impact of losing them |
| **Risk score** | **8 / 10** (high) |
| **Impact of asset loss** | Medium — the IT department doesn't yet know which assets are most at risk |
| **Risk of fines / compliance exposure** | High — key controls are missing and several compliance best practices aren't met |

## Controls Assessment

*Does Botium Toys currently have this control in place?*

| Control | In place? |
|---|:---:|
| Least privilege | ❌ No |
| Disaster recovery plans | ❌ No |
| Password policies | ❌ No |
| Separation of duties | ❌ No |
| Firewall | ✅ Yes |
| Intrusion detection system (IDS) | ❌ No |
| Backups | ❌ No |
| Antivirus software | ✅ Yes |
| Manual monitoring/maintenance for legacy systems | ❌ No |
| Encryption | ❌ No |
| Password management system | ❌ No |
| Locks (offices, storefront, warehouse) | ✅ Yes |
| CCTV surveillance | ✅ Yes |
| Fire detection/prevention | ✅ Yes |

## Compliance Assessment

*Does Botium Toys currently adhere to this compliance best practice?*

**Payment Card Industry Data Security Standard (PCI DSS)**

| Best practice | Met? |
|---|:---:|
| Only authorised users have access to customers' credit card information | ❌ No |
| Credit card information is stored, accepted, processed, and transmitted internally in a secure environment | ❌ No |
| Data encryption procedures secure credit card transaction touchpoints and data | ❌ No |
| Secure password management policies are adopted | ❌ No |

**General Data Protection Regulation (GDPR)**

| Best practice | Met? |
|---|:---:|
| E.U. customers' data is kept private/secured | ❌ No |
| A plan is in place to notify E.U. customers within 72 hours of a breach | ✅ Yes |
| Data is properly classified and inventoried | ❌ No |
| Privacy policies, procedures, and processes are enforced | ✅ Yes |

**System and Organisation Controls (SOC 1, SOC 2)**

| Best practice | Met? |
|---|:---:|
| User access policies are established | ❌ No |
| Sensitive data (PII/SPII) is confidential/private | ❌ No |
| Data integrity is ensured (consistent, complete, accurate, validated) | ✅ Yes |
| Data is available to authorised individuals | ❌ No |

## Recommendations

Based on the controls and compliance assessment, I recommended the following
priorities to Botium Toys:

- **Classify and inventory data.** Sensitive data, including PII and SPII, must be
  designated as confidential/private and handled accordingly.
- **Implement least privilege and separation of duties.** Enforce Access Control Lists
  (ACLs) so only authorised personnel can access and modify data — critical for
  restricting access to credit card information and maintaining PCI DSS and GDPR
  compliance.
- **Strengthen password security.** Enforce a stronger password policy backed by a
  centralised password management system to better secure employee accounts.
- **Build disaster recovery and business continuity plans**, including secure
  cloud-based backup solutions, to protect data availability and operational
  resilience.
- **Deploy an Intrusion Detection System (IDS)** to improve threat detection and
  incident response. This also supports regulatory compliance, such as the GDPR
requirement to notify affected parties of a data breach within 72 hours.
- **Formalise legacy system maintenance** with a regular monitoring/maintenance
  schedule and clearly defined response processes, and evaluate migrating off
  legacy systems where feasible to shrink the attack surface.
- **Encrypt customer data at rest and in transit** to protect confidentiality, reduce
  the impact of a potential breach, and support PCI DSS compliance for payment
  touchpoints.

Implementing these recommendations would significantly reduce Botium Toys' risk of
regulatory non-compliance and associated financial penalties, while strengthening the
organisation's overall security posture.

## What This Project Demonstrates

- Applying a recognised framework (NIST CSF) to structure a security audit
- Assessing technical and physical controls against real-world compliance
  frameworks (PCI DSS, GDPR, SOC)
- Translating audit findings into prioritised, actionable recommendations
- Communicating risk in business terms (risk scoring, regulatory/financial impact)

---
*This project is based on a fictional company (Botium Toys) as part of the Google
Cybersecurity Professional Certificate coursework.*
