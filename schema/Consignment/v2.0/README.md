# Consignment — v2.0

A Consignment is a collection of packages or shipments grouped together under a single commercial transaction between a shipper and consignee. Maps to beckn:Order.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Consignment/v2.0/attributes.yaml](https://schema.nfh.global/Consignment/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Consignment/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Consignment/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Consignment/v2.0/context.jsonld](https://schema.nfh.global/Consignment/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Consignment/v2.0/vocab.jsonld](https://schema.nfh.global/Consignment/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `id` | yes | string | Unique consignment identifier (e.g. AWB number) |
| `shipper` | yes | $ref: https://schema.nfh.global/Contact/v2.0/attributes.yaml#/components/schemas/Contact | - |
| `consignee` | yes | $ref: https://schema.nfh.global/Contact/v2.0/attributes.yaml#/components/schemas/Contact | - |
| `shipments` | no | array | List of shipments in this consignment |
| `carrier` | no | $ref: https://schema.nfh.global/Carrier/v2.0/attributes.yaml#/components/schemas/Carrier | - |
| `totalWeight` | no | object | - |
| `totalPackages` | no | integer | Total number of packages in this consignment |
| `serviceType` | no | string | - |
| `paymentMode` | no | string | Payment responsibility |
| `commercialInvoiceNumber` | no | string | Commercial invoice number for customs |
| `customsDeclaration` | no | boolean | Whether customs declaration is required |
| `status` | no | string | - |
| `createdAt` | no | string | - |
| `estimatedDelivery` | no | string | - |
