# FulfillmentStage — v2.0

Schema definition for FulfillmentStage in the Beckn Protocol v2.0.1

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/FulfillmentStage/v2.0/attributes.yaml](https://schema.nfh.global/FulfillmentStage/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/FulfillmentStage/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/FulfillmentStage/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/FulfillmentStage/v2.0/context.jsonld](https://schema.nfh.global/FulfillmentStage/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/FulfillmentStage/v2.0/vocab.jsonld](https://schema.nfh.global/FulfillmentStage/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `@context` | yes | string | CPD |
| `@type` | yes | string | - |
| `id` | yes | string | A unique identifier for this stage of fulfillment |
| `instructions` | no | array | A set of instructions to follow during this stage of fulfillment |
| `preferences` | no | array | A extensible set of attributes that describe the fulfillment preferences |
| `start` | no | $ref: https://schema.nfh.global/FulfillmentStageEndpoint/v2.0/attributes.yaml#/components/schemas/FulfillmentStageEndpoint | An extensible set of attributes that describe the criteria required to start this stage of fulfillment |
| `end` | no | $ref: https://schema.nfh.global/FulfillmentStageEndpoint/v2.0/attributes.yaml#/components/schemas/FulfillmentStageEndpoint | An extensible set of attributes that describe the criteria required to end this stage of fulfillment |
| `fulfillmentStageAttributes` | no | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | An extensible set of attributes that describe this stage of fulfillment |
