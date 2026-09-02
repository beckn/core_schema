# Driver — v2.0

A person who operates a transport vehicle and is responsible for the safe delivery of passengers during a mobility service trip.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Driver/v2.0/attributes.yaml](https://schema.nfh.global/Driver/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Driver/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Driver/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Driver/v2.0/context.jsonld](https://schema.nfh.global/Driver/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Driver/v2.0/vocab.jsonld](https://schema.nfh.global/Driver/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `licenseNumber` | no | string | Driver's license number |
| `vehicleNumber` | no | string | Registration number of the vehicle being driven |
| `yearsOfExperience` | no | number | Number of years of professional driving experience |
| `id` | no | string | Unique identifier for the fulfillment agent |
| `person` | no | $ref: https://schema.nfh.global/Person/v2.0/attributes.yaml#/components/schemas/Person | Personal details of the agent |
| `organization` | no | $ref: https://schema.nfh.global/Organization/v2.0/attributes.yaml#/components/schemas/Organization | Organisation the agent belongs to |
| `contact` | no | string | Contact information for the agent |
| `rating` | no | $ref: https://schema.nfh.global/Rating/v2.0/attributes.yaml#/components/schemas/Rating | Overall rating of the agent |
