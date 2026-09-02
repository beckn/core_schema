# Rider — v2.0

A person using a shared mobility service (such as a bike-share, scooter, or car-share) who has a registered account with the provider.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Rider/v2.0/attributes.yaml](https://schema.nfh.global/Rider/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Rider/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Rider/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Rider/v2.0/context.jsonld](https://schema.nfh.global/Rider/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Rider/v2.0/vocab.jsonld](https://schema.nfh.global/Rider/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `riderId` | no | string | Unique identifier for the rider account |
| `preferredPaymentMethod` | no | string | Rider preferred payment method |
| `membershipPlan` | no | string | Active membership or subscription plan |
| `id` | no | string | Unique identifier for the participant |
| `person` | no | $ref: https://schema.nfh.global/Person/v2.0/attributes.yaml#/components/schemas/Person | Personal details of the participant |
| `organization` | no | $ref: https://schema.nfh.global/Organization/v2.0/attributes.yaml#/components/schemas/Organization | Organisation the participant belongs to |
| `entitlements` | no | $ref: https://schema.nfh.global/Entitlement/v2.0/attributes.yaml#/components/schemas/Entitlement | Entitlements held by the participant |
