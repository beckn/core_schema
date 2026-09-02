# Fulfillment — v2.0

Schema definition for Fulfillment in the Beckn Protocol

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Fulfillment/v2.0/attributes.yaml](https://schema.nfh.global/Fulfillment/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Fulfillment/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Fulfillment/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Fulfillment/v2.0/context.jsonld](https://schema.nfh.global/Fulfillment/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Fulfillment/v2.0/vocab.jsonld](https://schema.nfh.global/Fulfillment/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `@context` | yes | string | - |
| `@type` | yes | string | - |
| `beckn:id` | no | string | Fulfillment identifier |
| `beckn:fulfillmentStatus` | no | string | Fulfillment status code (e.g., OutForDelivery, ReadyForPickup, Confirmed) |
| `beckn:mode` | yes | string | DELIVERY    → last-mile / parcel logistics PICKUP      → customer collects from a place RESERVATION → entitlement/booking is fulfilled (tickets, seats, appointments) DIGITAL     → digital good / license access  |
| `trackingAction` | no | $ref: https://schema.nfh.global/TrackAction/v2.1/attributes.yaml#/components/schemas/TrackAction | Tracking entrypoint for this fulfillment, modeled as schema.org TrackAction. Use target.url for a clickable tracking URL; may also include deliveryMethod.  |
| `beckn:deliveryAttributes` | no | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | Bundle of attributes for the chosen mode:  # DELIVERY: endpoints, slot windows, route & events → map to schema:ParcelDelivery / schema:DeliveryEvent # PICKUP: pickupPlace, counter codes, time windows → map to schema:Place + schema:openingHoursSpecification # RESERVATION: reservationStatus, reservedTicket → map to schema:Reservation # DIGITAL: contentUrl/license/expiry → map to schema:DataDownload/schema:MediaObject  |
