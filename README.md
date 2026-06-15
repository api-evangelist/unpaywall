# Unpaywall (unpaywall)

The Unpaywall REST API gives anyone free, programmatic access to the Unpaywall database of open access scholarly articles. The database covers over 120 million articles with Crossref DOIs and provides free, legal full-text links where available, with metadata on OA status (gold, hybrid, bronze, green), host type (publisher, repository), version (published, accepted, submitted), and license information.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Open Access
- Scholarly Articles
- Research
- Academic
- Libraries
- DOI
- Science

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-05-19

## APIs

### Unpaywall API

Free REST API providing open access status and full-text links for 120M+ scholarly articles. Look up any article by DOI to get its OA status, best open access location (publisher or repository), license, version, and all available free copies. Also supports title-based search across the full database. No API key required — just include your email address in requests. Rate limit: 100,000 calls per day.

- **Human URL:** [https://unpaywall.org/products/api](https://unpaywall.org/products/api)
- **Base URL:** `https://api.unpaywall.org/v2`

#### Tags

- Open Access
- DOI
- Scholarly Articles
- Search

#### Properties

- [Documentation](https://unpaywall.org/products/api)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/openapi/unpaywall-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/rules/unpaywall-rules.yml)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/json-schema/unpaywall-article-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/unpaywall.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/unpaywall.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/ourresearch)
- [LinkedIn](https://www.linkedin.com/company/impactstory)
- [Website](https://unpaywall.org)
- [Documentation](https://unpaywall.org/products/api)
- [Data Format](https://unpaywall.org/data-format)
- [Support](https://support.unpaywall.org)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/vocabulary/unpaywall-vocabulary.yml)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/unpaywall/refs/heads/main/json-ld/unpaywall-context.jsonld)
- [L L Ms Txt](https://unpaywall.org/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
