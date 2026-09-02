# GeneralMessageDelivery — v2.0

A real-time delivery of textual messages or alerts related to service disruptions or passenger information.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/GeneralMessageDelivery/v2.0/attributes.yaml](https://schema.nfh.global/GeneralMessageDelivery/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/GeneralMessageDelivery/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/GeneralMessageDelivery/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/GeneralMessageDelivery/v2.0/context.jsonld](https://schema.nfh.global/GeneralMessageDelivery/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/GeneralMessageDelivery/v2.0/vocab.jsonld](https://schema.nfh.global/GeneralMessageDelivery/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `responseTimestamp` | no | string | Timestamp of this general message delivery |
| `infoMessages` | no | $ref: https://schema.nfh.global/Alert/v2.0/attributes.yaml#/components/schemas/Alert | List of informational messages in this delivery |
| `channel` | no | string | Distribution channel for this message (e.g. WEB, SMS, APP) |
| `id` | no | string | Unique identifier for the alert |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the alert |
| `validity` | no | $ref: https://schema.nfh.global/TimePeriod/v2.0/attributes.yaml#/components/schemas/TimePeriod | Time period during which the alert is active |
| `status` | no | $ref: https://schema.nfh.global/State/v2.0/attributes.yaml#/components/schemas/State | Current status of the alert |
