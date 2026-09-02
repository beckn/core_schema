# DisputeAction — v2.0

`DisputeAction` is the container for the `dispute` / `on_dispute` messages exchanged between nodes. It carries the [`Dispute`](../../Dispute/v2.0/) object being created, updated, status-tracked, or cancelled (withdrawn). The action being performed is conveyed by the endpoint (`dispute` / `on_dispute`) and the lifecycle state of the carried `Dispute`, rather than by a separate action code.

## Files

| File | Purpose |
|---|---|
| [https://schema.nfh.global/DisputeAction/v2.0/attributes.yaml](https://schema.nfh.global/DisputeAction/v2.0/attributes.yaml) | OpenAPI schema envelope (versioned path) |
| [https://schema.nfh.global/DisputeAction/v2.0/context.jsonld](https://schema.nfh.global/DisputeAction/v2.0/context.jsonld) | JSON-LD context (versioned path) |
| [https://schema.nfh.global/DisputeAction/v2.0/vocab.jsonld](https://schema.nfh.global/DisputeAction/v2.0/vocab.jsonld) | RDF vocabulary (versioned path) |

## Properties

| Property | Required | Type | Description |
|---|---|---|---|
| `@context` | yes | string | JSON-LD context reference |
| `@type` | yes | string | JSON-LD type |
| `dispute` | yes | $ref: https://schema.nfh.global/Dispute/v2.0/attributes.yaml#/components/schemas/Dispute | The dispute being exchanged. |
