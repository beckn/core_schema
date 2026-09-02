# PickupPolicy — v2.0

A set of rules governing the locations and conditions under which passengers may be picked up for a ride-hailing or on-demand transport service.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/PickupPolicy/v2.0/attributes.yaml](https://schema.nfh.global/PickupPolicy/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/PickupPolicy/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/PickupPolicy/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/PickupPolicy/v2.0/context.jsonld](https://schema.nfh.global/PickupPolicy/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/PickupPolicy/v2.0/vocab.jsonld](https://schema.nfh.global/PickupPolicy/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `allowedPickupAreas` | no | $ref: https://schema.nfh.global/Geofence/v2.0/attributes.yaml#/components/schemas/Geofence | Geographic areas where pickup is permitted |
| `pickupConditions` | no | string | Conditions that must be met for a valid pickup |
| `pickupNote` | no | string | Customer-facing note about pickup rules |
| `id` | no | string | Unique identifier for the policy |
| `policyType` | no | string | Type of policy (extensible term) |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the policy |
| `validity` | no | $ref: https://schema.nfh.global/TimePeriod/v2.0/attributes.yaml#/components/schemas/TimePeriod | Validity window for this policy version |
| `policyAttributes` | no | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | Extensible domain-specific policy attributes |
