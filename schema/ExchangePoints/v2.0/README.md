# ExchangePoints — v2.0

Locations in a transport network where fixed-route and flexible services connect, enabling passenger interchange.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/ExchangePoints/v2.0/attributes.yaml](https://schema.nfh.global/ExchangePoints/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/ExchangePoints/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/ExchangePoints/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/ExchangePoints/v2.0/context.jsonld](https://schema.nfh.global/ExchangePoints/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/ExchangePoints/v2.0/vocab.jsonld](https://schema.nfh.global/ExchangePoints/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `exchangePointType` | no | string | Type of exchange point (e.g. FIXED_TO_FLEX, FLEX_TO_FLEX) |
| `connectingServices` | no | $ref: https://schema.nfh.global/VehicleJourney/v2.0/attributes.yaml#/components/schemas/VehicleJourney | Services that connect at this exchange point |
| `id` | no | string | Unique identifier for the fulfillment stop |
| `location` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | Geographic location of the stop |
| `type` | no | string | Type of stop (start, end, intermediate) |
| `instructions` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Instructions for passengers at this stop |
| `time` | no | $ref: https://schema.nfh.global/TimePeriod/v2.0/attributes.yaml#/components/schemas/TimePeriod | Expected time window at this stop |
