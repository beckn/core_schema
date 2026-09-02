# Tracking — v2.1

Information regarding live tracking of the fufillment of a contract

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Tracking/v2.1/attributes.yaml](https://schema.nfh.global/Tracking/v2.1/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Tracking/v2.1/attributes.jsonschema.yaml](https://schema.nfh.global/Tracking/v2.1/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Tracking/v2.1/context.jsonld](https://schema.nfh.global/Tracking/v2.1/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Tracking/v2.1/vocab.jsonld](https://schema.nfh.global/Tracking/v2.1/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `contract` | no | allOf | Attributes of the contract for which the tracking is performed |
| `status` | yes | string | - |
| `url` | yes | string | Link/handle to off-network tracking UI or endpoint. |
| `trackingAttributes` | no | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | Information specific to the use case for which the tracking is performed |
