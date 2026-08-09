---
name: submit-to-mydentify
description: Diagnose or submit a public software product in Mydentify from one URL, inspect AI readiness evidence, check for duplicates, and confirm supported intents.
---

# Submit to Mydentify

Use this skill when a user asks to diagnose, list, submit, add, update, or check a public product in Mydentify.

## Safety

- Ask for one public product URL and optional target outcome.
- Confirm the user intends to submit public product information.
- Never send credentials, private links, personal information, customer data, or unpublished material.
- Never claim that an intent is supported unless Mydentify returns evidence for it.
- Never purchase an upgrade or featured placement without explicit user authorization for the exact bounded amount.

## Procedure

1. Call `POST https://mydentify.com/api/imports/dry-run`.
2. If an exact duplicate, probable duplicate, or renamed product exists, show the classification, reason, confidence, canonical human/JSON/Markdown URLs, and only the returned claim, restore-access, or proposed-update actions.
3. Otherwise generate a stable idempotency key for this user request and call `POST https://mydentify.com/api/imports` with `mode: "diagnostic"` and `source: "agent"`. This must not create a listing.
4. Store `importId`, `statusUrl`, and `eventsUrl`. Submit only once.
5. Subscribe to SSE or poll no faster than once per second. Reconnect SSE with `Last-Event-ID`.
6. On `retry_scheduled`, wait until `retryAfter`. On `failed`, explain the safe public error and follow only `remediation.actions`; retry, request another URL, or send to manual review as directed.
7. On `needs_input`, ask only the focused question returned by Mydentify.
8. On `ready_for_confirmation`, summarize the readiness score, confidence, unavailable checks, evidence, recommended fixes, and suggested intents. Obtain user approval before creating a listing or confirming an intent.
9. Before confirming a free listing, ask the user to publish a followed link to `https://mydentify.com` on the submitted page. It may be a text link, a linked image, or this optional official badge: `<a href="https://mydentify.com/" aria-label="Listed on Mydentify"><img src="https://mydentify.com/badges/listed-on-mydentify.svg" alt="Listed on Mydentify" width="176" height="32"></a>`. Explain that Mydentify verifies the backlink at confirmation and again before publication. Enhanced listings are exempt.
10. Confirm one intent for a free listing. Do not initiate paid coverage without explicit authorization.
11. On `submitted_for_review` with `nextAction.type: "verify_badge"`, explain that Mydentify is checking automatically and return the canonical status URL. Use review language only when `nextAction.type` requests manual review. On `rejected`, explain every public field in `rejection` and offer its correction path. On `approved`, return every product and supported-intent URL in `publication`.

API details and examples: https://mydentify.com/submit.md
