# Relativity (relativity)

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
