# TripSpecification — v2.0

A description of the desired journey used as input to search and price transport options.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/TripSpecification/v2.0/attributes.yaml](https://schema.nfh.global/TripSpecification/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/TripSpecification/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/TripSpecification/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/TripSpecification/v2.0/context.jsonld](https://schema.nfh.global/TripSpecification/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/TripSpecification/v2.0/vocab.jsonld](https://schema.nfh.global/TripSpecification/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `origin` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | Desired origin of the trip |
| `destination` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | Desired destination of the trip |
| `time` | no | string | Desired departure or arrival time |
| `numTravelers` | no | number | Number of travelers for whom to price options |
| `modes` | no | string | Preferred transport modes for the trip |
| `textSearch` | no | string | Free-text search query expressing what the traveler is looking for |
| `filters` | no | string | JSONPath filter criteria applied to the search results |
| `spatial` | no | $ref: https://schema.nfh.global/SpatialConstraint/v2.0/attributes.yaml#/components/schemas/SpatialConstraint | Geographic constraints on the search area |
| `provider` | no | string | Identifier of a specific provider to search within |
