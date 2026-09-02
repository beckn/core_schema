# PlanningResult — v2.0

The output of a MaaS platform planning request, listing available transport options for a requested trip.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/PlanningResult/v2.0/attributes.yaml](https://schema.nfh.global/PlanningResult/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/PlanningResult/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/PlanningResult/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/PlanningResult/v2.0/context.jsonld](https://schema.nfh.global/PlanningResult/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/PlanningResult/v2.0/vocab.jsonld](https://schema.nfh.global/PlanningResult/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `origin` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | Origin location for the planning query |
| `destination` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | Destination location for the planning query |
| `options` | no | $ref: https://schema.nfh.global/RideOption/v2.0/attributes.yaml#/components/schemas/RideOption | Available transport options returned |
| `itineraries` | no | $ref: https://schema.nfh.global/Itinerary/v2.0/attributes.yaml#/components/schemas/Itinerary | Multi-modal itinerary options if applicable |
| `id` | no | string | Unique identifier for the catalog |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the catalog |
| `tags` | no | string | Tags associated with the catalog |
