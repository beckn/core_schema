# RequestAction — v2.0

DEPRECATED. This schema is structurally invalid and does not validate any payloads — the oneOf keyword was incorrectly nested inside properties, which is not valid JSON Schema.
Use https://schema.nfh.global/BecknAction/v2.0 instead. BecknAction is the unified envelope for all Beckn actions (both request and callback directions). The request/callback distinction is encoded in context.action (e.g. beckn/discover for requests, beckn/on_discover for callbacks).
This schema will be removed in a future major version.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/RequestAction/v2.0/attributes.yaml](https://schema.nfh.global/RequestAction/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/RequestAction/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/RequestAction/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/RequestAction/v2.0/context.jsonld](https://schema.nfh.global/RequestAction/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/RequestAction/v2.0/vocab.jsonld](https://schema.nfh.global/RequestAction/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| _none_ | - | - | - |
