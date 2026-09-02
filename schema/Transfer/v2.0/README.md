# Transfer — v2.0

A defined connection rule between two routes or services at a common stop, specifying minimum transfer time or transfer type.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Transfer/v2.0/attributes.yaml](https://schema.nfh.global/Transfer/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Transfer/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Transfer/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Transfer/v2.0/context.jsonld](https://schema.nfh.global/Transfer/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Transfer/v2.0/vocab.jsonld](https://schema.nfh.global/Transfer/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `fromStopId` | no | $ref: https://schema.nfh.global/Stop/v2.0/attributes.yaml#/components/schemas/Stop | Stop passengers transfer from |
| `toStopId` | no | $ref: https://schema.nfh.global/Stop/v2.0/attributes.yaml#/components/schemas/Stop | Stop passengers transfer to |
| `fromRouteId` | no | $ref: https://schema.nfh.global/Route/v2.0/attributes.yaml#/components/schemas/Route | Route passengers transfer from |
| `toRouteId` | no | $ref: https://schema.nfh.global/Route/v2.0/attributes.yaml#/components/schemas/Route | Route passengers transfer to |
| `transferType` | no | string | Type of transfer (0=recommended, 1=timed, 2=min_time, 3=not_possible) |
| `minTransferTime` | no | number | Minimum transfer time in seconds |
| `id` | no | string | Unique identifier for the fulfillment stop |
| `location` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | Geographic location of the stop |
| `type` | no | string | Type of stop (start, end, intermediate) |
| `instructions` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Instructions for passengers at this stop |
| `time` | no | $ref: https://schema.nfh.global/TimePeriod/v2.0/attributes.yaml#/components/schemas/TimePeriod | Expected time window at this stop |
