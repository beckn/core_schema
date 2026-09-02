# HyperlocalDelivery — v2.0

A Beckn domain schema for hyperlocal (same-city, typically sub-2-hour) physical delivery
of goods or prepared food from an origin to a destination within a short radius.

HyperlocalDelivery is a concrete, domain-specific fulfillmentAttributes value for a
beckn:Fulfillment entry. It is fully aligned with schema:ParcelDelivery.

schema.org alignment: schema:ParcelDelivery (subtype of schema:Intangible)
Use in: beckn:Fulfillment.fulfillmentAttributes

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/HyperlocalDelivery/v2.0/attributes.yaml](https://schema.nfh.global/HyperlocalDelivery/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/HyperlocalDelivery/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/HyperlocalDelivery/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/HyperlocalDelivery/v2.0/context.jsonld](https://schema.nfh.global/HyperlocalDelivery/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/HyperlocalDelivery/v2.0/vocab.jsonld](https://schema.nfh.global/HyperlocalDelivery/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `@context` | yes | string | - |
| `@type` | yes | string | - |
| `pickupLocation` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | The pickup/origin location (restaurant, warehouse, dark store). Corresponds to schema:originAddress on schema:ParcelDelivery.  |
| `deliveryLocation` | no | $ref: https://schema.nfh.global/Location/v2.0/attributes.yaml#/components/schemas/Location | The delivery destination (consumer's address). Corresponds to schema:deliveryAddress on schema:ParcelDelivery.  |
| `itemsShipped` | no | array | The items shipped in this delivery. Corresponds to schema:itemShipped on schema:ParcelDelivery.  |
| `agent` | no | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | The delivery agent (rider) carrying out this delivery. Corresponds to schema:carrier on schema:ParcelDelivery.  |
| `trackingUrl` | no | string | Live real-time tracking URL for the rider's location during delivery. Corresponds to schema:trackingUrl on schema:ParcelDelivery.  |
| `expectedArrivalFrom` | no | string | Earliest expected delivery time (ISO 8601). Maps to schema:expectedArrivalFrom. |
| `expectedArrivalUntil` | no | string | Latest expected delivery time (ISO 8601). Maps to schema:expectedArrivalUntil. |
