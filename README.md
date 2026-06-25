# ShellRecharge (shellrecharge)

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
