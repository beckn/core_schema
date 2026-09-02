# LocationInformationRequest — v2.0

A request for details about a specific geographic location, stop, or point of interest in the transport network.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/LocationInformationRequest/v2.0/attributes.yaml](https://schema.nfh.global/LocationInformationRequest/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/LocationInformationRequest/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/LocationInformationRequest/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/LocationInformationRequest/v2.0/context.jsonld](https://schema.nfh.global/LocationInformationRequest/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/LocationInformationRequest/v2.0/vocab.jsonld](https://schema.nfh.global/LocationInformationRequest/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `requestType` | no | string | Type of location information requested (e.g. STOP, ADDRESS, POI) |
| `locationName` | no | string | Name or keyword to search for |
| `coordinates` | no | $ref: https://schema.nfh.global/GeoJSONGeometry/v2.0/attributes.yaml#/components/schemas/GeoJSONGeometry | Geographic coordinates to query around |
| `radius` | no | number | Search radius in metres |
| `textSearch` | no | string | Free-text search query expressing what the traveler is looking for |
| `filters` | no | string | JSONPath filter criteria applied to the search results |
| `spatial` | no | $ref: https://schema.nfh.global/SpatialConstraint/v2.0/attributes.yaml#/components/schemas/SpatialConstraint | Geographic constraints on the search area |
| `provider` | no | string | Identifier of a specific provider to search within |
