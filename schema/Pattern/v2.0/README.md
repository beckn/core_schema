# Pattern — v2.0

A unique sequence of stops visited by trips on a route, grouping trips with identical stop sequences and timing structures.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Pattern/v2.0/attributes.yaml](https://schema.nfh.global/Pattern/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Pattern/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Pattern/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Pattern/v2.0/context.jsonld](https://schema.nfh.global/Pattern/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Pattern/v2.0/vocab.jsonld](https://schema.nfh.global/Pattern/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `patternId` | no | string | Unique identifier for the journey pattern |
| `routeRef` | no | $ref: https://schema.nfh.global/Route/v2.0/attributes.yaml#/components/schemas/Route | Reference to the route this pattern belongs to |
| `directionId` | no | string | Direction of travel (0 or 1) |
| `stops` | no | $ref: https://schema.nfh.global/Stop/v2.0/attributes.yaml#/components/schemas/Stop | Ordered list of stops in this pattern |
| `shapeRef` | no | $ref: https://schema.nfh.global/Shape/v2.0/attributes.yaml#/components/schemas/Shape | Reference to the geographic shape of this pattern |
| `id` | no | string | Unique identifier for the item |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable description of the item |
| `categoryId` | no | $ref: https://schema.nfh.global/CategoryCode/v2.1/attributes.yaml#/components/schemas/CategoryCode | Category code classifying the item |
| `price` | no | $ref: https://schema.nfh.global/PriceSpecification/v2.1/attributes.yaml#/components/schemas/PriceSpecification | Price specification for this item |
| `quantity` | no | $ref: https://schema.nfh.global/Quantity/v2.0/attributes.yaml#/components/schemas/Quantity | Available quantity of the item |
| `tags` | no | string | Tags associated with the item |
