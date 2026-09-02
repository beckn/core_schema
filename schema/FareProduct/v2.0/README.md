# FareProduct — v2.0

A purchasable entitlement to travel defining conditions of use, validity, and applicable passenger categories.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/FareProduct/v2.0/attributes.yaml](https://schema.nfh.global/FareProduct/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/FareProduct/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/FareProduct/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/FareProduct/v2.0/context.jsonld](https://schema.nfh.global/FareProduct/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/FareProduct/v2.0/vocab.jsonld](https://schema.nfh.global/FareProduct/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `fareProductId` | no | string | Unique identifier for the fare product |
| `riderCategoryId` | no | $ref: https://schema.nfh.global/RiderCategory/v2.0/attributes.yaml#/components/schemas/RiderCategory | Passenger category eligible for this fare product |
| `durationType` | no | string | Duration basis (e.g. SINGLE_TRIP, DAILY, MONTHLY) |
| `mediaDuration` | no | string | Duration for which the fare product is valid |
| `fixedStartDate` | no | string | Fixed start date for calendar-based fare products |
| `id` | no | string | Unique identifier for the offer |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the offer |
| `price` | no | $ref: https://schema.nfh.global/PriceSpecification/v2.1/attributes.yaml#/components/schemas/PriceSpecification | Price specification for this offer |
| `validity` | no | $ref: https://schema.nfh.global/TimePeriod/v2.0/attributes.yaml#/components/schemas/TimePeriod | Validity period of the offer |
| `tags` | no | string | Tags or labels associated with the offer |
