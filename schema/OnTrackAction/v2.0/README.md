# OnTrackAction — v2.0

Beckn /beckn/on_track message payload. Sent by a BPP to a BAP in
response to a /beckn/track call, returning a Tracking handle with
the URL and/or WebSocket endpoint for real-time fulfillment tracking.
(Context wrapper stripped; only the message-content portion is inlined.)

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/OnTrackAction/v2.0/attributes.yaml](https://schema.nfh.global/OnTrackAction/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/OnTrackAction/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/OnTrackAction/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/OnTrackAction/v2.0/context.jsonld](https://schema.nfh.global/OnTrackAction/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/OnTrackAction/v2.0/vocab.jsonld](https://schema.nfh.global/OnTrackAction/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `tracking` | yes | $ref: https://schema.nfh.global/Tracking/v2.1/attributes.yaml#/components/schemas/Tracking | - |
