# NoShowPolicy — v2.0

Rules governing the consequences and fees applied when a passenger fails to appear for a confirmed transport service booking.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/NoShowPolicy/v2.0/attributes.yaml](https://schema.nfh.global/NoShowPolicy/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/NoShowPolicy/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/NoShowPolicy/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/NoShowPolicy/v2.0/context.jsonld](https://schema.nfh.global/NoShowPolicy/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/NoShowPolicy/v2.0/vocab.jsonld](https://schema.nfh.global/NoShowPolicy/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `noShowFee` | no | number | Flat fee charged for a no-show |
| `gracePeriodMinutes` | no | number | Grace period in minutes before a no-show is recorded |
| `currency` | no | string | ISO 4217 currency code for the no-show fee |
| `id` | no | string | Unique identifier for the policy |
| `policyType` | no | string | Type of policy (extensible term) |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the policy |
| `validity` | no | $ref: https://schema.nfh.global/TimePeriod/v2.0/attributes.yaml#/components/schemas/TimePeriod | Validity window for this policy version |
| `policyAttributes` | no | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | Extensible domain-specific policy attributes |
