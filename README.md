# Royal Bank of Canada

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

Royal Bank of Canada (RBC) is Canada's largest bank by market capitalization and one of the country's Big Six, a Schedule I domestic bank chartered under the federal Bank Act and publicly traded (TSX/NYSE: RY) with headquarters in Toronto. RBC serves personal, commercial, wealth, capital-markets, and insurance clients in Canada, the U.S., and internationally. It was the first Canadian bank to launch a public API developer portal (developer.rbc.com — the "RBC External Developer Portal"), which offers self-serve informational/utility APIs (branch locator, credit card catalog, mortgage down-payment and amortization calculators) alongside a partner-gated Business Banking API suite for corporate treasury integration (RBC Move Money via Interac e-Transfer, RBC Pay, and Balance/Transactions, Tracking, and Validation APIs). RBC exposes no first-party open-banking consumer-data API; consumer data sharing today is aggregator-based via bilateral agreements (e.g. Plaid, Yodlee). Canada's federal Consumer-Driven Banking framework (Budget 2024 / Fall Economic Statement 2024, overseen by the FCAC) is legislated but not yet operational, so open finance in Canada remains voluntary and fragmented.

**Areas:** Financial Services · Banking · Canada · Big Six · Payments · Interac · Open Banking

## Royal Bank of Canada on APIs.io

Everything profiled for Royal Bank of Canada is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/rbc/](https://apis.io/providers/rbc/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [RBC Branch Locator API](https://apis.io/apis/rbc/branch-locator-api/) — Self-serve informational API on the RBC External Developer Portal that accepts a postal code or keyword search and returns the address and hours of…
- [RBC Credit Card Catalog API](https://apis.io/apis/rbc/credit-card-catalog-api/) — Self-serve informational API on the RBC External Developer Portal exposing RBC credit card product details, rates, and fees through a programmatic interface.
- [RBC Minimum Down Payment API](https://apis.io/apis/rbc/minimum-down-payment-api/) — Self-serve calculator API on the RBC External Developer Portal that computes the minimum down payment required for a given home purchase price under…
- [RBC Amortization Schedule API](https://apis.io/apis/rbc/amortization-schedule-api/) — Self-serve calculator API on the RBC External Developer Portal that returns the number of payments and amortization schedule for a mortgage given amount,…
- [RBC Move Money API (Interac e-Transfer)](https://apis.io/apis/rbc/move-money-interac-api/) — Partner-gated Business Banking payment API that lets companies send near real-time Interac e-Transfer transactions in Canada from an embedded, real-time…
- [RBC Pay API](https://apis.io/apis/rbc/rbc-pay-api/) — Partner-gated Business Banking payment API for embedding RBC payment capabilities into a company's financial systems. Documented on the RBC Royal Bank…
- [RBC Balance and Transactions API](https://apis.io/apis/rbc/balance-and-transactions-api/) — Partner-gated Business Banking informational API providing real-time account balance and transaction information for a company's RBC accounts. Onboarding is…
- [RBC Tracking API](https://apis.io/apis/rbc/tracking-api/) — Partner-gated Business Banking informational API for tracking the status of payments and transfers within RBC business banking. Onboarding is via an RBC…
- [RBC Validation API](https://apis.io/apis/rbc/validation-api/) — Partner-gated Business Banking informational API for validating account or payment details prior to initiating a transaction. Onboarding is via an RBC Advisor.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Rbc Domain Security](https://apis.io/security/rbc/rbc-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.rbc.com/)
- [Documentation](https://www.rbcroyalbank.com/business/api/index.html)
- [Getting started](https://developer.rbc.com/)
- [API reference](https://developer.rbc.com/)
- [Sign up](https://developer.rbc.com/)
- [Blog](https://www.rbc.com/newsroom/)
- [Terms of service](https://www.rbc.com/legal/)
- [Privacy policy](https://www.rbc.com/privacysecurity/ca/index.html)
- [GitHub](https://github.com/rbc)

## API Evangelist rating

**Kin Score 20.8** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 69.6 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 2.6 |
| Developer ergonomics | 40.5 |
| Access clarity | 34.2 |

**Agent readiness 0.0** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 11.0** — Banking & Open Finance

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/rbc/](https://apis.io/providers/rbc/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Royal Bank of Canada: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/rbc/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
