# Absentify (absentify)

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

Absentify is an absence management platform integrated with Microsoft 365 and Microsoft Teams that helps businesses track and manage employee absences, leave requests, approvals, and team schedules. Built by BrainCore Solutions GmbH, it provides a REST API for integrating absence management into custom workflows, HR systems, and business automation tools.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/absentify/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/absentify/refs/heads/main/apis.yml)

## Scope

- **Access:** 3rd-Party

## Tags

- Absence Management
- HR
- Leave Management
- Microsoft Teams
- Human Resources

## Timestamps

- **Created:** 2025-02-17
- **Modified:** 2026-05-19

## APIs

### Absentify API

REST API for managing employee absences, leave requests, members, departments, leave types, public holidays, and workspace settings. Requires an API key (x-api-key header) available on the Plus plan. Rate limit of 150 requests per second per IP address.

- **Human URL:** [https://absentify.com/docs/en/api-reference/introduction](https://absentify.com/docs/en/api-reference/introduction)
- **Base URL:** `https://api.absentify.com/api/v1`

#### Tags

- Absence Management
- Leave Requests
- Members
- Departments
- Leave Types

#### Properties

- [Documentation](https://absentify.com/docs/en/api-reference/introduction)
- [OpenAPI](openapi/absentify-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/absentify.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/absentify.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/absentify-member-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/absentify-department-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/absentify-leave-type-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/absentify-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/absentify-absence-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/absentify-workspace-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/absentify-public-holiday-calendar-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/absentify-member-structure.json)
- [JSON Structure](json-structure/absentify-department-structure.json)
- [JSON Structure](json-structure/absentify-leave-type-structure.json)
- [JSON Structure](json-structure/absentify-request-structure.json)
- [JSON Structure](json-structure/absentify-absence-structure.json)
- [JSON Structure](json-structure/absentify-workspace-structure.json)
- [JSON Structure](json-structure/absentify-public-holiday-calendar-structure.json)
- [JSON-LD](json-ld/absentify-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/absentify-member-example.json)
- [Example](examples/absentify-department-example.json)
- [Example](examples/absentify-leave-type-example.json)
- [Example](examples/absentify-request-example.json)
- [Example](examples/absentify-absence-example.json)
- [Example](examples/absentify-workspace-example.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/absentify)
- [Portal](https://absentify.com/)
- [Documentation](https://absentify.com/docs/en/)
- [Pricing](https://absentify.com/pricing)
- [Privacy Policy](https://absentify.com/privacy-policy)
- [Terms of Service](https://absentify.com/terms-and-conditions)
- [Blog](https://absentify.com/blog)
- [Status Page](https://status.absentify.com)
- [Security](https://absentify.com/security)
- [Tools](https://absentify.com/docs/en/mcp-server)
- [Spectral Rules](rules/absentify-spectral-rules.yml)
- [Vocabulary](vocabulary/absentify-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
