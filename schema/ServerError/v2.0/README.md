# ServerError — v2.0

Internal failure on the network participant's application; the request could not be processed. The response body MAY contain an `error` object with additional details.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/ServerError/v2.0/attributes.yaml](https://schema.nfh.global/ServerError/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/ServerError/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/ServerError/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/ServerError/v2.0/context.jsonld](https://schema.nfh.global/ServerError/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/ServerError/v2.0/vocab.jsonld](https://schema.nfh.global/ServerError/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `error` | no | $ref: https://schema.nfh.global/Error/v2.0/attributes.yaml#/components/schemas/Error | - |
