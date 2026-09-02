# OccupancyStatus — v2.0

An indicator of the current passenger load level of a vehicle, such as empty, many seats available, or full.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/OccupancyStatus/v2.0/attributes.yaml](https://schema.nfh.global/OccupancyStatus/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/OccupancyStatus/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/OccupancyStatus/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/OccupancyStatus/v2.0/context.jsonld](https://schema.nfh.global/OccupancyStatus/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/OccupancyStatus/v2.0/vocab.jsonld](https://schema.nfh.global/OccupancyStatus/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `occupancyLevel` | no | string | Occupancy level (EMPTY, MANY_SEATS_AVAILABLE, FEW_SEATS_AVAILABLE, STANDING_ROOM_ONLY, FULL, NOT_ACCEPTING_PASSENGERS) |
| `availableSeats` | no | number | Estimated number of seats currently available |
| `totalSeats` | no | number | Total seating capacity of the vehicle |
| `id` | no | string | Unique identifier for the state |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the state |
| `updatedAt` | no | string | Timestamp when the state was last updated |
