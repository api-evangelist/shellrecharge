# ShellRecharge (shellrecharge)

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

ShellRecharge (formerly NewMotion) is Shell's EV charging network and operator platform. Its EV-Platform / Shell Developer APIs let partners and charge point operators manage public charging - retrieving charging locations, starting, stopping, and tracking charge sessions, and exchanging locations, sessions, tariffs, tokens, and CDRs over the OCPI 2.2.1 standard. The APIs are partner-gated and secured with OAuth 2.0 client credentials.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/shellrecharge/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/shellrecharge/refs/heads/main/apis.yml)

## Tags

- EV Charging
- Electric Vehicles
- Mobility
- Charge Points
- OCPI
- Energy

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### ShellRecharge EV Public Locations API

Returns the list of public Shell Recharge EV charging locations - including locations available through roaming partners - with EVSE status, connector types, electrical specifications, opening hours, and tariff metadata. Supports listing all locations, fetching a location by uid, nearby search by latitude/longitude, and bounded map markers by zoom level.

- **Human URL:** [https://developer.shell.com/api-catalog/ev-public-locations/quick-start-guide](https://developer.shell.com/api-catalog/ev-public-locations/quick-start-guide)
- **Base URL:** `https://api.shell.com`

#### Tags

- Locations
- Charge Points
- Stations

#### Properties

- [Documentation](https://developer.shell.com/api-catalog/ev-public-locations/quick-start-guide)
- [API Reference](https://developer.shell.com/api-catalog/ev-public-locations)
- [OpenAPI](openapi/shellrecharge-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shellrecharge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shellrecharge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ShellRecharge EV Public Charge Sessions API

Manages charging at public Shell Recharge locations. Partners can start a session on an EVSE using an EV charge card number and EVSE ID, retrieve a session's status by id, stop an active session, and list the active sessions for a user (by EMAId).

- **Human URL:** [https://developer.shell.com/api-catalog/ev-public-charge-sessions/quick-start-guide](https://developer.shell.com/api-catalog/ev-public-charge-sessions/quick-start-guide)
- **Base URL:** `https://api.shell.com`

#### Tags

- Sessions
- Charging
- EVSE

#### Properties

- [Documentation](https://developer.shell.com/api-catalog/ev-public-charge-sessions/quick-start-guide)
- [API Reference](https://developer.shell.com/api-catalog/ev-public-charge-sessions)
- [OpenAPI](openapi/shellrecharge-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shellrecharge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shellrecharge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ShellRecharge OCPI API

Open Charge Point Interface (OCPI 2.2.1) API for charge point operators, organized around REST and GraphQL. Exposes the Credentials & Registration, Locations, Sessions, Tariffs, Tokens, and CDR (Charge Detail Record) modules for modernizing and roaming EV charging infrastructure.

- **Human URL:** [https://developer.shell.com/api-catalog/ev-private-locations-api/quick-start-guide](https://developer.shell.com/api-catalog/ev-private-locations-api/quick-start-guide)
- **Base URL:** `https://api.shell.com`

#### Tags

- OCPI
- Roaming
- Operator

#### Properties

- [Documentation](https://developer.shell.com/api-catalog/ev-private-locations-api/quick-start-guide)
- [API Reference](https://developer.shell.com/api-catalog)
- [OpenAPI](openapi/shellrecharge-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shellrecharge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shellrecharge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ShellRecharge Tariffs API

OCPI Tariffs module for retrieving and managing the pricing structures (energy, time, flat, and parking components) applied to charge points across the Shell Recharge network and roaming partners.

- **Human URL:** [https://developer.shell.com/api-catalog/ev-private-locations-api/quick-start-guide](https://developer.shell.com/api-catalog/ev-private-locations-api/quick-start-guide)
- **Base URL:** `https://api.shell.com`

#### Tags

- Tariffs
- Pricing
- OCPI

#### Properties

- [Documentation](https://developer.shell.com/api-catalog/ev-private-locations-api/quick-start-guide)
- [OpenAPI](openapi/shellrecharge-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shellrecharge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shellrecharge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ShellRecharge Tokens API

OCPI Tokens module for managing the RFID charge cards and app tokens used to authorize charging, including real-time authorization of a token against an EVSE.

- **Human URL:** [https://developer.shell.com/api-catalog/ev-private-locations-api/quick-start-guide](https://developer.shell.com/api-catalog/ev-private-locations-api/quick-start-guide)
- **Base URL:** `https://api.shell.com`

#### Tags

- Tokens
- Cards
- Authorization

#### Properties

- [Documentation](https://developer.shell.com/api-catalog/ev-private-locations-api/quick-start-guide)
- [OpenAPI](openapi/shellrecharge-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/shellrecharge.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/shellrecharge.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/shellrecharge)
- [Website](https://shellrecharge.com)
- [Documentation](https://developer.shell.com/api-catalog)
- [Plans](plans/shellrecharge-plans-pricing.yml)
- [Rate Limits](rate-limits/shellrecharge-rate-limits.yml)
- [Fin Ops](finops/shellrecharge-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
