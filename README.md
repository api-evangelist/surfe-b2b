# Surfe (surfe-b2b)

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
