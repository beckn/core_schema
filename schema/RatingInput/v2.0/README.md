# RatingInput — v2.0

Schema definition for RatingInput in the Beckn Protocol

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/RatingInput/v2.0/attributes.yaml](https://schema.nfh.global/RatingInput/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/RatingInput/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/RatingInput/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/RatingInput/v2.0/context.jsonld](https://schema.nfh.global/RatingInput/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/RatingInput/v2.0/vocab.jsonld](https://schema.nfh.global/RatingInput/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `@context` | yes | string | - |
| `@type` | yes | string | - |
| `id` | yes | string | Target entity ID being rated (order/item/fulfillment/provider/agent). |
| `ratingValue` | yes | number | Numeric rating value (legacy usually 1–5). |
| `bestRating` | no | number | Maximum of the rating scale (default 5 if omitted). |
| `worstRating` | no | number | Minimum of the rating scale (default 1 or 0 if omitted). |
| `category` | no | string | What is being rated. |
| `feedback` | no | object | - |
