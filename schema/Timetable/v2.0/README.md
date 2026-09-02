# Timetable — v2.0

A structured schedule listing planned arrival and departure times for vehicles at each stop along a route.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Timetable/v2.0/attributes.yaml](https://schema.nfh.global/Timetable/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Timetable/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Timetable/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Timetable/v2.0/context.jsonld](https://schema.nfh.global/Timetable/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Timetable/v2.0/vocab.jsonld](https://schema.nfh.global/Timetable/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `routeRef` | no | $ref: https://schema.nfh.global/Route/v2.0/attributes.yaml#/components/schemas/Route | Reference to the route this timetable covers |
| `trips` | no | $ref: https://schema.nfh.global/VehicleJourney/v2.0/attributes.yaml#/components/schemas/VehicleJourney | Vehicle journeys (trips) in this timetable |
| `validFrom` | no | string | Date from which this timetable is valid |
| `validUntil` | no | string | Date until which this timetable is valid |
| `id` | no | string | Unique identifier for the catalog |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the catalog |
| `tags` | no | string | Tags associated with the catalog |
