# Fare — v2.0

The monetary cost of travel for a specific journey or service, calculated based on applicable fare rules and passenger categories.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Fare/v2.0/attributes.yaml](https://schema.nfh.global/Fare/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Fare/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Fare/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Fare/v2.0/context.jsonld](https://schema.nfh.global/Fare/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Fare/v2.0/vocab.jsonld](https://schema.nfh.global/Fare/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `fareId` | no | string | Unique identifier for the fare |
| `amount` | no | number | Total fare amount |
| `currency` | no | string | ISO 4217 currency code |
| `fareAttributes` | no | string | Transfer permissions, agency, and transfer limit |
| `fareRules` | no | $ref: https://schema.nfh.global/FareLegRule/v2.0/attributes.yaml#/components/schemas/FareLegRule | Leg rules that determine when this fare applies |
| `id` | no | string | Unique identifier for the offer |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the offer |
| `price` | no | $ref: https://schema.nfh.global/PriceSpecification/v2.1/attributes.yaml#/components/schemas/PriceSpecification | Price specification for this offer |
| `validity` | no | $ref: https://schema.nfh.global/TimePeriod/v2.0/attributes.yaml#/components/schemas/TimePeriod | Validity period of the offer |
| `tags` | no | string | Tags or labels associated with the offer |
