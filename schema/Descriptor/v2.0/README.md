# Descriptor — v2.0

Schema definition for Descriptor in the Beckn Protocol

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Descriptor/v2.0/attributes.yaml](https://schema.nfh.global/Descriptor/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Descriptor/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Descriptor/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Descriptor/v2.0/context.jsonld](https://schema.nfh.global/Descriptor/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Descriptor/v2.0/vocab.jsonld](https://schema.nfh.global/Descriptor/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `@type` | yes | string | Type of the descriptor |
| `schema:name` | no | string | Name of the item |
| `beckn:shortDesc` | no | string | Short description of the item |
| `beckn:longDesc` | no | string | Detailed description of the item |
| `schema:image` | no | array | - |
