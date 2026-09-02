# MediaFile — v2.0

A image, audio, or video typically intended for display purposes

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/MediaFile/v2.0/attributes.yaml](https://schema.nfh.global/MediaFile/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/MediaFile/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/MediaFile/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/MediaFile/v2.0/context.jsonld](https://schema.nfh.global/MediaFile/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/MediaFile/v2.0/vocab.jsonld](https://schema.nfh.global/MediaFile/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `label` | no | string | The display name of the media file |
| `mimeType` | no | string | MIME type if 'data' is provided (application/pdf, image/png). |
| `uri` | no | string | URL to the document |
