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



- **[Port](https://www.getport.io/)**  

  Popular hosted internal developer portal and service catalog focused on flexible data modeling, self-service actions, and platform engineering workflows.



- **[OpsLevel](https://www.opslevel.com/)**  

  Service catalog and developer portal emphasizing service maturity scorecards, operational standards, and ownership tracking.



- **[Cortex](https://www.cortex.io/)**  

  Engineering intelligence and service catalog platform strong in scorecards, production readiness, and service ownership visibility.



- **[Atlassian Compass](https://www.atlassian.com/software/compass)**  

  Developer portal and component catalog tightly integrated with the Atlassian ecosystem (Jira, Bitbucket, etc.).



- **[Roadie](https://roadie.io/)**  

  Managed Backstage offering that provides a hosted, supported Backstage experience with enterprise features and reduced operational overhead.



- **[Humanitec, Mia-Platform, Appvia](https://humanitec.com/)**  

  Internal developer platform and platform-engineering solutions that include service catalog and self-service capabilities.



- **[ServiceNow Service Catalog](https://www.servicenow.com/)**  

  Enterprise service catalog capabilities within the broader ServiceNow platform, often used for IT and developer request workflows.



- **[CloudTruth, FireHydrant, StackState](https://www.cloudtruth.com/)**  

  Specialized tools that contribute configuration, incident, or observability context to service catalogs and developer portals.



- **[Rundeck, Morpheus, CloudBolt](https://www.rundeck.com/)**  

  Self-service automation and cloud-management platforms that frequently serve as action backends for service catalogs.



- **[Other developer portal & catalog platforms](https://backstage.io/)**  

  Additional commercial solutions in the internal developer portal and platform-engineering space.



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
