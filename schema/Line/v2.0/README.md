# Line — v2.0

A named, branded public transport service identified by a number or name, typically operating over one or more routes.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Line/v2.0/attributes.yaml](https://schema.nfh.global/Line/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Line/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Line/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Line/v2.0/context.jsonld](https://schema.nfh.global/Line/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Line/v2.0/vocab.jsonld](https://schema.nfh.global/Line/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `lineId` | no | string | GTFS or NeTEx identifier for the line |
| `shortName` | no | string | Short public-facing name (e.g. 42, M1, Jubilee) |
| `longName` | no | string | Full descriptive name of the line |
| `lineType` | no | string | Mode of transport (e.g. BUS, SUBWAY, RAIL, FERRY) |
| `color` | no | string | Hex colour code for line display on maps |
| `textColor` | no | string | Hex colour code for text displayed on the line colour |
| `operatorRef` | no | $ref: https://schema.nfh.global/Operator/v2.0/attributes.yaml#/components/schemas/Operator | Reference to the operator running this line |
| `networkRef` | no | $ref: https://schema.nfh.global/Network/v2.0/attributes.yaml#/components/schemas/Network | Reference to the network this line belongs to |
| `id` | no | string | Unique identifier for the item |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the item |
| `categoryId` | no | $ref: https://schema.nfh.global/CategoryCode/v2.1/attributes.yaml#/components/schemas/CategoryCode | Category code classifying the item |
| `price` | no | $ref: https://schema.nfh.global/PriceSpecification/v2.1/attributes.yaml#/components/schemas/PriceSpecification | Price specification for this item |
| `quantity` | no | $ref: https://schema.nfh.global/Quantity/v2.0/attributes.yaml#/components/schemas/Quantity | Available quantity of the item |
| `tags` | no | string | Tags associated with the item |
