# PriceSpecification — v2.0

Schema definition for PriceSpecification in the Beckn Protocol

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/PriceSpecification/v2.0/attributes.yaml](https://schema.nfh.global/PriceSpecification/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/PriceSpecification/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/PriceSpecification/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/PriceSpecification/v2.0/context.jsonld](https://schema.nfh.global/PriceSpecification/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/PriceSpecification/v2.0/vocab.jsonld](https://schema.nfh.global/PriceSpecification/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `currency` | no | string | ISO 4217 code |
| `value` | no | number | Total value for this price specification |
| `applicableQuantity` | no | $ref: https://schema.nfh.global/Quantity/v2.0/attributes.yaml#/components/schemas/Quantity | - |
| `components` | no | array | Optional components (tax, shipping, discount, fee, surcharge) |
