# SalesOfferPackage — v2.0

A combination of one or more fare products bundled for sale through a specific distribution channel.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/SalesOfferPackage/v2.0/attributes.yaml](https://schema.nfh.global/SalesOfferPackage/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/SalesOfferPackage/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/SalesOfferPackage/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/SalesOfferPackage/v2.0/context.jsonld](https://schema.nfh.global/SalesOfferPackage/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/SalesOfferPackage/v2.0/vocab.jsonld](https://schema.nfh.global/SalesOfferPackage/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `fareProducts` | no | $ref: https://schema.nfh.global/FareProduct/v2.0/attributes.yaml#/components/schemas/FareProduct | Fare products included in this sales package |
| `distributions` | no | $ref: https://schema.nfh.global/DistributionChannel/v2.0/attributes.yaml#/components/schemas/DistributionChannel | Channels through which this package can be purchased |
| `conditionsOfTravel` | no | string | Conditions applying to the use of this package |
| `id` | no | string | Unique identifier for the offer |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the offer |
| `price` | no | $ref: https://schema.nfh.global/PriceSpecification/v2.1/attributes.yaml#/components/schemas/PriceSpecification | Price specification for this offer |
| `validity` | no | $ref: https://schema.nfh.global/TimePeriod/v2.0/attributes.yaml#/components/schemas/TimePeriod | Validity period of the offer |
| `tags` | no | string | Tags or labels associated with the offer |
