# SupportTicket — v2.0

A support ticket raised against an order

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/SupportTicket/v2.0/attributes.yaml](https://schema.nfh.global/SupportTicket/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/SupportTicket/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/SupportTicket/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/SupportTicket/v2.0/context.jsonld](https://schema.nfh.global/SupportTicket/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/SupportTicket/v2.0/vocab.jsonld](https://schema.nfh.global/SupportTicket/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `id` | no | string | Ticket ID |
| `supportTicketAttributes` | no | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | - |
