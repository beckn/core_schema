# RideOption — v2.0

A specific ride-hailing vehicle category and pricing option presented to a passenger in response to a ride request.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/RideOption/v2.0/attributes.yaml](https://schema.nfh.global/RideOption/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/RideOption/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/RideOption/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/RideOption/v2.0/context.jsonld](https://schema.nfh.global/RideOption/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/RideOption/v2.0/vocab.jsonld](https://schema.nfh.global/RideOption/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `vehicleType` | no | $ref: https://schema.nfh.global/VehicleCategory/v2.0/attributes.yaml#/components/schemas/VehicleCategory | Category of vehicle for this ride option |
| `estimatedArrival` | no | string | Estimated vehicle arrival time at the pickup point |
| `estimatedDuration` | no | string | Estimated trip duration |
| `estimatedDistance` | no | number | Estimated trip distance in kilometres |
| `pricingModel` | no | $ref: https://schema.nfh.global/SystemPricingPlan/v2.0/attributes.yaml#/components/schemas/SystemPricingPlan | Pricing model applicable to this ride option |
| `id` | no | string | Unique identifier for the offer |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the offer |
| `price` | no | $ref: https://schema.nfh.global/PriceSpecification/v2.1/attributes.yaml#/components/schemas/PriceSpecification | Price specification for this offer |
| `validity` | no | $ref: https://schema.nfh.global/TimePeriod/v2.0/attributes.yaml#/components/schemas/TimePeriod | Validity period of the offer |
| `tags` | no | string | Tags or labels associated with the offer |
