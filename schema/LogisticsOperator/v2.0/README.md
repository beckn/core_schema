# LogisticsOperator — v2.0

Entity operating a logistics network or fleet, responsible for end-to-end delivery service.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/LogisticsOperator/v2.0/attributes.yaml](https://schema.nfh.global/LogisticsOperator/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/LogisticsOperator/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/LogisticsOperator/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/LogisticsOperator/v2.0/context.jsonld](https://schema.nfh.global/LogisticsOperator/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/LogisticsOperator/v2.0/vocab.jsonld](https://schema.nfh.global/LogisticsOperator/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `id` | yes | string | - |
| `name` | yes | string | - |
| `type` | no | string | - |
| `contact` | no | $ref: https://schema.nfh.global/Contact/v2.0/attributes.yaml#/components/schemas/Contact | - |
| `website` | no | string | - |
| `supportEmail` | no | string | - |
| `supportPhone` | no | string | - |
| `rating` | no | number | - |
| `activeCarriers` | no | integer | Number of carriers on the operator's network |
| `activeDrivers` | no | integer | - |
| `deliveriesPerDay` | no | integer | - |
| `serviceCoverage` | no | object | - |
| `certifications` | no | array | - |
