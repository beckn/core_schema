# Provider — v2.1

Schema definition for Provider in the Beckn Protocol v2.0.1

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Provider/v2.1/attributes.yaml](https://schema.nfh.global/Provider/v2.1/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Provider/v2.1/attributes.jsonschema.yaml](https://schema.nfh.global/Provider/v2.1/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Provider/v2.1/context.jsonld](https://schema.nfh.global/Provider/v2.1/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Provider/v2.1/vocab.jsonld](https://schema.nfh.global/Provider/v2.1/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `id` | yes | string | Unique identifier for the provider |
| `descriptor` | yes | $ref: https://schema.nfh.global/Descriptor/v2.1/attributes.yaml#/components/schemas/Descriptor | - |
| `availableAt` | no | array | Physical locations where the provider operates |
| `providerAttributes` | no | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | - |
