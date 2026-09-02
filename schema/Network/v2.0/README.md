# Network — v2.0

A grouping of routes and lines operated under a common brand or authority, used for fare and operational management.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Network/v2.0/attributes.yaml](https://schema.nfh.global/Network/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Network/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Network/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Network/v2.0/context.jsonld](https://schema.nfh.global/Network/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Network/v2.0/vocab.jsonld](https://schema.nfh.global/Network/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `networkId` | no | string | Unique identifier for the network |
| `networkName` | no | string | Human-readable name of the network |
| `operatorRef` | no | $ref: https://schema.nfh.global/Operator/v2.0/attributes.yaml#/components/schemas/Operator | Operator(s) running services within this network |
| `lines` | no | $ref: https://schema.nfh.global/Line/v2.0/attributes.yaml#/components/schemas/Line | Lines that belong to this network |
| `id` | no | string | Unique identifier for the catalog |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the catalog |
| `tags` | no | string | Tags associated with the catalog |
