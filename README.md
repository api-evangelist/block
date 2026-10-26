# Block (block)

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

Block, Inc. is a global technology company building economic empowerment tools through a family of products including Square (commerce and payments), Cash App (personal finance and investing), Afterpay (buy now pay later), TIDAL (music streaming), and Spiral (open-source Bitcoin development). The Square API enables developers to build commerce applications with payment processing, order management, catalog, customer engagement, and business operations capabilities.

**URL:** [https://www.block.xyz](https://www.block.xyz)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Commerce, Cryptocurrency, eCommerce, Fintech, Payments, Point Of Sale, Square

## Timestamps

- **Created:** 2024-09-27
- **Modified:** 2026-04-19

## APIs

### Square API
RESTful API for building commerce applications on the Square platform. Provides payment processing, order management, catalog management, customer profiles, loyalty programs, invoicing, and merchant operations.

**Human URL:** [https://developer.squareup.com/](https://developer.squareup.com/)

#### Tags:

 - Commerce, eCommerce, Payments, Point Of Sale, Square

#### Properties

- [Documentation](https://developer.squareup.com/docs)
- [OpenAPI](openapi/block-square-api-openapi.yaml)
- [NaftikoCapability](capabilities/block-square-commerce.yaml)
- [SpectralRules](rules/block-spectral-rules.yml)
- [Vocabulary](vocabulary/block-vocabulary.yaml)

## Common Properties

- [Website](https://www.block.xyz)
- [Documentation](https://developer.squareup.com/docs)
- [Getting Started](https://developer.squareup.com/docs/get-started)
- [Pricing](https://squareup.com/us/en/payments/our-rates)
- [Status Page](https://www.issquareup.com/)
- [Support](https://developer.squareup.com/forums)
- [GitHub Organization](https://github.com/square)
- [Terms of Service](https://squareup.com/us/en/legal/developer)
- [Privacy Policy](https://squareup.com/us/en/legal/privacy)
- [Login](https://developer.squareup.com/apps)
- [Square SDKs](https://developer.squareup.com/docs/sdks)

## Features

| Name | Description |
|------|-------------|
| Payment Processing | Accept card-present and card-not-present payments using Square hardware, web, or mobile SDKs with OAuth 2.0 or access token authentication. |
| Order Management | Create, update, and fulfill orders with line items, discounts, taxes, and service charges across online and in-person channels. |
| Catalog Management | Manage a unified product catalog with items, variations, modifiers, categories, taxes, and discounts synchronized across all locations. |
| Customer Engagement | Build customer profiles, loyalty programs, gift cards, and marketing campaigns to drive repeat business and customer retention. |
| Multi-Location Support | Manage multiple business locations with location-specific inventory, pricing, staff permissions, and reporting. |
| Webhook Events | Subscribe to real-time webhook events for payments, orders, inventory changes, customer activity, and subscription lifecycle events. |
| Sandbox Environment | Full sandbox environment with test card numbers, merchant accounts, and simulated hardware for development and testing. |

## Use Cases

| Name | Description |
|------|-------------|
| Point of Sale Integration | Retailers and restaurants build custom POS applications using Square's payment, catalog, and order APIs. |
| eCommerce Checkout | Online stores integrate Square's Web Payments SDK and Orders API to accept payments and manage fulfillment. |
| Marketplace Payments | Multi-seller marketplaces use Square Connect to route payments to sellers and manage fees through the Payouts API. |
| Subscription Billing | SaaS and service businesses use Square Subscriptions API for automated recurring billing and invoice management. |
| Loyalty and Rewards | Businesses implement custom loyalty programs using the Loyalty API to track points, tiers, and reward redemptions. |

## Integrations

| Name | Description |
|------|-------------|
| WooCommerce | Official Square extension for WooCommerce synchronizes inventory, products, and payments between WordPress stores and Square. |
| BigCommerce | Square integration for BigCommerce enables omnichannel selling with synchronized catalog and unified payment processing. |
| Xero | Square-Xero integration automatically syncs sales transactions and payments to Xero accounting for reconciliation. |
| QuickBooks | Square connector for QuickBooks Online syncs sales, refunds, and fees to QuickBooks for financial reporting. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Square API](openapi/block-square-api-openapi.yaml)

### JSON Schema

- [Payment](json-schema/block-payment-schema.json)
- [Order](json-schema/block-order-schema.json)
- [Customer](json-schema/block-customer-schema.json)
- [Catalog Object](json-schema/block-catalog-object-schema.json)

### JSON Structure

- [Payment](json-structure/block-payment-structure.json)
- [Order](json-structure/block-order-structure.json)
- [Customer](json-structure/block-customer-structure.json)
- [Catalog Object](json-structure/block-catalog-object-structure.json)

### JSON-LD

- [Block Context](json-ld/block-context.jsonld)

### Examples

- [Payment Example](examples/block-payment-example.json)
- [Order Example](examples/block-order-example.json)
- [Customer Example](examples/block-customer-example.json)
- [Catalog Object Example](examples/block-catalog-object-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Square API](capabilities/shared/block-square-api.yaml) — 8 operations for payments, orders, catalog, customers, and locations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Block Square Commerce](capabilities/block-square-commerce.yaml) | Square API | 8 | Retail Sellers, eCommerce Developers, Restaurant Operators, App Integrators |

## Vocabulary

- [Block Vocabulary](vocabulary/block-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 4 actions, 1 workflow, and 4 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Block Spectral Rules](rules/block-spectral-rules.yml) — 30 rules across 12 categories enforcing Square API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
