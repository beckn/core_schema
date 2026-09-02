# CancelAction — v2.0

Beckn /beckn/cancel message payload. Sent by a BAP to a BPP to request
cancellation of an active contract. Set context.try to true to first
retrieve cancellation terms and fees before committing.
(Context wrapper stripped; only the message-content portion is inlined.)

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/CancelAction/v2.0/attributes.yaml](https://schema.nfh.global/CancelAction/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/CancelAction/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/CancelAction/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/CancelAction/v2.0/context.jsonld](https://schema.nfh.global/CancelAction/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/CancelAction/v2.0/vocab.jsonld](https://schema.nfh.global/CancelAction/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `contract` | yes | allOf | - |
