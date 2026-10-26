# Cal.com (cal-com)

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

Cal.com is open-source scheduling infrastructure (Calendly alternative) available as a managed cloud service or self-hosted deployment. The Cal.com API v2 exposes bookings, event types, schedules, availability, slots, webhooks, OAuth, teams, organizations, OOO, conferencing, destination calendars, and the Cal.com Atoms (Platform) for embedding scheduling primitives into other apps.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cal-com/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cal-com/refs/heads/main/apis.yml)

## Tags

- Productivity
- Scheduling
- Calendar
- Open Source
- Booking

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-30

## APIs

### Cal.com Bookings API

Create, read, update, cancel, and reschedule bookings. Supports recurring, seated, and round-robin booking flows.

- **Human URL:** [https://cal.com/docs/api-reference/v2/bookings](https://cal.com/docs/api-reference/v2/bookings)
- **Base URL:** `https://api.cal.com/v2`

#### Tags

- Bookings
- CRUD

#### Properties

- [Documentation](https://cal.com/docs/api-reference)
- [API Reference](https://cal.com/docs/api-reference/v2/bookings)
- [OpenAPI](openapi/cal-com-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cal-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cal-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cal.com Event Types API

Manage event types (meeting templates) — duration, location, fields, locations, payment, recurrence, and team round-robin assignments.

- **Human URL:** [https://cal.com/docs/api-reference/v2/event-types](https://cal.com/docs/api-reference/v2/event-types)
- **Base URL:** `https://api.cal.com/v2`

#### Tags

- Event Types
- Configuration

#### Properties

- [API Reference](https://cal.com/docs/api-reference/v2/event-types)
- [OpenAPI](openapi/cal-com-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cal-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cal-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cal.com Schedules API

Manage user schedules — weekly working hours, date overrides, and timezone defaults.

- **Human URL:** [https://cal.com/docs/api-reference/v2/schedules](https://cal.com/docs/api-reference/v2/schedules)
- **Base URL:** `https://api.cal.com/v2`

#### Tags

- Schedules
- Working Hours

#### Properties

- [API Reference](https://cal.com/docs/api-reference/v2/schedules)
- [OpenAPI](openapi/cal-com-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cal-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cal-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cal.com Availability API

Compute and read user/team availability across event types, accounting for connected calendars and overrides.

- **Human URL:** [https://cal.com/docs/api-reference/v2/availability](https://cal.com/docs/api-reference/v2/availability)
- **Base URL:** `https://api.cal.com/v2`

#### Tags

- Availability
- Calendar

#### Properties

- [API Reference](https://cal.com/docs/api-reference/v2/availability)
- [OpenAPI](openapi/cal-com-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cal-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cal-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cal.com Slots API

Reserve, list, and release bookable time slots for event types — used by booking page UIs to lock a slot before confirmation.

- **Human URL:** [https://cal.com/docs/api-reference/v2/slots](https://cal.com/docs/api-reference/v2/slots)
- **Base URL:** `https://api.cal.com/v2`

#### Tags

- Slots
- Time

#### Properties

- [API Reference](https://cal.com/docs/api-reference/v2/slots)
- [OpenAPI](openapi/cal-com-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cal-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cal-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cal.com Webhooks API

Subscribe to BOOKING_CREATED, BOOKING_RESCHEDULED, BOOKING_CANCELLED, MEETING_STARTED, and other events; deliveries POST to a developer-defined endpoint.

- **Human URL:** [https://cal.com/docs/api-reference/v2/webhooks](https://cal.com/docs/api-reference/v2/webhooks)
- **Base URL:** `https://api.cal.com/v2`

#### Tags

- Webhooks
- Events

#### Properties

- [API Reference](https://cal.com/docs/api-reference/v2/webhooks)
- [OpenAPI](openapi/cal-com-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cal-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cal-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/cal-com-webhooks-asyncapi.yaml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Cal.com OAuth & Auth API

OAuth client management, token issuance, and refresh — primarily used by Cal.com Platform integrations to manage end-user accounts under a hosting application.

- **Human URL:** [https://cal.com/docs/api-reference/v2/oauth](https://cal.com/docs/api-reference/v2/oauth)
- **Base URL:** `https://api.cal.com/v2`

#### Tags

- OAuth
- Authentication

#### Properties

- [API Reference](https://cal.com/docs/api-reference/v2/oauth)
- [OpenAPI](openapi/cal-com-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cal-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cal-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cal.com Teams API

Manage teams, team members, and team event types for collective and round-robin scheduling.

- **Human URL:** [https://cal.com/docs/api-reference/v2/teams](https://cal.com/docs/api-reference/v2/teams)
- **Base URL:** `https://api.cal.com/v2`

#### Tags

- Teams
- Membership

#### Properties

- [API Reference](https://cal.com/docs/api-reference/v2/teams)
- [OpenAPI](openapi/cal-com-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cal-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cal-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cal.com Organizations API

Top-level organizations API for managing sub-teams, members, and organization-wide event types and routing forms.

- **Human URL:** [https://cal.com/docs/api-reference/v2/organizations](https://cal.com/docs/api-reference/v2/organizations)
- **Base URL:** `https://api.cal.com/v2`

#### Tags

- Organizations
- Enterprise

#### Properties

- [API Reference](https://cal.com/docs/api-reference/v2/organizations)
- [OpenAPI](openapi/cal-com-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cal-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cal-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cal.com Out-of-Office API

Mark users as out-of-office for a date range, with optional automatic forwarding to a delegate.

- **Human URL:** [https://cal.com/docs/api-reference/v2/out-of-office](https://cal.com/docs/api-reference/v2/out-of-office)
- **Base URL:** `https://api.cal.com/v2`

#### Tags

- OOO
- Availability

#### Properties

- [API Reference](https://cal.com/docs/api-reference/v2/out-of-office)
- [OpenAPI](openapi/cal-com-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cal-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cal-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cal.com Conferencing API

Connect and manage video-conferencing apps (Zoom, Google Meet, Microsoft Teams, Cal Video, Daily, etc.) used as event-type locations.

- **Human URL:** [https://cal.com/docs/api-reference/v2/conferencing](https://cal.com/docs/api-reference/v2/conferencing)
- **Base URL:** `https://api.cal.com/v2`

#### Tags

- Conferencing
- Video

#### Properties

- [API Reference](https://cal.com/docs/api-reference/v2/conferencing)
- [OpenAPI](openapi/cal-com-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cal-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cal-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cal.com Destination Calendars API

Connect Google, Outlook/Office 365, Apple, and CalDAV calendars; choose where new bookings are written and where conflicts are read from.

- **Human URL:** [https://cal.com/docs/api-reference/v2/destination-calendars](https://cal.com/docs/api-reference/v2/destination-calendars)
- **Base URL:** `https://api.cal.com/v2`

#### Tags

- Calendars
- Integration

#### Properties

- [API Reference](https://cal.com/docs/api-reference/v2/destination-calendars)
- [OpenAPI](openapi/cal-com-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cal-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cal-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Cal.com Atoms (Platform)

Cal.com Platform exposes pre-built React components ("Atoms") and a managed-user OAuth model so SaaS apps can embed scheduling primitives end-to-end. Used by platforms that want to ship Cal.com features under their own brand.

- **Human URL:** [https://cal.com/docs/platform](https://cal.com/docs/platform)
- **Base URL:** `https://api.cal.com/v2`

#### Tags

- Atoms
- SDK
- Embed

#### Properties

- [Documentation](https://cal.com/docs/platform)
- [SDK](https://www.npmjs.com/package/@calcom/atoms)
- [OpenAPI](openapi/cal-com-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cal-com.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cal-com.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/cal-com)
- [Website](https://cal.com/)
- [Documentation](https://cal.com/docs/api-reference)
- [Pricing](https://cal.com/pricing)
- [Git Hub](https://github.com/calcom/cal.com)
- [Plans](plans/cal-com-plans-pricing.yml)
- [Rate Limits](rate-limits/cal-com-rate-limits.yml)
- [Fin Ops](finops/cal-com-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
