# SystemPricingPlan — v2.0

A pricing plan defined by a shared mobility system, describing costs and billing rules for vehicle use.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/SystemPricingPlan/v2.0/attributes.yaml](https://schema.nfh.global/SystemPricingPlan/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/SystemPricingPlan/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/SystemPricingPlan/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/SystemPricingPlan/v2.0/context.jsonld](https://schema.nfh.global/SystemPricingPlan/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/SystemPricingPlan/v2.0/vocab.jsonld](https://schema.nfh.global/SystemPricingPlan/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `planId` | no | string | Unique identifier for the pricing plan |
| `currency` | no | string | ISO 4217 currency code |
| `isTaxable` | no | boolean | Whether tax is applied to this pricing plan |
| `perMinuteChargingRate` | no | number | Charge per minute of vehicle use |
| `perKmChargingRate` | no | number | Charge per kilometre of vehicle use |
| `perTripStartingFee` | no | number | Flat fee charged at the start of each trip |
| `id` | no | string | Unique identifier for the offer |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the offer |
| `price` | no | $ref: https://schema.nfh.global/PriceSpecification/v2.1/attributes.yaml#/components/schemas/PriceSpecification | Price specification for this offer |
| `validity` | no | $ref: https://schema.nfh.global/TimePeriod/v2.0/attributes.yaml#/components/schemas/TimePeriod | Validity period of the offer |
| `tags` | no | string | Tags or labels associated with the offer |
