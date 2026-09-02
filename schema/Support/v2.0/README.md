# Support — v2.0

Describes a support session info

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Support/v2.0/attributes.yaml](https://schema.nfh.global/Support/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Support/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Support/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Support/v2.0/context.jsonld](https://schema.nfh.global/Support/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Support/v2.0/vocab.jsonld](https://schema.nfh.global/Support/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `orderId` | no | string | The order against which support is required |
| `descriptor` | no | $ref: https://schema.nfh.global/Descriptor/v2.1/attributes.yaml#/components/schemas/Descriptor | A description of the nature of support needed |
| `channels` | no | array | Available support channels described in individual linked data JSON objects |
