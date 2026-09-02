# LogisticsSupportCase — v2.0

Customer support ticket for shipment issues — loss, damage, delay, or billing.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/LogisticsSupportCase/v2.0/attributes.yaml](https://schema.nfh.global/LogisticsSupportCase/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/LogisticsSupportCase/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/LogisticsSupportCase/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/LogisticsSupportCase/v2.0/context.jsonld](https://schema.nfh.global/LogisticsSupportCase/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/LogisticsSupportCase/v2.0/vocab.jsonld](https://schema.nfh.global/LogisticsSupportCase/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `id` | yes | string | - |
| `shipmentId` | yes | string | - |
| `issueType` | yes | string | - |
| `description` | no | string | - |
| `priority` | no | string | - |
| `status` | no | string | - |
| `raisedBy` | no | string | User ID who raised the ticket |
| `assignedAgent` | no | string | Support agent ID |
| `attachments` | no | array | Photo/document evidence |
| `claimAmount` | no | number | Amount claimed for loss/damage |
| `resolution` | no | string | Resolution details |
| `createdAt` | no | string | - |
| `resolvedAt` | no | string | - |
