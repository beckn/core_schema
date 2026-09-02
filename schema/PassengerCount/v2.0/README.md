# PassengerCount — v2.0

The measured number of passengers currently aboard a vehicle, used for real-time capacity and load management.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/PassengerCount/v2.0/attributes.yaml](https://schema.nfh.global/PassengerCount/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/PassengerCount/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/PassengerCount/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/PassengerCount/v2.0/context.jsonld](https://schema.nfh.global/PassengerCount/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/PassengerCount/v2.0/vocab.jsonld](https://schema.nfh.global/PassengerCount/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `boardingCount` | no | number | Number of passengers who boarded at the last stop |
| `alightingCount` | no | number | Number of passengers who alighted at the last stop |
| `currentOccupancy` | no | number | Total number of passengers currently on board |
| `unitCode` | no | string | Unit of measure code (UN/ECE Rec 20) |
| `value` | no | number | Numeric quantity value |
| `maximum` | no | number | Maximum allowed quantity |
| `minimum` | no | number | Minimum required quantity |
