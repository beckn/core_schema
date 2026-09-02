# Ack — v2.0

New v2.0 Ack format carrying an HTTP Counter-Signature proving the receiver authenticated, received, and processed the inbound request.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/Ack/v2.0/attributes.yaml](https://schema.nfh.global/Ack/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/Ack/v2.0/attributes.jsonschema.yaml](https://schema.nfh.global/Ack/v2.0/attributes.jsonschema.yaml) | JSON Schema document (versioned path) |
| [https://schema.nfh.global/Ack/v2.0/context.jsonld](https://schema.nfh.global/Ack/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/Ack/v2.0/vocab.jsonld](https://schema.nfh.global/Ack/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `status` | yes | string | ACK if the request was accepted; NACK if rejected. |
| `signature` | yes | $ref: https://schema.nfh.global/CounterSignature/v2.0/attributes.yaml#/components/schemas/CounterSignature | Counter-signature proving the receiver authenticated and processed the inbound request. |
