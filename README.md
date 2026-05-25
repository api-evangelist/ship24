# Ship24

API Evangelist profile of [Ship24](https://www.ship24.com/) — a universal package tracking aggregator that consolidates 1,500+ couriers worldwide behind a single REST API, webhook stream, and branded post-purchase experience.

This repository is part of the [API Evangelist](https://apievangelist.com) network. It contains an `apis.yml` index plus generated artifacts (OpenAPI, JSON Schema, JSON Structure, JSON-LD, Spectral rules, Naftiko capabilities, vocabulary, plans, rate limits, and FinOps) for the Ship24 Tracking API.

## What Ship24 Provides

- A single REST endpoint at `https://api.ship24.com` that normalizes shipment events from 1,500+ couriers (USPS, UPS, FedEx, DHL, Royal Mail, La Poste, China Post, Japan Post, etc.).
- Tracker resource lifecycle (create, list, get, update, bulk create) and synchronous "create + return results" operation.
- Webhook delivery of tracking events and a resend endpoint for replay.
- Courier catalog endpoint for client-side validation and dropdowns.
- Auto-detection of courier from tracking number patterns.
- Branded tracking pages, email and SMS delivery notifications, tracking widget, and a Shopify app for post-purchase workflows.
- IOSS fiscal intermediary service for EU VAT compliance on inbound cross-border parcels.

## Repository Layout

| Folder | Contents |
|---|---|
| `apis.yml` | Provider index and property manifest (APIs.json / APIs.yaml). |
| `openapi/` | Ship24 Tracking API OpenAPI 3.1 spec (mirrored from `docs.ship24.com`). |
| `capabilities/` | Naftiko capability definitions: trackers, tracking results, couriers, webhooks, parcel-tracking workflow. |
| `examples/` | Example request/response payloads for tracker creation and tracking results. |
| `json-schema/` | JSON Schemas for `Tracker` and `TrackingResult`. |
| `json-structure/` | JSON Structure documentation of the Ship24 entity model. |
| `json-ld/` | JSON-LD context aligning Ship24 terms with schema.org `ParcelDelivery`. |
| `rules/` | Spectral ruleset enforcing Ship24-specific OpenAPI conventions. |
| `vocabulary/` | Vocabulary capturing normalized status codes, entities, and domain dimensions. |
| `plans/` | Commercial pricing tiers (Free, Essential, Pro, Enterprise) in API Commons Plans 0.1 format. |
| `rate-limits/` | Per-endpoint per-second rate limits and rate-limit response headers. |
| `finops/` | FinOps Framework / FOCUS-aligned cost-allocation manifest. |

## Key Links

- Website: <https://www.ship24.com>
- Documentation: <https://docs.ship24.com>
- API Reference: <https://docs.ship24.com/tracking-api-reference/>
- OpenAPI: <https://docs.ship24.com/assets/openapi/ship24-tracking-api.yaml>
- Webhooks: <https://docs.ship24.com/webhooks>
- Rate Limits: <https://docs.ship24.com/rate-limiter>
- Pricing: <https://www.ship24.com/pricing>
- Dashboard: <https://dashboard.ship24.com>
- Status: <https://status.ship24.com>
- GitHub: <https://github.com/Ship24>

## Tier

Tier-1 — first-party OpenAPI published, documented rate limits, multi-tier published pricing, webhooks with signing, GitHub presence (n8n nodes), and a normalized cross-carrier status model.

## License

The artifacts in this repository are released under the same terms as the rest of the API Evangelist network. Ship24 trademarks and content belong to Ship24.
