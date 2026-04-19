# Amazon App Studio (amazon-app-studio)
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
