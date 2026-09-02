# LogisticsCancellationPolicy — v2.0

Defines terms under which a shipment booking can be cancelled.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/LogisticsCancellationPolicy/v2.0/attributes.yaml](https://schema.nfh.global/LogisticsCancellationPolicy/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/LogisticsCancellationPolicy/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/LogisticsCancellationPolicy/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/LogisticsCancellationPolicy/v2.0/context.jsonld](https://schema.nfh.global/LogisticsCancellationPolicy/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/LogisticsCancellationPolicy/v2.0/vocab.jsonld](https://schema.nfh.global/LogisticsCancellationPolicy/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `id` | no | string | - |
| `cancellableUntil` | no | string | Cancellation allowed until this lifecycle stage |
| `cancellationFee` | no | object | - |
| `refundPolicy` | no | object | - |
| `conditions` | no | array | - |
| `applicableServiceTypes` | no | array | - |
