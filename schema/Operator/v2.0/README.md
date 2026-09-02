# Operator — v2.0

An organization that provides and operates public transport or shared mobility services under a defined service agreement.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Operator/v2.0/attributes.yaml](https://schema.nfh.global/Operator/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Operator/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Operator/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Operator/v2.0/context.jsonld](https://schema.nfh.global/Operator/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Operator/v2.0/vocab.jsonld](https://schema.nfh.global/Operator/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `operatorId` | no | string | Unique identifier for the operator |
| `operatingRegions` | no | string | Geographic regions where the operator provides services |
| `licenseNumber` | no | string | Regulatory license or accreditation number |
| `contactInfo` | no | string | Public contact information for the operator |
| `id` | no | string | Unique identifier for the provider |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the provider |
| `categories` | no | $ref: https://schema.nfh.global/CategoryCode/v2.1/attributes.yaml#/components/schemas/CategoryCode | Service categories offered by the provider |
| `locations` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | Locations where the provider offers services |
| `items` | no | $ref: https://schema.nfh.global/Item/v2.1/attributes.yaml#/components/schemas/Item | Items available for discovery from this provider |
| `ratingsTotal` | no | number | Total number of ratings received |
| `rating` | no | $ref: https://schema.nfh.global/Rating/v2.0/attributes.yaml#/components/schemas/Rating | Aggregate rating of the provider |
