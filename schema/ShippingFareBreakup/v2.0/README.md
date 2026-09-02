# ShippingFareBreakup — v2.0

A single line item in the fare breakup for a logistics service.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/ShippingFareBreakup/v2.0/attributes.yaml](https://schema.nfh.global/ShippingFareBreakup/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/ShippingFareBreakup/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/ShippingFareBreakup/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/ShippingFareBreakup/v2.0/context.jsonld](https://schema.nfh.global/ShippingFareBreakup/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/ShippingFareBreakup/v2.0/vocab.jsonld](https://schema.nfh.global/ShippingFareBreakup/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `title` | yes | string | Name of the fare component |
| `amount` | yes | number | - |
| `currency` | no | string | - |
| `type` | no | string | - |
| `taxBreakup` | no | array | Tax sub-components if applicable |
| `waived` | no | boolean | Whether this component was waived |
