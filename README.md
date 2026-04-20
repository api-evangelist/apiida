# APIIDA (apiida)
APIIDA provides market-leading solutions for multi-vendor, cross-platform federated API management. The APIIDA API Control Plane enables enterprises to discover, govern, and provision APIs from a central location, while the API Gateway Manager automates API operations for Broadcom Layer7 environments with comprehensive deployment, migration, monitoring, and alarming capabilities.

**URL:** [https://apiida.com/](https://apiida.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Gateway, API Management, Federated API Management, Governance, Layer7

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-19

## APIs

### APIIDA API Control Plane
REST API for the APIIDA API Control Plane, enabling programmatic management of APIs across multiple API gateways. Supports validation of proxy specifications, API version management, and deployment to gateways from a central federated control plane.

**Human URL:** [https://apiida.com/product/apiida-api-control-plane/](https://apiida.com/product/apiida-api-control-plane/)

#### Tags:

 - API Lifecycle, API Management, Federated Control Plane, Governance

#### Properties

- [Documentation](https://apiida.com/product/apiida-api-control-plane/)
- [OpenAPI](openapi/apiida-api-control-plane-openapi.yml)
- [JSONSchema](json-schema/apiida-api.json)
- [JSONSchema](json-schema/apiida-deployment.json)
- [JSON-LD](json-ld/apiida-context.jsonld)

### APIIDA API Gateway Manager
REST API for the APIIDA API Gateway Manager, enabling programmatic management of Broadcom Layer7 API gateways. Supports gateway registration, API deployment and migration, monitoring and metrics collection, and alarm configuration across managed gateway instances.

**Human URL:** [https://apiida.com/product/apiida-api-gateway-manager/](https://apiida.com/product/apiida-api-gateway-manager/)

#### Tags:

 - API Deployments, API Gateway, Layer7, Monitoring

#### Properties

- [Documentation](https://apiida.com/product/apiida-api-gateway-manager/)
- [Documentation](https://apiida.atlassian.net/wiki/spaces/AAGM)
- [OpenAPI](openapi/apiida-api-gateway-manager-openapi.yml)
- [JSONSchema](json-schema/apiida-gateway.json)
- [JSONSchema](json-schema/apiida-deployment.json)
- [JSON-LD](json-ld/apiida-context.jsonld)

## Common Properties

- [Website](https://apiida.com/)
- [Documentation](https://apiida.atlassian.net/wiki/spaces/AAGM)
- [Support](https://apiida.com/support/?lang=en)
- [GitHubOrganization](https://github.com/apiida)

## Features

| Name | Description |
|------|-------------|
| Federated API Control Plane | Centrally discover, govern, and provision APIs across multiple API gateway vendors from a single control plane. |
| Multi-Gateway Support | Manage APIs across heterogeneous gateway environments including Broadcom Layer7, AWS API Gateway, Azure APIM, and others. |
| API Deployment Automation | Automate API deployments and migrations across gateway instances with version management and rollback. |
| Monitoring and Alarming | Collect gateway metrics and configure alarms for proactive API operations management. |
| Proxy Specification Validation | Validate API proxy specifications before deployment to ensure compatibility and standards compliance. |

## Use Cases

| Name | Description |
|------|-------------|
| Enterprise API Governance | Govern APIs across multiple teams and gateway technologies from a centralized control plane. |
| Gateway Migration | Migrate APIs between gateway vendors with automated tooling and compatibility validation. |
| Layer7 Operations Automation | Automate routine Broadcom Layer7 gateway operations including deployments, monitoring, and alarming. |
| Multi-Vendor API Management | Unify API management operations across heterogeneous gateway infrastructure. |

## Solutions

| Name | Description |
|------|-------------|
| API Control Plane | Central API management and governance for multi-vendor API gateway environments. |
| API Gateway Manager | Automated operations management for Broadcom Layer7 API gateway environments. |
| Enterprise | Custom licensing with dedicated support for large-scale federated API management deployments. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [APIIDA API Control Plane](openapi/apiida-api-control-plane-openapi.yml)
- [APIIDA API Gateway Manager](openapi/apiida-api-gateway-manager-openapi.yml)

### JSON Schema

- [apiida-api.json](json-schema/apiida-api.json)
- [apiida-deployment.json](json-schema/apiida-deployment.json)
- [apiida-gateway.json](json-schema/apiida-gateway.json)

### JSON Structure

- [apiida-api-structure.json](json-structure/apiida-api-structure.json)
- [apiida-deployment-structure.json](json-structure/apiida-deployment-structure.json)
- [apiida-gateway-structure.json](json-structure/apiida-gateway-structure.json)

### JSON-LD

- [apiida-context.jsonld](json-ld/apiida-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [APIIDA API Control Plane](capabilities/shared/api-control-plane.yaml) — 4 operations for federated API management
- [APIIDA API Gateway Manager](capabilities/shared/api-gateway-manager.yaml) — 3 operations for gateway management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Federated API Management](capabilities/federated-api-management.yaml) | API Control Plane, API Gateway Manager | 5 | API Platform Engineer, Enterprise Architect |

## Vocabulary

- [APIIDA Vocabulary](vocabulary/apiida-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across the federated API management domain

## Rules

- [apiida-spectral-rules.yml](rules/apiida-spectral-rules.yml) — 7 rules across 4 categories enforcing APIIDA API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
