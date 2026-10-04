---
name: jfrog-create-and-sign-release-bundle
description: Create a new release bundle and then sign it.
api: openapi/jfrog-release-bundles-v1-api-openapi.yml
operations:
- createReleaseBundle
- signReleaseBundle
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/jfrog-release-bundles-v1-api-openapi.yml ; every operationId checked against the contract
---

# jfrog-create-and-sign-release-bundle

Create a new release bundle and then sign it.

## Steps

1. 1. Call `createReleaseBundle` with the required request body fields for the bundle definition.
2. 2. Call `signReleaseBundle` with the required request body fields to sign the newly created bundle.

## Rules

- Authentication: include either the `Authorization` header with an API key (`apiKeyAuth`), the `X-JFrog-Art-Api` header with an API key (`apiKeyAuth`), basic auth credentials, or a bearer token (`bearerAuth`).
- Idempotency: `createReleaseBundle` is not idempotent; repeated calls may create duplicate bundles.
