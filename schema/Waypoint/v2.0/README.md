# Waypoint — v2.0

A Waypoint is an intermediate stop or checkpoint on a logistics route, such as a sorting hub, relay station, or customs checkpoint. Maps to beckn:Stop.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Waypoint/v2.0/attributes.yaml](https://schema.nfh.global/Waypoint/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Waypoint/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Waypoint/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Waypoint/v2.0/context.jsonld](https://schema.nfh.global/Waypoint/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Waypoint/v2.0/vocab.jsonld](https://schema.nfh.global/Waypoint/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `id` | yes | string | - |
| `name` | no | string | - |
| `place` | yes | $ref: https://schema.nfh.global/Place/v2.0/attributes.yaml#/components/schemas/Place | - |
| `type` | no | string | - |
| `sequenceNumber` | no | integer | Order of this waypoint in the route |
| `scheduledArrival` | no | string | - |
| `scheduledDeparture` | no | string | - |
| `actualArrival` | no | string | - |
| `actualDeparture` | no | string | - |
| `dwellTimeMinutes` | no | integer | Expected dwell time at this waypoint in minutes |
| `handoverRequired` | no | boolean | Whether shipment changes carrier/vehicle at this point |
| `status` | no | string | - |
