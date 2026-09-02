# LocationGroupStop — v2.0

An association between a stop and a location group, used in flexible transit service planning.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/LocationGroupStop/v2.0/attributes.yaml](https://schema.nfh.global/LocationGroupStop/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/LocationGroupStop/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/LocationGroupStop/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/LocationGroupStop/v2.0/context.jsonld](https://schema.nfh.global/LocationGroupStop/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/LocationGroupStop/v2.0/vocab.jsonld](https://schema.nfh.global/LocationGroupStop/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `locationGroupId` | no | string | Identifier of the parent location group |
| `stopId` | no | $ref: https://schema.nfh.global/Stop/v2.0/attributes.yaml#/components/schemas/Stop | Reference to the stop in this association |
| `id` | no | string | Unique identifier for the location |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the location |
| `gps` | no | string | GPS coordinates as a latitude,longitude string |
| `address` | no | $ref: https://schema.nfh.global/Address/v2.0/attributes.yaml#/components/schemas/Address | Physical address of the location |
| `city` | no | string | City name |
| `country` | no | string | ISO 3166-1 alpha-2 country code |
| `geojson` | no | $ref: https://schema.nfh.global/GeoJSONGeometry/v2.0/attributes.yaml#/components/schemas/GeoJSONGeometry | GeoJSON geometry object representing this location |
