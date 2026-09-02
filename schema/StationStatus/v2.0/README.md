# StationStatus — v2.0

The real-time operational state of a shared mobility station, including the number of available docks and vehicles.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/StationStatus/v2.0/attributes.yaml](https://schema.nfh.global/StationStatus/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/StationStatus/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/StationStatus/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/StationStatus/v2.0/context.jsonld](https://schema.nfh.global/StationStatus/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/StationStatus/v2.0/vocab.jsonld](https://schema.nfh.global/StationStatus/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `stationId` | no | string | Unique identifier of the station being reported |
| `numBikesAvailable` | no | number | Number of bikes currently available for rental |
| `numDocksAvailable` | no | number | Number of empty docking points currently available |
| `isInstalled` | no | boolean | Whether the station is physically installed and operational |
| `isRenting` | no | boolean | Whether the station is currently renting bikes |
| `isReturning` | no | boolean | Whether the station is currently accepting bike returns |
| `lastReported` | no | string | Timestamp of the last status update for this station |
| `id` | no | string | Unique identifier for the state |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the state |
| `updatedAt` | no | string | Timestamp when the state was last updated |
