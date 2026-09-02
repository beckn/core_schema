# OnStatusAction — v2.0

Beckn /beckn/on_status message payload. Sent by a BPP to a BAP in
response to a /beckn/status call (or as an unsolicited status push),
returning the current state of the contract.
(Context wrapper stripped; only the message-content portion is inlined.)

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/OnStatusAction/v2.0/attributes.yaml](https://schema.nfh.global/OnStatusAction/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/OnStatusAction/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/OnStatusAction/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/OnStatusAction/v2.0/context.jsonld](https://schema.nfh.global/OnStatusAction/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/OnStatusAction/v2.0/vocab.jsonld](https://schema.nfh.global/OnStatusAction/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `contract` | yes | $ref: https://schema.nfh.global/Contract/v2.0/attributes.yaml#/components/schemas/Contract | - |
