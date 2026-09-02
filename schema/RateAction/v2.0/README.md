# RateAction — v2.0

Beckn /beckn/rate message payload. Sent by a BAP to a BPP to submit
one or more rating inputs for entities in a completed contract
(order, fulfillment, item, provider, agent, support).
(Context wrapper stripped; only the message-content portion is inlined.)

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/RateAction/v2.0/attributes.yaml](https://schema.nfh.global/RateAction/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/RateAction/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/RateAction/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/RateAction/v2.0/context.jsonld](https://schema.nfh.global/RateAction/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/RateAction/v2.0/vocab.jsonld](https://schema.nfh.global/RateAction/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `ratingInputs` | yes | array | - |
