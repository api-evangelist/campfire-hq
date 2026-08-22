# Campfire (campfire-hq)

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
