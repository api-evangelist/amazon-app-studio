# Amazon App Studio (amazon-app-studio)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Amazon App Studio is a generative AI-powered low-code application builder that enables business users to create internal applications without requiring extensive coding knowledge. Built on AWS infrastructure, App Studio integrates with AWS data sources and services to enable rapid development of enterprise business tools.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-app-studio/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Generative AI, Internal Tools, Low-Code, No-Code

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon App Studio API
The Amazon App Studio API provides programmatic access to App Studio application management, enabling automation of low-code application lifecycle operations including listing and retrieving application details.

**Human URL:** [https://aws.amazon.com/app-studio/](https://aws.amazon.com/app-studio/)

#### Tags:

 - AWS, Low-Code, No-Code

#### Properties

- [Documentation](https://docs.aws.amazon.com/app-studio/)
- [OpenAPI](openapi/amazon-app-studio-openapi.yaml)
- [JSONSchema](json-schema/amazon-app-studio-app-schema.json)
- [JSONSchema](json-schema/amazon-app-studio-appsummary-schema.json)
- [JSONSchema](json-schema/amazon-app-studio-listappsresponse-schema.json)
- [JSONStructure](json-structure/amazon-app-studio-app-structure.json)
- [JSONLD](json-ld/amazon-app-studio-context.jsonld)
- [Pricing](https://aws.amazon.com/app-studio/pricing/)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Website](https://aws.amazon.com/app-studio/)
- [Documentation](https://docs.aws.amazon.com/app-studio/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://us-east-1.console.aws.amazon.com/appstudio/)
- [SignUp](https://signin.aws.amazon.com/signup?request_type=register)
- [Status](https://health.aws.amazon.com/health/status)
- [SpectralRules](rules/amazon-app-studio-spectral-rules.yml)
- [NaftikoCapability](capabilities/app-studio-management.yaml)
- [Vocabulary](vocabulary/amazon-app-studio-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Generative AI Application Builder | Use natural language prompts to generate application layouts, data models, and logic with Amazon Q assistance. |
| No-Code Application Development | Build internal business applications using drag-and-drop components without writing code. |
| AWS Data Source Integration | Connect applications to AWS DynamoDB, Aurora, S3, and other data sources with built-in connectors. |
| Role-Based Access Control | Configure fine-grained access permissions for application users using AWS IAM Identity Center. |
| One-Click Deployment | Deploy internal applications with a single click and share with team members using AWS access controls. |

## Use Cases

| Name | Description |
|------|-------------|
| Internal Business Tools | Build inventory management, employee onboarding, and operational dashboards for internal business use. |
| Data Entry Applications | Create forms and data entry tools connected to existing databases for field operations and back-office teams. |
| Workflow Automation | Automate approval workflows, task management, and process tracking with connected business logic. |
| IT Self-Service Portals | Build IT request portals, asset management tools, and helpdesk applications for internal teams. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon DynamoDB | Connect App Studio applications to DynamoDB for serverless NoSQL data storage and retrieval. |
| Amazon Aurora | Use Aurora as a relational database backend for App Studio applications requiring structured data. |
| AWS IAM Identity Center | Manage user access to App Studio applications using IAM Identity Center for single sign-on. |
| Amazon Q | Leverage Amazon Q generative AI capabilities within App Studio for AI-assisted application development. |

## Artifacts

### OpenAPI

- [Amazon App Studio API OpenAPI](openapi/amazon-app-studio-openapi.yaml)

### JSON Schema

- [amazon-app-studio-app-schema.json](json-schema/amazon-app-studio-app-schema.json)
- [amazon-app-studio-appsummary-schema.json](json-schema/amazon-app-studio-appsummary-schema.json)
- [amazon-app-studio-listappsresponse-schema.json](json-schema/amazon-app-studio-listappsresponse-schema.json)

### JSON-LD

- [amazon-app-studio-context.jsonld](json-ld/amazon-app-studio-context.jsonld)

## Capabilities

- [Amazon App Studio API](capabilities/shared/amazon-app-studio.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [App Studio Application Management](capabilities/app-studio-management.yaml) | Amazon App Studio API | 2 | Business Developer, IT Administrator |

## Vocabulary

- [Amazon App Studio Vocabulary](vocabulary/amazon-app-studio-vocabulary.yaml)

## Rules

- [Amazon App Studio Spectral Rules](rules/amazon-app-studio-spectral-rules.yml) — 3 rules

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
