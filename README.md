# Unpaywall

The Unpaywall REST API gives anyone free, programmatic access to the Unpaywall database of open access scholarly articles. The database covers over 120 million articles with Crossref DOIs and provides free, legal full-text links where available — with metadata on OA status, host type, version, and license.

**Website:** [unpaywall.org](https://unpaywall.org)
**API Docs:** [unpaywall.org/products/api](https://unpaywall.org/products/api)
**Data Format:** [unpaywall.org/data-format](https://unpaywall.org/data-format)

---

## API

### Unpaywall API (v2.0.0)

Free REST API for open access status lookups by DOI and title search.

- Base URL: `https://api.unpaywall.org/v2`
- Auth: `?email=you@example.com` (query parameter, no API key)
- Rate limit: 100,000 calls/day

**Endpoints:**
| Method | Path | Description |
|---|---|---|
| GET | `/{doi}?email={email}` | Get Open Access Status by DOI |
| GET | `/search/?query={q}&email={email}` | Search Articles by Title |

- [OpenAPI Specification](openapi/unpaywall-openapi.yml)

---

## Artifacts

### OpenAPI
| File | Description |
|---|---|
| [unpaywall-openapi.yml](openapi/unpaywall-openapi.yml) | Full Unpaywall API OpenAPI 3.0.3 specification |

### Spectral Rules
| File | Description |
|---|---|
| [unpaywall-rules.yml](rules/unpaywall-rules.yml) | Spectral ruleset for Unpaywall API conventions |

### Capabilities (Naftiko)
| File | Description |
|---|---|
| [shared/unpaywall.yaml](capabilities/shared/unpaywall.yaml) | Shared Unpaywall API consumed definition |
| [open-access-discovery.yaml](capabilities/open-access-discovery.yaml) | Open access discovery workflow (2 tools) |

### JSON Schema
| File | Description |
|---|---|
| [unpaywall-article-schema.json](json-schema/unpaywall-article-schema.json) | Unpaywall article object schema |

### JSON Structure
| File | Description |
|---|---|
| [unpaywall-article-structure.json](json-structure/unpaywall-article-structure.json) | Article field documentation |

### JSON-LD Context
| File | Description |
|---|---|
| [unpaywall-context.jsonld](json-ld/unpaywall-context.jsonld) | Linked data context mapping Unpaywall concepts to schema.org, bibo, dcterms |

### Examples
| File | Description |
|---|---|
| [unpaywall-get-doi-example.json](examples/unpaywall-get-doi-example.json) | DOI lookup request/response |
| [unpaywall-search-example.json](examples/unpaywall-search-example.json) | Title search request/response |

### Vocabulary
| File | Description |
|---|---|
| [unpaywall-vocabulary.yml](vocabulary/unpaywall-vocabulary.yml) | Domain vocabulary for open access and scholarly publishing concepts |

---

## APIs Index

- [apis.yml](apis.yml)

---

*Maintained by [API Evangelist](https://apievangelist.com)*
