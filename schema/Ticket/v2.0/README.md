# Ticket — v2.0

A document or digital record granting the holder the right to travel on a specific transport service or within a defined validity scope.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Ticket/v2.0/attributes.yaml](https://schema.nfh.global/Ticket/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Ticket/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Ticket/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Ticket/v2.0/context.jsonld](https://schema.nfh.global/Ticket/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Ticket/v2.0/vocab.jsonld](https://schema.nfh.global/Ticket/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `ticketId` | no | string | Unique identifier or serial number of the ticket |
| `ticketType` | no | string | Type of ticket (e.g. SINGLE, RETURN, SEASON, FLEXI) |
| `validFrom` | no | string | Date and time from which the ticket is valid |
| `validUntil` | no | string | Date and time until which the ticket is valid |
| `fareProductRef` | no | $ref: https://schema.nfh.global/FareProduct/v2.0/attributes.yaml#/components/schemas/FareProduct | Reference to the fare product this ticket is issued under |
| `passengerRef` | no | $ref: https://schema.nfh.global/Passenger/v2.0/attributes.yaml#/components/schemas/Passenger | Reference to the passenger this ticket is issued to |
| `id` | no | string | Unique identifier for the entitlement |
| `descriptor` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Human-readable information about the entitlement |
| `resource` | no | $ref: https://schema.nfh.global/ContractItem/v2.0/attributes.yaml#/components/schemas/ContractItem | The resource being accessed against this entitlement |
| `credentials` | no | $ref: https://schema.nfh.global/core/v2.0/Descriptor/attributes.yaml#components/schemas/Descriptor | Credential descriptors for the entitlement |
