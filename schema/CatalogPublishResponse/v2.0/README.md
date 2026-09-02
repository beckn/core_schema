# CatalogPublishResponse — v2.0

Beckn /beckn/on_catalog_publish message payload. Sent by a CDS back to a BPP
after processing a catalog publish request. Contains per-catalog processing results
indicating success, failure, or partial indexing.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/CatalogPublishResponse/v2.0/attributes.yaml](https://schema.nfh.global/CatalogPublishResponse/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/CatalogPublishResponse/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/CatalogPublishResponse/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/CatalogPublishResponse/v2.0/context.jsonld](https://schema.nfh.global/CatalogPublishResponse/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/CatalogPublishResponse/v2.0/vocab.jsonld](https://schema.nfh.global/CatalogPublishResponse/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `context` | yes | allOf | - |
| `message` | yes | object | - |
