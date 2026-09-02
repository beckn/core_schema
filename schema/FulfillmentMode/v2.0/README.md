# FulfillmentMode — v2.0

Describes the mode of fulfillment. This is an extensible container allowing domain-specific fulfillment modes to be expressed via attributes.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/FulfillmentMode/v2.0/attributes.yaml](https://schema.nfh.global/FulfillmentMode/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/FulfillmentMode/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/FulfillmentMode/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/FulfillmentMode/v2.0/context.jsonld](https://schema.nfh.global/FulfillmentMode/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/FulfillmentMode/v2.0/vocab.jsonld](https://schema.nfh.global/FulfillmentMode/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `@context` | no | string | - |
| `@type` | no | string | - |
| `id` | no | string | - |
| `descriptor` | no | $ref: https://schema.nfh.global/Descriptor/v2.1/attributes.yaml#/components/schemas/Descriptor | - |
| `modeAttributes` | no | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | Domain-specific fulfillment mode attributes (e.g., delivery, pickup, reservation, digital) |
