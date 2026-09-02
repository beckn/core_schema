# PassengerGroup — v2.0

A collection of passengers traveling together as a group, with a group size and a designated lead passenger.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/PassengerGroup/v2.0/attributes.yaml](https://schema.nfh.global/PassengerGroup/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/PassengerGroup/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/PassengerGroup/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/PassengerGroup/v2.0/context.jsonld](https://schema.nfh.global/PassengerGroup/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/PassengerGroup/v2.0/vocab.jsonld](https://schema.nfh.global/PassengerGroup/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `groupId` | no | string | Unique identifier for this passenger group |
| `groupSize` | no | number | Total number of passengers in the group |
| `leadPassenger` | no | $ref: https://schema.nfh.global/Passenger/v2.0/attributes.yaml#/components/schemas/Passenger | The lead or primary passenger for the group |
| `unitCode` | no | string | Unit of measure code (UN/ECE Rec 20) |
| `value` | no | number | Numeric quantity value |
| `maximum` | no | number | Maximum allowed quantity |
| `minimum` | no | number | Minimum required quantity |
