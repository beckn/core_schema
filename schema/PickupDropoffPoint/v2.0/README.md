# PickupDropoffPoint — v2.0

A designated location used as a pickup or dropoff point for passengers in a ride-hailing or demand-responsive transport service.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/PickupDropoffPoint/v2.0/attributes.yaml](https://schema.nfh.global/PickupDropoffPoint/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/PickupDropoffPoint/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/PickupDropoffPoint/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/PickupDropoffPoint/v2.0/context.jsonld](https://schema.nfh.global/PickupDropoffPoint/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/PickupDropoffPoint/v2.0/vocab.jsonld](https://schema.nfh.global/PickupDropoffPoint/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `pdpType` | no | string | Type of point (PICKUP, DROPOFF, BOTH) |
| `landmark` | no | string | Nearby landmark or reference point |
| `accessNotes` | no | string | Instructions for accessing this pickup/dropoff point |
| `id` | no | string | Unique identifier for the fulfillment stop |
| `location` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | Geographic location of the stop |
| `type` | no | string | Type of stop (start, end, intermediate) |
| `instructions` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Instructions for passengers at this stop |
| `time` | no | $ref: https://schema.nfh.global/TimePeriod/v2.0/attributes.yaml#/components/schemas/TimePeriod | Expected time window at this stop |
