# Fulfillment — v2.1

Schema definition for Fulfillment in the Beckn Protocol v2.0.1

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Fulfillment/v2.1/attributes.yaml](https://schema.nfh.global/Fulfillment/v2.1/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Fulfillment/v2.1/attributes.jsonschema.yaml](https://schema.nfh.global/Fulfillment/v2.1/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Fulfillment/v2.1/context.jsonld](https://schema.nfh.global/Fulfillment/v2.1/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Fulfillment/v2.1/vocab.jsonld](https://schema.nfh.global/Fulfillment/v2.1/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `@context` | yes | string | JSON-LD context URI |
| `@type` | yes | string | - |
| `agent` | no | $ref: https://schema.nfh.global/FulfillmentAgent/v2.0/attributes.yaml#/components/schemas/FulfillmentAgent | The entity that directly performs the fulfillment |
| `fulfillmentAttributes` | no | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | Extensible set of domain-specific attributes describing the fulfillment |
| `id` | no | string | Fulfillment identifier |
| `instructions` | no | array | - |
| `mode` | yes | $ref: https://schema.nfh.global/FulfillmentMode/v2.0/attributes.yaml#/components/schemas/FulfillmentMode | Extensible set of attributes describing the mode of fulfillment. Varies with Industry Use Case |
| `participants` | no | array | A list of participants who are entitled to receive the fulfillment of the order. By default, it is the consumer who placed the order |
| `state` | no | $ref: https://schema.nfh.global/State/v2.0/attributes.yaml#/components/schemas/State | The current state of fulfillment |
| `stages` | no | array | The various stages of the fulfillment |
| `trackingEnabled` | no | boolean | Whether tracking is enabled / possible for this fulfillment |
