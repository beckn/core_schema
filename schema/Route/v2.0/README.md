# Route — v2.0

The physical or logical path followed by a transport service, defined as an ordered sequence of stops or waypoints.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Route/v2.0/attributes.yaml](https://schema.nfh.global/Route/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Route/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Route/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Route/v2.0/context.jsonld](https://schema.nfh.global/Route/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Route/v2.0/vocab.jsonld](https://schema.nfh.global/Route/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `routeId` | no | string | Unique identifier for the route |
| `shortName` | no | string | Short public-facing name (e.g. 42A) |
| `longName` | no | string | Full descriptive name of the route |
| `routeType` | no | string | Mode of transport (e.g. BUS, RAIL, TRAM, FERRY) |
| `operatorRef` | no | $ref: https://schema.nfh.global/Operator/v2.0/attributes.yaml#/components/schemas/Operator | Operator providing this route |
| `networkRef` | no | $ref: https://schema.nfh.global/Network/v2.0/attributes.yaml#/components/schemas/Network | Network this route belongs to |
| `id` | no | string | Unique identifier for the item |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the item |
| `categoryId` | no | $ref: https://schema.nfh.global/CategoryCode/v2.1/attributes.yaml#/components/schemas/CategoryCode | Category code classifying the item |
| `price` | no | $ref: https://schema.nfh.global/PriceSpecification/v2.1/attributes.yaml#/components/schemas/PriceSpecification | Price specification for this item |
| `quantity` | no | $ref: https://schema.nfh.global/Quantity/v2.0/attributes.yaml#/components/schemas/Quantity | Available quantity of the item |
| `tags` | no | string | Tags associated with the item |
