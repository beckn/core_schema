# StopEvent — v2.0

A departure or arrival event at a stop, used to retrieve the next or previous vehicle movements at a specific location.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/StopEvent/v2.0/attributes.yaml](https://schema.nfh.global/StopEvent/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/StopEvent/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/StopEvent/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/StopEvent/v2.0/context.jsonld](https://schema.nfh.global/StopEvent/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/StopEvent/v2.0/vocab.jsonld](https://schema.nfh.global/StopEvent/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `stopEventType` | no | string | Type of event (DEPARTURE, ARRIVAL) |
| `timetabledTime` | no | string | Scheduled time for the event |
| `estimatedTime` | no | string | Estimated actual time for the event |
| `serviceJourneyRef` | no | $ref: https://schema.nfh.global/VehicleJourney/v2.0/attributes.yaml#/components/schemas/VehicleJourney | Reference to the vehicle journey for this event |
| `stopPointRef` | no | $ref: https://schema.nfh.global/StopPoint/v2.0/attributes.yaml#/components/schemas/StopPoint | Reference to the stop point where the event occurs |
| `id` | no | string | Unique identifier for the fulfillment stop |
| `location` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | Geographic location of the stop |
| `type` | no | string | Type of stop (start, end, intermediate) |
| `instructions` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Instructions for passengers at this stop |
| `time` | no | $ref: https://schema.nfh.global/TimePeriod/v2.0/attributes.yaml#/components/schemas/TimePeriod | Expected time window at this stop |
