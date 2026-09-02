# LostAndFoundItem — v2.0

An item that has been reported lost or found in connection with a transport service.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/LostAndFoundItem/v2.0/attributes.yaml](https://schema.nfh.global/LostAndFoundItem/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/LostAndFoundItem/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/LostAndFoundItem/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/LostAndFoundItem/v2.0/context.jsonld](https://schema.nfh.global/LostAndFoundItem/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/LostAndFoundItem/v2.0/vocab.jsonld](https://schema.nfh.global/LostAndFoundItem/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `itemType` | no | string | Type of the lost/found item (e.g. BAG, PHONE, WALLET) |
| `itemDescription` | no | string | Detailed description of the item |
| `foundAt` | no | string | Date and time the item was found |
| `lostAt` | no | string | Date and time the item was lost |
| `vehicleRef` | no | $ref: https://schema.nfh.global/Vehicle/v2.0/attributes.yaml#/components/schemas/Vehicle | Vehicle on which the item was found or lost |
| `orderId` | no | string | Identifier of the contract/order against which support is required |
| `ticketIds` | no | $ref: https://schema.nfh.global/SupportTicket/v2.0/attributes.yaml#/components/schemas/SupportTicket | Identifiers of any open support tickets |
| `callbackPhone` | no | string | Telephone number for callback support |
