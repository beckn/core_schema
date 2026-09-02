# StopMonitoring — v2.0

A real-time data service providing predicted arrivals and departures of vehicles at a specific stop.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/StopMonitoring/v2.0/attributes.yaml](https://schema.nfh.global/StopMonitoring/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/StopMonitoring/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/StopMonitoring/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/StopMonitoring/v2.0/context.jsonld](https://schema.nfh.global/StopMonitoring/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/StopMonitoring/v2.0/vocab.jsonld](https://schema.nfh.global/StopMonitoring/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `stopRef` | no | $ref: https://schema.nfh.global/Stop/v2.0/attributes.yaml#/components/schemas/Stop | Reference to the stop being monitored |
| `monitoredCalls` | no | $ref: https://schema.nfh.global/MonitoredCall/v2.0/attributes.yaml#/components/schemas/MonitoredCall | List of real-time arrival/departure calls at this stop |
| `responseTimestamp` | no | string | Timestamp of this stop monitoring response |
| `id` | no | string | Unique identifier for the tracking record |
| `url` | no | string | URL endpoint for real-time tracking information |
| `status` | no | $ref: https://schema.nfh.global/State/v2.0/attributes.yaml#/components/schemas/State | Current tracking status |
| `validity` | no | $ref: https://schema.nfh.global/TimePeriod/v2.0/attributes.yaml#/components/schemas/TimePeriod | Validity period for this tracking record |
