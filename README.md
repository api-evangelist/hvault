# HashiCorp Vault (hvault)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

HashiCorp Vault secures, stores, and tightly controls access to tokens, passwords, certificates, API keys, and other secrets in modern computing. Vault handles leasing, key revocation, key rolling, and auditing. Through a unified API, users can access an encrypted Key/Value store and network encryption-as-a-service, or generate AWS IAM/STS credentials, SQL/NoSQL databases, X.509 certificates, SSH credentials, and more.

**APIs.json:** [https://www.vaultproject.io/api-docs](https://www.vaultproject.io/api-docs)

## Tags

- Encryption
- Identity
- Infrastructure
- Secrets Management
- Security

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Vault System Backend API

API for system-level operations including authentication, secrets engines, audit devices, and general Vault configuration.

- **Human URL:** [https://www.vaultproject.io/](https://www.vaultproject.io/)
- **Base URL:** `https://vault.example.com/v1/sys`

#### Tags

- Administration
- Configuration
- System

#### Properties

- [Documentation](https://developer.hashicorp.com/vault/api-docs/system)
- [X-openapi](https://github.com/hashicorp/vault/blob/main/openapi.json)
- [Authentication](https://developer.hashicorp.com/vault/docs/auth)
- [OpenAPI](openapi/hvault-system-backend-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hvault-system-backend.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hvault-system-backend.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vault Secrets Engines API

APIs for various secrets engines including Key/Value, AWS, Azure, databases, PKI, SSH, and more.

- **Human URL:** [https://developer.hashicorp.com/vault/docs/secrets](https://developer.hashicorp.com/vault/docs/secrets)
- **Base URL:** `https://vault.example.com/v1`

#### Tags

- Cloud
- Databases
- Kv
- Secrets

#### Properties

- [Documentation](https://developer.hashicorp.com/vault/api-docs/secret)
- [X-kv-docs](https://developer.hashicorp.com/vault/api-docs/secret/kv/kv-v2)
- [X-aws-docs](https://developer.hashicorp.com/vault/api-docs/secret/aws)
- [X-database-docs](https://developer.hashicorp.com/vault/api-docs/secret/databases)
- [OpenAPI](openapi/hvault-secrets-engines-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hvault-secrets-engines.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hvault-secrets-engines.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vault Auth Methods API

APIs for authentication methods including Token, AppRole, Kubernetes, LDAP, JWT/OIDC, GitHub, and more.

- **Human URL:** [https://developer.hashicorp.com/vault/docs/auth](https://developer.hashicorp.com/vault/docs/auth)
- **Base URL:** `https://vault.example.com/v1/auth`

#### Tags

- Access Control
- Authentication
- Identity

#### Properties

- [Documentation](https://developer.hashicorp.com/vault/api-docs/auth)
- [X-token-docs](https://developer.hashicorp.com/vault/api-docs/auth/token)
- [X-approle-docs](https://developer.hashicorp.com/vault/api-docs/auth/approle)
- [X-kubernetes-docs](https://developer.hashicorp.com/vault/api-docs/auth/kubernetes)
- [OpenAPI](openapi/hvault-auth-methods-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hvault-auth-methods.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hvault-auth-methods.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vault Identity API

APIs for managing entities, entity aliases, and groups for identity management across authentication methods.

- **Human URL:** [https://developer.hashicorp.com/vault/docs/secrets/identity](https://developer.hashicorp.com/vault/docs/secrets/identity)
- **Base URL:** `https://vault.example.com/v1/identity`

#### Tags

- Entities
- Groups
- Identity

#### Properties

- [Documentation](https://developer.hashicorp.com/vault/api-docs/secret/identity)
- [OpenAPI](openapi/hvault-identity-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hvault-identity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hvault-identity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/hashicorp)
- [X-website](https://www.vaultproject.io/)
- [X-documentation](https://developer.hashicorp.com/vault/docs)
- [X-api-documentation](https://developer.hashicorp.com/vault/api-docs)
- [X-github](https://github.com/hashicorp/vault)
- [X-tutorials](https://developer.hashicorp.com/vault/tutorials)
- [X-support](https://support.hashicorp.com/)
- [X-terms-of-service](https://www.hashicorp.com/terms-of-service)
- [X-privacy-policy](https://www.hashicorp.com/privacy)
- [X-pricing](https://www.hashicorp.com/products/vault/pricing)
- [X-blog](https://www.hashicorp.com/blog)
- [X-status](https://status.hashicorp.com/)
- [JSON-LD](json-ld/hvault-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/hvault-secret-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hvault-entity-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hvault-entity-alias-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hvault-token-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hvault-policy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/hvault-group-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
