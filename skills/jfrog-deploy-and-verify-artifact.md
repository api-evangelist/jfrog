---
name: jfrog-deploy-and-verify-artifact
description: Deploy an artifact to a repository and verify its storage information.
api: openapi/jfrog-artifacts-storage-api-openapi.yml
operations:
- deployArtifact
- getStorageInfo
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/jfrog-artifacts-storage-api-openapi.yml ; every operationId checked against the contract
---

# jfrog-deploy-and-verify-artifact

Deploy an artifact to a repository and verify its storage information.

## Steps

1. 1. Use `deployArtifact` with the required path parameters `repoKey` and `itemPath`, and include the artifact binary in the request body. Provide authentication via either the `Authorization` header (apiKeyAuth) or `X-JFrog-Art-Api` header (apiKeyAuth).
2. 2. Use `getStorageInfo` with the same `repoKey` and `itemPath` to retrieve the stored file or folder information and confirm the upload succeeded.

## Rules

- Authentication: supply an API key using the `Authorization` header (e.g., `Authorization: APIKEY <key>`) or the `X-JFrog-Art-Api` header.
- Idempotency: `deployArtifact` is not idempotent; repeat uploads will overwrite the existing artifact.
- Rate limiting: the maximum number of parallel AQL/search API calls applies; exceeding it results in no specific HTTP status code.
