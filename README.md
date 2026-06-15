# Ship24 (ship24)

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
