# LogisticsDriver — v2.0

A Driver is an individual who operates a vehicle for logistics delivery. Drivers are assigned to shipments and responsible for physical transport. Maps to beckn:Agent.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/LogisticsDriver/v2.0/attributes.yaml](https://schema.nfh.global/LogisticsDriver/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/LogisticsDriver/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/LogisticsDriver/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/LogisticsDriver/v2.0/context.jsonld](https://schema.nfh.global/LogisticsDriver/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/LogisticsDriver/v2.0/vocab.jsonld](https://schema.nfh.global/LogisticsDriver/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `id` | yes | string | Unique driver identifier |
| `name` | yes | string | Full name of the driver |
| `phone` | no | string | - |
| `email` | no | string | - |
| `profilePhoto` | no | string | - |
| `licenseNumber` | yes | string | Driving license number |
| `licenseExpiry` | no | string | License expiry date |
| `rating` | no | number | - |
| `currentLocation` | no | object | Real-time GPS location |
| `status` | no | string | - |
| `vehicle` | no | $ref: https://schema.nfh.global/Vehicle/v2.0/attributes.yaml#/components/schemas/Vehicle | - |
| `experienceYears` | no | integer | Years of driving experience |
| `backgroundVerified` | no | boolean | Whether background verification is complete |
| `languagesSpoken` | no | array | - |
| `operatingZones` | no | array | Geographic zones the driver operates in |
