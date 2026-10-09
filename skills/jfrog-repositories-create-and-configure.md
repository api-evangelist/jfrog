---
name: jfrog-repositories-create-and-configure
description: Create a new repository and configure its settings in JFrog.
api: openapi/jfrog-repositories-api-openapi.yml
operations:
- createRepository
- updateRepository
- getRepository
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/jfrog-repositories-api-openapi.yml ; every operationId checked against the contract
---

# jfrog-repositories-create-and-configure

Create a new repository and configure its settings in JFrog.

## Steps

1. 1. Use `createRepository` with the required path parameter `repoKey` and the repository configuration body.
2. 2. Use `updateRepository` with the same `repoKey` and the fields you wish to modify in the request body.
3. 3. Use `getRepository` with `repoKey` to verify the repository was created and configured correctly.

## Rules

- Authentication: Provide an API key using either the `Authorization` header or the `X-JFrog-Art-Api` header (apiKeyAuth).
- Idempotency: `createRepository` is idempotent when the same `repoKey` is used; repeated calls will not create duplicate repositories.
- Rate limiting: Parallel AQL/search API calls are limited; exceeding the limit returns no specific HTTP status code.
