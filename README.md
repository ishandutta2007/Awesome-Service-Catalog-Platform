# Awesome-Service-Catalog-Platform

## Top Service Catalog Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Internal Developer Portals, Software Catalogs, Service Ownership, Scorecards & Platform Engineering*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Service Catalog** and Internal Developer Portals. These systems provide a centralized inventory of services, ownership, documentation, dependencies, and self-service capabilities so engineering teams can discover, understand, and manage software at scale.



**Examples** include Backstage, Port, OpsLevel, Cortex, Atlassian Compass, Roadie, ServiceNow Service Catalog, CloudTruth, Mia-Platform, Humanitec, Rundeck, Morpheus Data, CloudBolt, FireHydrant, StackState, and Appvia (the category leaders).



**Open-source emphasis**: **Backstage** (CNCF) is the dominant open-source framework for building developer portals and software catalogs. Most commercial offerings are either managed Backstage (Roadie) or proprietary portals inspired by the same concepts. Additional open-source related projects and plugins are listed below.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Platform / Product | Description | Starting Tier Pricing | Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- |
| **[Port](https://www.getport.io/)** | Flexible internal developer portal & service catalog focused on data modeling, self-service actions, and scorecards. | $30 / seat / month (Basic plan) | Free forever for up to 15 seats |
| **[OpsLevel](https://www.opslevel.com/)** | Service catalog and developer portal emphasizing service maturity scorecards and operational standards. | ~$39 / developer / month (Standard plan) | 14-day to 30-day free trial / Proof-of-Concept |
| **[Cortex](https://www.cortex.io/)** | Engineering intelligence and developer portal for scorecards, production readiness, and cataloging. | ~$35 / developer / month (Starting tier) | 14-day guided free trial / Proof-of-Concept |
| **[Atlassian Compass](https://www.atlassian.com/software/compass)** | Component catalog and portal tightly integrated with Jira, Bitbucket, and Atlassian tools. | $7.00 / full user / month (Standard plan) | Free forever for up to 3 full users (unlimited basic users) |
| **[Roadie](https://roadie.io/)** | Managed SaaS Backstage offering providing a hosted software catalog without operational overhead. | $24 / developer / month (Teams plan) | 30-day free trial (SaaS) / Free forever for <15 users (Roadie Local) |
| **[Humanitec](https://humanitec.com/)** | Internal developer platform and cloud-native application orchestrator with service catalog capabilities. | $1,979 / month (Teams plan, 5 users) | 30-day free trial |
| **[Mia-Platform](https://mia-platform.eu/)** | Enterprise internal developer platform and software catalog for orchestrating microservices and APIs. | ~$5,000 / month ($60,000/yr base tier) | 30-day guided free trial / Proof-of-Concept |
| **[Appvia (Wayfinder)](https://www.appvia.io/)** | Kubernetes developer portal and platform management tool for self-service infrastructure. | $799 / month (Pro plan up to 3 products) | Free forever for 1 product (unlimited users) |
| **[ServiceNow Service Catalog](https://www.servicenow.com/)** | Enterprise IT service catalog and request portal embedded within ServiceNow ITSM. | ~$70 / fulfiller user / month (ITSM starting tier) | Free Personal Developer Instance (PDI) sandbox |
| **[CloudTruth](https://www.cloudtruth.com/)** | Centralized configuration management platform providing parameter and secret context to catalogs. | $499 / month (Pro plan) | 14-day free trial (Free forever for open-source & non-profits) |
| **[FireHydrant](https://www.firehydrant.com/)** | Incident management platform with service catalog mapping services, ownership, and response. | $25 / responder / month (Pro plan, annual) | Free forever for up to 10 responders (or 14-day Pro trial) |
| **[StackState](https://www.stackstate.com/)** | Observability and topology-based catalog (SUSE Cloud Observability) mapping service dependencies. | $99 / month ($9.99/host/mo, min 10 hosts) | 30-day free trial (Free for SUSE Rancher Prime users) |
| **[Rundeck](https://www.rundeck.com/)** | Self-service runbook automation platform serving as an action execution backend for developer portals. | $59 / user / month (PagerDuty Runbook Automation SaaS) | Free forever for Community Edition (self-hosted) / 14-day trial (SaaS) |
| **[Morpheus Data](https://morpheusdata.com/)** | Multi-cloud management and self-service orchestration portal for hybrid IT and platform engineering. | ~$2,083 / month ($25,000/yr entry tier) | Free Community Edition (home lab) / 60-day trial (VM Essentials) |
| **[CloudBolt](https://www.cloudbolt.io/)** | Hybrid cloud management platform and self-service portal for provisioning infrastructure and services. | ~$708 / month ($8,500/yr entry subscription) | Free forever for up to 100 managed resources |



## Open-Source GitHub Projects



- **[Backstage](https://github.com/backstage/backstage)**  

  The leading open-source framework for building internal developer portals and software catalogs (created by Spotify, now CNCF). Provides a powerful Software Catalog, Software Templates, TechDocs, and an extensive plugin ecosystem.



- **[Backstage Software Catalog](https://backstage.io/docs/features/software-catalog/)**  

  Core Backstage feature that ingests metadata YAML files from repositories to maintain a living inventory of services, libraries, websites, and other software entities with ownership and relations.



- **[Roadie / managed Backstage alternatives](https://roadie.io/)**  

  While Roadie itself is commercial, it is built directly on open-source Backstage and contributes to the ecosystem.



- **[Kratix & platform orchestration tools](https://github.com/syntasso/kratix)**  

  Open-source platform-engineering framework that can integrate with Backstage to provide self-service infrastructure and service provisioning.



- **[Score](https://github.com/score-spec/spec)**  

  Open specification and tooling for defining workload specifications that can feed developer portals and platform abstractions.



- **[Other Backstage plugins & extensions](https://github.com/backstage/backstage/tree/master/plugins)**  

  Large collection of official and community plugins that extend the catalog, add scorecards, integrate with CI/CD, Kubernetes, monitoring, and more.



- **[Open Service Portal & community Backstage distributions](https://github.com/open-service-portal)**  

  Community efforts to package and extend Backstage into ready-to-use internal developer platforms.



- **[Additional catalog & portal experiments](https://github.com/search?q=developer+portal+OR+service+catalog+OR+backstage)**  

  Emerging open-source projects exploring service discovery, ownership tracking, and self-service portals.



### Additional Strong Open-Source Options



- **Software Templates (Cookiecutter, Cookiecutter-based, Backstage Scaffolder)**: Standardized service creation flows.

- **TechDocs / documentation-as-code**: Backstage’s built-in docs system and related MkDocs tooling.

- **Entity providers & ingestion**: Connectors that pull data from GitHub, Kubernetes, cloud providers, and CI systems into the catalog.

- **Scorecard & maturity plugins**: Community and commercial plugins that implement service maturity models on top of Backstage.

- **IDP reference architectures**: Open examples of how organizations structure their Backstage deployments.

- Integration with open-source observability, CI/CD, and infrastructure-as-code tools.



**Frameworks for building custom systems**:  

The clear open-source foundation is **Backstage**. Most organizations either self-host Backstage, use a managed offering such as Roadie, or adopt a commercial portal (Port, Cortex, OpsLevel, Compass) that provides similar catalog and scorecard capabilities with less operational effort.  

Backstage’s strength is extreme flexibility and a rich plugin model; its trade-off is the engineering investment required to customize and maintain it.  

Commercial platforms trade some flexibility for faster time-to-value, hosted operations, and opinionated features around scorecards and self-service.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Service catalogs and developer portals become sources of truth for ownership, compliance, and operational readiness. Accuracy of metadata, access control, and integration quality are critical.

- Self-hosting Backstage or other open-source portals requires dedicated platform-engineering capacity for upgrades, plugin maintenance, and reliability. Evaluate total cost of ownership carefully against managed or commercial alternatives.



---



**Made for platform engineers, internal developer platform teams, engineering managers, and SREs.**  

Let's make software discoverable, owned, and self-serviceable through open frameworks and well-designed commercial portals.
