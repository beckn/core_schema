# CourseOfferAttributes — v2.1

Commercial and availability terms under which a course is offered. The proposedConsideration on the core Offer carries the headline fee; this extension provides pricing type context and enrollment window.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/CourseOfferAttributes/v2.1/attributes.yaml](https://schema.nfh.global/CourseOfferAttributes/v2.1/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/CourseOfferAttributes/v2.1/attributes.jsonschema.yaml](https://schema.nfh.global/CourseOfferAttributes/v2.1/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/CourseOfferAttributes/v2.1/context.jsonld](https://schema.nfh.global/CourseOfferAttributes/v2.1/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/CourseOfferAttributes/v2.1/vocab.jsonld](https://schema.nfh.global/CourseOfferAttributes/v2.1/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `pricing_type` | no | string | - |
| `seats_available` | no | integer | - |
| `enrollment_deadline` | no | string | - |
| `offer_validity` | no | object | - |
| `sponsorship_body` | no | string | Name of the sponsoring body (e.g. NSDC, ministry scheme name). |
| `eligibility_constraints` | no | array | Additional eligibility notes beyond formal prerequisites. |
