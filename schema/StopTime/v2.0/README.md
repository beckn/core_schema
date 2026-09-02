# StopTime — v2.0

The scheduled arrival and departure times for a vehicle at a specific stop within a vehicle journey.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/StopTime/v2.0/attributes.yaml](https://schema.nfh.global/StopTime/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/StopTime/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/StopTime/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/StopTime/v2.0/context.jsonld](https://schema.nfh.global/StopTime/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/StopTime/v2.0/vocab.jsonld](https://schema.nfh.global/StopTime/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `arrivalTime` | no | string | Scheduled arrival time in HH:MM:SS format |
| `departureTime` | no | string | Scheduled departure time in HH:MM:SS format |
| `stopSequence` | no | number | Order of this stop within the vehicle journey |
| `stopRef` | no | $ref: https://schema.nfh.global/Stop/v2.0/attributes.yaml#/components/schemas/Stop | Reference to the stop for this stop time |
| `pickupType` | no | string | How passengers board at this stop (0=regular, 1=no_pickup, 2=phone_agency, 3=coordinate_with_driver) |
| `dropOffType` | no | string | How passengers alight at this stop (0=regular, 1=no_drop_off, 2=phone_agency, 3=coordinate_with_driver) |
| `distanceTraveled` | no | number | Distance from the route origin to this stop in metres |
| `startDate` | no | string | Start date and time of the period |
| `endDate` | no | string | End date and time of the period |
| `startTime` | no | string | Start time of day in HH:MM:SS format |
| `endTime` | no | string | End time of day in HH:MM:SS format |
