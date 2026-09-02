# Pagination — v2.0

Pagination metadata returned with list responses

This schema is part of the Long Term Support of Beckn Protocol V2.0 API specification and MUST NOT be extended. Any domain-specific extension must use the property of this schema which is of type Attribute.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Pagination/v2.0/attributes.yaml](https://schema.nfh.global/Pagination/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Pagination/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Pagination/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Pagination/v2.0/context.jsonld](https://schema.nfh.global/Pagination/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Pagination/v2.0/vocab.jsonld](https://schema.nfh.global/Pagination/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `count` | no | integer | Number of items in this page |
| `limit` | no | integer | Page size used in this response |
| `offset` | no | integer | Zero-based offset used in this response |
