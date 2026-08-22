# Citizens Financial (citizens-financial)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
