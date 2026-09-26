# Awesome-Engineering-Intelligence-Platform

# 🧠 Top Engineering Intelligence Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Engineering Intelligence, Developer Productivity, Developer Experience, DORA Metrics, Software Engineering Analytics, Value Stream Management & Engineering Management*
**Last updated: September 2026**

This repository tracks notable **SaaS/Hosted platforms** and **open-source GitHub projects** for **Engineering Intelligence**.

Engineering Intelligence platforms aggregate data from source control, pull requests, code reviews, CI/CD, issue trackers, project-management systems, incidents, deployments and developer-experience signals to provide a unified view of software delivery.

These platforms are commonly used to measure **DORA metrics, engineering velocity, PR cycle time, review time, deployment performance, developer experience, engineering capacity, investment allocation, software delivery bottlenecks, technical debt, developer productivity and business impact**.

**Examples** include Jellyfish, Faros AI, LinearB, Swarmia, Code Climate Velocity, DX, Typo, Pluralsight Flow, Waydev and Haystack.

**Open-source emphasis:** This repository places particular emphasis on **self-hosted Engineering Intelligence platforms**, while also including open-source developer analytics frameworks, DORA implementations, engineering-data platforms, software-development analytics projects, code intelligence tools and visualization/BI building blocks.

A key distinction is that an **Engineering Intelligence platform** normally combines several layers:

```text
Git / GitHub / GitLab
        +
Jira / Linear / Issues
        +
CI/CD
        +
Deployments
        +
Incidents
        +
Code Quality
        +
Developer Experience
        ↓
Engineering Data Platform
        ↓
Metrics / DORA / SPACE
        ↓
Engineering Intelligence
        ↓
Management & Developer Insights
```

Open-source projects such as **Apache DevLake** and **GrimoireLab** provide particularly important foundations because they ingest and correlate software-development data from multiple systems rather than focusing only on Git statistics. Apache DevLake describes itself as an open-source dev-data platform for ingesting, analyzing and visualizing fragmented DevOps data, with pre-built DORA and other engineering dashboards.

Contributions welcome! Add new Engineering Intelligence platforms, developer analytics projects, DORA implementations, engineering-data connectors and self-hosted alternatives.

---

## Table of Contents

