# Trip — v2.0

A confirmed and booked journey from an origin to a destination, representing a completed mobility service order.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Trip/v2.0/attributes.yaml](https://schema.nfh.global/Trip/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Trip/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Trip/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Trip/v2.0/context.jsonld](https://schema.nfh.global/Trip/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Trip/v2.0/vocab.jsonld](https://schema.nfh.global/Trip/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `tripId` | no | string | Unique identifier for the trip |
| `origin` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | Pickup location |
| `destination` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | Dropoff location |
| `startTime` | no | string | Actual start time of the trip |
| `endTime` | no | string | Actual end time of the trip |
| `distance` | no | number | Total distance of the trip in kilometres |
| `driverRef` | no | $ref: https://schema.nfh.global/Driver/v2.0/attributes.yaml#/components/schemas/Driver | Reference to the driver for this trip |
| `vehicleRef` | no | $ref: https://schema.nfh.global/Vehicle/v2.0/attributes.yaml#/components/schemas/Vehicle | Reference to the vehicle for this trip |
| `id` | no | string | Unique identifier for the trip |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the trip |
