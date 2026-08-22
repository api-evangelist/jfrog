# JFrog (jfrog)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

JFrog provides universal DevOps solutions for software supply chain automation and security, offering a unified platform for managing binaries, securing the software supply chain, and automating DevOps workflows.

**APIs.json:** [https://jfrog.com](https://jfrog.com)

## Tags

- Artifactory
- CI/CD
- Container Registry
- DevOps
- MLOps
- Package Management
- Security
- Software Supply Chain

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### JFrog Artifactory REST API

REST API for managing artifacts, repositories, security, and system configuration in JFrog Artifactory. Provides endpoints for uploading, downloading, searching, and managing binary artifacts across all package types, including the Skills repository type for AI Agent Skills published via the JFrog AI Catalog.

- **Human URL:** [https://jfrog.com/artifactory/](https://jfrog.com/artifactory/)
- **Base URL:** `https://myserver.jfrog.io/artifactory/api`

#### Tags

- Artifacts
- Binary Management
- DevOps
- Package Management
- Repository Management
- Skills
- AI Agents

#### Properties

- [Documentation](https://www.jfrog.com/confluence/display/JFROG/Artifactory+REST+API)
- [OpenAPI](openapi/jfrog-artifactory-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jfrog-artifactory.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jfrog-artifactory.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://www.jfrog.com/confluence/display/JFROG/Access+Tokens)
- [Getting Started](https://jfrog.com/help/r/jfrog-artifactory-documentation/use-the-rest-api)
- [Reference](https://jfrog.com/help/r/jfrog-rest-apis/artifactory-rest-apis)
- [Blog](https://jfrog.com/blog/agent-skills-new-ai-packages/)

### JFrog Artifactory REST API V2

The next generation Artifactory REST API providing improved endpoints for repository management, artifact operations, and system administration with enhanced consistency and functionality.

- **Human URL:** [https://jfrog.com/artifactory/](https://jfrog.com/artifactory/)
- **Base URL:** `https://myserver.jfrog.io/artifactory/api/v2`

#### Tags

- API V2
- Artifacts
- Binary Management
- Package Management
- Repository Management

#### Properties

- [Documentation](https://jfrog.com/help/r/jfrog-rest-apis/artifactory-rest-api-v2)
- [OpenAPI](openapi/jfrog-artifactory-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jfrog-artifactory.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jfrog-artifactory.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens)

### JFrog Xray REST API

API for vulnerability scanning, license compliance, and impact analysis. Provides Software Composition Analysis capabilities tightly integrated with Artifactory to ensure security and compliance governance.

- **Human URL:** [https://jfrog.com/xray/](https://jfrog.com/xray/)
- **Base URL:** `https://myserver.jfrog.io/xray/api`

#### Tags

- DevSecOps
- License Compliance
- Security
- Software Composition Analysis
- Vulnerability Scanning

#### Properties

- [Documentation](https://www.jfrog.com/confluence/display/JFROG/Xray+REST+API)
- [OpenAPI](openapi/jfrog-xray-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jfrog-xray.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jfrog-xray.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens)
- [Reference](https://jfrog.com/help/r/xray-rest-apis)
- [Getting Started](https://jfrog.com/help/r/xray-rest-apis/introduction-to-the-xray-rest-apis)

### JFrog Distribution REST API

API for distributing release binaries to multiple remote locations. Enables secure, reliable distribution of release bundles across edge nodes and remote sites at scale.

- **Human URL:** [https://jfrog.com/distribution/](https://jfrog.com/distribution/)
- **Base URL:** `https://myserver.jfrog.io/distribution/api`

#### Tags

- CDN
- Distribution
- Edge Nodes
- Release Management
- Software Distribution

#### Properties

- [Documentation](https://www.jfrog.com/confluence/display/JFROG/Distribution+REST+API)
- [OpenAPI](openapi/jfrog-distribution-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jfrog-distribution.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jfrog-distribution.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens)
- [Reference](https://jfrog.com/help/r/jfrog-rest-apis/distribution-rest-apis)

### JFrog Pipelines REST API

API for managing CI/CD pipelines and automation workflows. Provides endpoints for creating, executing, and monitoring pipelines, runs, resources, and pipeline artifacts.

- **Human URL:** [https://jfrog.com/pipelines/](https://jfrog.com/pipelines/)
- **Base URL:** `https://myserver.jfrog.io/pipelines/api`

#### Tags

- Automation
- CI/CD
- DevOps
- Pipelines
- Workflows

#### Properties

- [Documentation](https://www.jfrog.com/confluence/display/JFROG/Pipelines+REST+API)
- [OpenAPI](openapi/jfrog-pipelines-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jfrog-pipelines.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jfrog-pipelines.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens)
- [Getting Started](https://jfrog.com/help/r/jfrog-rest-apis/introduction-to-the-pipelines-rest-apis)
- [Reference](https://jfrog.com/help/r/jfrog-rest-apis/pipelines-rest-apis)

### JFrog Platform REST API

Unified API for JFrog Platform services and administration. Provides centralized endpoints for managing platform-wide configuration, system health, licenses, and cross-service operations.

- **Human URL:** [https://jfrog.com/platform/](https://jfrog.com/platform/)
- **Base URL:** `https://myserver.jfrog.io/`

#### Tags

- Access Management
- Administration
- Configuration
- Platform
- System Health

#### Properties

- [Documentation](https://www.jfrog.com/confluence/display/JFROG/JFrog+Platform+REST+API)
- [OpenAPI](openapi/jfrog-platform-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jfrog-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jfrog-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://www.jfrog.com/confluence/display/JFROG/Access+Tokens)
- [Getting Started](https://jfrog.com/help/r/jfrog-rest-apis/introduction-to-the-jfrog-platform-rest-apis)
- [Reference](https://jfrog.com/help/r/jfrog-rest-apis/jfrog-platform-rest-apis)

### JFrog Access REST API

API for managing users, groups, permissions, projects, and access tokens across the JFrog Platform. Handles identity management, role-based access control, and scoped token creation.

- **Human URL:** [https://jfrog.com/platform/](https://jfrog.com/platform/)
- **Base URL:** `https://myserver.jfrog.io/access/api`

#### Tags

- Access Management
- Authentication
- Permissions
- Tokens
- Users

#### Properties

- [Documentation](https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-token-rest-api)
- [OpenAPI](openapi/jfrog-access-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jfrog-access.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jfrog-access.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens)
- [Getting Started](https://jfrog.com/help/r/jfrog-platform-administration-documentation/introduction-to-access-tokens)

### JFrog Curation REST API

API for managing package curation policies that automatically vet and block malicious, vulnerable, or risky open-source packages before they enter the development environment.

- **Human URL:** [https://jfrog.com/curation/](https://jfrog.com/curation/)
- **Base URL:** `https://myserver.jfrog.io/curation/api`

#### Tags

- Curation
- Open Source
- Policy Management
- Security
- Software Supply Chain

#### Properties

- [Documentation](https://jfrog.com/help/r/jfrog-rest-apis/jfrog-curation-rest-apis)
- [OpenAPI](openapi/jfrog-curation-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jfrog-curation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jfrog-curation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens)

### JFrog Mission Control REST API

API for centralized management and monitoring of multiple JFrog Platform instances, including Artifactory servers, configurations, and cross-instance operations.

- **Human URL:** [https://jfrog.com/platform/](https://jfrog.com/platform/)
- **Base URL:** `https://myserver.jfrog.io/mc/api`

#### Tags

- Administration
- Mission Control
- Monitoring
- Multi-Instance Management
- Operations

#### Properties

- [Documentation](https://jfrog.com/help/r/jfrog-rest-apis/mission-control-rest-apis)
- [OpenAPI](openapi/jfrog-mission-control-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jfrog-mission-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jfrog-mission-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens)

### JFrog Release Lifecycle Management REST API

API for managing release bundles, promotion workflows, and evidence collection throughout the software release lifecycle from development to production.

- **Human URL:** [https://jfrog.com/rlm/](https://jfrog.com/rlm/)
- **Base URL:** `https://myserver.jfrog.io/lifecycle/api`

#### Tags

- Evidence
- Lifecycle
- Promotion
- Release Bundles
- Release Management

#### Properties

- [Documentation](https://jfrog.com/help/r/jfrog-rest-apis/release-lifecycle-management)
- [OpenAPI](openapi/jfrog-release-lifecycle-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jfrog-release-lifecycle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jfrog-release-lifecycle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens)

### JFrog Workers REST API

API for creating and managing custom serverless workers that extend JFrog Platform functionality through synchronized hooks and automation in a secure, isolated execution environment.

- **Human URL:** [https://jfrog.com/platform/workers/](https://jfrog.com/platform/workers/)
- **Base URL:** `https://myserver.jfrog.io/worker/api`

#### Tags

- Automation
- Extensibility
- Plugins
- Serverless
- Workers

#### Properties

- [Documentation](https://jfrog.com/help/r/jfrog-rest-apis/workers-rest-apis)
- [OpenAPI](openapi/jfrog-workers-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jfrog-workers.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jfrog-workers.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens)

### JFrog ML REST API

API for managing machine learning models, experiments, and deployments including model registry, versioning, and serving capabilities.

- **Human URL:** [https://jfrog.com/jfrog-ml/](https://jfrog.com/jfrog-ml/)
- **Base URL:** `https://myserver.jfrog.io/ml/api`

#### Tags

- AI
- Machine Learning
- MLOps
- Model Management
- Model Registry

#### Properties

- [Documentation](https://jfrog.com/help/r/jfrog-ml-documentation/jfrog-ml-rest-api)
- [OpenAPI](openapi/jfrog-ml-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jfrog-ml.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jfrog-ml.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens)

### JFrog Connect REST API

API for managing IoT and edge devices, deploying over-the-air software updates, and monitoring device fleets at scale.

- **Human URL:** [https://jfrog.com/connect/](https://jfrog.com/connect/)
- **Base URL:** `https://api.connect.jfrog.io/v2`

#### Tags

- Device Management
- Edge Computing
- Fleet Management
- IoT
- OTA Updates

#### Properties

- [Documentation](https://docs.connect.jfrog.io/rest-api-v2/connect-api-reference)
- [OpenAPI](openapi/jfrog-connect-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jfrog-connect.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jfrog-connect.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://docs.connect.jfrog.io/developers)

### JFrog Catalog REST API

API for querying and managing package metadata, searching for packages and CVEs, and managing custom labels for software components through a GraphQL-based interface.

- **Human URL:** [https://jfrog.com/platform/](https://jfrog.com/platform/)
- **Base URL:** `https://myserver.jfrog.io/catalog/api/v1`

#### Tags

- Catalog
- CVE Search
- Package Metadata
- Security
- Software Supply Chain

#### Properties

- [Documentation](https://jfrog.com/help/r/jfrog-security-user-guide/products/catalog)
- [OpenAPI](openapi/jfrog-catalog-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jfrog-catalog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jfrog-catalog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens)

### JFrog Evidence REST API

API for creating and attaching cryptographically signed evidence to artifacts, builds, packages, and release bundles, enabling supply chain verification and compliance attestation throughout the software delivery lifecycle.

- **Human URL:** [https://jfrog.com/platform/](https://jfrog.com/platform/)
- **Base URL:** `https://myserver.jfrog.io/evidence/api`

#### Tags

- Attestation
- Compliance
- Evidence
- Software Supply Chain
- Supply Chain Security

#### Properties

- [Documentation](https://jfrog.com/help/r/jfrog-artifactory-documentation/create-evidence-using-rest-apis)
- [OpenAPI](openapi/jfrog-evidence-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jfrog-evidence.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jfrog-evidence.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://jfrog.com/developers/)
- [Documentation](https://jfrog.com/help/r/jfrog-rest-apis/jfrog-rest-apis)
- [Getting Started](https://jfrog.com/artifactory/getting-started/)
- [Authentication](https://jfrog.com/help/r/jfrog-platform-administration-documentation/access-tokens)
- [Blog](https://jfrog.com/blog/)
- [Status Page](https://status.jfrog.io/)
- [Support](https://jfrog.com/support/)
- [Terms of Service](https://jfrog.com/terms-of-service/)
- [Privacy Policy](https://jfrog.com/privacy-policy/)
- [GitHub Organization](https://github.com/jfrog)
- [Community](https://jfrog.com/community/)
- [Website](https://jfrog.com/)
- [Login](https://my.jfrog.com/login/)
- [Sign Up](https://jfrog.com/start-free/)
- [Pricing](https://jfrog.com/pricing/)
- [C L I](https://jfrog.com/getcli/)
- [Changelog](https://jfrog.com/help/r/jfrog-release-information/jfrog-release-notes)
- [S D Ks](https://github.com/jfrog/jfrog-client-go)
- [Java  S D K](https://github.com/jfrog/artifactory-client-java)
- [Java Script  S D K](https://github.com/jfrog/jfrog-client-js)
- [Academy](https://academy.jfrog.com/)
- [Webhooks](https://jfrog.com/help/r/jfrog-platform-administration-documentation/webhooks)
- [Terraform  Provider](https://registry.terraform.io/providers/jfrog/platform/latest/docs)
- [YouTube](https://www.youtube.com/@jfrog)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/jfrog)
- [Rate Limits](https://jfrog.com/help/r/jfrog-rest-apis/usage-and-rate-limits)
- [Postman  Collection](https://www.postman.com/api-evangelist/jfrog/documentation/zgmorin/jfrog-rest-api)
- [LinkedIn](https://www.linkedin.com/company/jfrog-ltd)
- [J S O N- L D  Context](json-ld/jfrog-context.jsonld)
- [J S O N  Schema -  Artifact](json-schema/jfrog-artifact-schema.json)
- [J S O N  Schema -  Repository](json-schema/jfrog-repository-schema.json)
- [J S O N  Schema -  Build  Info](json-schema/jfrog-build-info-schema.json)
- [J S O N  Schema -  Release  Bundle](json-schema/jfrog-release-bundle-schema.json)
- [J S O N  Schema -  Security  Vulnerability](json-schema/jfrog-security-vulnerability-schema.json)
- [J S O N  Schema -  User](json-schema/jfrog-user-schema.json)
- [J S O N  Schema -  Permission](json-schema/jfrog-permission-schema.json)
- [J S O N  Schema -  Pipeline](json-schema/jfrog-pipeline-schema.json)
- [J S O N  Schema -  Worker](json-schema/jfrog-worker-schema.json)
- [J S O N  Schema -  Curation  Policy](json-schema/jfrog-curation-policy-schema.json)
- [J S O N  Schema -  Evidence](json-schema/jfrog-evidence-schema.json)
- [Integrations](https://jfrog.com/integrations/)
- [M C P Server](https://github.com/jfrog/mcp-jfrog)
- [Agent Skill](https://github.com/jfrog/jfrog-skills)
- [L L Ms Txt](https://docs.connect.jfrog.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
