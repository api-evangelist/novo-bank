# Novo (novo-bank)

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
