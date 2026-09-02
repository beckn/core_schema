# Order — v2.0

Schema definition for Order in the Beckn Protocol

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Order/v2.0/attributes.yaml](https://schema.nfh.global/Order/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Order/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Order/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Order/v2.0/context.jsonld](https://schema.nfh.global/Order/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Order/v2.0/vocab.jsonld](https://schema.nfh.global/Order/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `@context` | yes | string | - |
| `@type` | yes | string | - |
| `beckn:id` | no | string | - |
| `beckn:orderStatus` | yes | string | Order status/state |
| `beckn:orderNumber` | no | string | Human-visible order number |
| `beckn:seller` | yes | $ref: https://schema.nfh.global/Provider/v2.1/attributes.yaml#/components/schemas/Provider | - |
| `beckn:buyer` | yes | $ref: https://schema.nfh.global/Buyer/v2.0/attributes.yaml#/components/schemas/Buyer | - |
| `beckn:orderItems` | yes | array | - |
| `beckn:acceptedOffers` | no | array | Offers accepted at order-level (optional if captured per line) |
| `beckn:orderValue` | no | $ref: https://schema.nfh.global/PriceSpecification/v2.1/attributes.yaml#/components/schemas/PriceSpecification | Order totals snapshot (derivable from lines; optional) |
| `beckn:invoice` | no | $ref: https://schema.nfh.global/Invoice/v2.1/attributes.yaml#/components/schemas/Invoice | Invoice reference/summary |
| `beckn:payment` | no | $ref: https://schema.nfh.global/Payment/v2.0/attributes.yaml#/components/schemas/Payment | Method/status; rail-specific payloads go to packs |
| `beckn:fulfillment` | no | $ref: https://schema.nfh.global/Fulfillment/v2.1/attributes.yaml#/components/schemas/Fulfillment | Parcel delivery or reservation summary |
| `beckn:orderAttributes` | no | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | Order-level Attribute Pack (vertical/regulatory specifics) |
