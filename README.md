# Exact Online (exact-online)

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

Exact Online is a Dutch cloud business software suite from Exact (Delft, NL) serving SMEs and accountants with accounting, ERP, invoicing, CRM, project management, and AI-driven automation, used by more than 675,000 companies. The platform exposes a comprehensive REST and OData API covering financial, HRM, logistics, CRM, and project data across regional deployments (start.exactonline.nl, .co.uk, .be, .de, .fr, .es, .com). Authentication is via OAuth 2.0 with regional authorization and token endpoints.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/exact-online/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/exact-online/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Accounting
- ERP
- Invoicing
- Business Software
- CRM
- Financial Software
- SME

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Exact Online REST / OData API

REST and OData API (v1) for Exact Online covering financials, sales, purchasing, inventory, HRM, CRM, project management, and master data. Authentication is OAuth 2.0; applications register in the Exact App Center and use regional auth/token endpoints (e.g. start.exactonline.nl for the Netherlands, start.exactonline.co.uk for the UK).

- **Human URL:** [https://start.exactonline.nl/docs/HlpRestAPIResources.aspx](https://start.exactonline.nl/docs/HlpRestAPIResources.aspx)
- **Base URL:** `https://start.exactonline.nl/api/v1`

#### Tags

- Accounting
- ERP
- Invoicing
- Financial

#### Properties

- [Documentation](https://start.exactonline.nl/docs/HlpRestAPIResources.aspx)
- [Reference](https://support.exactonline.com/community/s/article/All-All-DNO-Content-restrefdocs)
- [Introduction](https://support.exactonline.com/community/s/article/All-All-DNO-Content-restintro)
- [O Auth  Authorization  Endpoint](https://start.exactonline.nl/api/oauth2/auth)
- [O Auth  Token  Endpoint](https://start.exactonline.nl/api/oauth2/token)
- [Sample  Code](https://support.exactonline.com/community/s/article/All-All-DNO-Content-restsamplecode)
- [Postman Collection](collections/exact-online.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/exact-online.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/exact)
- [Website](https://www.exact.com)
- [Documentation](https://support.exactonline.com/community/s/knowledge-base)
- [A P I  Documentation](https://start.exactonline.nl/docs/HlpRestAPIResources.aspx)
- [Pricing](https://www.exact.com/nl/software/prijs)
- [Sign Up](https://www.exact.com/nl/probeer-gratis)
- [App  Center](https://apps.exactonline.com)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
