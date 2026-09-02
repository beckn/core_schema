# Provider — v2.0

Schema definition for Provider in the Beckn Protocol

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Provider/v2.0/attributes.yaml](https://schema.nfh.global/Provider/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Provider/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Provider/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Provider/v2.0/context.jsonld](https://schema.nfh.global/Provider/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Provider/v2.0/vocab.jsonld](https://schema.nfh.global/Provider/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `beckn:id` | yes | string | Unique identifier for the provider |
| `beckn:descriptor` | yes | $ref: https://schema.nfh.global/Descriptor/v2.1/attributes.yaml#/components/schemas/Descriptor | - |
| `beckn:validity` | no | $ref: https://schema.nfh.global/TimePeriod/v2.1/attributes.yaml#/components/schemas/TimePeriod | - |
| `beckn:locations` | no | array | Physical locations where the provider operates |
| `beckn:rateable` | no | boolean | Whether the provider can be rated by customers |
| `beckn:rating` | no | $ref: https://schema.nfh.global/Rating/v2.1/attributes.yaml#/components/schemas/Rating | - |
| `beckn:providerAttributes` | no | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | - |
