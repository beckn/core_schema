# Settlement — v2.0

Container schemas fetched from beckn.yaml. This cannot be extended as it is a reserved schema in beckn protocol. Any additional properties added to this schema can only be made using its *Attributes property

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Settlement/v2.0/attributes.yaml](https://schema.nfh.global/Settlement/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Settlement/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Settlement/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Settlement/v2.0/context.jsonld](https://schema.nfh.global/Settlement/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Settlement/v2.0/vocab.jsonld](https://schema.nfh.global/Settlement/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `id` | no | string | - |
| `considerationId` | no | $ref: #/components/schemas/Consideration/properties/id | - |
| `status` | no | string | - |
| `settlementAttributes` | no | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | - |
