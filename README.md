# Awesome-Cloud-Activity-Auditing-Governance 🔍 🛡️

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Cloud Activity Auditing Governance Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Activity-Auditing-Governance"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Cloud-Activity-Auditing-Governance?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Activity-Auditing-Governance/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Cloud-Activity-Auditing-Governance?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Cloud-Activity-Auditing-Governance/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Cloud-Activity-Auditing-Governance?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Cloud Activity Auditing & Governance Ecosystem

**Curated List of Commercial Cloud Audit Platforms & Open-Source Security Assessment Tools**  

*Focused on Cloud Trail Analysis, Continuous Compliance Monitoring, Multi-Cloud Security Posture Management (CSPM), SIEM Telemetry & Self-Hosted Security Auditing*

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary

Welcome to the definitive, SEO-optimized repository of **cloud activity auditing platforms**, **open-source security posture management (CSPM) engines**, and **continuous compliance governance frameworks**. Modern cloud infrastructure across AWS, Microsoft Azure, Google Cloud Platform (GCP), and Kubernetes generates vast volumes of API trail records, administrative event logs, and resource mutation streams.

Whether your team requires enterprise-grade commercial SIEM platforms (*AWS CloudTrail Lake*, *Datadog Cloud SIEM*, *Splunk Cloud*, *Prisma Cloud*) or self-hostable open-source security assessment utilities (*Trivy*, *Prowler*, *Falco*, *Checkov*, *Steampipe*, *ScoutSuite*), this curated directory provides granular pricing breakdowns, free tier evaluation limits, market capitalization rankings, and GitHub star analytics.

---

## 📑 Table of Contents

- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms

💡 **Market Overview**: The global Cloud Activity Auditing, SIEM, and Cloud Security Posture Management (CSPM) market is estimated at **~$18.5 Billion in 2026** and projected to expand to **~$34.2 Billion by 2030** at a CAGR of ~16.8%. The market is **moderately fragmented**, with hyperscale cloud providers (Microsoft Azure, AWS, GCP) dominating native audit log collection while third-party enterprise observability and security vendors (Splunk, Palo Alto Networks, Datadog, Rapid7) compete for cross-cloud telemetry aggregation, threat detection, and compliance governance.

*Sorted by Company Size / Market Capitalization (Descending)* 📉

