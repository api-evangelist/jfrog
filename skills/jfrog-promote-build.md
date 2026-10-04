---
name: jfrog-promote-build
description: Promote a specific build after locating it among the available builds.
api: openapi/jfrog-builds-api-openapi.yml
operations:
- listBuilds
- getBuildRuns
- getBuildInfo
- promoteBuild
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/jfrog-builds-api-openapi.yml ; every operationId checked against the contract
---

# jfrog-promote-build

Promote a specific build after locating it among the available builds.

## Steps

1. 1. `listBuilds` – no request body; optional query parameters as defined by the API.
2. 2. `getBuildRuns` – path parameters: `buildName`.
3. 3. `getBuildInfo` – path parameters: `buildName`, `buildNumber`.
4. 4. `promoteBuild` – path parameters: `buildName`, `buildNumber`; request body as defined by the promotion schema.

## Rules

- Authentication: provide an API key via the `Authorization` header (apiKeyAuth) or `X-JFrog-Art-Api` header.
- Idempotency: the `promoteBuild` operation is not idempotent; repeated calls may cause duplicate promotion actions.
