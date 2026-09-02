# TripUpdate — v2.0

A multi-dimensional update to an in-progress or upcoming mobility trip, covering contract modifications (added/removed services, route changes), status notifications (driver arriving, trip started), and real-time tracking endpoint information.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/TripUpdate/v2.0/attributes.yaml](https://schema.nfh.global/TripUpdate/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/TripUpdate/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/TripUpdate/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/TripUpdate/v2.0/context.jsonld](https://schema.nfh.global/TripUpdate/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/TripUpdate/v2.0/vocab.jsonld](https://schema.nfh.global/TripUpdate/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `contractChanges` | no | $ref: https://schema.nfh.global/ContractItem/v2.0/attributes.yaml#/components/schemas/ContractItem | Items added or modified in the trip contract (new stop, route change, add-on service) |
| `cancelledItems` | no | $ref: https://schema.nfh.global/ContractItem/v2.0/attributes.yaml#/components/schemas/ContractItem | Items removed from the original trip contract |
| `stateUpdate` | no | $ref: https://schema.nfh.global/State/v2.0/attributes.yaml#/components/schemas/State | Status notification for the traveler (e.g. driver arriving, trip started, trip ended, driver changed) |
| `trackingEndpoint` | no | $ref: https://schema.nfh.global/Tracking/v2.1/attributes.yaml#/components/schemas/Tracking | Real-time tracking endpoint including URL, protocol, and data schema reference |
| `driverRef` | no | $ref: https://schema.nfh.global/Driver/v2.0/attributes.yaml#/components/schemas/Driver | Reference to the current driver if changed from the originally assigned driver |
| `updatedAt` | no | string | Timestamp when this trip update was issued |
| `id` | no | string | Unique identifier for the trip update |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the trip update |
