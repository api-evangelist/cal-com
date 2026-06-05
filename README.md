# Cal.com (cal-com)

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
