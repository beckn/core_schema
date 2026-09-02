# CallbackSignature — v2.0

A digitally signed authentication credential transmitted in the HTTP Authorization header of PN solicited callbacks to CN `/on_*` endpoints. Extends the standard Signature by chaining the PN's signature to the CN's original request signature, allowing the CN to verify that the callback is a genuine response to a request it sent.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/CallbackSignature/v2.0/attributes.yaml](https://schema.nfh.global/CallbackSignature/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/CallbackSignature/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/CallbackSignature/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/CallbackSignature/v2.0/context.jsonld](https://schema.nfh.global/CallbackSignature/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/CallbackSignature/v2.0/vocab.jsonld](https://schema.nfh.global/CallbackSignature/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| _none_ | - | - | - |
