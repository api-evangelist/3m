# 3M (3m)
3M is a global science and manufacturing company. The 3M Partner and Supplier API provides real-time access to product, pricing, order, delivery, and invoice data for partners and suppliers, enabling automated commerce and supply chain integration.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/3m/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Industrial, Manufacturing, Supply Chain

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-04-19

## APIs

### 3M Partner and Supplier API
The 3M Partner and Supplier API provides real-time access to 3M product, pricing, order, delivery, and invoice data for partners and suppliers. The API supports GET and POST operations for product/price lookups, order and delivery tracking, and invoice status queries. Authentication uses OAuth 2.0 bearer tokens with client credentials provided during onboarding.

**Human URL:** [https://www.3m.com/3M/en_US/company-us/partners-suppliers/api/](https://www.3m.com/3M/en_US/company-us/partners-suppliers/api/)

#### Tags:

 - Manufacturing, Orders, Product Data, Supply Chain

#### Properties

- [Documentation](https://www.3m.com/3M/en_US/company-us/partners-suppliers/api/api-details/)
- [OpenAPI](openapi/3m-partner-supplier-api-openapi.yml)
- [JSONSchema](json-schema/3m-partner-supplier-api-product-schema.json)
- [JSONSchema](json-schema/3m-partner-supplier-api-order-schema.json)
- [JSONSchema](json-schema/3m-partner-supplier-api-delivery-schema.json)
- [JSONSchema](json-schema/3m-partner-supplier-api-invoice-schema.json)
- [JSON-LD](json-ld/3m-partner-supplier-api-context.jsonld)

## Common Properties

- [Website](https://www.3m.com/)
- [Portal](https://developer.3m.com/s/)
- [Documentation](https://www.3m.com/3M/en_US/company-us/partners-suppliers/api/api-details/)
- [GettingStarted](https://www.3m.com/3M/en_US/company-us/partners-suppliers/api/)

## Features

| Name | Description |
|------|-------------|
| Product Catalog Access | Real-time access to 3M product catalog with availability and pricing information |
| Partner Pricing | Negotiated pricing tiers based on partner agreements |
| Order Management | Submit and track purchase orders programmatically |
| Delivery Tracking | Real-time delivery status and carrier tracking information |
| Invoice Retrieval | Access invoices for billing reconciliation and accounts payable automation |
| OAuth 2.0 Authentication | Secure bearer token authentication via client credentials OAuth 2.0 flow |

## Use Cases

| Name | Description |
|------|-------------|
| Automated Procurement | Automate purchase order creation based on inventory levels or demand signals |
| Supply Chain Visibility | Track order and delivery status in real-time for supply chain planning |
| ERP Integration | Integrate 3M product data, orders, and invoices with ERP systems |
| Price Comparison | Retrieve partner-negotiated pricing for procurement decision support |
| Accounts Payable Automation | Automatically retrieve and reconcile invoices with purchase orders |
| Inventory Management | Check product availability and pricing for inventory replenishment |

## Integrations

| Name | Description |
|------|-------------|
| ERP Systems | Integrate product, order, and invoice data with SAP, Oracle, or Microsoft Dynamics |
| Procurement Platforms | Connect with procurement management platforms for automated ordering |
| Accounting Systems | Sync invoices with accounting software for automated AP reconciliation |
| Supply Chain Platforms | Feed order and delivery data into supply chain visibility platforms |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [3M Partner and Supplier API](openapi/3m-partner-supplier-api-openapi.yml)

### JSON Schema

- 12 schema files covering products, product pricing, orders, order items, shipping addresses, deliveries, and invoices

### JSON Structure

- 12 JSON Structure files (json-structure.org format)

### JSON-LD

- [3M Partner and Supplier API Context](json-ld/3m-partner-supplier-api-context.jsonld)

### Examples

- 12 example JSON files for all schemas

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [3M Partner and Supplier API](capabilities/shared/3m-partner-supplier-api.yaml) — 6 operations for product lookup, order management, delivery tracking, and invoice retrieval

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [3M Supply Chain Integration](capabilities/3m-supply-chain-integration.yaml) | 3M Partner and Supplier API | 6 | Procurement Manager, Supply Chain Analyst, Accounts Payable |

## Vocabulary

- [3M Vocabulary](vocabulary/3m-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 3 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [3M Spectral Rules](rules/3m-spectral-rules.yml) — 28 rules across 12 categories enforcing 3M API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
