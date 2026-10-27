# Awesome-Business-Process-Management-BPM

# Awesome-Business-Process-Management-BPM

**Top Business Process Management BPM (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on BPMN Modeling, Workflow Automation, Process Orchestration & Low-Code Application Development*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Business Process Management (BPM)**. These tools enable organizations to model, automate, execute, and optimize business processes—from fully managed enterprise suites with AI-powered orchestration and low-code app builders to self-hosted engines that give teams complete control over their process logic, data, and infrastructure.



**Examples** include Workday Business Process Framework, Appian, Pegasystems, Camunda, Nintex, ProcessMaker, Kissflow, Bizagi, ServiceNow App Engine, and IBM BPM (the category leaders in commercial space).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, BPMN execution, and open workflow infrastructure—ideal for developers, process engineers, and organizations seeking transparent, vendor-independent process automation.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Workday Business Process Framework](https://www.workday.com/)**

  **Embedded business process engine** within Workday HCM and Financials. **Features**: Configurable approval workflows, condition rules, subprocesses, organization-specific process inheritance, and step types (Action, To Do, Service) tied directly to Workday transactions . **Pricing**: Quote-only; included as part of the Workday platform subscription. **Free tier**: None. **Best for**: organizations already on Workday needing process automation tightly coupled to HR and finance transactions—not a standalone BPM tool.



- **[Appian](https://appian.com/)**

  **Low-code automation platform** combining BPM, case management, and AI. **Pricing**: Starting at **$75/month** according to third-party listings; enterprise pricing quote-only . **Free tier**: Free trial available. **Best for**: enterprises wanting rapid low-code process application development with strong integration and case management capabilities.



- **[Pegasystems (Pega)](https://www.pega.com/)**

  **Enterprise AI-powered workflow automation** platform. Pega Infinity '26 introduces MCP protocol support for third-party AI agents (Claude, Gemini, OpenAI) to invoke Pega workflows, plus a new pricing model charging per completed business case rather than per AI token . **Pricing**: Quote-only; new case-based pricing aims to reduce AI cost unpredictability. **Free tier**: None. **Best for**: large enterprises deploying AI agents within governed business processes at scale.



- **[Camunda](https://camunda.com/)**

  **Process orchestration platform** with BPMN, DMN, and CMMN engines. **Pricing**: **Development** (self-managed) is free for local building and testing; **Production** (self-managed) requires Enterprise license; **SaaS** offers 30-day free trial then quote-only . **Free tier**: Free for development/non-production self-managed use. **Best for**: developer-centric teams wanting the most widely adopted open-core BPM engine with strong microservice orchestration support.



- **[Nintex](https://www.nintex.com/)**

  **Workflow automation and process management** platform with document generation and RPA. **Pricing**: Quote-only; observed annual contracts range from **$15,000–$50,000** for small deployments to **$200,000+** for enterprise, with professional services often 30–80% of first-year software cost . **Free tier**: None. **Best for**: organizations heavily invested in Microsoft/SharePoint ecosystems wanting workflow automation with document generation.



- **[ProcessMaker](https://www.processmaker.com/)**

  **Low-code BPM and workflow platform** with process modeling, forms, and integrations. **Pricing**: Starting at **$1,500/month** according to third-party listings . **Free tier**: Trial available. **Best for**: mid-market organizations wanting a low-code BPM platform with flexible deployment options.



- **[Kissflow](https://kissflow.com/)**

  **No-code/low-code workflow and process platform**. **Pricing**: **Basic** starting at **$2,500/month** with limited apps, unlimited workflows, and limited integrations; **Enterprise** pricing custom with AI Copilot, unlimited apps/workflows, advanced analytics, SSO/SCIM, and SLA support . **Free tier**: None; trial available. **Best for**: business teams wanting self-service process automation without developer involvement.



- **[Bizagi](https://www.bizagi.com/)**

  **Digital process automation platform** with BPMN modeling and low-code app development. **Pricing**: Quote-only; public sector price lists show per-user training and license costs (e.g., $10,710 for up to 10 users) . **Free tier**: Free Process Modeler available. **Best for**: organizations wanting strong BPMN modeling with a path to process automation.



- **[ServiceNow App Engine](https://www.servicenow.com/)**

  **Low-code application development** on the ServiceNow platform. **Pricing**: Quote-only; three tiers (Starter, Foundation, Prime) available on request. Integration Hub requires separate subscription . **Free tier**: None. **Best for**: organizations already on ServiceNow wanting custom workflow apps that integrate with ITSM and enterprise data.



- **[IBM Business Process Manager](https://www.ibm.com/)**

  **Enterprise BPM platform** with process modeling, execution, and monitoring. **Pricing**: UK government listings show **£290.40–£373.20 per user per year** for IBM BPM on Cloud . **Free tier**: None. **Best for**: enterprises with existing IBM infrastructure requiring formal BPM governance and BPMN 2.0 export capabilities.



## Open-Source GitHub Projects



- **[Camunda 7 / Operaton](https://github.com/camunda/camunda-bpm-platform)**

  **BPMN process engine and platform** (Apache 2.0 for community edition) — **the most widely adopted open-source BPM engine** with a mature ecosystem. **Note**: Camunda 7 is in maintenance mode; **Operaton** is a community fork maintaining compatibility for teams not ready to migrate to Camunda 8's Zeebe architecture . **Features**: BPMN 2.0 execution, DMN, CMMN, task management, REST API, and extensive Spring integration. **Deploy**: Self-managed (embedded Java or standalone). **Best for**: teams with existing Camunda 7 deployments or those wanting a proven, embedded BPMN engine without the distributed complexity of Camunda 8.



- **[Flowable](https://github.com/flowable/flowable-engine)**

  **Cloud-native BPMN, CMMN, and DMN engine suite** (Apache 2.0) — **the strongest alternative to Camunda** for microservice and event-driven architectures. **Features**: Separate embeddable engines for BPMN, case management (CMMN), and decision management (DMN); Spring Boot starter; official Docker images and Helm charts for Kubernetes; web-based Flowable Modeler; comprehensive REST API . **Tech stack**: Java, Spring Boot. **Deploy**: Self-managed; Docker/Kubernetes ready. **Trade-off**: Smaller community than Camunda; commercial Flowable Work UI is enterprise-licensed . **Best for**: development teams building cloud-native applications needing lightweight BPMN/CMMN/DMN orchestration with strong Spring Boot and Kubernetes support .



- **[jBPM / Apache KIE](https://github.com/kiegroup/jbpm)**

  **BPM suite with integrated rules engine** (Apache 2.0) — **the choice for rule-heavy processes**. **Features**: BPMN 2.0 execution tightly integrated with Drools rules engine and DMN decision models; case management; web-based designer. Currently in Apache incubation as part of Apache KIE (Kogito) . **Tech stack**: Java. **Deploy**: Self-managed. **Trade-off**: Complex to set up; migration to Apache KIE governance underway. **Best for**: processes where business rules and workflows are deeply intertwined (e.g., insurance claims, compliance-driven approvals).



- **[Bonita](https://github.com/bonitasoft/bonita-engine)**

  **Full BPM platform with low-code studio** (GPL-2.0 for Community) — **the most complete open-source BPM experience** for business analysts and developers. **Features**: Visual process modeling (BPMN), form builder, task portal, runtime engine, and UI designer; upcoming AI features for process improvement suggestions . **Tech stack**: Java. **Deploy**: Self-managed. **Trade-off**: Community vs. Subscription feature boundaries; heavier than pure engines . **Best for**: organizations wanting a complete BPM suite (modeling + execution + portals) where business analysts can own workflow design without deep coding .



- **[Activiti](https://github.com/Activiti/Activiti)**

  **BPMN process engine** (Apache 2.0) — **the original fork ancestor of Flowable**. **Features**: BPMN 2.0 execution, REST API, and Spring integration. Version 9.0.0 requires Java 25 baseline; 8.8.1 is the maintenance line . **Tech stack**: Java. **Deploy**: Self-managed. **Trade-off**: Forked into Flowable; community momentum has largely shifted there. **Best for**: teams with existing Activiti deployments evaluating hardening and gradual migration rather than greenfield adoption .



- **[ProcessMaker (Community)](https://github.com/processmaker/processmaker)**

  **Open-source BPM and workflow platform** (AGPL-3.0) — **the community edition of the commercial ProcessMaker**. **Features**: Process modeling, form builder, case management, and REST API; self-hosted deployment. **Tech stack**: PHP (Laravel), Vue.js. **Deploy**: Self-managed (Docker available). **Trade-off**: Commercial edition offers more features and support; community edition has limited documentation. **Best for**: teams wanting a PHP-based BPM platform with a visual designer and case management.



- **[LiteFlow](https://github.com/dromara/liteflow)**

  **Application-internal logic orchestration** (Apache 2.0) — **not a BPMN engine**, but a lightweight rule-chain orchestration framework for Java. **Features**: Component-based logic orchestration with EL rules; hot-reload; suitable for marketing calculations, risk control, and complex business logic chains . **Tech stack**: Java. **Deploy**: Embedded in applications. **Trade-off**: No human task management, persistence of approval workflows, or BPMN modeling—purely for application-internal logic orchestration . **Best for**: developers needing to orchestrate complex Java business logic within a single application, not cross-department approval workflows.



- **[CIB seven](https://github.com/cibseven/cibseven)**

  **Camunda 7-compatible BPM platform** (Apache 2.0) — **a community fork providing a migration path for Camunda 7 users**. **Features**: BPMN execution, basic web applications, and compatibility with Camunda 7 APIs. **Tech stack**: Java. **Deploy**: Self-managed. **Trade-off**: Community vs. Enterprise feature distinction; smaller ecosystem than Camunda or Flowable . **Best for**: teams wanting to continue using Camunda 7-style BPMN execution with a community-governed alternative to commercial Camunda.



### Additional Strong Open-Source Options



- **Conductor OSS** — Microservice and agent orchestration platform (Apache 2.0). **Note**: Not a BPMN engine for human approval workflows—designed for durable, distributed service orchestration with decoupled workers . **Best for**: engineering teams orchestrating microservices and AI agents, not business approval processes.

- **Apache Airflow** — Workflow scheduling and DAG orchestration (Apache 2.0). **Note**: Data pipeline and batch job orchestration, not human-centric BPM. **Best for**: data engineering workflows, not business process management.

- **Temporal** — Durable execution and workflow orchestration (MIT). **Note**: Code-first microservice orchestration; no BPMN modeling or human task portals . **Best for**: developers orchestrating reliable microservice transactions.



**Frameworks for building custom systems**: Combine **Flowable** for cloud-native BPMN/CMMN/DMN orchestration with **Bonita** for business-analyst-friendly process design, **jBPM** for rule-heavy workflows, and **LiteFlow** for application-internal logic chains—creating a BPM stack matched to each team's technical depth and process complexity.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- BPM platforms handling business-critical process data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls and audit logging.

- **The "BPMN process engine vs. full BPM suite vs. application orchestration" distinction matters.** **Flowable, Camunda 7/Operaton, and Activiti** are engines—you embed them in your applications and build your own UI. **Bonita and ProcessMaker** are full suites with modeling, forms, and task portals out of the box. **LiteFlow, Temporal, and Conductor** are application-internal or microservice orchestration tools—**not BPM for human approval workflows** . **Choose based on whether you need a engine to build upon, a ready-made suite, or service orchestration.**

- **Camunda 7 is in maintenance mode; migration decisions are critical.** Camunda 8 uses a fundamentally different architecture (Zeebe distributed engine) and licensing model. **Operaton** and **CIB seven** offer community-governed Camunda 7-compatible forks for teams not ready to migrate . **Evaluate your existing Camunda 7 footprint carefully before choosing a path.**

- **Flowable is the strongest developer-centric open-source choice for cloud-native stacks.** It offers separate BPMN, CMMN, and DMN engines, excellent Spring Boot and Kubernetes support, and Apache 2.0 licensing . **The trade-off**: smaller community than Camunda and enterprise UI features require a commercial license.

- **Bonita offers the most complete open-source BPM experience for business analysts.** It includes modeling, forms, task portal, and runtime in one package . **The trade-off**: Community vs. Subscription boundaries and a heavier footprint than pure engines.

- **Pricing transparency is poor across commercial vendors.** Workday, Appian, Pega, Nintex, Kissflow, Bizagi, ServiceNow, and IBM BPM all require sales contact for quotes. **Observed ranges vary by orders of magnitude**—from Appian's ~$75/month starting point to Nintex enterprise contracts exceeding $200,000/year . **Validate with direct vendor conversations against your actual scope.**

- Self-hosted open-source solutions require proper server setup, backup configuration, and ongoing maintenance. **Process engines execute business-critical logic**—ensure your hosting meets your organization's reliability and security requirements before deploying.



---



**Made for developers, process engineers, and organizations building transparent process automation solutions.**

Let's make Business Process Management more open, data-driven, and workflow-friendly.
