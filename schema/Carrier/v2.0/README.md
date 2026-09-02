# Carrier — v2.0

A Carrier is a transport service provider responsible for moving goods across distances. Carriers operate fleets of vehicles and may own/manage logistics hubs. Maps to beckn:Provider.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Carrier/v2.0/attributes.yaml](https://schema.nfh.global/Carrier/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Carrier/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Carrier/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Carrier/v2.0/context.jsonld](https://schema.nfh.global/Carrier/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Carrier/v2.0/vocab.jsonld](https://schema.nfh.global/Carrier/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `id` | yes | string | Unique carrier identifier |
| `name` | yes | string | Legal name of the carrier |
| `code` | no | string | Short carrier code |
| `logo` | no | string | URL to carrier logo |
| `website` | no | string | - |
| `contact` | no | $ref: https://schema.nfh.global/Contact/v2.0/attributes.yaml#/components/schemas/Contact | - |
| `rating` | no | number | - |
| `serviceTypes` | no | array | Types of logistics services offered |
| `serviceCoverage` | no | array | Geographic regions served |
| `fleetSize` | no | integer | Number of vehicles in fleet |
| `hubs` | no | array | Logistics hubs operated by this carrier |
| `licenseNumber` | no | string | Transport license number |
| `gstNumber` | no | string | GST registration number |
| `panNumber` | no | string | PAN for tax purposes |
| `active` | no | boolean | Whether carrier is currently active on network |
