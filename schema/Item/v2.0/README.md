# Item — v2.0

Schema definition for Item in the Beckn Protocol

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Item/v2.0/attributes.yaml](https://schema.nfh.global/Item/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Item/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Item/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Item/v2.0/context.jsonld](https://schema.nfh.global/Item/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Item/v2.0/vocab.jsonld](https://schema.nfh.global/Item/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `@context` | yes | string | JSON-LD context URI for the core Item schema |
| `@type` | yes | string | Type of the core item |
| `beckn:id` | yes | string | Unique identifier for the item |
| `beckn:descriptor` | yes | $ref: https://schema.nfh.global/Descriptor/v2.1/attributes.yaml#/components/schemas/Descriptor | - |
| `beckn:category` | no | $ref: https://schema.nfh.global/CategoryCode/v2.1/attributes.yaml#/components/schemas/CategoryCode | - |
| `beckn:availableAt` | no | array | Physical locations where the item is available |
| `beckn:availabilityWindow` | no | array | Time periods when the item is available |
| `beckn:rateable` | no | boolean | Whether the item can be rated by customers |
| `beckn:rating` | no | $ref: https://schema.nfh.global/Rating/v2.1/attributes.yaml#/components/schemas/Rating | - |
| `beckn:isActive` | no | boolean | Whether the item is active |
| `beckn:networkId` | no | array | Array of network identifiers for the BAP (Beckn App Provider) that offers this item |
| `beckn:provider` | yes | $ref: https://schema.nfh.global/Provider/v2.1/attributes.yaml#/components/schemas/Provider | - |
| `beckn:itemAttributes` | yes | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | - |
