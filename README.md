# HashiCorp Vault (hvault)

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
