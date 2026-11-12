# Awesome-Contract-Data-Security-Information-Governance

## Top Contract Data Security & Information Governance Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Sensitive Data Discovery, Contract Data Classification & Regulatory Compliance*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Contract Data Security & Information Governance**. These tools help organizations discover where contract data lives, classify its sensitivity, enforce access controls, and maintain compliance evidence across structured repositories and unstructured file shares—reducing the risk of exposing confidential pricing, personal data, or trade secrets buried inside agreements.

**Examples** include Vanta, OneTrust, BigID, Microsoft Purview, Securiti.ai, Egnyte Governance, CyberArk, Rubrik, Collibra, and Icertis (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted data discovery, open-source governance platforms, and community-driven compliance tooling—ideal for organizations seeking data sovereignty and transparent classification logic over opaque vendor SaaS.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Vanta](https://www.vanta.com/)** | Trust management platform automating compliance (SOC 2, ISO 27001, HIPAA) with continuous control monitoring and evidence collection. Essentials tier covers one framework; Professional adds risk management, custom tests, and advanced reporting . | Quote-only; Vendr data shows small companies (1–50 employees, single framework) at **$12,000–$28,000/year** . Multi-year discounts of 10–25% available . | No free tier; demo via sales. Implementation fees of $2,000–$10,000 may apply . Annual escalation clauses of 5–10% common . |
| **[OneTrust](https://www.oneTrust.com/)** | Privacy, security, and governance platform with modules for consent management, data mapping, and third-party risk. Modular pricing means costs grow as compliance needs expand . | Quote-only. Vendr data: median annual spend **~$10,514** (278 transactions) . Single-domain CMP from **~$827/month**; Privacy Essentials Suite from **~$3,680/month** . | No free tier; demo via sales. Implementation fees 15–30% higher than TrustArc for enterprise deployments . |
| **[BigID](https://bigid.com/)** | Data intelligence platform for sensitive data discovery, classification, and cataloging across 100+ data sources. Integrates with Microsoft Purview Information Protection to automate labeling and policy enforcement . | Microsoft Marketplace: C4 Foundation Package (required base) **$525,000 one-time** (3-year term) for >100 data sources; Purview MPIP integration **$35,000/year** or **$70,000–$105,000 one-time** depending on term . | No free tier; demo via sales . Pricing is enterprise-scale only. |
| **[Microsoft Purview](https://www.microsoft.com/en-us/security/business/microsoft-purview)** | Integrated data security and governance suite. Two billing models: **per-user licensing** (included with Microsoft 365 E3/E5) for M365 and Windows/macOS endpoints; **pay-as-you-go** (Azure-billed) for non-M365 sources including AWS, Azure SQL, Google Drive, and Box . | Per-user: included with M365 E3/E5. Pay-as-you-go: governed assets **~$0.0165/unique asset/day**; Data Map scanning and capacity **free** if Unified Catalog features are not used . | **No separate free tier**; Purview Data Map features are free under pay-as-you-go if you avoid Unified Catalog governance features . |
| **[Securiti.ai](https://securiti.ai/)** | Unified Data Command Center for data security, privacy, governance, and AI safety. Automates sensitive data discovery and compliance across hybrid-cloud environments. Positioned as more aggressive on pricing for competitive deals vs. OneTrust or TrustArc . | Enterprise/custom (subscription based on data volume and connectors) . | No public free tier; demo via sales . |
| **[Egnyte](https://www.egnyte.com/)** | Content governance platform with contract lifecycle management, user permissions, content lifecycle management, unusual behavior detection, and automated compliance workflows. Enterprise Lite tier includes 25 users and 2 TB storage . | Enterprise Lite: **$11,838.75/year** (1-year term, 25 users, 2 TB) . Enterprise Platform: **$20,097/year** adds AI classification, SAR/DSAR fulfillment, and watermarking . | No free tier; demo via sales . |
| **[CyberArk](https://www.cyberark.com/)** | Privileged access management platform. Protects privileged access across identities, infrastructure, and apps. Standard user subscription available via CDW . | Privileged Standard subscription: **$95.75** (1-year, 1 standard user, 24x7 support) . | No free tier; trial via sales . |
| **[Rubrik](https://www.rubrik.com/)** | Data security and cyber resilience platform. Scale Subscription is 3-year minimum; on-prem measured in BETB (post-dedup), cloud in FETB (pre-dedup). Foundation edition covers basic backup; Business adds ransomware protection; Enterprise adds compliance analytics . | Foundation: **$156,000/year** (100 BETB, list); Business: **$195,600/year**; Enterprise: **$273,600/year** . 3-year minimum commitment . | No free tier; trial via sales . Training **$3,000/seat**; professional services extra . |
| **[Collibra](https://www.collibra.com/)** | Data intelligence and governance platform. DQ & Observability module for data quality monitoring. Positioned as premium enterprise pricing . | DQ & Observability: **$150,000–$400,000/year** (10 users, 1,000 tables, list) . | No free tier; demo via sales . |
| **[Icertis](https://www.icertis.com/)** | Contract intelligence platform with data security and governance controls embedded. Manages contract data classification, access controls, and audit trails. No public pricing; Software Advice listing shows placeholder $1.00/year . | Quote-only (enterprise contract) . | No free trial; demo via sales . |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)** | [![Stars](https://img.shields.io/github/stars/open-metadata/OpenMetadata?style=social&color=white)](https://github.com/open-metadata/OpenMetadata/stargazers) | Open-source metadata management and data governance platform (Apache-2.0). Centralized metadata store, data discovery, lineage, and governance workflows. Supports column-level lineage and sensitive data classification. The leading open-source alternative to Collibra for data cataloging . |
| **[DataHub](https://github.com/datahub-project/datahub)** | [![Stars](https://img.shields.io/github/stars/datahub-project/datahub?style=social&color=white)](https://github.com/datahub-project/datahub/stargazers) | Open-source metadata platform (Apache-2.0) from LinkedIn. Real-time metadata ingestion, search, lineage, and governance. Can catalog contract-related data assets and track schema changes across databases . |
| **[Amundsen](https://github.com/amundsen-io/amundsen)** | [![Stars](https://img.shields.io/github/stars/amundsen-io/amundsen?style=social&color=white)](https://github.com/amundsen-io/amundsen/stargazers) | Open-source data discovery and metadata engine (Apache-2.0) from Lyft. Provides searchable data catalog with ownership and documentation. Suitable for organizations building internal data governance foundations . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Apache Atlas](https://github.com/apache/atlas)** | [![Stars](https://img.shields.io/github/stars/apache/atlas?style=social&color=white)](https://github.com/apache/atlas/stargazers) | Open-source metadata and governance framework (Apache-2.0). Provides data classification, lineage, and centralized metadata store. Older but battle-tested for Hadoop ecosystem governance . |
| **[Great Expectations](https://github.com/great-expectations/great_expectations)** | [![Stars](https://img.shields.io/github/stars/great-expectations/great_expectations?style=social&color=white)](https://github.com/great-expectations/great_expectations/stargazers) | Open-source data validation and profiling framework (Apache-2.0). Defines expectations for data quality and validates them against contract-related datasets. Can enforce data governance rules as code . |
| **[OpenDLP](https://github.com/ezra100/OpenDLP)** | [![Stars](https://img.shields.io/github/stars/ezra100/OpenDLP?style=social&color=white)](https://github.com/ezra100/OpenDLP/stargazers) | Open-source data loss prevention scanner. Identifies sensitive data (credit cards, SSNs, etc.) across file shares and databases. Can be adapted to scan contract repositories for PII exposure . |

**Frameworks for building custom systems**: Combine **OpenMetadata** or **DataHub** for data cataloging and lineage across contract repositories, **Great Expectations** for data quality validation on extracted contract metadata, and **OpenDLP** for sensitive data discovery in unstructured contract files—creating a fully self-hosted governance stack without six-figure enterprise licensing.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Contract data security and governance platforms process sensitive commercial terms and personal data; enforce encryption at rest and in transit, least-privilege access, and compliance with GDPR, CCPA, and industry-specific regulations.
- Pricing in this category is extraordinarily opaque: OneTrust and Vanta are quote-only with median spends around $10K–$28K/year, BigID requires a **$525,000 base package**, and Collibra runs **$150K–$400K/year** for modest deployments . Microsoft Purview is the exception—its Data Map features are free under pay-as-you-go if Unified Catalog governance features are avoided . Open-source alternatives (OpenMetadata, DataHub) require engineering effort but eliminate per-asset or per-connector licensing.

---

**Made for compliance officers, data governance teams, legal ops professionals, and developers building secure contract data infrastructure.**  
Let's make contract data security and information governance more open, discoverable, and auditable.
