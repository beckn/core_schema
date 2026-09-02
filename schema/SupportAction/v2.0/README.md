# SupportAction — v2.0

Beckn /beckn/support message payload. Sent by a BAP to a BPP to request
support contact information or to open a support ticket for an existing
order/contract.
(Context wrapper stripped; only the message-content portion is inlined.)

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/SupportAction/v2.0/attributes.yaml](https://schema.nfh.global/SupportAction/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/SupportAction/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/SupportAction/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/SupportAction/v2.0/context.jsonld](https://schema.nfh.global/SupportAction/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/SupportAction/v2.0/vocab.jsonld](https://schema.nfh.global/SupportAction/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `support` | yes | $ref: https://schema.nfh.global/Support/v2.0/attributes.yaml#/components/schemas/Support | - |
