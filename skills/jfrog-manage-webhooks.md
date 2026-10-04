---
name: jfrog-manage-webhooks
description: Create, list, retrieve, update, and delete webhooks in JFrog.
api: openapi/jfrog-webhooks-api-openapi.yml
operations:
- createWebhook
- listWebhooks
- getWebhook
- updateWebhook
- deleteWebhook
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/jfrog-webhooks-api-openapi.yml ; every operationId checked against the contract
---

# jfrog-manage-webhooks

Create, list, retrieve, update, and delete webhooks in JFrog.

## Steps

1. 1. `createWebhook` – body fields: `event`, `url`, `enabled` (as defined in the contract).
2. 2. `listWebhooks` – query parameters: `page`, `pageSize` (if pagination is supported).
3. 3. `getWebhook` – path parameter: `webhookKey`.
4. 4. `updateWebhook` – path parameter: `webhookKey`; body fields: any updatable webhook attributes.
5. 5. `deleteWebhook` – path parameter: `webhookKey`.

## Rules

- Authentication: provide an API key via the `Authorization` header (`apiKeyAuth`) or `X-JFrog-Art-Api` header.
- Idempotency: `createWebhook` and `updateWebhook` are not idempotent; repeat calls may create duplicates.
- Pagination: `listWebhooks` supports `page` and `pageSize` query parameters for result paging.
