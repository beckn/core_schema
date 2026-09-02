# SafetyPolicy — v2.0

A set of rules, protocols, and standards governing safety requirements for drivers, vehicles, and passengers on a mobility platform.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/SafetyPolicy/v2.0/attributes.yaml](https://schema.nfh.global/SafetyPolicy/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/SafetyPolicy/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/SafetyPolicy/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/SafetyPolicy/v2.0/context.jsonld](https://schema.nfh.global/SafetyPolicy/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/SafetyPolicy/v2.0/vocab.jsonld](https://schema.nfh.global/SafetyPolicy/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `safetyInstructions` | no | string | Instructions and guidelines for passenger and driver safety |
| `emergencyContact` | no | $ref: https://schema.nfh.global/ContactHandle/v2.0/attributes.yaml#/components/schemas/ContactHandle | Emergency contact handle for safety incidents |
| `insuranceCoverage` | no | string | Description of insurance coverage under this policy |
| `id` | no | string | Unique identifier for the policy |
| `policyType` | no | string | Type of policy (extensible term) |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the policy |
| `validity` | no | $ref: https://schema.nfh.global/TimePeriod/v2.0/attributes.yaml#/components/schemas/TimePeriod | Validity window for this policy version |
| `policyAttributes` | no | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | Extensible domain-specific policy attributes |
