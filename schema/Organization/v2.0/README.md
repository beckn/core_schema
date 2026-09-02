# Organization — v2.0

An organization such as a company, non-profit, or governmental institution. Modeled after schema.org/Organization.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Organization/v2.0/attributes.yaml](https://schema.nfh.global/Organization/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Organization/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Organization/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Organization/v2.0/context.jsonld](https://schema.nfh.global/Organization/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Organization/v2.0/vocab.jsonld](https://schema.nfh.global/Organization/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `@context` | yes | string | - |
| `@type` | yes | string | - |
| `id` | yes | string | Unique identifier for the organization |
| `name` | no | string | Name of the organization |
| `email` | no | string | Email address |
| `telephone` | no | string | Telephone number |
| `address` | no | any | Physical address |
| `credentials` | no | array | Credentials held by the organization |
| `skills` | no | array | Skills or capabilities of the organization |
| `organizationAttributes` | no | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | Extensible attribute pack for jurisdictional or domain-specific organization properties |
