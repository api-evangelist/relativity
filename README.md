# Relativity (relativity)

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

Relativity is an eDiscovery and legal review platform offering RelativityOne, a cloud-based SaaS solution for managing the full legal data lifecycle. Its REST API enables programmatic access to workspaces, document import and export, processing pipelines, search and analytics, production management, legal hold, automated workflows, user and permission management, and AI-powered review features. Relativity exposes 80+ integration APIs organized by business domain, supporting OAuth2, basic, and cookie-based authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- eDiscovery
- Legal
- Document Review
- Legal Technology
- Data Processing
- AI Review
- Litigation
- Compliance

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Relativity Object Manager API

Core API for working with documents and Relativity Dynamic Objects (RDOs). Supports CRUD operations, querying, bulk/mass operations, and field management across all workspace objects.

- **Human URL:** [https://platform.relativity.com/RelativityOne/Content/REST_API/REST_API.htm](https://platform.relativity.com/RelativityOne/Content/REST_API/REST_API.htm)
- **Base URL:** `https://{host}/Relativity.REST/api/relativity-object-model/v1`

#### Tags

- Documents
- Objects
- CRUD
- Search

#### Properties

- [Documentation](https://platform.relativity.com/RelativityOne/Content/REST_API/REST_API.htm)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/openapi/relativity-object-manager-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Plans](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/plans/relativity-plans-pricing.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/rate-limits/relativity-rate-limits.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/finops/relativity-finops.yml)
- [Graph Q L](graphql/relativity-graphql.md)

### Relativity Import Service API

REST API for importing large numbers of documents, images, and RDOs into RelativityOne workspaces. Supports native files, extracted text, images, and metadata.

- **Human URL:** [https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm)
- **Base URL:** `https://{host}/Relativity.REST/api/import-service/v1`

#### Tags

- Import
- Documents
- Data Ingestion

#### Properties

- [Documentation](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/openapi/relativity-import-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Getting Started](https://platform.relativity.com/RelativityOne/Content/Getting_Started/Basic_REST_API_concepts.htm)

### Relativity Export Service API

REST API for exporting documents, images, PDFs, and native files from RelativityOne workspaces, as well as exporting applications as RAP or schema files.

- **Human URL:** [https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm)
- **Base URL:** `https://{host}/Relativity.REST/api/export-service/v1`

#### Tags

- Export
- Documents
- Production

#### Properties

- [Documentation](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/openapi/relativity-export-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Relativity Workspace Manager API

REST API for performing CRUD operations on RelativityOne workspaces, including creation, configuration, and deletion.

- **Human URL:** [https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm)
- **Base URL:** `https://{host}/Relativity.REST/api/workspace-service/v1`

#### Tags

- Workspaces
- Administration

#### Properties

- [Documentation](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/openapi/relativity-workspace-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Relativity Production Manager API

REST API for creating, deleting, staging, and running production sets in RelativityOne. Manages production data sources, placeholders, and the production queue.

- **Human URL:** [https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm)
- **Base URL:** `https://{host}/Relativity.REST/api/production-manager/v1`

#### Tags

- Production
- Legal Review
- Documents

#### Properties

- [Documentation](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/openapi/relativity-productions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Relativity Legal Hold API

REST API for managing legal holds, custodians, and data preservation workflows in RelativityOne.

- **Human URL:** [https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm)
- **Base URL:** `https://{host}/Relativity.REST/api/legal-hold/v1`

#### Tags

- Legal Hold
- Compliance
- Custodians

#### Properties

- [Documentation](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/openapi/relativity-legal-hold-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Relativity Automated Workflows API

REST API for registering and managing automated workflow actions, triggers, and events within RelativityOne to streamline review processes.

- **Human URL:** [https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm)
- **Base URL:** `https://{host}/Relativity.REST/api/automated-workflows/v1`

#### Tags

- Workflows
- Automation
- Review

#### Properties

- [Documentation](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/openapi/relativity-automated-workflows-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Relativity Audit API

REST API for reverting, retrieving, and searching audit records stored in Elasticsearch. Provides full audit trail access for compliance and investigation.

- **Human URL:** [https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm)
- **Base URL:** `https://{host}/Relativity.REST/api/audit/v1`

#### Tags

- Audit
- Compliance
- Elasticsearch

#### Properties

- [Documentation](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/openapi/relativity-permissions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Relativity User and Permission Manager API

REST API for managing users, groups, clients, and permissions within RelativityOne. Supports OAuth2 client management, login profiles, and federated instance access.

- **Human URL:** [https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm)
- **Base URL:** `https://{host}/Relativity.REST/api/user-management/v1`

#### Tags

- Users
- Permissions
- Identity
- OAuth2

#### Properties

- [Documentation](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/openapi/relativity-identity-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Relativity Billing Insights API

REST API for programmatically checking billing metrics and data usage in RelativityOne, enabling FinOps monitoring of active data, cold storage, and ECA volumes.

- **Human URL:** [https://help.relativity.com/RelativityOne/Content/Management_Console/Cost_Explorer.htm](https://help.relativity.com/RelativityOne/Content/Management_Console/Cost_Explorer.htm)
- **Base URL:** `https://{host}/Relativity.REST/api/billing-insights/v1`

#### Tags

- Billing
- FinOps
- Usage

#### Properties

- [Documentation](https://help.relativity.com/RelativityOne/Content/Management_Console/Cost_Explorer.htm)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/openapi/relativity-billing-v2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/finops/relativity-finops.yml)

## Common Properties

- [Plans](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/plans/relativity-plans-pricing.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/rate-limits/relativity-rate-limits.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/finops/relativity-finops.yml)
- [Documentation](https://platform.relativity.com/)
- [Developer  Portal](https://platform.relativity.com/RelativityOne/Content/Relativity_Platform/Platform_APIs.htm)
- [Getting Started](https://platform.relativity.com/RelativityOne/Content/Getting_Started/Basic_REST_API_concepts.htm)
- [Changelog](https://platform.relativity.com/RelativityOne/Content/What_s_new/What_s_new.htm)
- [Platform Change Log](https://platform.relativity.com/RelativityOne/Content/What_s_new/Platform_change_log.htm)
- [Git Hub](https://github.com/relativitydev)
- [Git Hub Dev Tools](https://relativitydev.github.io/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/openapi/relativity-object-manager-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/relativity/refs/heads/main/json-ld/relativity-context.jsonld)
- [Authentication](https://platform.relativity.com/RelativityOne/Content/Getting_Started/Basic_REST_API_concepts.htm)
- [Known Issues](https://help.relativity.com/RelativityOne/Content/What_s_New/Known_issues_list.htm)
- [Pricing](https://www.relativity.com/pricing/)
- [Blog](https://www.relativity.com/blog/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
