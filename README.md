# Surfe (surfe-b2b)

Surfe (formerly Leadjet) is a B2B contact-discovery and data-enrichment platform whose REST API turns partial signals - a LinkedIn URL, a name plus a company, a domain, or an email - into verified professional email addresses, mobile phone numbers, company firmographics, and lookalike account recommendations. It is the web-intelligence and contact-discovery layer that sits behind Surfe's LinkedIn and CRM experiences, exposed to developers under https://api.surfe.com/v2 with Bearer API-key auth and a credit-based model. Bulk people and company enrichment run as asynchronous jobs (start with POST, then poll the GET job endpoint or receive a webhook callback). This entry focuses on the contact-discovery, data-enrichment, and B2B/sales-intelligence use cases (people search, people enrichment, company search, company enrichment).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/surfe-b2b/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/surfe-b2b/refs/heads/main/apis.yml)

## Tags

- Contact Discovery
- Data Enrichment
- B2B Data
- Sales Intelligence
- Lead Enrichment
- Web Intelligence
- Contact Data
- People Enrichment
- Company Enrichment
- Prospecting

## Timestamps

- **Created:** 2026-07-11
- **Modified:** 2026-07-11

## APIs

### Surfe Account API

Credit balance and account utilities.

- **Human URL:** [https://developers.surfe.com/public-015-create-people-bulk-enrichment](https://developers.surfe.com/public-015-create-people-bulk-enrichment)
- **Base URL:** `https://api.surfe.com/v2`

#### Tags

- Account

#### Properties

- [OpenAPI](openapi/surfe-b2b-account-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/surfe-b2b-account-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surfe-b2b-account-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://developers.surfe.com/public-015-create-people-bulk-enrichment)
- [API Reference](https://developers.surfe.com/)
- [Postman Collection](collections/surfe-b2b.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surfe-b2b.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://developers.surfe.com/public-009-search-people-v2)
- [Documentation](https://developers.surfe.com/public-014-get-bulk-enrichment-organizations)
- [Documentation](https://developers.surfe.com/public-011-search-companies)
- [Documentation](https://developers.surfe.com/)

### Surfe Companies API

Search and enrich organizations.

- **Human URL:** [https://developers.surfe.com/public-015-create-people-bulk-enrichment](https://developers.surfe.com/public-015-create-people-bulk-enrichment)
- **Base URL:** `https://api.surfe.com/v2`

#### Tags

- Companies

#### Properties

- [OpenAPI](openapi/surfe-b2b-companies-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/surfe-b2b-companies-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surfe-b2b-companies-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://developers.surfe.com/public-015-create-people-bulk-enrichment)
- [API Reference](https://developers.surfe.com/)
- [Postman Collection](collections/surfe-b2b.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surfe-b2b.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://developers.surfe.com/public-009-search-people-v2)
- [Documentation](https://developers.surfe.com/public-014-get-bulk-enrichment-organizations)
- [Documentation](https://developers.surfe.com/public-011-search-companies)
- [Documentation](https://developers.surfe.com/)

### Surfe People API

Search and enrich individual contacts.

- **Human URL:** [https://developers.surfe.com/public-015-create-people-bulk-enrichment](https://developers.surfe.com/public-015-create-people-bulk-enrichment)
- **Base URL:** `https://api.surfe.com/v2`

#### Tags

- People

#### Properties

- [OpenAPI](openapi/surfe-b2b-people-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/surfe-b2b-people-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surfe-b2b-people-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://developers.surfe.com/public-015-create-people-bulk-enrichment)
- [API Reference](https://developers.surfe.com/)
- [Postman Collection](collections/surfe-b2b.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surfe-b2b.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://developers.surfe.com/public-009-search-people-v2)
- [Documentation](https://developers.surfe.com/public-014-get-bulk-enrichment-organizations)
- [Documentation](https://developers.surfe.com/public-011-search-companies)
- [Documentation](https://developers.surfe.com/)

### Surfe Recommendations API

ICP definition and lookalike account recommendations.

- **Human URL:** [https://developers.surfe.com/public-015-create-people-bulk-enrichment](https://developers.surfe.com/public-015-create-people-bulk-enrichment)
- **Base URL:** `https://api.surfe.com/v2`

#### Tags

- Recommendations

#### Properties

- [OpenAPI](openapi/surfe-b2b-recommendations-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/surfe-b2b-recommendations-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surfe-b2b-recommendations-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://developers.surfe.com/public-015-create-people-bulk-enrichment)
- [API Reference](https://developers.surfe.com/)
- [Postman Collection](collections/surfe-b2b.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/surfe-b2b.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://developers.surfe.com/public-009-search-people-v2)
- [Documentation](https://developers.surfe.com/public-014-get-bulk-enrichment-organizations)
- [Documentation](https://developers.surfe.com/public-011-search-companies)
- [Documentation](https://developers.surfe.com/)

## Common Properties

- [Agentic Access](agentic-access/surfe-b2b-agentic-access.yml)
- [Domain Security](security/surfe-b2b-domain-security.yml)
- [Authentication](authentication/surfe-b2b-authentication.yml)
- [LinkedIn](https://www.linkedin.com/company/surfe)
- [Website](https://surfe.com)
- [Documentation](https://developers.surfe.com/)
- [Plans](plans/surfe-b2b-plans-pricing.yml)
- [Rate Limits](rate-limits/surfe-b2b-rate-limits.yml)
- [Fin Ops](finops/surfe-b2b-finops.yml)
- [Blog](https://www.surfe.com/blog/feed/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
