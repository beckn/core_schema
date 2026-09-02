# CatalogPullAction — v2.0

Message payload for catalog/pull

This schema is part of the Long Term Support of Beckn Protocol V2.0 API specification and MUST NOT be extended. Any domain-specific extension must use the property of this schema which is of type Attribute.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/CatalogPullAction/v2.0/attributes.yaml](https://schema.nfh.global/CatalogPullAction/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/CatalogPullAction/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/CatalogPullAction/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/CatalogPullAction/v2.0/context.jsonld](https://schema.nfh.global/CatalogPullAction/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/CatalogPullAction/v2.0/vocab.jsonld](https://schema.nfh.global/CatalogPullAction/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `mode` | yes | string | - `FULL` — returns the latest version of each matching catalog. - `INCREMENTAL` — returns all catalog versions indexed between   `fromDate` and `toDate` (inclusive).  |
| `filters` | no | object | Optional filters narrowing which catalogs are returned |
| `catalogIds` | no | array | Explicit catalog IDs to pull (alternative to filters) |
| `limit` | no | integer | Maximum number of catalogs to return (server may apply its own cap) |
| `fromDate` | no | string | Inclusive lower bound for INCREMENTAL mode |
| `toDate` | no | string | Inclusive upper bound for INCREMENTAL mode |
