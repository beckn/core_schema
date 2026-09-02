# Feed — v2.0

A data publication providing transit or mobility information in a standardised format for consumption by applications or planners.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Feed/v2.0/attributes.yaml](https://schema.nfh.global/Feed/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Feed/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Feed/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Feed/v2.0/context.jsonld](https://schema.nfh.global/Feed/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Feed/v2.0/vocab.jsonld](https://schema.nfh.global/Feed/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `feedType` | no | string | Format of the feed (e.g. GTFS, GTFS_RT, GBFS, NeTEx) |
| `feedId` | no | string | Unique identifier for the feed |
| `feedPublisher` | no | string | Name of the organisation publishing this feed |
| `feedLanguage` | no | string | BCP-47 language code for the feed content |
| `feedStartDate` | no | string | Date from which the feed data is valid |
| `feedEndDate` | no | string | Date until which the feed data is valid |
| `id` | no | string | Unique identifier for the catalog |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the catalog |
| `tags` | no | string | Tags associated with the catalog |
