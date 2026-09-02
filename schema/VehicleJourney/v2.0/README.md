# VehicleJourney — v2.0

A specific operational instance of a vehicle traveling a defined route at a scheduled time on a given service day.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/VehicleJourney/v2.0/attributes.yaml](https://schema.nfh.global/VehicleJourney/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/VehicleJourney/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/VehicleJourney/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/VehicleJourney/v2.0/context.jsonld](https://schema.nfh.global/VehicleJourney/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/VehicleJourney/v2.0/vocab.jsonld](https://schema.nfh.global/VehicleJourney/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `vehicleJourneyCode` | no | string | Unique code for this vehicle journey |
| `routeRef` | no | $ref: https://schema.nfh.global/Route/v2.0/attributes.yaml#/components/schemas/Route | Reference to the route being served |
| `serviceCalendarRef` | no | $ref: https://schema.nfh.global/ServiceCalendar/v2.0/attributes.yaml#/components/schemas/ServiceCalendar | Calendar defining when this journey operates |
| `vehicleRef` | no | $ref: https://schema.nfh.global/Vehicle/v2.0/attributes.yaml#/components/schemas/Vehicle | Vehicle assigned to this journey |
| `patternRef` | no | $ref: https://schema.nfh.global/Pattern/v2.0/attributes.yaml#/components/schemas/Pattern | Journey pattern being followed |
| `stopTimes` | no | $ref: https://schema.nfh.global/StopTime/v2.0/attributes.yaml#/components/schemas/StopTime | Scheduled stop times for each stop on this journey |
| `id` | no | string | Unique identifier for the fulfillment |
| `type` | no | string | Type of fulfillment (extensible term) |
| `agent` | no | $ref: https://schema.nfh.global/FulfillmentAgent/v2.0/attributes.yaml#/components/schemas/FulfillmentAgent | The entity responsible for performing the fulfillment |
| `mode` | no | $ref: https://schema.nfh.global/FulfillmentMode/v2.0/attributes.yaml#/components/schemas/FulfillmentMode | Mode of fulfillment |
| `participants` | no | $ref: https://schema.nfh.global/Participant/v2.0/attributes.yaml#/components/schemas/Participant | Participants entitled to receive this fulfillment |
| `stages` | no | $ref: https://schema.nfh.global/FulfillmentStage/v2.0/attributes.yaml#/components/schemas/FulfillmentStage | Stages in the fulfillment lifecycle |
| `instructions` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Instructions for fulfillment |
