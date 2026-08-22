# Ship24 (ship24)

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

Ship24 is a universal shipment tracking platform that consolidates 1,500+ couriers and marketplaces into a single API, dashboard, and post-purchase customer experience. It is operated as an enterprise tracking aggregator with reported coverage of over a billion shipments tracked, a Shopify app, branded tracking pages, email and SMS delivery notifications, a tracking widget, and an IOSS fiscal intermediary service for EU VAT compliance on inbound parcels. The developer surface is a single REST tracking API delivering normalized status codes and webhook events designed to reduce WISMO ("where is my order?") support load for ecommerce, 3PL, and marketplace operators.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ship24/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ship24/refs/heads/main/apis.yml)

## Scope

- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Tracking
- Logistics
- Shipping
- Couriers
- Parcels
- Webhooks
- Ecommerce
- PostPurchase

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Ship24 Tracking API

The Ship24 Tracking API is a universal package tracking aggregator that abstracts 1,500+ couriers worldwide behind a single REST endpoint. Developers create a Tracker by submitting a tracking number (with optional courier hint) and receive a normalized timeline of shipment events — accepted, in transit, out for delivery, delivered, exception, pending, etc. — pushed via webhooks or pulled by tracker ID. The API exposes courier auto-detection, bulk tracker creation, a courier catalog endpoint, and webhook resend tooling for replay. It powers branded tracking pages, dashboards, and post-purchase customer experiences across ecommerce, 3PL, and marketplace workloads.

- **Human URL:** [https://docs.ship24.com/](https://docs.ship24.com/)
- **Base URL:** `https://api.ship24.com`

#### Tags

- Tracking
- Logistics
- Shipping
- Parcels
- Couriers
- Webhooks
- Ecommerce

#### Properties

- [Documentation](https://docs.ship24.com/)
- [API Reference](https://docs.ship24.com/tracking-api-reference/)
- [Getting Started](https://docs.ship24.com/getting-started)
- [OpenAPI](https://docs.ship24.com/assets/openapi/ship24-tracking-api.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/ship24-tracking-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ship24-tracking-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ship24-tracking-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Webhooks](https://docs.ship24.com/webhooks)
- [Rate Limits](https://docs.ship24.com/rate-limiter)
- [Integration](https://github.com/Ship24/n8n-nodes-ship24)
- [Spectral Rules](rules/ship24-rules.yml)
- [JSON Schema](json-schema/ship24-tracker-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/ship24-tracking-result-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/ship24-tracker-structure.json)
- [JSON-LD](json-ld/ship24-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/ship24-vocabulary.yml)
- [Example](examples/ship24-create-tracker-example.json)
- [Example](examples/ship24-tracking-result-example.json)
- [Plans](plans/ship24-plans-pricing.yml)
- [Rate Limits Artifact](rate-limits/ship24-rate-limits.yml)
- [Fin Ops](finops/ship24-finops.yml)

## Common Properties

- [Website](https://www.ship24.com)
- [Documentation](https://docs.ship24.com/)
- [API Reference](https://docs.ship24.com/tracking-api-reference/)
- [Getting Started](https://docs.ship24.com/getting-started)
- [Webhooks](https://docs.ship24.com/webhooks)
- [Rate Limits](https://docs.ship24.com/rate-limiter)
- [Pricing](https://www.ship24.com/pricing)
- [Sign Up](https://dashboard.ship24.com/register)
- [Login](https://dashboard.ship24.com/)
- [Authentication](https://dashboard.ship24.com/integrations/api-keys)
- [Status](https://status.ship24.com)
- [Blog](https://www.ship24.com/blog)
- [Contact Us](https://www.ship24.com/contact-us)
- [Terms of Service](https://www.ship24.com/terms-and-conditions)
- [Privacy Policy](https://www.ship24.com/privacy-policy)
- [LinkedIn](https://www.linkedin.com/company/ship24/)
- [GitHub Organization](https://github.com/Ship24)
- [Shopify App](https://apps.shopify.com/ship24)
- [Features](undefined)
- [Integrations](https://www.ship24.com/integrations)
- [Agent Skill](https://github.com/Ship24/n8n-nodes-ship24)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
