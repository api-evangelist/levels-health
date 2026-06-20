# Levels (levels-health)

Levels is a continuous glucose monitoring (CGM) metabolic-health app that pairs glucose sensors with lab testing and personalized guidance. The platform is a consumer product delivered through iOS, Android, and a member web portal; it consumes health data (Apple Health, wearables, uploaded labs) but does not publish a documented public or partner developer API as of this catalog date.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/levels-health/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/levels-health/refs/heads/main/apis.yml)

> Note: This catalog entry documents a provider with **no public developer API**. The "APIs" listed below describe member-facing data export, in-app data integrations, and a clinic/partner program — none of which expose documented programmatic endpoints. They are captured here for completeness; OpenAPI, plans, rate-limit, and FinOps artifacts are marked `reconciled: false` where the underlying surface is not publicly documented.

## Tags

- Metabolic Health
- CGM
- Continuous Glucose Monitoring
- Health
- Wellness

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Levels Data Export

Member-facing data export of glucose/CGM, activity, zones, and nutrition logs as CSV downloads from the Levels member portal. This is a UI download only; no programmatic/public API endpoint is documented for export.

- **Human URL:** [https://support.levels.com/article/105-how-to-export-your-data](https://support.levels.com/article/105-how-to-export-your-data)

#### Tags

- Data Export
- Glucose
- CSV

#### Properties

- [Documentation](https://support.levels.com/article/105-how-to-export-your-data)
- [OpenAPI](openapi/levels-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/levels-health.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/levels-health.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Levels Health Data Integrations

Inbound connectivity that lets members link Apple Health and wearable data and upload prior labs, DEXA scans, and health records into the Levels app. These are in-app integrations, not an outbound public API surface.

- **Human URL:** [https://www.levelshealth.com](https://www.levelshealth.com)

#### Tags

- Integrations
- Apple Health
- Wearables

#### Properties

- [Documentation](https://www.levelshealth.com)
- [OpenAPI](openapi/levels-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/levels-health.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/levels-health.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Levels Partner Program

A "Partner With Us" program for clinics and partners surfaced in the Levels site footer. No partner-facing developer API, OAuth flow, or documented endpoints are published; engagement is via a contact/inquiry form.

- **Human URL:** [https://www.levelshealth.com](https://www.levelshealth.com)

#### Tags

- Partners
- Clinics
- B2B

#### Properties

- [Documentation](https://www.levelshealth.com)
- [OpenAPI](openapi/levels-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/levels-health.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/levels-health.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/levels-health)
- [Website](https://www.levelshealth.com)
- [Documentation](https://support.levels.com)
- [Plans](plans/levels-health-plans-pricing.yml)
- [Rate Limits](rate-limits/levels-health-rate-limits.yml)
- [Fin Ops](finops/levels-health-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
