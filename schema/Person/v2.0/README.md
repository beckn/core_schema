# Person — v2.0

A person (alive, deceased, or fictional). Modeled after schema.org/Person.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Person/v2.0/attributes.yaml](https://schema.nfh.global/Person/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Person/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Person/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Person/v2.0/context.jsonld](https://schema.nfh.global/Person/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Person/v2.0/vocab.jsonld](https://schema.nfh.global/Person/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `@context` | yes | string | - |
| `@type` | yes | string | - |
| `id` | yes | string | Unique identifier for the person |
| `name` | no | string | Full name of the person |
| `email` | no | string | Email address |
| `telephone` | no | string | Telephone number |
| `address` | no | any | Physical address |
| `age` | no | integer | Age in years |
| `knowsLanguage` | no | array | Languages known by the person (BCP-47 codes or language names) |
| `worksFor` | no | $ref: https://schema.nfh.global/Organization/v2.0/attributes.yaml#/components/schemas/Organization | Organization the person works for |
| `credentials` | no | array | Credentials held by the person |
| `skills` | no | array | Skills possessed by the person |
| `personAttributes` | no | $ref: https://schema.nfh.global/Attributes/v2.0/attributes.yaml#/components/schemas/Attributes | Extensible attribute pack for jurisdictional or domain-specific person properties |
