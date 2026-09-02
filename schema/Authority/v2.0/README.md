# Authority — v2.0

A governmental or administrative body responsible for planning, regulating, and overseeing transport services within a jurisdiction.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Authority/v2.0/attributes.yaml](https://schema.nfh.global/Authority/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Authority/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Authority/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Authority/v2.0/context.jsonld](https://schema.nfh.global/Authority/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Authority/v2.0/vocab.jsonld](https://schema.nfh.global/Authority/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `authorityId` | no | string | Unique identifier for the authority |
| `jurisdiction` | no | string | Geographic or administrative jurisdiction of this authority |
| `regulatoryScope` | no | string | Scope of regulatory powers (e.g. national, regional, local) |
| `id` | no | string | Unique identifier for the provider |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the provider |
| `categories` | no | $ref: https://schema.nfh.global/CategoryCode/v2.1/attributes.yaml#/components/schemas/CategoryCode | Service categories offered by the provider |
| `locations` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | Locations where the provider offers services |
| `items` | no | $ref: https://schema.nfh.global/Item/v2.1/attributes.yaml#/components/schemas/Item | Items available for discovery from this provider |
| `ratingsTotal` | no | number | Total number of ratings received |
| `rating` | no | $ref: https://schema.nfh.global/Rating/v2.0/attributes.yaml#/components/schemas/Rating | Aggregate rating of the provider |
