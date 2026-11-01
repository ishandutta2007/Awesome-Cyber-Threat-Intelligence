# Awesome-Cyber-Threat-Intelligence

# Awesome-Cyber-Threat-Intelligence
**Top Cyber Threat Intelligence (Opensource) 🌟 Star if you like it! 🌟**

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Adversary Tracking, IOC Enrichment, Dark Web Monitoring & Self-Hosted Intelligence Platforms*
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cyber Threat Intelligence (CTI)**. These tools enable security teams to collect, enrich, analyze, and operationalize intelligence about adversaries, their infrastructure, and their tactics—from fully managed enterprise platforms with proprietary dark web collection and finished intelligence reports to self-hosted platforms that give organizations control over their intelligence data and sharing communities.

**Examples** include CrowdStrike Falcon Intelligence, Recorded Future, Mandiant Threat Intelligence, Flashpoint, Palo Alto Unit 42, Microsoft Defender Threat Intelligence, IntSights (Rapid7), ZeroFox, Cybersixgill, and ThreatConnect (the category leaders in commercial space).

**Open-source emphasis**: This section is expanded with every relevant project for self-hosted threat intelligence, IOC management, and open intelligence sharing. **Critical note**: The open-source CTI landscape is anchored by **MISP** and **OpenCTI**—both are production-grade, widely deployed, and serve different primary purposes (sharing communities vs. knowledge management) . **IntelOwl** provides enrichment, **Yeti** focuses on CTI-DFIR intersection, and **Threat Bus** handles dissemination . No open-source project matches Recorded Future's Intelligence Graph or Mandiant's frontline incident response telemetry, but for intelligence management and sharing, the open-source options are mature.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[CrowdStrike Falcon Intelligence](https://www.crowdstrike.com/)**
  **Threat intelligence integrated with Falcon platform**, named a **Leader in the inaugural Gartner Magic Quadrant for Cyberthreat Intelligence Technologies** (2026) . **Features**: Automatically investigates malware found on endpoints; finds related samples from CrowdStrike's malware search engine; enriches results with customized threat intelligence; provides custom IOCs to share with other security tools; intelligence reporting tells the complete attack story . **Pricing**: **Falcon Go free** (100 devices max, includes Threat Intelligence & Hunting); **Falcon Pro $14.99/device/month**; **Falcon Enterprise $19.99**; **Falcon Complete $59.99–$184.99/device annually**; **Falcon Intelligence Expansion Pack** separate subscription (up to 5,000 files/month) . **Free tier**: Yes, Falcon Go free with threat intelligence. **Best for**: CrowdStrike customers wanting intelligence tightly coupled to endpoint telemetry—**trade-off**: full intelligence depth requires Falcon platform and expansion packs.

- **[Recorded Future](https://www.recordedfuture.com/)**
  **Intelligence platform** with Intelligence Graph and three packages: **Core** (foundational cyber ops and digital risk protection), **Professional** (adds autonomous threat hunts, continuous monitoring, external intelligence ingestion), **Elite** (adds third-party risk) . All packages include full Intelligence Graph access, Recorded Future AI, integrations, APIs, and Collective Insights—no hidden costs . **Pricing**: **Quote-only**; packages scale with maturity. **Free tier**: Not specified in results. **Best for**: enterprises wanting comprehensive intelligence across cyber ops, digital risk, and third-party risk—**trade-off**: quote-only pricing; package structure requires careful scope modeling.

- **[Mandiant Threat Intelligence](https://www.mandiant.com/)**
  **Frontline intelligence** from incident response experts. **Free tier**: **Mandiant Advantage Free** includes dynamic actor and malware pivot views with MITRE ATT&CK map, object explorer, indicator downloads (IP, domain, file hash, URL with maliciousness scoring), news analysis, quarterly threat briefings, and API access . **Security Operations** subscription adds up-to-the-minute actor/malware/vulnerability tracking and SOC alert correlation . **Fusion** subscription provides full unlimited access to all Mandiant intelligence including historical and predictive activity . **Pricing**: Quote-only for paid tiers. **Free tier**: Yes, substantial free tier. **Best for**: teams wanting intelligence grounded in real incident response—**trade-off**: full value requires paid subscriptions; free tier is lookup-focused.

- **[Flashpoint](https://flashpoint.io/)**
  **Threat intelligence platform** with illicit community collection. **Core Packages**: **Cyber Threat Intelligence** (Flashpoint Ignite, API access, account takeover credentials, vulnerability intelligence, curated alerts, integrations); **Vulnerability** (415,000+ vulnerabilities including non-CVEs without scanning); **Physical Security** (Echosec, global event monitoring) . **Pricing**: **Quote-only**; claims **482% ROI in 6 months** and **$500M fraud loss avoided per year** . **Free tier**: None. **Best for**: CTI and fraud teams needing broad illicit-source coverage—**trade-off**: enterprise pricing; value depends on dark web relevance to your threat model.

- **[Palo Alto Unit 42](https://www.paloaltonetworks.com/)**
  **Threat intelligence and offensive security services**. **Unit 42 Continuous Frontier AI Defense** (available on OpenAI Marketplace) is an always-on, agentic offensive security service that discovers, validates, and accelerates remediation of exposures using defender-grade models including GPT-5.6-Cyber . Internal deployment uncovered **two years' worth of exposures in three weeks**; customer assessments found exposures in **100% of organizations**, with **37% high/critical severity**; over **two-thirds of third-party exposures had no known CVE** . **Pricing**: Annual subscription; quote-only. **Free tier**: None. **Best for**: enterprises wanting AI-driven exposure validation alongside threat intelligence—**trade-off**: premium service; requires Palo Alto engagement.

- **[Microsoft Defender Threat Intelligence](https://www.microsoft.com/security/)**
  **Threat intelligence integrated into Defender XDR and Sentinel**. **Standalone MDTI portal retired**; intelligence now available in Defender portal (Intelligence Explorer, Intel profiles) and Sentinel via free Microsoft Threat Intelligence connector . **Pricing**: Available at **no additional MDTI charge within Defender XDR and Sentinel**, but requires eligible Defender XDR or Sentinel license—**not universally free** . **Free tier**: Limited community version existed; now integrated into licensed products. **Best for**: Microsoft security customers wanting intelligence embedded in existing workflows—**trade-off**: requires Defender XDR/Sentinel licensing; standalone portal no longer available.

- **[IntSights (Rapid7)](https://www.rapid7.com/)**
  **External threat protection** within Rapid7's security operations platform. **Features**: Cloud-based external threat detection; deep and dark web harvesting; network traffic pattern analysis; complete exposure monitoring . **Pricing**: Quote-only; no public pricing. Gartner reviewers note **quality has declined since Rapid7 acquisition** and **limited API integrations with SOC orchestration** . **Free tier**: None. **Best for**: Rapid7 customers wanting external threat visibility integrated with their platform—**trade-off**: post-acquisition quality concerns; limited customization for large organizations.

- **[ZeroFox](https://www.zerofox.com/)**
  **Digital risk protection** platform with threat intelligence. **Features**: Brand, executive, attack surface, and threat intelligence protection; **Global Disruption Network** with 80+ provider ecosystem for takedowns; analyst-vetted alerts with context; built-in remediation workflows . Claims **287% ROI** (Forrester TEI study) and **M+ disruptions** . **Pricing**: **Outcome-based, not per-headcount**—intelligence shared across teams . **Free tier**: None. **Best for**: organizations prioritizing brand protection and takedown capability alongside intelligence—**trade-off**: digital risk focus; less depth in pure adversary tracking.

- **[Cybersixgill](https://cybersixgill.com/)**
  **Dark web intelligence** platform with Investigative Portal. **Features**: One of the largest dark web data lakes; real-time alerts; threat actor analysis with profiles and history; access to exclusive sources including Genesis Marketplace; automatic translations; API capabilities . PeerSpot rating **8.8/10**; users recommend for IOC to threat advisories and dark web intelligence . **Pricing**: **Good ROI due to favorable pricing model and lower setup costs** per PeerSpot . **Free tier**: Not specified. **Best for**: teams needing deep dark web coverage—**trade-off**: onboarding requires careful false positive tuning; portal-centric.

- **[ThreatConnect](https://threatconnect.com/)**
  **Threat intelligence operations platform (TI Ops)**. **Features**: Ingests hundreds of internal and external sources; enriches with AI; aligns to intelligence requirements and MITRE ATT&CK gaps; operationalizes across SOC, IR, hunt, and vulnerability teams . **Pricing**: **Quote-only**; no public plans . **Free tier**: Trial listed; free version unclear. **Best for**: enterprises wanting intelligence operations alignment across teams—**trade-off**: no transparent pricing; requires sales engagement.

## Open-Source GitHub Projects

- **[MISP](https://github.com/MISP/MISP)**
  **Open Source Threat Intelligence Platform** (AGPL-3.0) — **the most widely deployed open-source threat intelligence sharing platform**, used by security teams, CERTs, and national agencies worldwide . **Features**: **IOC management and correlation**—store, correlate, and share indicators of compromise; **sharing communities** with granular distribution controls; **taxonomies and galaxies** for structured classification; **STIX/TAXII support**; **MISP Workflows** for automation; **MISP Modules** for expansion and enrichment . **Tech stack**: PHP, MySQL. **Deploy**: Self-hosted (Docker, packages). **Trade-off**: **UI feels dated**; complex for small teams; sharing requires community trust and governance. **Best for**: organizations needing to participate in intelligence sharing communities—the de facto standard for ISACs, CERTs, and threat sharing groups.

- **[OpenCTI](https://github.com/OpenCTI-Platform/opencti)**
  **Open Cyber Threat Intelligence Platform** (Apache-2.0) — **the most capable open-source knowledge management platform for CTI**, built on STIX 2.1 . **Features**: **Structured knowledge base** of threat actors, campaigns, malware, tools, and indicators with relationships; **STIX 2.1 native**—all data modeled in the standard; **connectors** for MISP, MITRE ATT&CK, VirusTotal, AlienVault, and more; **visualization** with graphs and timelines; **role-based access control**; **export to STIX, CSV, PDF** . **Tech stack**: Python, GraphQL, Elasticsearch, Redis, RabbitMQ. **Deploy**: Self-hosted (Docker Compose). **Trade-off**: **Resource-heavy** (Elasticsearch, Redis, RabbitMQ); steeper learning curve than MISP for simple sharing. **Best for**: teams wanting a knowledge-centric CTI platform with rich relationships and STIX-native modeling—especially those building intelligence programs from the ground up.

- **[IntelOwl](https://github.com/intelowlproject/IntelOwl)**
  **Open-source intelligence enrichment platform** (AGPL-3.0) — **the best open-source tool for IOC enrichment at scale** . **Features**: **Enriches observables** (IPs, domains, hashes, URLs) with 100+ analyzers including VirusTotal, Shodan, AbuseIPDB, GreyNoise, and more; **REST API and web UI**; **supports multiple observable types**; **scan and analyze files**; **connector integrations** with MISP, OpenCTI, and SIEMs . **Tech stack**: Python, Django, Celery, RabbitMQ, PostgreSQL. **Deploy**: Self-hosted (Docker Compose). **Trade-off**: **Enrichment only**—not a full TIP for intelligence management or sharing; requires API keys for most analyzers. **Best for**: SOC teams wanting to enrich IOCs with multiple intelligence sources without a commercial platform.

- **[Yeti](https://github.com/yeti-platform/yeti)**
  **Platform for organizing observables and indicators** (Apache-2.0) — **the CTI-DFIR intersection tool**, designed for teams that need to track observables across investigations . **Features**: **Observable and indicator management**; **analysis and correlation**; **investigation workflows**; **integrations** with MISP and other tools; **REST API** . **Tech stack**: Python, MongoDB, Redis, Docker. **Deploy**: Self-hosted. **Trade-off**: **Smaller community than MISP or OpenCTI**; less active development; focused on DFIR workflows rather than broad sharing. **Best for**: incident response and threat hunting teams wanting a lightweight observable tracking platform alongside their TIP.

### Additional Strong Open-Source Options

- **Threat Bus** — Threat intelligence dissemination layer (BSD-3-Clause). Routes intelligence between security systems; integrates with MISP, OpenCTI, and other tools . **Note**: **Dissemination layer, not a TIP**—does not replace MISP or OpenCTI for intelligence management; recent maintenance activity appears limited . **Best for**: teams needing efficient intelligence distribution between systems.
- **TheHive (legacy)** — Collaborative incident response platform (AGPL-3.0 for v3/v4). **Note**: **TheHive 3 and 4 are no longer maintained or publicly distributed**—latest version is commercially distributed . **Do not adopt for new deployments.** **Best for**: historical reference only.

**Frameworks for building custom systems**: Combine **OpenCTI** for knowledge management with **MISP** for sharing communities, **IntelOwl** for enrichment, and **Threat Bus** for dissemination—creating a complete open-source CTI stack. **None of these match Recorded Future's Intelligence Graph or Mandiant's incident response telemetry**, but for intelligence management, sharing, and enrichment, the open-source options are mature and production-proven.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Threat intelligence platforms handling sensitive intelligence data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls for intelligence sharing and dark web collection.
- **The "proprietary intelligence platform" vs. "sharing platform" vs. "knowledge management" vs. "enrichment" distinction is critical.** **CrowdStrike, Recorded Future, Mandiant, Flashpoint, Unit 42, Microsoft, IntSights, ZeroFox, Cybersixgill, and ThreatConnect** are **proprietary intelligence platforms**—they provide curated intelligence, analysis, and often finished reports . **MISP** is a **sharing platform**—it excels at IOC management and community sharing . **OpenCTI** is **knowledge management**—it models threat actors, campaigns, and relationships in STIX 2.1 . **IntelOwl** is **enrichment**—it adds context to observables but does not manage intelligence programs . **Yeti** is **CTI-DFIR**—it tracks observables across investigations . **Choose based on whether you need curated intelligence, sharing, knowledge management, or enrichment.**
- **Microsoft retired standalone MDTI.** Intelligence is now embedded in Defender XDR and Sentinel—**available at no additional MDTI charge but requires eligible licensing** . **Do not plan to evaluate the standalone portal.**
- **IntSights quality has reportedly declined since Rapid7 acquisition.** Gartner reviewers note reduced intel quality and limited API integrations . **Evaluate carefully before committing.**
- **MISP and OpenCTI serve different primary purposes.** MISP is the standard for **sharing communities** (ISACs, CERTs); OpenCTI is the standard for **knowledge management** (STIX-native modeling, relationships) . **Many organizations run both**—MISP for sharing, OpenCTI for analysis.
- **TheHive 3/4 is no longer maintained.** The current version is commercially distributed—**do not adopt for new open-source deployments** .
- **Pricing opacity varies.** CrowdStrike publishes device-based pricing. Recorded Future, Mandiant (paid tiers), Flashpoint, Unit 42, IntSights, ZeroFox, Cybersixgill, and ThreatConnect require sales contact or quote requests. **Validate with direct vendor conversations against your intelligence requirements and team size.**
- Self-hosted open-source solutions require proper infrastructure (Elasticsearch/Redis/RabbitMQ for OpenCTI, PHP/MySQL for MISP, Django/Celery for IntelOwl), security hardening, and ongoing maintenance. **Threat intelligence data is highly sensitive**—ensure your deployment meets your organization's security and sharing governance requirements before storing or distributing intelligence.

---

**Made for CTI analysts, SOC teams, and organizations building transparent threat intelligence solutions.**
Let's make Cyber Threat Intelligence more open, data-driven, and adversary-aware.
