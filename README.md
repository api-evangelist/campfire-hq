# Campfire (campfire-hq)

Campfire is an AI-native ERP and accounting platform for high-growth startups and mid-market companies, unifying the general ledger, revenue recognition, accounts payable/receivable, reporting, and close management. Its "Ember" AI assistant automates transaction categorization, bank reconciliation, and revenue recognition. Campfire ships a documented REST developer API (api.meetcampfire.com) for custom accounting integrations and webhook-driven sync with tools like Stripe, Ramp, and Brex.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/campfire-hq/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/campfire-hq/refs/heads/main/apis.yml)

## Tags

- Accounting
- ERP
- General Ledger
- Revenue Recognition
- FinTech
- AI

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Campfire Core Accounting API

Create and manage journal entries (including intercompany entries), chart transactions, budgets, fixed assets, and transaction matching against the general ledger. The heart of Campfire's double-entry accounting engine.

- **Human URL:** [https://docs.campfire.ai/](https://docs.campfire.ai/)
- **Base URL:** `https://api.meetcampfire.com`

#### Tags

- General Ledger
- Journal Entries
- Transactions
- Budgets

#### Properties

- [Documentation](https://docs.campfire.ai/)
- [API Reference](https://api.meetcampfire.com/api/schema?format=json)
- [OpenAPI](openapi/campfire-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/campfire-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campfire-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Campfire Chart of Accounts & Company Objects API

Manage the chart of accounts and supporting company objects - departments, vendors, custom fields, custom dimensions and dimension groups, cost allocations, and fixed asset classes - that structure how transactions are coded.

- **Human URL:** [https://docs.campfire.ai/](https://docs.campfire.ai/)
- **Base URL:** `https://api.meetcampfire.com`

#### Tags

- Chart of Accounts
- Departments
- Vendors
- Custom Dimensions

#### Properties

- [Documentation](https://docs.campfire.ai/)
- [OpenAPI](openapi/campfire-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/campfire-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campfire-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Campfire Financial Statements API

Programmatically pull financial statements and reports - balance sheet (and comparative), income statement (and comparative), cash flow, cash-basis statements, trial balance, and the general ledger report.

- **Human URL:** [https://docs.campfire.ai/](https://docs.campfire.ai/)
- **Base URL:** `https://api.meetcampfire.com`

#### Tags

- Reporting
- Balance Sheet
- Income Statement
- Trial Balance

#### Properties

- [Documentation](https://docs.campfire.ai/)
- [OpenAPI](openapi/campfire-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/campfire-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campfire-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Campfire Accounts Payable API

Create, modify, pay, and void bills and bill drafts; manage debit memos, bill payments, and amortization schedules; and sync bills to Ramp.

- **Human URL:** [https://docs.campfire.ai/](https://docs.campfire.ai/)
- **Base URL:** `https://api.meetcampfire.com`

#### Tags

- Accounts Payable
- Bills
- Debit Memos
- Payments

#### Properties

- [Documentation](https://docs.campfire.ai/)
- [OpenAPI](openapi/campfire-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/campfire-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campfire-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Campfire Accounts Receivable API

Create, send, pay, and void invoices and credit memos; apply invoice payments in bulk; and generate client invoice statement and credit memo PDFs.

- **Human URL:** [https://docs.campfire.ai/](https://docs.campfire.ai/)
- **Base URL:** `https://api.meetcampfire.com`

#### Tags

- Accounts Receivable
- Invoices
- Credit Memos
- Payments

#### Properties

- [Documentation](https://docs.campfire.ai/)
- [OpenAPI](openapi/campfire-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/campfire-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campfire-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Campfire Revenue Recognition API

Manage revenue contracts, products and product bundles, subscriptions, milestones, usage-based revenue, prepaid commits, and revenue transactions - including a Parse Contract endpoint for AI-assisted contract ingestion.

- **Human URL:** [https://docs.campfire.ai/](https://docs.campfire.ai/)
- **Base URL:** `https://api.meetcampfire.com`

#### Tags

- Revenue Recognition
- Contracts
- Subscriptions
- Usage Billing

#### Properties

- [Documentation](https://docs.campfire.ai/)
- [OpenAPI](openapi/campfire-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/campfire-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campfire-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Campfire Cash Management API

Manage bank accounts and bank transactions, and post bank feed data for downstream categorization and reconciliation.

- **Human URL:** [https://docs.campfire.ai/](https://docs.campfire.ai/)
- **Base URL:** `https://api.meetcampfire.com`

#### Tags

- Cash Management
- Bank Accounts
- Bank Transactions
- Bank Feed

#### Properties

- [Documentation](https://docs.campfire.ai/api-reference/cash-management/list-bank-accounts)
- [OpenAPI](openapi/campfire-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/campfire-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campfire-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Campfire Bank Reconciliation API

Create and manage bank reconciliation reports, list and bulk-match GL transactions, parse bank statement pages, and confirm transaction selections to accelerate the monthly close.

- **Human URL:** [https://docs.campfire.ai/](https://docs.campfire.ai/)
- **Base URL:** `https://api.meetcampfire.com`

#### Tags

- Bank Reconciliation
- Matching
- Close

#### Properties

- [Documentation](https://docs.campfire.ai/)
- [OpenAPI](openapi/campfire-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/campfire-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campfire-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Campfire Settings API

Configure legal entities for multi-entity consolidation, manage customer currencies and exchange rates, and upload and manage files and attachments.

- **Human URL:** [https://docs.campfire.ai/](https://docs.campfire.ai/)
- **Base URL:** `https://api.meetcampfire.com`

#### Tags

- Settings
- Entities
- Currencies
- Files

#### Properties

- [Documentation](https://docs.campfire.ai/)
- [OpenAPI](openapi/campfire-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/campfire-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campfire-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Campfire Integrations & Webhooks API

Register and manage webhooks for event-driven sync, and list available webhook events, so external systems (Stripe, Ramp, Brex, ERPs) stay in step with Campfire's ledger.

- **Human URL:** [https://docs.campfire.ai/](https://docs.campfire.ai/)
- **Base URL:** `https://api.meetcampfire.com`

#### Tags

- Integrations
- Webhooks
- Event Sync

#### Properties

- [Documentation](https://docs.campfire.ai/)
- [OpenAPI](openapi/campfire-hq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/campfire-hq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/campfire-hq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/meetcampfire)
- [Website](https://www.campfire.ai/)
- [Documentation](https://docs.campfire.ai/)
- [Plans](plans/campfire-hq-plans-pricing.yml)
- [Rate Limits](rate-limits/campfire-hq-rate-limits.yml)
- [Fin Ops](finops/campfire-hq-finops.yml)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
