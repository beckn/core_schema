# NackDiscretionary — v2.0

The synchronous rejection body returned when a responding NP exercises its protocol-level agency to decline engagement for policy-governed reasons — insufficient caller trust, capacity limits, scheduled inactivity, or general refusal — without an underlying exception in the received message. The caller MUST NOT expect an on_* callback.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/NackDiscretionary/v2.0/attributes.yaml](https://schema.nfh.global/NackDiscretionary/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/NackDiscretionary/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/NackDiscretionary/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/NackDiscretionary/v2.0/context.jsonld](https://schema.nfh.global/NackDiscretionary/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/NackDiscretionary/v2.0/vocab.jsonld](https://schema.nfh.global/NackDiscretionary/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `message` | yes | object | - |
