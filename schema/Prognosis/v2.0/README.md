# Prognosis — v2.0

A real-time prediction of a vehicle's arrival or departure time at a stop, including an indication of prediction confidence.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Prognosis/v2.0/attributes.yaml](https://schema.nfh.global/Prognosis/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Prognosis/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Prognosis/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Prognosis/v2.0/context.jsonld](https://schema.nfh.global/Prognosis/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Prognosis/v2.0/vocab.jsonld](https://schema.nfh.global/Prognosis/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `scheduledTime` | no | string | Timetabled scheduled time |
| `estimatedTime` | no | string | Predicted actual time |
| `certainty` | no | string | Confidence of the prognosis (e.g. real, prognosis, calculated, unknown) |
| `delaySeconds` | no | number | Delay in seconds relative to the scheduled time |
| `id` | no | string | Unique identifier for the tracking record |
| `url` | no | string | URL endpoint for real-time tracking information |
| `status` | no | $ref: https://schema.nfh.global/State/v2.0/attributes.yaml#/components/schemas/State | Current tracking status |
| `validity` | no | $ref: https://schema.nfh.global/TimePeriod/v2.0/attributes.yaml#/components/schemas/TimePeriod | Validity period for this tracking record |
