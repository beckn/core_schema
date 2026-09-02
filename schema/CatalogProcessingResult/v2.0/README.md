# CatalogProcessingResult — v2.0

Processing result for a single catalog submission.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/CatalogProcessingResult/v2.0/attributes.yaml](https://schema.nfh.global/CatalogProcessingResult/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/CatalogProcessingResult/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/CatalogProcessingResult/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/CatalogProcessingResult/v2.0/context.jsonld](https://schema.nfh.global/CatalogProcessingResult/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/CatalogProcessingResult/v2.0/vocab.jsonld](https://schema.nfh.global/CatalogProcessingResult/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `catalogId` | yes | string | Identifier of the submitted catalog |
| `status` | yes | string | Processing outcome. Using oneOf [string, object] to allow domain-specific status objects (e.g. beckn:CatalogAccepted) alongside standard string codes. |
| `errors` | no | array | Per-item or per-catalog errors (present when REJECTED or PARTIAL) |
| `stats` | no | object | Optional statistics about the processed catalog |
