# Novo (novo-bank)

Novo is a U.S. business banking platform built for small businesses, freelancers, and self-employed professionals, offering a free business checking account, invoicing, reserves, AI-assisted bookkeeping, a business credit card, and funding. Banking services are provided by Middlesex Federal Savings, F.A. Novo does not publish a public self-service developer API; programmatic access to Novo account data is currently delivered through third-party aggregators (Plaid), and product integrations connect Novo accounts to tools like Stripe, Shopify, QuickBooks, Xero, Wise, and Square.

> Disambiguation: This profile covers **Novo** (banknovo / novo.co), the U.S. SMB business banking platform. It is **not** Novo Nordisk (pharmaceutical), **NovoPayment** (Latin American BaaS at developer.novopayment.com), or **Novo Banco** (Portuguese bank at api.novobanco.es) — all distinct companies.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/novo-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/novo-bank/refs/heads/main/apis.yml)

## Tags

- Banking
- Business Banking
- Fintech
- Small Business
- Freelancers
- Payments

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Novo Accounts

Novo business checking account data - account identity, balances, and auth. Novo does not expose a public first-party Accounts API; account connectivity is provided through the Plaid aggregator (Assets, Auth, Balance products). Modeled here as a product surface, not a documented Novo endpoint.

- **Human URL:** [https://www.novo.co/business-banking](https://www.novo.co/business-banking)

#### Tags

- Accounts
- Balances
- Banking

#### Properties

- [Documentation](https://www.novo.co/business-banking)
- [API Reference](https://plaid.com/institutions/novo/)
- [OpenAPI](openapi/novo-bank-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/novo-bank.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novo-bank.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Novo Transactions

Novo transaction history and categorization used for bookkeeping and reconciliation. There is no documented public Novo Transactions API; transaction data is accessed via aggregators such as Plaid, or synced into accounting tools through Novo's productized integrations.

- **Human URL:** [https://www.novo.co/business-banking](https://www.novo.co/business-banking)

#### Tags

- Transactions
- Statements
- Reconciliation

#### Properties

- [Documentation](https://www.novo.co/business-banking)
- [API Reference](https://plaid.com/institutions/novo/)
- [OpenAPI](openapi/novo-bank-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/novo-bank.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novo-bank.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Novo Payments

Novo money movement - invoicing, ACH transfers, and faster payouts (Express ACH). These capabilities are delivered through the Novo app and partner rails; no public payments API is documented for third-party developers. Modeled as a product surface.

- **Human URL:** [https://www.novo.co/features/invoices](https://www.novo.co/features/invoices)

#### Tags

- Payments
- ACH
- Invoicing

#### Properties

- [Documentation](https://www.novo.co/features/invoices)
- [OpenAPI](openapi/novo-bank-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/novo-bank.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novo-bank.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Novo Integrations

Productized, prebuilt integrations that connect a Novo account to business tools - Stripe, Shopify, Square, Amazon, Etsy, eBay, Wise, QuickBooks, Xero, Slack, and DocuSign. These are configured in-app rather than via a public developer API, so no OpenAPI is modeled for this surface.

- **Human URL:** [https://www.novo.co/integrations](https://www.novo.co/integrations)

#### Tags

- Integrations
- Partners
- Accounting

#### Properties

- [Documentation](https://www.novo.co/integrations)
- [Documentation](https://www.novo.co/features/stripe-integration)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/banknovo)
- [Website](https://www.novo.co/)
- [Documentation](https://www.novo.co/integrations)
- [Plans](plans/novo-bank-plans-pricing.yml)
- [Rate Limits](rate-limits/novo-bank-rate-limits.yml)
- [Fin Ops](finops/novo-bank-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
