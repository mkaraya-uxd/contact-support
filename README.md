# HubSpot Support Page — Usability Test Prototypes

This repository hosts 4 HTML prototypes of a redesigned **Contact Support** page for help.hubspot.com. Each variant is a standalone, fully interactive prototype built for unmoderated usability testing.

---

## Live Prototypes

| Variant | Description | Link |
|---------|-------------|------|
| **V1** | Original layout with support tier matrix table | [View V1](./contact-support.html) |
| **V2** | Original layout with support tier matrix table (Pro & Enterprise merged) | [View V2](./contact-support-v2.html) |
| **V3** | Card-based layout — account tiers as interactive cards with channel links | [View V3](./contact-support-v3.html) |
| **V4** | Tiered list + channel comparison table with green check indicators | [View V4](./contact-support-v4.html) |

> **Note:** Replace the links above with your full GitHub Pages URLs once the site is live:
> `https://your-username.github.io/hubspot-support-prototypes/contact-support-v2.html`

---

## What's in Each Prototype

All 4 prototypes share the following interactions:

- **Country dropdown** — selects from 33 countries sourced from help.hubspot.com; updates the Pro/Enterprise and Premium Support phone numbers simultaneously
- **Prototype modal** — clicking any link or CTA triggers an overlay that reads *"You're viewing a prototype. Links and navigation are not active."* — dismissible via the Ok button, backdrop click, or Escape key
- **Inline SVGs** — all icons are embedded directly so there are no external asset dependencies or expiry issues

### V1 — Support Matrix
Two-column layout matching the current help.hubspot.com contact support section. Left column shows tiered support cards with a country phone dropdown. Right column shows a 5-tier support matrix table (Free / Starter / Pro / Enterprise / Premium) with checkmarks.

### V2 — Support Matrix
Two-column layout matching the current help.hubspot.com contact support section. Left column shows tiered support cards with a country phone dropdown. Right column shows a 4-tier support matrix table (Free / Starter / Pro/Enterprise / Premium) with checkmarks.

### V3 — Card Layout
Centered card-based layout. Free, Starter, and Professional/Enterprise tiers each have their own card with channel action links (View Community, Send email, Start chat). The Pro/Enterprise card includes the phone dropdown and a dark maroon Premium Support section anchored to the bottom.

### V4 — Tiered List + Table
Two-column layout combining a tiered text list on the left (with orange tier labels, action links, phone dropdown, and Premium card) and a channel comparison table on the right using green filled checkmarks.

---

## Phone Number Data

Phone numbers are sourced from HubSpot's publicly known regional toll-free support lines. The country list matches help.hubspot.com exactly (33 countries).

---

## Research Context

**Project:** Help Center / Contact Support module redesign
**Team:** HubSpot UX — Marketing Design
**Testing platform:** Lysna (unmoderated)
**Stakeholders:** Sarah Armstrong, Adrianna DiMare

These prototypes are intended to test whether layout and information architecture changes to the Contact Support section improve a user's ability to identify the correct support channel for their account type.