| SaaS / Commercial Platform | Company / Owner | Company Size / Valuation | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Azure Activity Log](https://azure.microsoft.com/en-us/products/monitor/)** 🔷 | Microsoft | ~$3.90 Trillion | **$2.53 per GB** log ingest for Log Analytics workspace | **90-day free retention** in Activity Log; **5 GB/month free** log ingest in Log Analytics | **Azure-native audit logging** — Records subscription-level management events. Integrates with Microsoft Sentinel for enterprise SIEM analytics. |
| **[AWS CloudTrail](https://aws.amazon.com/cloudtrail/)** ☁️ | Amazon | ~$2.0 Trillion | **$2.00 per 100,000 management events** delivered beyond first copy | **90-day free event history** for management events; 1 copy delivered free to S3 | **AWS-native API activity logging** — Audit log records across AWS services. CloudTrail Lake provides SQL-based multi-year querying. |
| **[Google Cloud Audit Logs](https://cloud.google.com/audit-logs)** 🌐 | Google (Alphabet) | ~$2.0 Trillion | **$0.50 per GB** for Cloud Logging ingest beyond free tier | **50 GiB/month free** log ingest; **30-day default retention** free | **GCP-native audit logging** — Tracks Admin Activity, Data Access, and Policy Denied events. BigQuery export for long-term analytics. |
| **[Splunk Cloud](https://www.splunk.com/)** 🟠 | Cisco (Splunk) | ~$200 Billion | **$173 per GB/month** (~$300K/year starting enterprise ingest) | **14-day free trial** with 5 GB/day log ingest limit | **Enterprise SIEM and observability leader** — Advanced cloud log ingestion, threat detection, and audit compliance reporting. |
| **[Prisma Cloud](https://www.paloaltonetworks.com/prisma/cloud)** 🛡️ | Palo Alto Networks | ~$60 Billion | **$100 per credit/year** (~$300/workload unit annually) | **30-day free trial** with access to CSPM and compliance scans | **Cloud Native Application Protection Platform (CNAPP)** — Comprehensive CSPM, CIEM, and multi-cloud compliance auditing. |
| **[Datadog Cloud SIEM](https://www.datadoghq.com/)** 🐶 | Datadog Inc. | ~$40 Billion | **$0.10 per GB** scanned for log analysis + $0.15 per 1k events | **14-day free trial** with full access to Cloud SIEM & Log Management | **Cloud SIEM with real-time log analytics** — Aggregates AWS CloudTrail, Azure Activity Logs, and GCP Audit Logs for unified security posture. |
| **[Rapid7 InsightIDR](https://www.rapid7.com/products/insightidr/)** 🟧 | Rapid7 Inc. | ~$3.0 Billion | **$1.93 per asset/month** (minimum 500 assets = $965/month) | **30-day free trial** with unlimited log ingest for testing | **SIEM & User Behavior Analytics (UEBA)** — Cloud activity monitoring, detection rules, and incident response automation. |
| **[Sumo Logic](https://www.sumologic.com/)** 📈 | Sumo Logic | ~$1.7 Billion | **$3.14 per GB** log analytics ingest (Flex credit pricing model) | **30-day free trial** with 1 GB/day log ingest limit | **Cloud-native SIEM & log analytics** — Flex pricing eliminates base ingest charges; pay only for analytical query workload. |
| **[Panther Labs](https://panther.com/)** 🐾 | Panther Labs | ~$1.4 Billion | **$50,000 per year** base platform fee + $200 per source/year | **30-day sandbox trial** supporting up to 10 log sources | **Detections-as-code cloud SIEM** — Python-based security rules deployed via CI/CD for engineering-driven SOC audit pipelines. |
| **[Lacework](https://www.lacework.com/)** 🕸️ | Fortinet (Lacework) | ~$1.2 Billion | **$1.00 per instance-hour** or $20/agent/month base | **14-day free trial** with full cloud environment scanning | **Polygraph-powered cloud security** — Behavioral baseline analysis of activity logs to detect anomalous API requests and breaches. |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub Stars_Count (Descending)* 🌟

- **[Trivy](https://github.com/aquasecurity/trivy)** [![Stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=social&color=white)](https://github.com/aquasecurity/trivy/stargazers)  
  **Comprehensive open-source security scanner**, Apache-2.0 licensed. Multi-cloud security posture management (AWS, Azure, GCP), vulnerability scanner, and misconfiguration auditor for container images, Kubernetes clusters, and Infrastructure as Code (IaC). 🛡️

- **[Prowler](https://github.com/prowler-cloud/prowler)** [![Stars](https://img.shields.io/github/stars/prowler-cloud/prowler?style=social&color=white)](https://github.com/prowler-cloud/prowler/stargazers)  
  **Premier open-source cloud security assessment tool**, Apache-2.0 licensed. Performs multi-cloud security audits for AWS, Azure, GCP, and Kubernetes. Includes **553+ checks for AWS, 138 for Azure, 77 for GCP, and 83 for Kubernetes** covering CIS, NIST 800, PCI-DSS, GDPR, HIPAA, and SOC2 standards. Outputs OCSF JSON. ⚡

- **[Falco](https://github.com/falcosecurity/falco)** [![Stars](https://img.shields.io/github/stars/falcosecurity/falco?style=social&color=white)](https://github.com/falcosecurity/falco/stargazers)  
  **Cloud-native runtime security & activity auditing engine**, Apache-2.0 licensed. Monitors kernel system calls and cloud event streams in real time. Detects unexpected behavioral changes, unauthorized privilege escalation, and policy violations in cloud workloads. 🦅

- **[Checkov](https://github.com/bridgecrewio/checkov)** [![Stars](https://img.shields.io/github/stars/bridgecrewio/checkov?style=social&color=white)](https://github.com/bridgecrewio/checkov/stargazers)  
  **Static code analysis for Infrastructure as Code (IaC)**, Apache-2.0 licensed. Scans Terraform, CloudFormation, Kubernetes, ARM templates, and Serverless frameworks to audit security misconfigurations before deployment. 🔎

- **[Steampipe](https://github.com/turbot/steampipe)** [![Stars](https://img.shields.io/github/stars/turbot/steampipe?style=social&color=white)](https://github.com/turbot/steampipe/stargazers)  
  **Query cloud infrastructure with SQL**, AGPL-3.0 licensed. Zero-ETL engine allowing engineers to query AWS CloudTrail, Azure Monitor, GCP Audit Logs, Kubernetes, and 100+ services using standard SQL statements. 🔗

- **[ScoutSuite](https://github.com/nccgroup/ScoutSuite)** [![Stars](https://img.shields.io/github/stars/nccgroup/ScoutSuite?style=social&color=white)](https://github.com/nccgroup/ScoutSuite/stargazers)  
  **Multi-cloud security auditing engine**, GPL-2.0 licensed. Collects configuration telemetry via cloud provider APIs (AWS, Azure, GCP, Alibaba, Oracle) to evaluate security posture and flag publicly exposed S3 buckets, weak IAM policies, and open security groups. 🔍

- **[CloudQuery](https://github.com/cloudquery/cloudquery)** [![Stars](https://img.shields.io/github/stars/cloudquery/cloudquery?style=social&color=white)](https://github.com/cloudquery/cloudquery/stargazers)  
  **High-performance cloud asset inventory & CSPM engine**, MPL-2.0 licensed. Extracts cloud configuration assets into PostgreSQL or Snowflake to build custom governance dashboards and compliance reports. 📦

- **[Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian)** [![Stars](https://img.shields.io/github/stars/cloud-custodian/cloud-custodian?style=social&color=white)](https://github.com/cloud-custodian/cloud-custodian/stargazers)  
  **Stateless rules engine for cloud governance**, Apache-2.0 licensed. Enables real-time policy enforcement, security compliance checks, resource tag enforcement, and cost optimization across AWS, Azure, and GCP. 🤖

- **[Cartography](https://github.com/lyft/cartography)** [![Stars](https://img.shields.io/github/stars/lyft/cartography?style=social&color=white)](https://github.com/lyft/cartography/stargazers)  
  **Graph-based cloud asset and relationship mapper**, Apache-2.0 licensed. Consolidates multi-cloud infrastructure assets and IAM permissions into Neo4j graph views to analyze attack paths and privilege boundaries. 🗺️

- **[CloudFox](https://github.com/BishopFox/cloudfox)** [![Stars](https://img.shields.io/github/stars/BishopFox/cloudfox?style=social&color=white)](https://github.com/BishopFox/cloudfox/stargazers)  
  **AWS penetration testing & activity audit tool**, Apache-2.0 licensed. Automates cloud situational awareness, enumerating S3 bucket access, cross-account privilege escalation, secrets in environment variables, and EKS exposures. 🦊

- **[Cloudsplaining](https://github.com/salesforce/cloudsplaining)** [![Stars](https://img.shields.io/github/stars/salesforce/cloudsplaining?style=social&color=white)](https://github.com/salesforce/cloudsplaining/stargazers)  
  **AWS IAM security assessment engine**, BSD-3-Clause licensed. Parses IAM policies to identify least-privilege violations, wildcard permissions, data exfiltration risks, and privilege escalation vectors. 🔐

- **[Matano](https://github.com/matanolabs/matano)** [![Stars](https://img.shields.io/github/stars/matanolabs/matano?style=social&color=white)](https://github.com/matanolabs/matano/stargazers)  
  **Open-source serverless security data lake**, Apache-2.0 licensed. Ingests petabytes of CloudTrail, VPC Flow Logs, and audit streams into Apache Iceberg format with Python detections as code. 🏞️

- **[PacBot (Policy as Code Bot)](https://github.com/tmobile/pacbot)** [![Stars](https://img.shields.io/github/stars/tmobile/pacbot?style=social&color=white)](https://github.com/tmobile/pacbot/stargazers)  
  **T-Mobile's continuous compliance & CSPM framework**, Apache-2.0 licensed. Automated cloud governance platform with policy-as-code evaluation, misconfiguration discovery, and auto-remediation. 🤖

- **[Substation](https://github.com/brexhq/substation)** [![Stars](https://img.shields.io/github/stars/brexhq/substation?style=social&color=white)](https://github.com/brexhq/substation/stargazers)  
  **Security event & audit log routing toolkit**, Apache-2.0 licensed. Scalable data pipeline toolkit for normalizing, enriching, and routing high-volume AWS CloudTrail and cloud audit streams to data lakes. 🚰

- **[Clouditor](https://github.com/clouditor/clouditor)** [![Stars](https://img.shields.io/github/stars/clouditor/clouditor?style=social&color=white)](https://github.com/clouditor/clouditor/stargazers)  
  **Continuous cloud assurance & compliance auditor**, Apache-2.0 licensed. Evaluates multi-cloud environments (AWS, Azure, OpenStack) against BSI C5 and CSA CCM security compliance frameworks. 🎯

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new cloud activity auditing platforms or open-source governance software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Cloud-Activity-Auditing-Governance&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Cloud-Activity-Auditing-Governance&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

Thank you for exploring this curated cloud activity auditing & governance resource! If you find this repository valuable for your cloud security, compliance, or DevOps workflows, please consider supporting the project:

- ⭐ **Star** this repository to help others discover it!
- 🔀 **Fork** and share with fellow cloud security engineers, auditors, and open-source advocates.
- ☕ **Buy Me a Coffee / Sponsor**: Support ongoing curation and open-source updates via the [GitHub Sponsor Dashboard](http://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- **Audit-trail logs have limited default retention**: AWS CloudTrail **90 days**, GCP Cloud Audit Logs **30 days**, Azure Activity Log **90 days**. These default tiers are not 7-year compliance archives — log streams must be exported to object storage or a SIEM pipeline for long-term audit compliance. 📂
- **Ingest costs dominate long-term retention bills**: Ingestion fees at **$0.63/GB to $2.53/GB** account for the vast majority of cloud monitoring expenses before long-term archiving. Direct-to-S3/GCS logging architecture reduces long-term audit trail storage costs significantly. 💰
- Open-source solutions (Trivy, Prowler, Falco, ScoutSuite, Steampipe) provide transparent self-hosted ownership, while enterprise commercial platforms offer managed SLA guarantees, compliance reporting, and 24/7 support. Always validate audit configurations against your organization's compliance requirements. 🔒

---

<p align="center">
  <b>Made with ❤️ for cloud security engineers, compliance officers, and open-source governance advocates.</b>
</p>