* [SaaS/Hosted Platforms](#saashosted-platforms)
* [Open-Source GitHub Projects](#open-source-github-projects)

  * [Complete Engineering Intelligence Platforms](#complete-engineering-intelligence-platforms)
  * [Software Development Analytics Platforms](#software-development-analytics-platforms)
  * [DORA & DevOps Intelligence](#dora--devops-intelligence)
  * [Developer Productivity & Engineering Metrics](#developer-productivity--engineering-metrics)
  * [Code & Repository Analytics](#code--repository-analytics)
  * [Engineering Data & Observability Platforms](#engineering-data--observability-platforms)
  * [Visualization & BI](#visualization--bi)
  * [Additional Strong Open-Source Options](#additional-strong-open-source-options)
* [Commercial → Open-Source Capability Mapping](#commercial--open-source-capability-mapping)
* [Framework for Building a Self-Hosted Engineering Intelligence Platform](#framework-for-building-a-self-hosted-engineering-intelligence-platform)
* [How to Contribute](#how-to-contribute)
* [Disclaimer](#disclaimer)

---

## SaaS/Hosted Platforms

* **[Jellyfish](https://www.jellyfish.co/)**
  Engineering management platform connecting engineering activity and resource allocation with business strategy, product priorities and investment decisions.

* **[Faros AI](https://www.faros.ai/)**
  Engineering intelligence and data platform that unifies engineering data across development and delivery systems to provide visibility into engineering performance and organizational workflows.

* **[LinearB](https://linearb.io/)**
  Engineering intelligence platform combining DORA metrics, software delivery analytics, developer productivity insights and workflow automation.

* **[Swarmia](https://www.swarmia.com/)**
  Engineering productivity and developer-experience platform providing insights into software delivery, team health, DORA metrics, developer experience and engineering workflows.

* **[Code Climate Velocity](https://codeclimate.com/velocity/)**
  Engineering intelligence and developer productivity platform focused on software delivery performance, engineering velocity and workflow analytics.

* **[DX](https://getdx.com/)**
  Developer experience platform combining engineering productivity data with developer surveys and qualitative signals to analyze friction, developer experience and organizational effectiveness.

* **[Typo](https://typoapp.io/)**
  Engineering management and developer productivity platform combining DORA metrics, engineering analytics, project tracking, developer experience and engineering insights.

* **[Pluralsight Flow](https://www.pluralsight.com/product/flow)**
  Engineering analytics platform analyzing Git activity, pull requests, code reviews, workflow patterns and software delivery performance.

* **[Waydev](https://waydev.co/)**
  Engineering analytics and developer productivity platform focused on engineering metrics, DORA, Git analytics, team performance and software delivery insights.

* **[Haystack](https://www.usehaystack.io/)**
  Engineering intelligence and developer productivity platform providing Git, Jira and delivery analytics, engineering metrics and team-level insights.

* **[Allstacks](https://www.allstacks.com/)**
  Value stream management and engineering analytics platform covering DORA metrics, software delivery, engineering productivity, forecasting and workflow intelligence.

* **[CodeSee](https://learn.codesee.io/)**
  Codebase visualization and engineering intelligence platform providing codebase maps, dependency visualization and software architecture insights.

* **[Athenian](https://athenian.com/)**
  Engineering analytics platform focused on software delivery performance, engineering metrics, cycle time, team productivity and workflow analytics.

* **[Propelo](https://propelo.ai/)**
  Engineering productivity and value-stream analytics platform combining engineering metrics, DORA, workflow insights and developer productivity analytics.

* **[Linear Insights](https://linear.app/)**
  Engineering and product analytics capabilities integrated into Linear for understanding issue flow, project progress, cycles and delivery patterns.

* **[GitLab Value Stream Analytics](https://about.gitlab.com/solutions/value-stream-management/)**
  Built-in software-delivery analytics across planning, issues, merge requests, CI/CD and deployments.

* **[GitHub Insights](https://github.com/features/insights)**
  Native repository and engineering activity analytics covering repository activity, pull requests, Actions and development workflows.

* **[Atlassian Analytics](https://www.atlassian.com/platform/analytics)**
  Analytics layer across Atlassian products, useful for combining Jira, Bitbucket, Confluence and DevOps data for engineering and delivery reporting.

* **[Jira Product Discovery & Analytics Ecosystem](https://www.atlassian.com/software/jira)**
  Atlassian's Jira ecosystem provides issue, project, delivery and engineering workflow data that can feed engineering intelligence systems.

* **[Harness Engineering Insights](https://www.harness.io/products/engineering-insights)**
  Engineering intelligence and DevOps analytics capabilities focused on developer productivity, DORA and software delivery performance.

* **[Sleuth](https://www.sleuth.io/)**
  Deployment intelligence platform focused on DORA metrics, deployment performance, change failure and engineering delivery insights.

* **[Waydev](https://waydev.co/)**
  Engineering analytics platform focused on Git activity, developer productivity, DORA and engineering management insights.

* **[Faros AI Community Edition](https://github.com/faros-ai)**
  Faros maintains public open-source repositories and tooling for collecting and sending engineering events into Faros; the broader Faros platform is commercial.

---

## Open-Source GitHub Projects

> **Open-source emphasis:** The projects below are intentionally broader than a simple list of direct SaaS replacements. Complete/self-hosted engineering intelligence platforms are listed first, followed by software-development analytics frameworks, DORA tools, metrics projects, data platforms and reusable building blocks.

### Complete Engineering Intelligence Platforms

* **[Apache DevLake](https://github.com/apache/devlake)**
  Open-source dev-data platform for collecting, transforming, correlating and visualizing fragmented software-development data. It supports sources such as GitHub, GitLab, Jenkins, Jira and SonarQube and provides pre-built dashboards for DORA and engineering analytics.

* **[Propel](https://github.com/PropelReviews/Propel)**
  Fully open-source and self-hostable developer-performance analytics platform focused on transparent engineering metrics. Its metrics are represented as readable SQL and can connect engineering activity from GitHub and Linear.

* **[GrimoireLab](https://github.com/chaoss/grimoirelab)**
  Open-source software-development analytics platform from CHAOSS. It retrieves data from software-development systems, stores and enriches it, computes metrics and provides analytics and visualization capabilities.

* **[Faros Community / Open-Source Components](https://github.com/faros-ai)**
  Faros maintains public GitHub components including event-reporting and CI/CD integrations that can be used to feed engineering data into Faros-based workflows.

* **[EngMetrics AI](https://github.com/engmetrics-ai/engmetrics-ai)**
  Experimental open-source Engineering Intelligence platform combining Jira, GitHub and AI-usage data into local engineering-delivery dashboards. It explicitly describes itself as an early experiment rather than a production-ready system.

* **[DevTrack](https://github.com/Priyanshu-byte-coder/devtrack)**
  Open-source, self-hostable developer analytics dashboard focused on GitHub activity, contributions, pull requests, developer statistics, streaks and goals.

* **[Developer Productivity Analytics](https://github.com/developerproductivity)**
  Open-source initiative focused on tools and connectors for evaluating developer productivity and collecting data for engineering analytics.

### Software Development Analytics Platforms

* **[GrimoireLab](https://github.com/chaoss/grimoirelab)**
  Comprehensive software-development analytics toolkit covering data retrieval, enrichment, identity management, storage, metrics and visualization. GrimoireLab includes components such as Perceval, GrimoireELK, SortingHat, Sigils and Mordred.

* **[GrimoireLab Core](https://github.com/chaoss/grimoirelab-core)**
  Scheduling and execution infrastructure for retrieving software-development data using Perceval and related GrimoireLab components.

* **[GrimoireLab Perceval](https://github.com/chaoss/perceval)**
  Open-source data retrieval engine for collecting information from software-development repositories and collaboration systems.

* **[GrimoireLab SortingHat](https://github.com/chaoss/grimoirelab-sortinghat)**
  Open-source identity-management component for consolidating developer identities across different data sources.

* **[GrimoireELK](https://github.com/chaoss/grimoirelab-elk)**
  Open-source data enrichment and storage component within the GrimoireLab ecosystem.

* **[CHAOSS](https://github.com/chaoss)**
  Open-source community and ecosystem developing metrics, tools and frameworks for understanding software-development and open-source project health.

* **[CollectOSS](https://github.com/chaoss/CollectOSS)**
  Open-source successor project to the archived CHAOSS Augur repository, continuing the project's metrics-collection work. The original Augur repository was archived in July 2026 and explicitly directs users toward CollectOSS.

### DORA & DevOps Intelligence

* **[Apache DevLake](https://github.com/apache/devlake)**
  Open-source DORA and engineering analytics platform with integrations across source control, issue tracking, CI/CD and code-quality systems.

* **[Sleuth OSS Integrations / DORA Tooling](https://github.com/sleuth-io)**
  Public tooling and integrations around deployment intelligence and DORA-style engineering metrics.

* **[DevOpsMetrics](https://github.com/DevOpsMetrics/DevOpsMetrics)**
  Open-source project focused on collecting and presenting DevOps metrics for engineering teams.

* **[OpenTelemetry](https://github.com/open-telemetry/opentelemetry-collector)**
  Open-source observability standard and collection infrastructure that can be extended to collect engineering and delivery telemetry alongside operational telemetry.

* **[Keptn](https://github.com/keptn/keptn)**
  Open-source event-driven automation platform useful for connecting deployment, quality and operational events to engineering intelligence workflows.

* **[Jenkins](https://github.com/jenkinsci/jenkins)**
  Open-source automation server providing CI/CD execution data that can become a major source for DORA and engineering analytics.

* **[Argo CD](https://github.com/argoproj/argo-cd)**
  Open-source GitOps continuous-delivery platform whose deployment events can feed deployment-frequency and change-related engineering metrics.

* **[Tekton](https://github.com/tektoncd/pipeline)**
  Open-source Kubernetes-native CI/CD pipeline framework providing execution data useful for delivery analytics.

### Developer Productivity & Engineering Metrics

* **[Propel](https://github.com/PropelReviews/Propel)**
  Transparent developer-performance analytics with inspectable SQL-based metrics and self-hosting support.

* **[DevTrack](https://github.com/Priyanshu-byte-coder/devtrack)**
  Self-hostable developer dashboard for GitHub activity, contribution metrics, PR analytics and developer goals.

* **[git-quick-stats](https://github.com/arzzen/git-quick-stats)**
  Command-line tool for extracting statistics from Git repositories, useful for lightweight developer and repository analytics.

* **[SCC](https://github.com/boyter/scc)**
  Extremely fast source-code statistics utility providing lines-of-code, language, complexity and repository-level measurements.

* **[git-of-theseus](https://github.com/erikbern/git-of-theseus)**
  Tool for analyzing how codebases evolve over time using Git history, useful for code churn and repository evolution studies.

* **[GitStats](https://github.com/Ignus5/git-stats)**
  Git repository statistics and contribution visualization tooling.

* **[GitHub Readme Stats](https://github.com/anuraghaziz/github-readme-stats)**
  Open-source project for generating GitHub contribution and repository statistics, useful as a lightweight developer analytics component.

* **[Gitential](https://github.com/omergulcicek/gitential)**
  Open-source engineering analytics project focused on extracting development metrics from Git histories.

### Code & Repository Analytics

* **[SCC](https://github.com/boyter/scc)**
  Fast multi-language source-code statistics tool providing LOC, complexity, language and repository statistics.

* **[CLOC](https://github.com/AlDanial/cloc)**
  Open-source utility for counting lines of source code by programming language and generating codebase statistics.

* **[SonarQube Community Build](https://github.com/SonarSource/sonarqube)**
  Open-source code-quality platform providing static analysis, bugs, vulnerabilities, code smells, duplication and maintainability metrics.

* **[Semgrep](https://github.com/semgrep/semgrep)**
  Open-source code-analysis engine useful for security, quality and engineering-health signals.

* **[OpenGrep](https://github.com/opengrep/opengrep)**
  Open-source static-analysis engine for code-pattern detection and security/quality analysis.

* **[PMD](https://github.com/pmd/pmd)**
  Open-source source-code analyzer providing rule-based quality and complexity metrics.

* **[CodeQL](https://github.com/github/codeql-cli-binaries)**
  Semantic code-analysis technology used to identify vulnerabilities and structural patterns in source code.

* **[Lizard](https://github.com/terryyin/lizard)**
  Open-source code-complexity analyzer useful for engineering-health metrics.

### Engineering Data & Observability Platforms

* **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)**
  Open-source metadata platform that can provide governance and data-discovery infrastructure for engineering-data warehouses.

* **[OpenLineage](https://github.com/OpenLineage/OpenLineage)**
  Open standard for collecting data lineage events, useful for understanding engineering-data pipelines.

* **[Apache Airflow](https://github.com/apache/airflow)**
  Open-source workflow orchestration platform useful for periodically extracting GitHub, GitLab, Jira, CI/CD and other engineering data.

* **[Dagster](https://github.com/dagster-io/dagster)**
  Open-source data orchestration platform useful for building reliable engineering-analytics pipelines.

* **[Meltano](https://github.com/meltano/meltano)**
  Open-source ELT platform useful for extracting engineering data from source-control, project-management and DevOps systems.

* **[Airbyte](https://github.com/airbytehq/airbyte)**
  Open-source data-integration platform with connectors that can be used to move engineering data into a central analytics warehouse.

* **[ClickHouse](https://github.com/ClickHouse/ClickHouse)**
  Open-source analytical database well suited to high-volume engineering-event and time-series analytics.

* **[PostgreSQL](https://github.com/postgres/postgres)**
  Open-source relational database suitable for engineering-data warehouses, normalized event models and custom metric computation.

* **[DuckDB](https://github.com/duckdb/duckdb)**
  Open-source analytical database particularly useful for local and embedded engineering-data analysis.

* **[Apache Kafka](https://github.com/apache/kafka)**
  Open-source event-streaming platform useful for collecting real-time Git, CI/CD, deployment and engineering events.

* **[Redpanda](https://github.com/redpanda-data/redpanda)**
  Kafka-compatible open-source streaming platform suitable for real-time engineering telemetry pipelines.

### Visualization & BI

* **[Grafana](https://github.com/grafana/grafana)**
  Open-source visualization and dashboard platform. Apache DevLake uses Grafana-powered dashboards for engineering and DORA analytics.

* **[Metabase](https://github.com/metabase/metabase)**
  Open-source BI platform suitable for engineering-management dashboards and custom SQL-based analytics.

* **[Apache Superset](https://github.com/apache/superset)**
  Open-source BI and visualization platform suitable for engineering analytics warehouses.

* **[Evidence](https://github.com/evidence-dev/evidence)**
  Open-source code-based BI platform for building version-controlled analytics applications and engineering reports.

* **[Apache ECharts](https://github.com/apache/echarts)**
  Open-source visualization library suitable for building custom Engineering Intelligence dashboards.

* **[Plotly](https://github.com/plotly/plotly.py)**
  Open-source visualization library useful for custom engineering-performance charts and analytics applications.

* **[Grafana Loki](https://github.com/grafana/loki)**
  Open-source log aggregation system that can provide CI/CD, deployment and engineering-event logs for analytics pipelines.

### Additional Strong Open-Source Options

* **[OpenSearch](https://github.com/opensearch-project/OpenSearch)**
  Open-source search and analytics engine useful for indexing engineering events and powering analytics systems.

* **[OpenSearch Dashboards](https://github.com/opensearch-project/OpenSearch-Dashboards)**
  Open-source dashboarding layer for OpenSearch-based engineering analytics.

* **[Apache Superset](https://github.com/apache/superset)**
  Open-source analytics interface suitable for engineering metrics, DORA dashboards and organizational reporting.

* **[JupyterLab](https://github.com/jupyterlab/jupyterlab)**
  Open-source interactive environment useful for exploratory engineering analytics, metric research and custom engineering-intelligence models.

* **[Pandas](https://github.com/pandas-dev/pandas)**
  Open-source Python analytics library useful for engineering event processing, aggregation and metric computation.

* **[Polars](https://github.com/pola-rs/polars)**
  High-performance open-source DataFrame engine useful for processing large engineering-event datasets.

* **[scikit-learn](https://github.com/scikit-learn/scikit-learn)**
  Open-source machine-learning library useful for engineering analytics, anomaly detection, forecasting and classification.

* **[Prophet](https://github.com/facebook/prophet)**
  Open-source forecasting library useful for forecasting engineering throughput, workload and delivery trends.

* **[MLflow](https://github.com/mlflow/mlflow)**
  Open-source machine-learning lifecycle platform useful when engineering-intelligence systems incorporate predictive models.

* **[Keycloak](https://github.com/keycloak/keycloak)**
  Open-source identity and access-management platform useful for securing self-hosted engineering intelligence applications.

* **[n8n](https://github.com/n8n-io/n8n)**
  Open-source workflow automation platform useful for connecting engineering metrics with Slack, email, Jira, GitHub and other systems.

* **[Node-RED](https://github.com/node-red/node-red)**
  Open-source event-driven workflow platform useful for engineering-data integrations and notifications.

* **[Mattermost](https://github.com/mattermost/mattermost)**
  Open-source collaboration platform that can be used for engineering alerts, metric notifications and delivery-health workflows.

* **[Rocket.Chat](https://github.com/RocketChat/Rocket.Chat)**
  Open-source messaging platform useful for engineering notifications and workflow integrations.

---

## Commercial → Open-Source Capability Mapping

| Commercial Platform              | Primary Focus                                         | Open-Source Equivalents / Building Blocks                    |
| -------------------------------- | ----------------------------------------------------- | ------------------------------------------------------------ |
| **Jellyfish**                    | Engineering investment + business alignment           | Apache DevLake + GrimoireLab + PostgreSQL + Metabase/Grafana |
| **Faros AI**                     | Engineering data platform + intelligence              | Apache DevLake + Airbyte + Kafka + Grafana                   |
| **LinearB**                      | DORA + developer productivity + workflow intelligence | Apache DevLake + Time-series DB + Grafana + n8n              |
| **Swarmia**                      | Developer productivity + DevEx + DORA                 | Apache DevLake + GrimoireLab + Grafana                       |
| **Code Climate Velocity**        | Engineering velocity + software delivery              | Apache DevLake + SonarQube + Grafana                         |
| **DX**                           | Developer experience + qualitative/quantitative DevEx | Apache DevLake + GrimoireLab + survey platform + BI          |
| **Typo**                         | DORA + engineering productivity + DevEx               | Apache DevLake + GrimoireLab + Grafana                       |
| **Pluralsight Flow**             | Git analytics + developer productivity                | GrimoireLab + SCC + git-quick-stats + Grafana                |
| **Waydev**                       | Git analytics + engineering metrics                   | Apache DevLake + GrimoireLab + Grafana                       |
| **Haystack**                     | Engineering productivity + Git/Jira analytics         | Apache DevLake + GrimoireLab + Metabase                      |
| **Allstacks**                    | Value stream management + engineering analytics       | Apache DevLake + Airbyte + Grafana                           |
| **Athenian**                     | Engineering analytics + delivery performance          | Apache DevLake + GrimoireLab + ClickHouse                    |
| **Propelo**                      | Engineering productivity + value stream analytics     | Apache DevLake + GrimoireLab + Metabase                      |
| **Sleuth**                       | Deployment intelligence + DORA                        | Apache DevLake + Jenkins/Argo CD + Grafana                   |
| **GitLab VSA**                   | End-to-end DevOps analytics                           | Apache DevLake + GitLab + Grafana                            |
| **GitHub Insights**              | GitHub repository analytics                           | GitHub API + DevLake + Grafana                               |
| **Harness Engineering Insights** | DORA + engineering intelligence                       | Apache DevLake + Jenkins/Argo/Tekton + Grafana               |
| **CodeSee**                      | Codebase visualization                                | CodeQL + Lizard + CLOC + custom graph visualization          |

> **Important:** These mappings are **capability-oriented rather than feature-for-feature replacements**. Commercial Engineering Intelligence platforms typically bundle data collection, identity resolution, metrics, dashboards, benchmarking, workflow automation, integrations, permissions and enterprise support. A self-hosted equivalent will generally require multiple open-source components.

---

## Framework for Building a Self-Hosted Engineering Intelligence Platform

A practical open-source architecture for building a **Jellyfish / Faros AI / LinearB / Swarmia-style Engineering Intelligence platform** can be assembled from the following components:

| Layer                  | Open-Source Technologies                         |
| ---------------------- | ------------------------------------------------ |
| Source Control         | GitHub API · GitLab · Gitea · Gerrit             |
| Project Management     | Jira API · Linear API · GitLab Issues            |
| CI/CD                  | Jenkins · GitHub Actions · GitLab CI · Tekton    |
| Deployment             | Argo CD · Flux · Jenkins                         |
| Incident Data          | PagerDuty API · Opsgenie API · Grafana OnCall    |
| Code Quality           | SonarQube · Semgrep · PMD · Lizard               |
| Data Collection        | Apache DevLake · GrimoireLab · Airbyte · Meltano |
| Engineering Events     | OpenTelemetry · Kafka · Redpanda                 |
| Identity Resolution    | GrimoireLab SortingHat · Custom identity graph   |
| Data Warehouse         | ClickHouse · PostgreSQL · DuckDB                 |
| Data Lake              | MinIO · S3-compatible storage                    |
| ETL / ELT              | Airflow · Dagster · dbt                          |
| Metrics Engine         | SQL · Python · Pandas · Polars                   |
| DORA                   | Apache DevLake · Custom SQL                      |
| Developer Productivity | DevLake · GrimoireLab · Propel                   |
| Code Analytics         | SCC · CLOC · SonarQube · CodeQL                  |
| DevEx                  | Surveys + Git/Issue analytics + custom metrics   |
| Visualization          | Grafana · Metabase · Superset                    |
| Search                 | OpenSearch                                       |
| ML / AI                | scikit-learn · PyTorch · MLflow                  |
| Workflow Automation    | n8n · Node-RED                                   |
| Notifications          | Mattermost · Rocket.Chat · ntfy                  |
| Authentication         | Keycloak                                         |
| API                    | FastAPI · Django · Go                            |
| Deployment             | Docker · Kubernetes                              |

### Recommended Architecture

```text
                         ENGINEERING DATA SOURCES
                                   │
             ┌─────────────────────┼──────────────────────┐
             │                     │                      │
             ▼                     ▼                      ▼
        Git / GitHub          Jira / Linear          CI/CD Systems
        GitLab / Gerrit       Issues / Projects      Jenkins / Actions
             │                     │                      │
             └─────────────────────┼──────────────────────┘
                                   │
                                   ▼
                     ┌─────────────────────────┐
                     │   DATA COLLECTION LAYER │
                     │                         │
                     │ Apache DevLake          │
                     │ GrimoireLab             │
                     │ Airbyte / Meltano       │
                     │ OpenTelemetry            │
                     └────────────┬────────────┘
                                  │
                                  ▼
                     ┌─────────────────────────┐
                     │ IDENTITY RESOLUTION     │
                     │                         │
                     │ SortingHat               │
                     │ GitHub ↔ Jira ↔ Slack   │
                     │ Developer Identity Graph│
                     └────────────┬────────────┘
                                  │
                                  ▼
                     ┌─────────────────────────┐
                     │ ENGINEERING DATA LAYER  │
                     │                         │
                     │ ClickHouse              │
                     │ PostgreSQL              │
                     │ DuckDB                  │
                     │ OpenSearch              │
                     └────────────┬────────────┘
                                  │
             ┌────────────────────┼─────────────────────┐
             │                    │                     │
             ▼                    ▼                     ▼
       DORA Metrics        Productivity Metrics     Code Quality
       Deployment Freq.    PR Cycle Time            Complexity
       Lead Time           Review Time              Bugs
       Change Failure      Throughput               Vulnerabilities
       MTTR                WIP                      Technical Debt
             │                    │                     │
             └────────────────────┼─────────────────────┘
                                  │
                                  ▼
                     ┌─────────────────────────┐
                     │ INTELLIGENCE LAYER      │
                     │                         │
                     │ Engineering Trends      │
                     │ Bottleneck Detection    │
                     │ Forecasting              │
                     │ Anomaly Detection       │
                     │ Team Insights            │
                     │ Investment Allocation    │
                     └────────────┬────────────┘
                                  │
                                  ▼
                     ┌─────────────────────────┐
                     │ VISUALIZATION / BI       │
                     │                         │
                     │ Grafana                 │
                     │ Metabase                │
                     │ Apache Superset         │
                     └────────────┬────────────┘
                                  │
             ┌────────────────────┼───────────────────┐
             ▼                    ▼                   ▼
        Engineering          CTO / VP Eng        Developers
        Managers             Dashboards          Self-Service
```

### Core Engineering Intelligence Data Model

```text
Developer
    │
    ├── commits
    ├── pull requests
    ├── reviews
    ├── issues
    ├── deployments
    ├── incidents
    ├── code changes
    └── CI/CD executions
             │
             ▼
        Engineering Events
             │
             ▼
       Identity Resolution
             │
             ▼
      Standard Data Model
             │
     ┌───────┼────────┐
     ▼       ▼        ▼
   DORA    SPACE    Custom KPIs
     │       │        │
     └───────┼────────┘
             ▼
       Engineering
       Intelligence
```

### Core Metrics

```text
                    ENGINEERING INTELLIGENCE
                              │
       ┌──────────────────────┼───────────────────────┐
       │                      │                       │
       ▼                      ▼                       ▼
   DELIVERY                QUALITY                 PEOPLE
       │                      │                       │
       ├─ Deployment Freq.    ├─ Defect Rate          ├─ DevEx
       ├─ Lead Time            ├─ Code Churn           ├─ Developer Survey
       ├─ Cycle Time           ├─ Complexity           ├─ Cognitive Load
       ├─ PR Throughput        ├─ Vulnerabilities      ├─ Flow State
       └─ WIP                  └─ Technical Debt       └─ Satisfaction
       │
       ▼
   RELIABILITY
       │
       ├─ Change Failure Rate
       ├─ MTTR
       ├─ Incident Frequency
       └─ Deployment Risk
       │
       ▼
   BUSINESS ALIGNMENT
       │
       ├─ Engineering Investment
       ├─ Feature Development
       ├─ Technical Debt
       ├─ Maintenance
       ├─ Infrastructure
       └─ Security
```

### DORA Metrics Layer

A self-hosted platform can calculate the standard delivery-performance signals from Git, CI/CD, deployment and incident data:

| Metric                | Typical Data Sources                      |
| --------------------- | ----------------------------------------- |
| Deployment Frequency  | CI/CD · Argo CD · GitHub Actions · GitLab |
| Lead Time for Changes | Git commits · PRs · Deployments           |
| Change Failure Rate   | Deployments · Incidents · Rollbacks       |
| Mean Time to Recovery | Incident system · Deployment system       |
| PR Cycle Time         | GitHub · GitLab · Gerrit                  |
| Review Time           | PR/MR reviews                             |
| Review Depth          | PR/MR comments and approvals              |
| Deployment Size       | Git commits · PRs                         |
| CI Duration           | Jenkins · GitHub Actions · GitLab CI      |
| Build Failure Rate    | CI/CD                                     |
| Rework / Churn        | Git history                               |
| WIP                   | Jira · Linear · GitHub Issues             |

### Engineering Intelligence Stack

```text
┌───────────────────────────────────────────────────────┐
│                    EXPERIENCE LAYER                   │
│                                                       │
│  CTO Dashboard · VP Engineering · EM · Developer     │
└───────────────────────────┬───────────────────────────┘
                            │
┌───────────────────────────▼───────────────────────────┐
│                  INTELLIGENCE LAYER                   │
│                                                       │
│  DORA · SPACE · Forecasting · Anomaly Detection      │
│  Engineering Investment · Bottleneck Detection       │
└───────────────────────────┬───────────────────────────┘
                            │
┌───────────────────────────▼───────────────────────────┐
│                    METRICS LAYER                      │
│                                                       │
│  Cycle Time · Throughput · WIP · Review Time         │
│  Deployment Frequency · MTTR · Change Failure        │
└───────────────────────────┬───────────────────────────┘
                            │
┌───────────────────────────▼───────────────────────────┐
│                     DATA LAYER                        │
│                                                       │
│ ClickHouse · PostgreSQL · DuckDB · OpenSearch        │
└───────────────────────────┬───────────────────────────┘
                            │
┌───────────────────────────▼───────────────────────────┐
│                 COLLECTION / ETL                      │
│                                                       │
│ DevLake · GrimoireLab · Airbyte · Meltano · Kafka    │
└───────────────────────────┬───────────────────────────┘
                            │
┌───────────────────────────▼───────────────────────────┐
│                    DATA SOURCES                       │
│                                                       │
│ GitHub · GitLab · Jira · Linear · Jenkins · CI/CD    │
│ SonarQube · PagerDuty · Slack · Deployments          │
└───────────────────────────────────────────────────────┘
```

---

## Open-Source Landscape

```text
                    ENGINEERING INTELLIGENCE
                             │
        ┌────────────────────┼─────────────────────┐
        │                    │                     │
        ▼                    ▼                     ▼
   DATA PLATFORM       SOFTWARE ANALYTICS      DORA / DEVOPS
        │                    │                     │
   Apache DevLake       GrimoireLab          Apache DevLake
   Airbyte              CollectOSS           Jenkins
   Meltano              Perceval              Argo CD
   Kafka                SortingHat            Tekton
        │                    │                     │
        └────────────────────┼─────────────────────┘
                             │
                             ▼
                    ENGINEERING METRICS
                             │
               ┌─────────────┼─────────────┐
               ▼             ▼             ▼
             DORA         Productivity     Quality
               │             │             │
               │          Propel           SonarQube
               │          DevTrack         Semgrep
               │          SCC              CodeQL
               │          git-quick-stats  CLOC
               │
               └─────────────┬─────────────┘
                             ▼
                       DATA WAREHOUSE
                             │
                  ClickHouse / PostgreSQL
                             │
                             ▼
                       BI / DASHBOARDS
                             │
                Grafana / Metabase / Superset
```

---

## How to Contribute

1. Fork the repository.

2. Add or edit entries in `README.md` following the existing format.

3. Include the official website or GitHub repository.

4. Clearly identify whether the project is **SaaS/Hosted**, **Open Source**, **Engineering Intelligence**, **Software Analytics**, **DORA**, **Developer Productivity**, **Code Analytics**, **Data Platform**, or a **Supporting Building Block**.

5. Prefer actively maintained open-source repositories.

6. Include the project's license when known.

7. Distinguish complete Engineering Intelligence platforms from individual metrics libraries, data connectors and visualization tools.

8. Add new self-hosted Engineering Intelligence platforms.

9. Add projects implementing DORA, SPACE or other engineering metrics.

10. Add engineering-data connectors for GitHub, GitLab, Jira, Linear, Jenkins and other SDLC systems.

11. Add open-source tools for developer productivity, developer experience and engineering management.

12. Submit a pull request with a short explanation of the addition or update.

⭐ **Star the repository if you find it useful!**

---

## Disclaimer

* This repository is a **curated directory**, not a ranking or endorsement of any particular product.
* Commercial products and features change frequently; verify current capabilities, pricing, licensing and integrations with the vendor.
* Open-source projects vary substantially in maturity, maintenance activity, documentation, scalability and production readiness.
* A project such as **Apache DevLake or GrimoireLab** can provide a substantial engineering-analytics foundation, but a full commercial Engineering Intelligence platform may include additional proprietary benchmarking, integrations, workflow automation, support and organizational features.
* DORA, SPACE and developer-productivity metrics should be interpreted in organizational context rather than treated as complete measures of individual developer performance.
* Engineering analytics systems can involve sensitive employee and organizational data; review privacy, security, access-control and data-retention requirements before deployment.
* Always review the license of each open-source project before using it commercially.
* Project links, features and availability may change over time.

---

**Made for engineering leaders, developers, CTOs, platform teams, DevOps teams & builders exploring the open-source Engineering Intelligence ecosystem.**
**Let's make engineering intelligence more transparent, extensible and self-hostable.**
