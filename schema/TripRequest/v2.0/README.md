# TripRequest — v2.0

A request submitted to a journey planning system specifying origin, destination, travel time, and preferences.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/TripRequest/v2.0/attributes.yaml](https://schema.nfh.global/TripRequest/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/TripRequest/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/TripRequest/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/TripRequest/v2.0/context.jsonld](https://schema.nfh.global/TripRequest/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/TripRequest/v2.0/vocab.jsonld](https://schema.nfh.global/TripRequest/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `origin` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | Origin location for the trip |
| `destination` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | Destination location for the trip |
| `departureTime` | no | string | Requested departure time |
| `arrivalTime` | no | string | Requested arrival time (alternative to departureTime) |
| `modes` | no | string | Permitted transport modes (e.g. BUS, RAIL, WALK) |
| `numItineraries` | no | number | Number of itinerary alternatives requested |
| `textSearch` | no | string | Free-text search query expressing what the traveler is looking for |
| `filters` | no | string | JSONPath filter criteria applied to the search results |
| `spatial` | no | $ref: https://schema.nfh.global/SpatialConstraint/v2.0/attributes.yaml#/components/schemas/SpatialConstraint | Geographic constraints on the search area |
| `provider` | no | string | Identifier of a specific provider to search within |
