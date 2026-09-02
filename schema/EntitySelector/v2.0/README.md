# EntitySelector — v2.0

A selector that identifies which transport entities (routes, trips, stops, or agencies) are affected by a given alert.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/EntitySelector/v2.0/attributes.yaml](https://schema.nfh.global/EntitySelector/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/EntitySelector/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/EntitySelector/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/EntitySelector/v2.0/context.jsonld](https://schema.nfh.global/EntitySelector/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/EntitySelector/v2.0/vocab.jsonld](https://schema.nfh.global/EntitySelector/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `agencyId` | no | string | Identifier of the affected agency |
| `routeId` | no | string | Identifier of the affected route |
| `routeType` | no | string | Type of the affected route (e.g. BUS, RAIL) |
| `tripDescriptor` | no | $ref: https://schema.nfh.global/TripDescriptor/v2.0/attributes.yaml#/components/schemas/TripDescriptor | Descriptor identifying the affected trip |
| `stopId` | no | string | Identifier of the affected stop |
| `id` | no | string | Unique identifier for the alert |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the alert |
| `validity` | no | $ref: https://schema.nfh.global/TimePeriod/v2.0/attributes.yaml#/components/schemas/TimePeriod | Time period during which the alert is active |
| `status` | no | $ref: https://schema.nfh.global/State/v2.0/attributes.yaml#/components/schemas/State | Current status of the alert |
