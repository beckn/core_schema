# OnRateAction — v2.0

Beckn /beckn/on_rate message payload. Sent by a BPP to a BAP in
response to a /beckn/rate call, optionally returning rating forms
to collect structured feedback from the consumer.
(Context wrapper stripped; only the message-content portion is inlined.)

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/OnRateAction/v2.0/attributes.yaml](https://schema.nfh.global/OnRateAction/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/OnRateAction/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/OnRateAction/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/OnRateAction/v2.0/context.jsonld](https://schema.nfh.global/OnRateAction/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/OnRateAction/v2.0/vocab.jsonld](https://schema.nfh.global/OnRateAction/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `ratings` | yes | array | - |
