---
pdf_options:
  format: A4
  margin: 20mm
stylesheet:
  - https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css
  - https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap
css: |
  body { font-family: 'Inter', sans-serif; font-size: 11pt; line-height: 1.5; color: #333; }
  h1 { color: #1a1a1a; border-bottom: 2px solid #2563eb; padding-bottom: 8px; margin-bottom: 4px; }
  h1 + p { margin-top: 0; }
  h2 { color: #1e40af; font-size: 14pt; margin-top: 20px; border-bottom: 1px solid #e5e7eb; padding-bottom: 4px; }
  h3 { color: #374151; font-size: 12pt; margin-bottom: 4px; }
  h4 { color: #4b5563; font-size: 11pt; margin-top: 12px; margin-bottom: 4px; }
  a { color: #2563eb; text-decoration: none; }
  a:hover { text-decoration: underline; }
  hr { border: none; border-top: 1px solid #e5e7eb; margin: 16px 0; }
  ul { margin-top: 8px; margin-bottom: 8px; }
  li { margin-bottom: 4px; }
  strong { color: #1f2937; }
  p { margin: 8px 0; }
  .fa-solid, .fa-brands { color: #6b7280; margin-right: 4px; }
---

# Arman Haeri

**Senior Software Engineer & Azure Solution Architect | AI | Agents | Integration | .NET | Technical Discovery & POCs**

<i class="fa-solid fa-envelope"></i>&nbsp; haeri.arman@gmail.com  
<i class="fa-solid fa-phone"></i>&nbsp; +351 912 32 7427  
<i class="fa-solid fa-location-dot"></i>&nbsp; Lisbon, Portugal  
<i class="fa-brands fa-linkedin"></i>&nbsp; [linkedin.com/in/armanhaeri](https://www.linkedin.com/in/armanhaeri/)  
<i class="fa-brands fa-github"></i>&nbsp; [github.com/CyberEgo](https://github.com/CyberEgo/)

---

## Summary

Hands-on Azure Solution Architect and senior engineer with 20+ years in software development, including 10+ years designing and operating cloud-native systems on Microsoft Azure for startups, mid-market firms, and enterprises (50–2,000+ staff, $10M–$300M+ revenue).

Lead Azure-first architecture and delivery of cross-platform products end to end, from technical discovery and solution design through PoCs, implementation, CI/CD, observability, and production support.

Drive Azure and application modernization for enterprise and SaaS products, including migrations to cost‑optimized cloud‑native/serverless architectures, refactoring monoliths into microservices, redesigning integration services, and implementing network isolation, identity, and end‑to‑end observability.

Recently focused on agentic AI solutions using Azure AI Foundry, designing and implementing AI voice agents, MCP-based architecture, and orchestration patterns that integrate external tools and systems into production-grade workflows.

Strong believer in AI-assisted software development, using tools like GitHub Copilot and modern agentic patterns to accelerate delivery, improve code quality, and enable teams to build and operate complex cloud-native solutions.

---

## Core Competencies

- **Cloud:** Azure (Functions, App Service, Container Apps, Logic Apps, Service Bus, Storage, Key Vault, APIM, RBAC, IAM, Entra ID, OAuth2, OIDC), Cloudflare (Workers, DNS, CDN, rate limiting)
- **Software Design:** Clean Architecture, DDD, TDD, patterns (repository, factory, adapter, decorator, observer, plugin/extensibility)
- **Cloud Patterns:** Publisher/Subscriber, Queue-Based Load Leveling, CQRS, Saga; resilience (Retry, Circuit Breaker, Bulkhead)
- **Backend:** C# / .NET, Python, .NET Aspire, MCP Server/Client, Web APIs/BFF, EF Core, OpenAPI Spec, n8n
- **DevOps & IaC:** GitHub Actions, Azure DevOps, Docker, Bicep, GitHub CLI, Azure CLI, PowerShell, Bash
- **AI & Agent Development:** Azure AI Foundry, Microsoft.Agents SDK, Semantic Kernel, tool-calling models, MCP integration, agent orchestration
- **Data & RAG:** Azure SQL, PostgreSQL, Cosmos DB, Azure AI Search, Databricks, Azure Data Factory, embedding models, vector search, MLOps
- **Testing & Quality:** xUnit, integration testing, pipeline quality gates
- **Leadership & Delivery:** code reviews, mentoring, technical decision-making, architecture governance, estimation & capacity planning, technical debt management, knowledge sharing
- **Client & Tooling:** Unity, Blazor, SDK/NuGet design, automation tooling
- **Technical Documentation:** Solution design documents, API specs, ADRs, operational runbooks, architecture diagrams (PlantUML, Mermaid, Draw.io), Docusaurus
- **Observability:** OpenTelemetry, Application Insights, Log Analytics, Graphana, ADX, KQL
- **AI-Assisted Development:** GitHub Copilot, Claude Code, Codex, agentic workflows; prompt engineering, Perplexity

---

## Professional Experience

### Lead Engineer & Solution Architect — Neuxis Technologies (Lisbon, Portugal, remote)
**Sep 2024 – Present**  
**Company:** Technology startup and IT consultancy building cloud-native SaaS products, AI-native solutions, integration solutions, and cross-platform applications. Based in Portugal and targeting global markets.

- Architected and led development of micro-services using **.NET** and **.NET Aspire**, and **MCP-style interfaces**.
- Built **AI Voice Agent** systems integrating **Azure AI Foundry**, **Microsoft Agent Framework**, and tool-calling capabilities; supports multi-model switching (Azure OpenAI, Anthropic Claude, GitHub Copilot models) with dynamic endpoint abstraction .
- Designed and Implemented **MCP** clients and servers enabling the AI agent to discover and invoke external tools dynamically.
- Delivered authentication and SSO solution with **Azure AD B2C (OIDC/OAuth2)**, enhancing security and user experience across applications.
- Designed and delivered cross-platform **Unity** clients (Windows desktop & Android).
- Implemented distributed multi-region, **SaaS marketplace**, integrated **Stripe** payment processing.
- Delivered signed installers using **WiX (MSI)** with update channels and rollback support.
- Implemented CI/CD quality gates in **GitHub Actions** (build, tests, static analysis, dependency scanning) 
- Implemented observability with **OpenTelemetry**, **Application Insights**, and **Log Analytics**.
- Built semantic search and knowledge retrieval pipelines using **Azure AI Search** with vector indexing and hybrid search to ground AI agent responses in indexed knowledge bases.
- Designed data ingestion and transformation workflows using **Azure Data Factory** and **Databricks** to prepare datasets for AI training, evaluation, and analytics.
- Applied **MLOps** practices for model lifecycle management, evaluation tracking, prompt versioning.
- Implemented real-time data processing pipelines using **Azure Stream Analytics** for event-driven ingestion, transformation, and routing of streaming data to downstream services.
- Built **Power BI** dashboards and reports on top of processed data to surface operational insights and KPIs to stakeholders.
- Deployed serverless edge APIs on **Cloudflare Workers** with **KV** and **R2 Storage** for state, rate limiting, and edge caching; configured **CDN**, **DNS**, and **DDoS protection** via Cloudflare.
- Enforced code quality through **PR reviews** and coding standards; drove technical decision-making and trade-off analysis across backend, client, and infrastructure layers, and managed backlog prioritization, effort estimation.
- Authored and maintained comprehensive technical documentations and developer guides.

**Technologies:** .NET 8, .NET Aspire, EF Core, Azure SQL, Azure Storage, RBAC, Key Vault, Cloudflare, Azure AI Foundry, Microsoft.Agents SDK, Semantic Kernel, MCP, Azure AI Search, Databricks, Azure Data Factory, Azure Stream Analytics, Power BI, MLOps, Unity (IL2CPP), Blazor, OAuth2, Entra ID, OIDC, Azure AD B2C, NuGet, Stripe, Service Bus, APIM, Frontdoor, GitHub Actions, AZD, Bicep, Docker, Kubernetes, WiX/MSIX, OpenTelemetry

---

### Azure Consultant — Codit (Portugal, remote)
**Mar 2023 – Aug 2024**  
**Company:** European Azure integration and digital transformation consultancy with 300+ employees operating across Belgium, Portugal, France, Switzerland, and the UK, part of the Proximus Group (leading Belgian telecom and digital services provider) and delivering Azure‑native solutions for enterprise clients in logistics, insurance, and manufacturing.

#### Customer: Port of Antwerp · Project: NxtPort (Belgium, remote)
**Jan 2024 – Aug 2024**
- Researched and implemented semi-automated **BFF/backend scaffolding** from **OpenAPI specifications** using **NSwag** to accelerate service scaffolding and standardize API contracts.
- Designed and delivered **CI/CD pipelines** in **Azure DevOps**, including quality gates for build, automated tests, and deployment.
- Authored and maintained **xUnit** unit tests and contributed to **integration test** suites; wired both into the pipeline to improve reliability.
- Implemented/maintained **API versioning**, and improved observability via structured logging and **Log Analytics** integration.
- Integrated a **third-party B2C identity provider** (**OIDC/OAuth2**) into the backend authentication and authorization flow.
- Designed and implemented data integration pipelines using **Azure Data Factory** for logistics data ingestion, transformation, and delivery to downstream consumers.
- Integrated **Azure AI Search** to enable structured and semantic document retrieval across platform data, supporting search and filtering use cases.
- Applied **MLOps** practices and leveraged **Databricks** for data analytics, feature engineering, and model serving workflows supporting the platform.
- Conducted **PR reviews** to uphold code quality; contributed to architecture decisions and delivered internal **knowledge-sharing sessions**.

**Technologies:** Azure Container Apps, ACR, Azure DevOps, Storage Accounts, RBAC/IAM, Entra ID, OAuth2, APIM, Key Vault, Azure SQL, Service Bus, Application Insights, Log Analytics, Azure AI Search, Azure Data Factory, Databricks, MLOps, .NET 8, xUnit, PowerShell, Bicep

#### Customer: Codit Customer Care · Project: Azure Alert Enricher (Belgium, remote)
**Oct 2023 – Jan 2024**
- Designed and developed a tool to enrich monitoring alerts by querying **Azure Resource Graph** and **ARM APIs** for resource metadata (subscription/resource group, resource type/name, region, tags).
- Implemented an end-to-end CI/CD pipeline in **GitHub Actions** (build/test, Docker image build + publish to **ACR**, and automated deployments).

**Technologies:** Azure Resource Graph, ARM APIs, Container Apps, ACR, GitHub Actions, Key Vault, .NET 6, Bicep, PowerShell, Bash

---

### Integration Consultant — Codit (Portugal, remote)
**Mar 2023 – Oct 2023**  
**Customer:** Hiscox UK (remote) · **Project:** Nexus Integration Platform

- Contributed to migration planning from **Azure App Service Environment (ASE) v2** to a cost-optimized Azure hosting model centered on **Azure Functions**.
- Implemented network isolation (**VNet integration**, **NSGs**, **UDRs**, **Private Endpoints**) for key dependencies including **Service Bus**, **Storage Accounts**, **Key Vault**, and **API Management**.
- Provisioned and updated infrastructure using **Terraform**; adapted application code and CI/CD pipelines for the new deployment and networking model.
- Defined and executed a migration validation plan (connectivity, Service Bus message flows, APIM routing/policies) and updated project documentation.
- Participated in **PR reviews** and contributed to technical decision-making on hosting model trade-offs and migration strategy.

**Technologies:** Azure Functions, Logic Apps, Storage Accounts, Key Vault, Service Bus, Application Insights, Log Analytics, APIM, VNET, Azure DevOps, RBAC/IAM, KQL, Terraform

---

### Dev Support Engineer — Microsoft (Lisbon, Portugal, remote)
**Dec 2021 – Apr 2023**  
**Company:** Microsoft Corporation, global technology leader with 220,000+ employees and $200B+ annual revenue. Worked within the Azure App Service support organization serving Premier and ProDirect enterprise customers across EMEA.

- Troubleshot production incidents and configuration issues for **Azure Function Apps** and **App Service** for enterprise customers (Premier/ProDirect SLAs).
- Aggregated telemetry and logs across customer environments and performed deep-dive investigations using **KQL** (Application Insights, Log Analytics, Azure Data Explorer) to identify root causes and mitigations.
- Led/participated in incident triage with Technical Support Managers and coordinated with internal SMEs for complex cross-team escalations.

**Technologies:** Azure Functions, App Services, Docker, Kubernetes, C#, PowerShell, Azure CLI, Bash, KQL, Application Insights, Log Analytics, Azure Data Explorer, ARM templates

---

### Lead Developer / Azure Integration — Newhotel Software (Lisbon, Portugal, hybrid)
**May 2019 – Oct 2021**  
**Company:** Portuguese hospitality technology company with 50-75 employees providing Property Management Systems (PMS) to hotels across Portugal, Spain, and Brazil. Serving 200+ hotel properties with integrated booking, guest management, and IoT solutions.

- Led design and POC development of distributed integration solutions using **Azure Service Bus, Functions, Logic Apps, and Blob Storage**; drove implementation and knowledge transfer.
- Built ETL pipelines and reporting systems.
- Developed mobile applications for hotel guests (check-in/out, smart device integration).
- Migrated PMS systems to **.NET Core** and refactored shared libraries into **NuGet packages**.
- Conducted **code reviews**, mentored junior developers, and drove architecture decisions; managed estimation, sprint planning, and technical debt prioritization.
- Contributed to CI/CD pipelines in **Azure DevOps**.

**Technologies:** Azure Service Bus, Azure Functions, Logic Apps, C#, .NET Core, Dapper, Oracle, MongoDB, Docker, Ionic (Angular), Stripe APIs, GraphQL, SignalR, Entity Framework

---

### Software Engineer - Independent
**Apr 2016 – Apr 2019**  
**Company:** Independent software engineer delivering custom application development, ML prototypes, and Unity-based game development for individual clients and small businesses.

- Implemented ML-based skin lesion classification using **CNNs** and **OpenCV**.
- Developed Android, PC, and VR games using **Unity3D**.
- Created Android services for file sync and location sharing.
- Built chatbots for **Discord** and **Twitch**.
- Built web applications and small-business websites.

**Technologies:** Unity3D, C#, Python, CNNs, OpenCV, Firebase, Docker, Java, .NET, MSSQL, ASP.NET, Bootstrap

---

### Lead .NET & Android Developer — Shirin Asal (Iran, on-site)
**Dec 2013 – Apr 2016**  
**Company:** Iranian software company with 200+ employees developing CRM and POS systems for retail, distribution, and logistics companies across Iran. Serving 100+ SMB clients with integrated GPS tracking and mobile workforce management solutions.

- Led technical research, POC development, and solution design; drove implementation and knowledge transfer.
- Conducted **code reviews**, mentored team members, and drove architecture decisions; identified and prioritized technical debt reduction across CRM and POS codebases.
- Implemented new features, refactored and enhanced CRM and POS systems.
- Built socket-based services for GPS data ingestion.
- Developed Android applications integrated with CRM/POS workflows.
- Implemented reporting, data validation, and visualization features; contributed to SEO improvements.

**Technologies:** C#, ASP.NET, MSSQL, Java, SQLite, SOAP Web Services, Google Maps APIs, Teltonika GPS, HTML5, CSS3, JavaScript, D3.js, Bootstrap

---

## Current Top Technical Interests (in order)
- AI Agents (MCP, A2A, Semantic Kernel)
- Microsoft Azure & Azure AI Foundry
- Voice AI (Azure Speech, ElevenLabs)
- VR / AR / XR (Unity)
- C# / .NET
- GenAI 
- RAG
- CLI Tools & Automation
- Containerization & DevOps
- PowerShell & KQL

---

## Personal Interests
Metaverse, Aviation & Drones, Brain–Computer Interfaces, Automation, Robotics, Psychology, Philosophy

---

## Certifications
- Azure Fundamentals (AZ-900)
- MCITP 2008 (legacy)
- MCSE 2003 (legacy)

---

## Education
**Bachelor of Computer Engineering (40 units completed)**  
Azad University of Garmsar — 2004–2009

---

## Languages
- English — Fluent (full professional proficiency)

