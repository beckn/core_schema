# Performance — v2.0

Generalized execution/performance unit. This is where downstream objects bind:
- Fulfillment-like details (where/when/how)
- Tracking handles
- Support touchpoints
- Status updates

A minimal envelope that carries identity, status, and a performanceAttributes
bag that holds the concrete domain-specific delivery schema.

Domain specification authors can attach rich context and types via `performanceAttributes`.

For example, Hyperlocal delivery details (pickup/delivery locations, items shipped, agent, etc.)
are placed inside performanceAttributes using a well-known domain schema such as
HyperlocalDelivery. Use the generic Attributes schema when no well-known
domain schema exists.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Performance/v2.0/attributes.yaml](https://schema.nfh.global/Performance/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Performance/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Performance/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Performance/v2.0/context.jsonld](https://schema.nfh.global/Performance/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Performance/v2.0/vocab.jsonld](https://schema.nfh.global/Performance/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `id` | no | string | Unique identifier for this fulfillment record. |
| `status` | no | $ref: https://schema.nfh.global/Descriptor/v2.1/attributes.yaml#/components/schemas/Descriptor | Current status of this fulfillment, expressed as a Descriptor. Use Descriptor.code for machine-readable status values. |
| `commitmentIds` | no | array | - |
| `performanceAttributes` | no | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | Domain-specific extension attributes for this fulfillment. Use beckn:HyperlocalDelivery (aligned with schema:ParcelDelivery) for hyperlocal physical delivery. Use the generic Attributes schema for other fulfillment types where no well-known domain schema exists. |
