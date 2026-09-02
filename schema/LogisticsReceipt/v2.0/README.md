# LogisticsReceipt — v2.0

Digital acknowledgment of payment and delivery for a logistics service.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/LogisticsReceipt/v2.0/attributes.yaml](https://schema.nfh.global/LogisticsReceipt/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/LogisticsReceipt/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/LogisticsReceipt/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/LogisticsReceipt/v2.0/context.jsonld](https://schema.nfh.global/LogisticsReceipt/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/LogisticsReceipt/v2.0/vocab.jsonld](https://schema.nfh.global/LogisticsReceipt/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `id` | yes | string | - |
| `shipmentId` | yes | string | - |
| `invoiceNumber` | no | string | - |
| `issuedAt` | no | string | - |
| `fare` | yes | $ref: https://schema.nfh.global/Fare/v2.0/attributes.yaml#/components/schemas/Fare | - |
| `paymentMode` | no | string | - |
| `paymentTransactionId` | no | string | - |
| `paidAt` | no | string | - |
| `shipper` | no | $ref: https://schema.nfh.global/Contact/v2.0/attributes.yaml#/components/schemas/Contact | - |
| `consignee` | no | $ref: https://schema.nfh.global/Contact/v2.0/attributes.yaml#/components/schemas/Contact | - |
| `carrier` | no | $ref: https://schema.nfh.global/Carrier/v2.0/attributes.yaml#/components/schemas/Carrier | - |
| `deliveryProof` | no | $ref: https://schema.nfh.global/Proof/v2.0/attributes.yaml#/components/schemas/Proof | - |
| `downloadUrl` | no | string | URL to download PDF receipt |
