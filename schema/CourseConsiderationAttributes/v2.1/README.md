# CourseConsiderationAttributes — v2.1

Beckn v2.1 extension schema for the considerationAttributes container. Captures value-exchange specifics for a course enrollment — fee category, payment schedule, installment count, subsidy source, and refund policy. Used when course pricing_type is FULL_FEE, SUBSIDIZED, or SCHOLARSHIP.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/CourseConsiderationAttributes/v2.1/attributes.yaml](https://schema.nfh.global/CourseConsiderationAttributes/v2.1/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/CourseConsiderationAttributes/v2.1/attributes.jsonschema.yaml](https://schema.nfh.global/CourseConsiderationAttributes/v2.1/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/CourseConsiderationAttributes/v2.1/context.jsonld](https://schema.nfh.global/CourseConsiderationAttributes/v2.1/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/CourseConsiderationAttributes/v2.1/vocab.jsonld](https://schema.nfh.global/CourseConsiderationAttributes/v2.1/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `fee_category` | no | string | How the fee obligation is structured for this learner. |
| `payment_schedule` | no | string | When payment is expected relative to course delivery. |
| `installment_count` | no | integer | Number of installments, if payment_schedule is INSTALLMENT. |
| `subsidy_source` | no | string | Name of the government scheme or sponsoring body covering the subsidy. |
| `refund_policy` | no | string | Brief statement of the refund terms applicable to this enrollment. |
