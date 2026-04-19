# Amazon CodeArtifact

Amazon CodeArtifact is a fully managed, secure artifact repository service that helps organizations store, publish, and share software packages used in their software development process. CodeArtifact works with popular build tools and package managers including npm, yarn, pip, twine, Maven, Gradle, NuGet, and more. It supports Cargo, generic, Maven, npm, NuGet, PyPI, Ruby, and Swift package formats and integrates natively with AWS IAM, AWS KMS, AWS CloudTrail, and Amazon EventBridge.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/amazon-codeartifact/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Amazon, AWS, Artifact Repository, Package Management, DevOps, Software Supply Chain, npm, Maven, PyPI, NuGet

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon CodeArtifact API

The Amazon CodeArtifact REST API enables programmatic management of artifact repositories, domains, packages, and package versions. Manage domains and repositories, control permissions policies, publish and copy package versions, retrieve authorization tokens, and manage external connections to public package registries such as npmjs, PyPI, Maven Central, NuGet Gallery, and RubyGems.

**Human URL:** [https://docs.aws.amazon.com/codeartifact/latest/APIReference/Welcome.html](https://docs.aws.amazon.com/codeartifact/latest/APIReference/Welcome.html)

#### Tags:

 - Amazon, AWS, Artifact Repository, Package Management, REST API

#### Properties

- [Documentation](https://docs.aws.amazon.com/codeartifact/latest/ug/welcome.html)
- [APIReference](https://docs.aws.amazon.com/codeartifact/latest/APIReference/Welcome.html)
- [OpenAPI](openapi/amazon-codeartifact-openapi-original.yaml)
- [JSONSchema](json-schema/codeartifact-domain-description-schema.json)
- [JSONSchema](json-schema/codeartifact-repository-description-schema.json)
- [JSONSchema](json-schema/codeartifact-package-version-description-schema.json)

## Common Properties

- [GettingStarted](https://docs.aws.amazon.com/codeartifact/latest/ug/getting-started.html)
- [Authentication](https://docs.aws.amazon.com/codeartifact/latest/ug/tokens-authentication.html)
- [Pricing](https://aws.amazon.com/codeartifact/pricing/)
- [Console](https://console.aws.amazon.com/codesuite/codeartifact/start)
- [Portal](https://aws.amazon.com/codeartifact/)
- [Documentation](https://docs.aws.amazon.com/codeartifact/latest/ug/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Blog](https://aws.amazon.com/blogs/devops/category/developer-tools/amazon-codeartifact/)
- [SignUp](https://portal.aws.amazon.com/gp/aws/developer/registration/index.html)
- [GitHubOrganization](https://github.com/aws)

## Features

| Name | Description |
|------|-------------|
| Multi-Format Package Support | Supports Cargo, generic, Maven, npm, NuGet, PyPI, Ruby, and Swift package formats in polyglot repositories that can hold |
| Public Repository Integration | Connect repositories to public sources including npmjs, PyPI, Maven Central, NuGet Gallery, and RubyGems.org to proxy an |
| Domain-Based Organization | Aggregate multiple repositories into a domain to apply organizational policies, manage encryption, and share packages ac |
| Upstream Repositories | Create upstream relationships between repositories so downstream repositories can transparently access packages from ups |
| Package Groups and Origin Controls | Apply configuration to multiple packages using package groups with pattern matching. Use origin controls to block or all |
| Authorization Token Generation | Generate temporary authorization tokens (up to 12 hours) for secure authentication with package managers without long-li |
| AWS IAM Integration | Control access to domains and repositories using AWS Identity and Access Management for fine-grained permissions policie |
| AWS KMS Encryption | All assets and metadata in a domain are encrypted with the same AWS KMS key, supporting both AWS managed and customer ma |
| AWS CloudTrail Integration | Track package usage and access across your organization with full audit logging via AWS CloudTrail. |
| Amazon EventBridge Integration | Automate package governance workflows and trigger actions on package events using Amazon EventBridge. |
| AWS PrivateLink Support | Access CodeArtifact repositories from within a VPC without exposing traffic to the public internet using AWS PrivateLink |
| High Availability Storage | Multi-Availability Zone operation with redundant package asset storage across Amazon S3 and DynamoDB, fully managed with |

## Use Cases

| Name | Description |
|------|-------------|
| Internal Package Distribution | Share proprietary software components and internal libraries between multiple applications and development teams within  |
| Open-Source Dependency Caching | Proxy and cache open-source packages from public registries to ensure build reproducibility and availability even when u |
| Software Supply Chain Security | Control which packages developers can use with package origin controls to protect against dependency confusion and subst |
| Multi-Team Package Governance | Apply organizational policies across multiple repositories in a domain and audit package consumption across development  |
| CI/CD Pipeline Integration | Integrate with CI/CD systems using native package manager support (npm, Maven, pip, NuGet) to fetch and publish packages |

## Integrations

| Name | Description |
|------|-------------|
| AWS IAM | Fine-grained access control for domains, repositories, and package operations. |
| AWS KMS | Encryption key management for all package assets and metadata stored in a domain. |
| AWS CloudTrail | Audit logging for all CodeArtifact API calls and package access events. |
| Amazon EventBridge | Event-driven automation for package governance workflows and notifications. |
| AWS PrivateLink | Private network connectivity to CodeArtifact from within a VPC. |
| npm Registry (npmjs.com) | Public upstream connection for npm package proxying and caching. |
| PyPI (pypi.org) | Public upstream connection for Python package proxying and caching. |
| Maven Central | Public upstream connection for Java/Maven package proxying and caching. |
| NuGet Gallery (nuget.org) | Public upstream connection for .NET package proxying and caching. |
| RubyGems.org | Public upstream connection for Ruby gem proxying and caching. |
| crates.io | Public upstream connection for Rust/Cargo package proxying and caching. |
| GitHub Actions | Integrate CodeArtifact with GitHub Actions CI/CD workflows for package management. |
| AWS CodeBuild | Use CodeArtifact as the package source in AWS CodeBuild build projects. |
| AWS CodePipeline | Incorporate package publishing and consumption into AWS CodePipeline deployment pipelines. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-codeartifact-openapi-original](openapi/amazon-codeartifact-openapi-original.yaml)

### JSON Schema

159 JSON Schema files generated from the OpenAPI specification.

- [codeartifact-account-id-schema](json-schema/codeartifact-account-id-schema.json)
- [codeartifact-allow-publish-schema](json-schema/codeartifact-allow-publish-schema.json)
- [codeartifact-allow-upstream-schema](json-schema/codeartifact-allow-upstream-schema.json)
- [codeartifact-arn-schema](json-schema/codeartifact-arn-schema.json)
- [codeartifact-asset-hashes-schema](json-schema/codeartifact-asset-hashes-schema.json)
- ...and 154 more in [json-schema/](json-schema/)

### JSON Structure

159 JSON Structure files converted from JSON Schema, available in [json-structure/](json-structure/).

### JSON-LD

- [amazon-codeartifact-context](json-ld/amazon-codeartifact-context.jsonld)

### Examples

159 example JSON files generated from JSON Schema, available in [examples/](examples/).

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [codeartifact](capabilities/shared/codeartifact.yaml) — 38 operations for Amazon CodeArtifact management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon CodeArtifact Package Management](capabilities/amazon-codeartifact-package-management.yaml) | codeartifact | 15 | DevOps Engineer |

## Vocabulary

- [amazon-codeartifact-vocabulary](vocabulary/amazon-codeartifact-vocabulary.yaml) — Unified taxonomy mapping 10 resources, 7 actions, 1 workflows, and 3 personas

## Rules

- [amazon-codeartifact-spectral-rules](rules/amazon-codeartifact-spectral-rules.yml) — 23 rules enforcing Amazon CodeArtifact API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
