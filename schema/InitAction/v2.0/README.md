# InitAction — v2.0

Beckn /beckn/init message payload. Sent by a BAP to a BPP to initialise
a contract with consumer details (billing address, fulfillment preferences, etc.).
(Context wrapper stripped; only the message-content portion is inlined.)

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/InitAction/v2.0/attributes.yaml](https://schema.nfh.global/InitAction/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/InitAction/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/InitAction/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/InitAction/v2.0/context.jsonld](https://schema.nfh.global/InitAction/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/InitAction/v2.0/vocab.jsonld](https://schema.nfh.global/InitAction/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `contract` | yes | $ref: https://schema.nfh.global/Contract/v2.0/attributes.yaml#/components/schemas/Contract | - |
