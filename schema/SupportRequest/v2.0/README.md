# SupportRequest — v2.0

Support request by a user. If no field is set, the user can expect a public support contact info

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/SupportRequest/v2.0/attributes.yaml](https://schema.nfh.global/SupportRequest/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/SupportRequest/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/SupportRequest/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/SupportRequest/v2.0/context.jsonld](https://schema.nfh.global/SupportRequest/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/SupportRequest/v2.0/vocab.jsonld](https://schema.nfh.global/SupportRequest/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `@context` | yes | string | - |
| `@type` | yes | string | - |
| `orderId` | no | string | The order against which support is required |
| `ticketIds` | no | array | IDs of support ticket if open |
| `callbackPhone` | no | string | Telephone number of the user for callback. |
