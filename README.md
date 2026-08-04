# Dodo Payments (dodo-payments)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Dodo Payments is a merchant-of-record (MoR) payments platform for global digital businesses. Its REST API handles one-time payments, subscriptions, checkout sessions, customers, products, discounts, license keys, payouts, refunds, disputes, and webhooks, while Dodo acts as the seller of record and calculates, collects, and remits sales tax, VAT, and GST across 190+ jurisdictions.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dodo-payments/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dodo-payments/refs/heads/main/apis.yml)

## Tags

- Payments
- Merchant of Record
- Subscriptions
- Billing
- Global Commerce

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Dodo Payments Products API

Create, list, update, and archive the digital products, prices, and files customers can buy, including one-time and recurring (subscription) products.

- **Human URL:** [https://docs.dodopayments.com/api-reference/products](https://docs.dodopayments.com/api-reference/products)
- **Base URL:** `https://live.dodopayments.com`

#### Tags

- Products
- Catalog
- Digital Goods

#### Properties

- [Documentation](https://docs.dodopayments.com/api-reference/products/create-product)
- [API Reference](https://docs.dodopayments.com/api-reference/products)
- [OpenAPI](openapi/dodo-payments-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dodo-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dodo-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dodo Payments Payments API

Create one-time payments and payment links, list and retrieve payments, and pull the invoice and line items for a completed transaction.

- **Human URL:** [https://docs.dodopayments.com/api-reference/payments](https://docs.dodopayments.com/api-reference/payments)
- **Base URL:** `https://live.dodopayments.com`

#### Tags

- Payments
- Transactions
- Invoices

#### Properties

- [Documentation](https://docs.dodopayments.com/api-reference/payments/create-payment)
- [API Reference](https://docs.dodopayments.com/api-reference/payments)
- [OpenAPI](openapi/dodo-payments-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dodo-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dodo-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dodo Payments Subscriptions API

Create and manage recurring subscriptions, change plans with preview, apply on-demand charges, and inspect usage and credit history across the billing lifecycle.

- **Human URL:** [https://docs.dodopayments.com/api-reference/subscriptions](https://docs.dodopayments.com/api-reference/subscriptions)
- **Base URL:** `https://live.dodopayments.com`

#### Tags

- Subscriptions
- Recurring Billing
- Plans

#### Properties

- [Documentation](https://docs.dodopayments.com/api-reference/subscriptions/create-subscription)
- [API Reference](https://docs.dodopayments.com/api-reference/subscriptions)
- [OpenAPI](openapi/dodo-payments-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dodo-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dodo-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dodo Payments Customers API

Create, list, and update customers and mint self-service customer portal sessions for managing their own subscriptions, payment methods, and invoices.

- **Human URL:** [https://docs.dodopayments.com/api-reference/customers](https://docs.dodopayments.com/api-reference/customers)
- **Base URL:** `https://live.dodopayments.com`

#### Tags

- Customers
- Customer Portal
- Wallets

#### Properties

- [Documentation](https://docs.dodopayments.com/api-reference/customers/create-customer)
- [API Reference](https://docs.dodopayments.com/api-reference/customers)
- [OpenAPI](openapi/dodo-payments-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dodo-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dodo-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dodo Payments Checkout Sessions API

Create hosted checkout sessions for one-time and subscription products, preview totals and taxes, and retrieve session status to drive a conversion-optimized payment flow.

- **Human URL:** [https://docs.dodopayments.com/api-reference/checkout-sessions](https://docs.dodopayments.com/api-reference/checkout-sessions)
- **Base URL:** `https://live.dodopayments.com`

#### Tags

- Checkout Sessions
- Hosted Checkout
- Conversion

#### Properties

- [Documentation](https://docs.dodopayments.com/api-reference/checkout-sessions/create-checkout-session)
- [API Reference](https://docs.dodopayments.com/api-reference/checkout-sessions)
- [OpenAPI](openapi/dodo-payments-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dodo-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dodo-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dodo Payments Discounts API

Create, list, update, and delete discount codes, and look up a discount by its public code to apply percentage or fixed-amount promotions at checkout.

- **Human URL:** [https://docs.dodopayments.com/api-reference/discounts](https://docs.dodopayments.com/api-reference/discounts)
- **Base URL:** `https://live.dodopayments.com`

#### Tags

- Discounts
- Coupons
- Promotions

#### Properties

- [Documentation](https://docs.dodopayments.com/api-reference/discounts/create-discount)
- [API Reference](https://docs.dodopayments.com/api-reference/discounts)
- [OpenAPI](openapi/dodo-payments-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dodo-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dodo-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dodo Payments Licenses API

Validate, activate, and deactivate software license keys and manage license key records and per-device instances for licensed digital products.

- **Human URL:** [https://docs.dodopayments.com/api-reference/licenses](https://docs.dodopayments.com/api-reference/licenses)
- **Base URL:** `https://live.dodopayments.com`

#### Tags

- Licenses
- License Keys
- Software Licensing

#### Properties

- [Documentation](https://docs.dodopayments.com/api-reference/licenses/validate-license)
- [API Reference](https://docs.dodopayments.com/api-reference/licenses)
- [OpenAPI](openapi/dodo-payments-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dodo-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dodo-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dodo Payments Payouts API

List settlement payouts and retrieve a per-payout breakup, line-item details, and a downloadable CSV reconciling gross sales, fees, taxes, and net settlement.

- **Human URL:** [https://docs.dodopayments.com/api-reference/payouts](https://docs.dodopayments.com/api-reference/payouts)
- **Base URL:** `https://live.dodopayments.com`

#### Tags

- Payouts
- Settlements
- Reporting

#### Properties

- [Documentation](https://docs.dodopayments.com/api-reference/payouts/list-payouts)
- [API Reference](https://docs.dodopayments.com/api-reference/payouts)
- [OpenAPI](openapi/dodo-payments-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dodo-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dodo-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dodo Payments Webhooks API

Register and manage webhook endpoints, configure custom headers, and retrieve the signing key used to verify event payloads for payments, subscriptions, refunds, and disputes.

- **Human URL:** [https://docs.dodopayments.com/api-reference/webhooks](https://docs.dodopayments.com/api-reference/webhooks)
- **Base URL:** `https://live.dodopayments.com`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.dodopayments.com/api-reference/webhooks/create-webhook)
- [API Reference](https://docs.dodopayments.com/api-reference/webhooks)
- [OpenAPI](openapi/dodo-payments-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dodo-payments.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dodo-payments.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/dodopayments)
- [LinkedIn](https://www.linkedin.com/company/dodopayments)
- [Website](https://dodopayments.com)
- [Documentation](https://docs.dodopayments.com)
- [Plans](plans/dodo-payments-plans-pricing.yml)
- [Rate Limits](rate-limits/dodo-payments-rate-limits.yml)
- [Fin Ops](finops/dodo-payments-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
