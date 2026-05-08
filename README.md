# Cal.com (cal-com)

Cal.com is open-source scheduling infrastructure (Calendly alternative) available as a managed cloud service or self-hosted deployment. The Cal.com API v2 exposes bookings, event types, schedules, availability, slots, webhooks, OAuth, teams, organizations, OOO, conferencing, destination calendars, and the Cal.com Atoms (Platform) for embedding scheduling primitives.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/cal-com/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=cal-com-api-evangelist&utm_content=repo)

## Type

- **x-type:** company

## Tags:

 - Productivity, Scheduling, Calendar, Open Source, Booking

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

| API | Description |
|---|---|
| Cal.com Bookings API | Create, read, update, cancel, reschedule bookings. |
| Cal.com Event Types API | Manage meeting templates and round-robin assignment. |
| Cal.com Schedules API | Working-hours, date overrides, timezone defaults. |
| Cal.com Availability API | Compute user/team availability. |
| Cal.com Slots API | Reserve/list/release bookable time slots. |
| Cal.com Webhooks API | Subscribe to BOOKING_*, MEETING_* events. |
| Cal.com OAuth & Auth API | OAuth client management; tokens for Platform integrations. |
| Cal.com Teams API | Teams, members, team event types. |
| Cal.com Organizations API | Sub-teams, org-wide event types, routing forms. |
| Cal.com Out-of-Office API | OOO date ranges with optional delegate. |
| Cal.com Conferencing API | Zoom, Meet, Teams, Cal Video, Daily integration. |
| Cal.com Destination Calendars API | Google/Outlook/Apple/CalDAV calendar wiring. |
| Cal.com Atoms (Platform) | React SDK + managed-user OAuth for SaaS embedders. |

## Common Properties

- [Website](https://cal.com/)
- [Documentation](https://cal.com/docs/api-reference)
- [Pricing](https://cal.com/pricing)
- [GitHub](https://github.com/calcom/cal.com)
- [Plans](plans/cal-com-plans-pricing.yml) — API Commons Plans 0.1
- [RateLimits](rate-limits/cal-com-rate-limits.yml) — API Commons Rate Limits 0.1
- [FinOps](finops/cal-com-finops.yml) — FOCUS-aligned FinOps Framework 1.0

## Artifacts

| Artifact | Path | Notes |
|---|---|---|
| Plans | `plans/cal-com-plans-pricing.yml` | Self-Hosted (free) / Free / Teams $12 / Organizations $28 / Enterprise / Platform |
| Rate Limits | `rate-limits/cal-com-rate-limits.yml` | Per-API-key (cloud) and per-OAuth-client (Platform); none on self-host |
| FinOps | `finops/cal-com-finops.yml` | Per-seat subscription + Platform managed-user volume |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
