# DiscoverAction — v2.0

Beckn /beckn/discover message payload as published at schema.nfh.global.
Requires all discover qualifiers to be nested inside an `intent`
container object.
(Context wrapper stripped; only the message-content portion is inlined.)

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/DiscoverAction/v2.0/attributes.yaml](https://schema.nfh.global/DiscoverAction/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/DiscoverAction/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/DiscoverAction/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/DiscoverAction/v2.0/context.jsonld](https://schema.nfh.global/DiscoverAction/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/DiscoverAction/v2.0/vocab.jsonld](https://schema.nfh.global/DiscoverAction/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `intent` | yes | $ref: https://schema.nfh.global/Intent/v2.0/attributes.yaml#/components/schemas/Intent | - |
| `text_search` | no | string | Legacy flat free-text discover query |
| `textSearch` | no | string | Flat free-text discover query |
