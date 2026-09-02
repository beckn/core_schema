# TrackingUpdate — v2.0

A TrackingUpdate is a real-time or periodic update on the status and location of a shipment during transit. Maps to beckn:Event.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/TrackingUpdate/v2.0/attributes.yaml](https://schema.nfh.global/TrackingUpdate/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/TrackingUpdate/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/TrackingUpdate/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/TrackingUpdate/v2.0/context.jsonld](https://schema.nfh.global/TrackingUpdate/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/TrackingUpdate/v2.0/vocab.jsonld](https://schema.nfh.global/TrackingUpdate/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `id` | yes | string | - |
| `shipmentId` | yes | string | - |
| `status` | yes | string | - |
| `location` | no | object | - |
| `timestamp` | yes | string | - |
| `message` | no | string | Human-readable status message |
| `hub` | no | $ref: https://schema.nfh.global/Hub/v2.0/attributes.yaml#/components/schemas/Hub | - |
| `driver` | no | $ref: https://schema.nfh.global/Driver/v2.0/attributes.yaml#/components/schemas/Driver | - |
| `vehicle` | no | $ref: https://schema.nfh.global/Vehicle/v2.0/attributes.yaml#/components/schemas/Vehicle | - |
| `exceptionDetails` | no | object | Details if this update is an exception |
| `nextAction` | no | string | Next planned action |
| `notificationSent` | no | boolean | Whether customer was notified of this update |
