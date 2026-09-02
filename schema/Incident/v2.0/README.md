# Incident — v2.0

A reported event on the transport network that affects normal service operations, such as a disruption, roadblock, or infrastructure failure.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Incident/v2.0/attributes.yaml](https://schema.nfh.global/Incident/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Incident/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Incident/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Incident/v2.0/context.jsonld](https://schema.nfh.global/Incident/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Incident/v2.0/vocab.jsonld](https://schema.nfh.global/Incident/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `incidentType` | no | string | Type of incident (e.g. DISRUPTION, ROADBLOCK, MAINTENANCE) |
| `severity` | no | string | Severity level of the incident (LOW, MEDIUM, HIGH) |
| `affectedArea` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | Geographic area affected by the incident |
| `startTime` | no | string | Date and time the incident started |
| `endTime` | no | string | Expected or actual end date and time of the incident |
| `id` | no | string | Unique identifier for the alert |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the alert |
| `validity` | no | $ref: https://schema.nfh.global/TimePeriod/v2.0/attributes.yaml#/components/schemas/TimePeriod | Time period during which the alert is active |
| `status` | no | $ref: https://schema.nfh.global/State/v2.0/attributes.yaml#/components/schemas/State | Current status of the alert |
