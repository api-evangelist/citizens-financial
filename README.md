# Citizens Financial (citizens-financial)

Citizens Financial Group is one of the oldest and largest financial institutions in the United States, providing retail and commercial banking products and services to individuals, small businesses, middle-market companies, and large corporations. Citizens exposes its programmable surface through the Citizens developer portal at developer.citizensbank.com, with REST APIs for deposit account and transaction data, ATM location services, and point-of-sale consumer financing through Citizens Pay. Authentication is OAuth 2.0 and the portal provides both sandbox and production environments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/citizens-financial/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/citizens-financial/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Accounts
- ATMs
- Banking
- Open Banking
- Payments
- Point of Sale
- Transactions

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-19

## APIs

### Citizens Bank Accounts API

The Citizens Bank Accounts API enables authenticated consumers to programmatically retrieve deposit account and transaction data for Citizens Bank customers. Designed exclusively for Savings and Checking accounts, it provides structured access to account metadata and detailed transaction histories through a RESTful interface.

- **Human URL:** [https://developer.citizensbank.com/](https://developer.citizensbank.com/)
- **Base URL:** `https://api.citizensbank.com`

#### Tags

- Accounts
- Banking
- Open Banking
- Transactions

#### Properties

- [Portal](https://developer.citizensbank.com/)
- [Documentation](https://developer.citizensbank.com/product/35/api/26)
- [OpenAPI](openapi/citizens-bank-accounts-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/citizens-bank-accounts-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citizens-bank-accounts-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Citizens Bank ATM Locator API

The Citizens Bank ATM Locator API enables users to locate all Citizens Bank ATMs throughout the USA. The API supports queries by zip code, street address, or latitude and longitude coordinates, returning ATM location details including hours of operation and whether the location is a standalone ATM or part of another entity.

- **Human URL:** [https://developer.citizensbank.com/](https://developer.citizensbank.com/)
- **Base URL:** `https://api.citizensbank.com`

#### Tags

- ATMs
- Banking
- Geolocation
- Locations

#### Properties

- [Documentation](https://developer.citizensbank.com/)
- [OpenAPI](openapi/citizens-bank-atm-locator-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/citizens-bank-atm-locator-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citizens-bank-atm-locator-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Citizens Pay API

The Citizens Pay API enables merchants and partners to integrate Citizens Pay point-of-sale financing into their applications and checkout experiences. Citizens Pay provides consumer financing solutions that allow customers to pay over time for purchases through participating retailers.

- **Human URL:** [https://developer-citizenspay.citizensbank.com/](https://developer-citizenspay.citizensbank.com/)
- **Base URL:** `https://api.citizenspay.com`

#### Tags

- Financing
- Lending
- Payments
- Point of Sale

#### Properties

- [Portal](https://developer-citizenspay.citizensbank.com/)
- [Postman Collection](collections/citizens-bank-accounts-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citizens-bank-accounts-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/citizens-bank-atm-locator-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/citizens-bank-atm-locator-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/rbs-citizens-financial-group)
- [Website](https://www.citizensbank.com/)
- [Portal](https://developer.citizensbank.com/)
- [Sandbox](https://sandboxdeveloper.citizensbank.com/api)
- [Support](https://developer.citizensbank.com/support)
- [Privacy Policy](https://www.citizensbank.com/privacy)
- [JSON-LD](json-ld/citizens-financial-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/citizens-financial-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
