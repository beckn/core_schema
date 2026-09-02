# PriceSpecification — v2.2

Schema definition for PriceSpecification in the Beckn Protocol v2.0.1

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/PriceSpecification/v2.2/attributes.yaml](https://schema.nfh.global/PriceSpecification/v2.2/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/PriceSpecification/v2.2/attributes.jsonschema.yaml](https://schema.nfh.global/PriceSpecification/v2.2/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/PriceSpecification/v2.2/context.jsonld](https://schema.nfh.global/PriceSpecification/v2.2/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/PriceSpecification/v2.2/vocab.jsonld](https://schema.nfh.global/PriceSpecification/v2.2/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `currency` | no | string | ISO 4217 code |
| `value` | no | number | Total value for this price specification |
| `applicableQuantity` | no | $ref: https://schema.nfh.global/Quantity/v2.0/attributes.yaml#/components/schemas/Quantity | - |
| `components` | no | array | Optional components (tax, shipping, discount, fee, surcharge) |
