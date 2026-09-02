# FulfillmentStageAuthorization — v2.0

A credential/document/proof relevant to authorization at a fulfillment stage endpoint. This may be a token to be verified (QR/OTP/URL) or a document to be inspected manually.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/FulfillmentStageAuthorization/v2.0/attributes.yaml](https://schema.nfh.global/FulfillmentStageAuthorization/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/FulfillmentStageAuthorization/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/FulfillmentStageAuthorization/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/FulfillmentStageAuthorization/v2.0/context.jsonld](https://schema.nfh.global/FulfillmentStageAuthorization/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/FulfillmentStageAuthorization/v2.0/vocab.jsonld](https://schema.nfh.global/FulfillmentStageAuthorization/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `@context` | no | string | CPD |
| `@type` | no | string | - |
| `mediaFiles` | no | array | Media files required to enter or exit this fulfillment stage. The could be images of delivered packages, recorded video proof of installation, etc |
| `docs` | no | array | Documents required to enter or exit this fulfillment stage. The could be entry tickets, boarding passes, waybill, permits, certificates, credentials, etc |
| `purpose` | yes | string | The purpose of this authorization. e.g., proof of delivery, entry verification, identity check |
| `requirement` | yes | string | Describes what is required to fulfill this authorization. e.g., OTP, QR code, government ID |
| `status` | yes | string | The current status of this authorization. e.g., valid, expired, pending, used |
| `authToken` | no | string | A human readable string that needs to be provided to enter or exit this fulfillment stage. Like an OTP |
