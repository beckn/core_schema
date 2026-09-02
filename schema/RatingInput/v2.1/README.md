# RatingInput — v2.1

A form designed to capture rating and feedback from a user. This can be used by both BAP and BPP to fetch ratings and feedback of their respective users.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/RatingInput/v2.1/attributes.yaml](https://schema.nfh.global/RatingInput/v2.1/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/RatingInput/v2.1/attributes.jsonschema.yaml](https://schema.nfh.global/RatingInput/v2.1/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/RatingInput/v2.1/context.jsonld](https://schema.nfh.global/RatingInput/v2.1/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/RatingInput/v2.1/vocab.jsonld](https://schema.nfh.global/RatingInput/v2.1/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `target` | yes | object | The thing being rated. It could be a person, an application, a service, a product, an instrument used in the fulfillment of the contract, or the overall experience. |
| `range` | yes | object | - |
| `feedbackFormSubmission` | no | $ref: https://schema.nfh.global/FormSubmission/v2.0/attributes.yaml#/components/schemas/FormSubmission | The submission to the feedback form sent along with a rating request |
