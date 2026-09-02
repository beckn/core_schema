# CatalogSubscribeAction — v2.0

Message payload for catalog/subscription.
At least one of `networkIds` or `schemaTypes` must be non-empty.
An empty `schemaTypes` array is treated as the wildcard sentinel `"*"`,
matching all schema types for the specified networks.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/CatalogSubscribeAction/v2.0/attributes.yaml](https://schema.nfh.global/CatalogSubscribeAction/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/CatalogSubscribeAction/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/CatalogSubscribeAction/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/CatalogSubscribeAction/v2.0/context.jsonld](https://schema.nfh.global/CatalogSubscribeAction/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/CatalogSubscribeAction/v2.0/vocab.jsonld](https://schema.nfh.global/CatalogSubscribeAction/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `subscription` | yes | object | - |
