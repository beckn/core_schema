# RiderCategory — v2.0

A classification of passenger type (e.g., adult, child, senior, student) used to determine applicable fare entitlements.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/RiderCategory/v2.0/attributes.yaml](https://schema.nfh.global/RiderCategory/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/RiderCategory/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/RiderCategory/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/RiderCategory/v2.0/context.jsonld](https://schema.nfh.global/RiderCategory/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/RiderCategory/v2.0/vocab.jsonld](https://schema.nfh.global/RiderCategory/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `riderCategoryId` | no | string | Unique identifier for the rider category |
| `eligibilityRules` | no | string | Rules defining who qualifies for this rider category |
| `proofRequired` | no | string | Type of proof required to qualify (e.g. student ID, senior card) |
| `id` | no | string | Unique identifier for the category code |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable label for the category |
| `parentCategoryId` | no | string | Identifier of the parent category if hierarchical |
