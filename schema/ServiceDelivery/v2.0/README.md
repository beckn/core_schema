# ServiceDelivery — v2.0

The top-level response container in SIRI encapsulating one or more real-time data delivery types.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/ServiceDelivery/v2.0/attributes.yaml](https://schema.nfh.global/ServiceDelivery/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/ServiceDelivery/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/ServiceDelivery/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/ServiceDelivery/v2.0/context.jsonld](https://schema.nfh.global/ServiceDelivery/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/ServiceDelivery/v2.0/vocab.jsonld](https://schema.nfh.global/ServiceDelivery/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `responseTimestamp` | no | string | Timestamp when this service delivery was generated |
| `producerRef` | no | string | Identifier of the system producing this delivery |
| `requestMessageRef` | no | string | Reference to the request that triggered this delivery |
| `stopMonitoring` | no | $ref: https://schema.nfh.global/StopMonitoring/v2.0/attributes.yaml#/components/schemas/StopMonitoring | Stop monitoring delivery payloads |
| `vehicleMonitoring` | no | $ref: https://schema.nfh.global/VehicleMonitoringDelivery/v2.0/attributes.yaml#/components/schemas/VehicleMonitoringDelivery | Vehicle monitoring delivery payloads |
| `estimatedTimetable` | no | $ref: https://schema.nfh.global/EstimatedTimetableDelivery/v2.0/attributes.yaml#/components/schemas/EstimatedTimetableDelivery | Estimated timetable delivery payloads |
| `id` | no | string | Unique identifier for the catalog |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the catalog |
| `tags` | no | string | Tags associated with the catalog |
