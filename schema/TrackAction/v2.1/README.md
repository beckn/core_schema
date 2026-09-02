# TrackAction — v2.1

Details required to initiate real-time tracking (if relevant) for an ongoing transaction

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/TrackAction/v2.1/attributes.yaml](https://schema.nfh.global/TrackAction/v2.1/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/TrackAction/v2.1/attributes.jsonschema.yaml](https://schema.nfh.global/TrackAction/v2.1/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/TrackAction/v2.1/context.jsonld](https://schema.nfh.global/TrackAction/v2.1/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/TrackAction/v2.1/vocab.jsonld](https://schema.nfh.global/TrackAction/v2.1/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `tracking` | yes | $ref: https://schema.nfh.global/Tracking/v2.1/attributes.yaml#/components/schemas/Tracking | - |
