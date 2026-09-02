# BikeAllowed — v2.0

An indicator specifying whether bicycles are permitted on board a particular route or vehicle journey.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/BikeAllowed/v2.0/attributes.yaml](https://schema.nfh.global/BikeAllowed/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/BikeAllowed/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/BikeAllowed/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/BikeAllowed/v2.0/context.jsonld](https://schema.nfh.global/BikeAllowed/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/BikeAllowed/v2.0/vocab.jsonld](https://schema.nfh.global/BikeAllowed/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `bikeAllowedValue` | no | string | Indicates whether bikes are allowed: yes, no, or unknown |
| `id` | no | string | Unique identifier for the feature |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable label of the feature |
| `value` | no | string | Value of the feature (e.g. yes, no, unknown) |
