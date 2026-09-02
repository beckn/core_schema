# Rating — v2.1

Aggregated rating information for an entity. Aligns with schema.org/AggregateRating semantics.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Rating/v2.1/attributes.yaml](https://schema.nfh.global/Rating/v2.1/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Rating/v2.1/attributes.jsonschema.yaml](https://schema.nfh.global/Rating/v2.1/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Rating/v2.1/context.jsonld](https://schema.nfh.global/Rating/v2.1/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Rating/v2.1/vocab.jsonld](https://schema.nfh.global/Rating/v2.1/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `@context` | no | string | - |
| `@type` | no | string | - |
| `ratingValue` | no | number | Rating value (typically 0-5) |
| `ratingCount` | no | integer | Number of ratings |
| `reviewText` | no | string | Optional textual review or comment |
