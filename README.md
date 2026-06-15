# The Index (the-index-fyi)

theindex.fyi is a maintained meta-index of indie web and small web index sites — a curated catalog of curated catalogs. It tracks ~40 indexes spanning six categories (curated directories, RSS / feed aggregators, search engines, random-discovery tools, constraint-based clubs, and IndieWeb infrastructure), and exposes the catalog through a public, read-only JSON:API.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/the-index-fyi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/the-index-fyi/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Indie Web
- Small Web
- Directories
- Search
- RSS
- Webrings
- Open Data
- JSON:API

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### The Index Public API

Public, read-only API listing every active index in theindex.fyi. Responses follow JSON:API 1.1 (`application/vnd.api+json`) and include filterable / paginated collection endpoints plus single- resource lookups by slug. Rate-limited to 60 requests / minute per IP, with standard `X-RateLimit-*` and `Retry-After` headers.

- **Human URL:** [https://theindex.fyi/api/docs](https://theindex.fyi/api/docs)
- **Base URL:** `https://theindex.fyi/api`

#### Tags

- Indexes
- Curated Directories
- RSS Aggregators
- Search Engines
- Random Discovery
- Constraint-Based Clubs
- IndieWeb Infrastructure

#### Properties

- [Documentation](https://theindex.fyi/api/docs)
- [OpenAPI](openapi/the-index-fyi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/the-index-fyi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/the-index-fyi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [OpenAPI](openapi/the-index-fyi-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Human U R L](https://theindex.fyi/)
- [About Us](https://theindex.fyi/about)

## Common Properties

- [Website](https://theindex.fyi/)
- [About Us](https://theindex.fyi/about)
- [Documentation](https://theindex.fyi/api/docs)
- [OpenAPI](openapi/the-index-fyi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Plan](plans/the-index-fyi-plans-pricing.yml)
- [Rate  Limit](rate-limits/the-index-fyi-rate-limits.yml)
- [Fin Ops](finops/the-index-fyi-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
