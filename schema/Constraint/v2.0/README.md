# Constraint — v2.0

Schema definition for Constraint in the Beckn Protocol v2.0.1

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Constraint/v2.0/attributes.yaml](https://schema.nfh.global/Constraint/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Constraint/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Constraint/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Constraint/v2.0/context.jsonld](https://schema.nfh.global/Constraint/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Constraint/v2.0/vocab.jsonld](https://schema.nfh.global/Constraint/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `@context` | yes | string | CPD |
| `@type` | yes | string | - |
| `constraintType` | no | string | Type of constraint (extensible term) |
| `id` | yes | string | Identifier for the constraint |
| `operator` | no | string | Comparator/operator (<=, >=, =, etc.) |
| `unitCode` | no | string | Unit code (e.g., km, min) |
| `validity` | no | $ref: https://schema.nfh.global/TimePeriod/v2.1/attributes.yaml#/components/schemas/TimePeriod | - |
| `value` | no | number | Constraint value |
