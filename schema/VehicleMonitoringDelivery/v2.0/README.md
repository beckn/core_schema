# VehicleMonitoringDelivery — v2.0

A real-time data delivery providing current positions and operational states of a set of vehicles.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/VehicleMonitoringDelivery/v2.0/attributes.yaml](https://schema.nfh.global/VehicleMonitoringDelivery/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/VehicleMonitoringDelivery/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/VehicleMonitoringDelivery/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/VehicleMonitoringDelivery/v2.0/context.jsonld](https://schema.nfh.global/VehicleMonitoringDelivery/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/VehicleMonitoringDelivery/v2.0/vocab.jsonld](https://schema.nfh.global/VehicleMonitoringDelivery/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `responseTimestamp` | no | string | Timestamp of this monitoring delivery |
| `vehicleActivities` | no | $ref: https://schema.nfh.global/MonitoredVehicleJourney/v2.0/attributes.yaml#/components/schemas/MonitoredVehicleJourney | List of vehicle activity records in this delivery |
| `validUntil` | no | string | Time until which this delivery data is valid |
| `id` | no | string | Unique identifier for the tracking record |
| `url` | no | string | URL endpoint for real-time tracking information |
| `status` | no | $ref: https://schema.nfh.global/State/v2.0/attributes.yaml#/components/schemas/State | Current tracking status |
| `validity` | no | $ref: https://schema.nfh.global/TimePeriod/v2.0/attributes.yaml#/components/schemas/TimePeriod | Validity period for this tracking record |
