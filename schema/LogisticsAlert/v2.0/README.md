# LogisticsAlert — v2.0

An Alert is a notification or warning related to a shipment, such as delays, exceptions, damage reports, or SLA breaches. Maps to beckn:Event.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/LogisticsAlert/v2.0/attributes.yaml](https://schema.nfh.global/LogisticsAlert/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/LogisticsAlert/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/LogisticsAlert/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/LogisticsAlert/v2.0/context.jsonld](https://schema.nfh.global/LogisticsAlert/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/LogisticsAlert/v2.0/vocab.jsonld](https://schema.nfh.global/LogisticsAlert/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `id` | yes | string | - |
| `shipmentId` | no | string | - |
| `type` | yes | string | - |
| `severity` | yes | string | - |
| `message` | yes | string | - |
| `cause` | no | string | Root cause of the alert |
| `impactedETA` | no | string | Revised ETA due to alert |
| `timestamp` | yes | string | - |
| `resolvedAt` | no | string | - |
| `status` | no | string | - |
| `notificationChannels` | no | array | - |
| `actionRequired` | no | boolean | Whether customer action is needed |
| `suggestedAction` | no | string | - |
