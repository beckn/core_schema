# LogisticsFare — v2.0

Total cost charged for a logistics service including base freight, surcharges, taxes.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/LogisticsFare/v2.0/attributes.yaml](https://schema.nfh.global/LogisticsFare/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/LogisticsFare/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/LogisticsFare/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/LogisticsFare/v2.0/context.jsonld](https://schema.nfh.global/LogisticsFare/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/LogisticsFare/v2.0/vocab.jsonld](https://schema.nfh.global/LogisticsFare/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `currency` | yes | string | - |
| `baseFreight` | no | number | Base freight charge |
| `fuelSurcharge` | no | number | - |
| `odaSurcharge` | no | number | Out of Delivery Area surcharge |
| `codCharge` | no | number | Cash on delivery charge |
| `insuranceCharge` | no | number | - |
| `gst` | no | number | GST amount |
| `otherCharges` | no | number | - |
| `discount` | no | number | - |
| `totalAmount` | yes | number | Final total payable |
| `breakup` | no | array | Detailed fare breakup line items |
| `estimatedFare` | no | boolean | Whether this is an estimate or confirmed fare |
| `paymentMode` | no | string | - |
