# Leg — v2.0

A single uninterrupted segment of a journey made using one transport mode or service between two consecutive locations.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Leg/v2.0/attributes.yaml](https://schema.nfh.global/Leg/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Leg/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Leg/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Leg/v2.0/context.jsonld](https://schema.nfh.global/Leg/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Leg/v2.0/vocab.jsonld](https://schema.nfh.global/Leg/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `mode` | no | $ref: https://schema.nfh.global/FulfillmentMode/v2.0/attributes.yaml#/components/schemas/FulfillmentMode | Mode of fulfillment |
| `origin` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | Start location of the leg |
| `destination` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | End location of the leg |
| `startTime` | no | string | Scheduled or actual start time of the leg |
| `endTime` | no | string | Scheduled or actual end time of the leg |
| `distance` | no | number | Distance of this leg in metres |
| `headsign` | no | string | Destination sign text displayed on the vehicle |
| `routeRef` | no | $ref: https://schema.nfh.global/Route/v2.0/attributes.yaml#/components/schemas/Route | Reference to the route served on this leg |
| `id` | no | string | Unique identifier for the fulfillment |
| `type` | no | string | Type of fulfillment (extensible term) |
| `agent` | no | $ref: https://schema.nfh.global/FulfillmentAgent/v2.0/attributes.yaml#/components/schemas/FulfillmentAgent | The entity responsible for performing the fulfillment |
| `participants` | no | $ref: https://schema.nfh.global/Participant/v2.0/attributes.yaml#/components/schemas/Participant | Participants entitled to receive this fulfillment |
| `stages` | no | $ref: https://schema.nfh.global/FulfillmentStage/v2.0/attributes.yaml#/components/schemas/FulfillmentStage | Stages in the fulfillment lifecycle |
| `instructions` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Instructions for fulfillment |
