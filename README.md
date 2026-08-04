# Cvent Platform (cvent-platform)

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

Cvent is a leading meetings, events, and hospitality technology provider serving more than 22,000 customers worldwide. The Cvent Platform spans two product groups: Event Cloud (event management, registration, mobile event apps, virtual and hybrid events, Attendee Hub, surveys, and analytics) and Hospitality Cloud (Cvent Supplier Network, Passkey hotel room block management, Venue Sourcing, and Sales & Catering). Programmatic access is delivered through the Cvent Platform REST API protected by OAuth 2.0 client credentials, with the token endpoint at api-platform.cvent.com/ea/oauth2/token. Earlier integrations also use legacy XML SOAP / RegLink web services. The developer portal at developers.cvent.com hosts API references, guides, and OpenAPI downloads.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cvent-platform/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cvent-platform/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Attendee Hub
- Conferences
- Event Management
- Event Marketing
- Events
- Hospitality
- Hospitality Cloud
- Hybrid Events
- Meetings
- OAuth 2.0
- Passkey
- Registration
- REST API
- Supplier Network
- Surveys
- Venue Management
- Virtual Events

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-28

## APIs

### Cvent Platform REST API

The Cvent Platform REST API is the unified RESTful interface across the Event Cloud product line, providing programmatic access to events, contacts, registrations, attendees, sessions, speakers, exhibitors, surveys, webhooks, and Attendee Hub resources. The API uses OAuth 2.0 client credentials. Authorization code flow is available to planner administrators. Developers can download the OpenAPI specification from the API reference.

- **Human URL:** [https://developers.cvent.com/docs/rest-api/overview](https://developers.cvent.com/docs/rest-api/overview)
- **Base URL:** `https://api-platform.cvent.com`

#### Tags

- Attendees
- Contacts
- Events
- OAuth 2.0
- Registration
- REST
- Sessions
- Surveys
- Webhooks

#### Properties

- [Documentation](https://developers.cvent.com/docs/rest-api/overview)
- [Concepts](https://developers.cvent.com/docs/rest-api)
- [Guides](https://developers.cvent.com/docs/rest-api/guides/rest-guides)
- [Migration Guide](https://developers.cvent.com/docs/rest-api/migration-guide/benefits)
- [Registration Guide](https://developers.cvent.com/docs/rest-api/guides/registration-guide)
- [O Auth Token Endpoint](https://api-platform.cvent.com/ea/oauth2/token)
- [Postman Collection](collections/cvent-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cvent-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cvent Passkey RegLink API

Passkey RegLink APIs are RESTful JSON APIs (with legacy URL-based and SOAP options) connecting Cvent with external registration and reservation applications. Primary functions include streamlining the hotel reservation process by sending registrant information to Passkey, fetching event details and hotel room availability, retrieving reservation information, and creating, updating, and cancelling registrant hotel reservations.

- **Human URL:** [https://developers.cvent.com/docs/passkey/REST/overview](https://developers.cvent.com/docs/passkey/REST/overview)
- **Base URL:** `https://api-platform.cvent.com`

#### Tags

- Group Bookings
- Hotel
- Passkey
- Reservations
- Room Blocks

#### Properties

- [Documentation](https://developers.cvent.com/docs/passkey/REST/overview)
- [Getting Started](https://developers.cvent.com/docs/passkey/REST/getting-started)
- [Passkey Docs](https://developers.cvent.com/doc/passkey/)
- [Postman Collection](collections/cvent-platform.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cvent-platform.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/cvent)
- [Website](https://www.cvent.com/)
- [Developer Portal](https://developers.cvent.com/)
- [API Reference](https://developers.cvent.com/docs/rest-api/overview)
- [Authentication](https://developers.cvent.com/docs/rest-api)
- [O Auth Token Endpoint](https://api-platform.cvent.com/ea/oauth2/token)
- [Support Articles](https://support.cvent.com/)
- [Status Page](https://status.cvent.com/)
- [Pricing](https://www.cvent.com/en/pricing)
- [Terms of Service](https://www.cvent.com/en/terms-of-service)
- [Privacy Policy](https://www.cvent.com/en/privacy-policy)
- [Blog](https://www.cvent.com/blog)
- [Twitter](https://twitter.com/cvent)
- [LinkedIn](https://www.linkedin.com/company/cvent/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
