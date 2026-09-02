# OrderItem — v2.0

Schema definition for OrderItem in the Beckn Protocol

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/OrderItem/v2.0/attributes.yaml](https://schema.nfh.global/OrderItem/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/OrderItem/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/OrderItem/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/OrderItem/v2.0/context.jsonld](https://schema.nfh.global/OrderItem/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/OrderItem/v2.0/vocab.jsonld](https://schema.nfh.global/OrderItem/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `beckn:lineId` | no | string | Unique line id within order |
| `beckn:orderedItem` | yes | $ref: https://schema.nfh.global/Item/v2.1/attributes.yaml#/components/schemas/Item | - |
| `beckn:acceptedOffer` | no | $ref: https://schema.nfh.global/Offer/v2.1/attributes.yaml#/components/schemas/Offer | Offer applied to this line (if different from order-level) |
| `beckn:quantity` | no | $ref: https://schema.nfh.global/Quantity/v2.0/attributes.yaml#/components/schemas/Quantity | - |
| `beckn:price` | no | $ref: https://schema.nfh.global/PriceSpecification/v2.1/attributes.yaml#/components/schemas/PriceSpecification | Line price composition (unit/tax/delivery/discount) |
| `beckn:orderItemAttributes` | no | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | Line-level Attribute Pack (options, substitutions, ESG, etc.) |
