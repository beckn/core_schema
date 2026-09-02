# Interchange — v2.0

A planned transfer connection point where passengers switch between two or more transport services, with defined timing constraints.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Interchange/v2.0/attributes.yaml](https://schema.nfh.global/Interchange/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Interchange/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Interchange/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Interchange/v2.0/context.jsonld](https://schema.nfh.global/Interchange/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Interchange/v2.0/vocab.jsonld](https://schema.nfh.global/Interchange/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `minTransferTime` | no | number | Minimum required transfer time in seconds |
| `transferType` | no | string | Type of interchange (e.g. TIMED, GUARANTEED, IN_SEAT) |
| `fromStopId` | no | $ref: https://schema.nfh.global/Stop/v2.0/attributes.yaml#/components/schemas/Stop | The stop passengers transfer from |
| `toStopId` | no | $ref: https://schema.nfh.global/Stop/v2.0/attributes.yaml#/components/schemas/Stop | The stop passengers transfer to |
| `fromTripId` | no | $ref: https://schema.nfh.global/VehicleJourney/v2.0/attributes.yaml#/components/schemas/VehicleJourney | The vehicle journey passengers transfer from |
| `toTripId` | no | $ref: https://schema.nfh.global/VehicleJourney/v2.0/attributes.yaml#/components/schemas/VehicleJourney | The vehicle journey passengers transfer to |
| `stopId` | no | string | Unique identifier for the stop |
| `stopCode` | no | string | Short public-facing code for the stop |
| `stopName` | no | string | Human-readable name of the stop |
| `locationType` | no | string | Classification of location (0=stop, 1=station, 2=entrance, 3=generic_node, 4=boarding_area) |
| `parentStation` | no | $ref: https://schema.nfh.global/Station/v2.0/attributes.yaml#/components/schemas/Station | Reference to the parent station if this is a platform |
| `wheelchairBoarding` | no | string | Wheelchair accessibility (0=no info, 1=accessible, 2=not accessible) |
