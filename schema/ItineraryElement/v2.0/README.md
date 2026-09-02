# ItineraryElement — v2.0

A component of an aviation itinerary such as a flight segment, ground transport leg, or ancillary service.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/ItineraryElement/v2.0/attributes.yaml](https://schema.nfh.global/ItineraryElement/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/ItineraryElement/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/ItineraryElement/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/ItineraryElement/v2.0/context.jsonld](https://schema.nfh.global/ItineraryElement/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/ItineraryElement/v2.0/vocab.jsonld](https://schema.nfh.global/ItineraryElement/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `elementType` | no | string | Type of itinerary element (FLIGHT, GROUND_TRANSPORT, ANCILLARY) |
| `segmentRef` | no | $ref: https://schema.nfh.global/FlightSegment/v2.0/attributes.yaml#/components/schemas/FlightSegment | Reference to a flight segment if this is a flight element |
| `legRef` | no | $ref: https://schema.nfh.global/Leg/v2.0/attributes.yaml#/components/schemas/Leg | Reference to a transport leg if this is a surface element |
| `sequence` | no | number | Sequential order of this element within the itinerary |
| `id` | no | string | Unique identifier for the contract item |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the item |
| `price` | no | $ref: https://schema.nfh.global/PriceSpecification/v2.1/attributes.yaml#/components/schemas/PriceSpecification | Price for this contract item |
| `quantity` | no | $ref: https://schema.nfh.global/Quantity/v2.0/attributes.yaml#/components/schemas/Quantity | Quantity of this contract item |
