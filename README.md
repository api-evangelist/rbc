# Royal Bank of Canada (rbc)

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

Royal Bank of Canada (RBC) is Canada's largest bank by market capitalization and one of the country's Big Six, a Schedule I domestic bank chartered under the federal Bank Act and publicly traded (TSX/NYSE: RY), headquartered in Toronto. RBC was the first Canadian bank to launch a public API developer portal and today runs both a self-serve informational/utility API set on that portal and a partner-gated Business Banking API suite for corporate treasury integration.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rbc/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rbc/refs/heads/main/apis.yml)

## Open-Finance Posture

- **First-party developer portal:** [developer.rbc.com](https://developer.rbc.com/) — the "RBC External Developer Portal" (live, HTTP 200). A React single-page app; no downloadable OpenAPI/Swagger is published publicly. It offers self-serve informational/utility APIs (branch locator, credit card catalog, mortgage down-payment and amortization calculators).
- **Business Banking APIs:** [rbcroyalbank.com/business/api](https://www.rbcroyalbank.com/business/api/index.html) — partner-gated corporate/treasury APIs (RBC Move Money via Interac e-Transfer, RBC Pay, and Balance/Transactions, Tracking, and Validation). Onboarding is via an RBC Advisor.
- **Consumer data access:** No first-party open-banking consumer-data API. Consumer data sharing today is aggregator-based via bilateral agreements (e.g. Plaid, Yodlee).
- **Consumer-Driven Banking:** Canada's federal framework (Budget 2024 / Fall Economic Statement 2024, overseen by the FCAC) is legislated but **not yet operational** — open finance in Canada remains voluntary and fragmented. RBC publishes no operational CDB/FDX data-access endpoint.

## Tags

- Financial Services
- Banking
- Canada
- Big Six
- Payments
- Interac
- Open Banking
- Developer Portal

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### RBC Branch Locator API

Self-serve informational API on the RBC External Developer Portal that returns the address and hours of the closest RBC branch(es) for a postal code or keyword search.

- **Human URL:** [https://developer.rbc.com/](https://developer.rbc.com/)

### RBC Credit Card Catalog API

Self-serve informational API exposing RBC credit card product details, rates, and fees.

- **Human URL:** [https://developer.rbc.com/](https://developer.rbc.com/)

### RBC Minimum Down Payment API

Self-serve calculator API computing the minimum down payment required for a given home purchase price under Canadian mortgage rules.

- **Human URL:** [https://developer.rbc.com/](https://developer.rbc.com/)

### RBC Amortization Schedule API

Self-serve calculator API returning the number of payments and amortization schedule for a mortgage.

- **Human URL:** [https://developer.rbc.com/](https://developer.rbc.com/)

### RBC Move Money API (Interac e-Transfer)

Partner-gated Business Banking payment API for sending near real-time Interac e-Transfer transactions with optional enriched remittance/invoice data. Onboarding via an RBC Advisor.

- **Human URL:** [https://www.rbcroyalbank.com/business/api/index.html](https://www.rbcroyalbank.com/business/api/index.html)

### RBC Pay API

Partner-gated Business Banking payment API for embedding RBC payment capabilities into a company's financial systems.

- **Human URL:** [https://www.rbcroyalbank.com/business/api/index.html](https://www.rbcroyalbank.com/business/api/index.html)

### RBC Balance and Transactions API

Partner-gated Business Banking informational API providing real-time account balance and transaction information.

- **Human URL:** [https://www.rbcroyalbank.com/business/api/index.html](https://www.rbcroyalbank.com/business/api/index.html)

### RBC Tracking API

Partner-gated Business Banking informational API for tracking the status of payments and transfers.

- **Human URL:** [https://www.rbcroyalbank.com/business/api/index.html](https://www.rbcroyalbank.com/business/api/index.html)

### RBC Validation API

Partner-gated Business Banking informational API for validating account or payment details before a transaction.

- **Human URL:** [https://www.rbcroyalbank.com/business/api/index.html](https://www.rbcroyalbank.com/business/api/index.html)

## Common Properties

- [Website](https://www.rbc.com/)
- [Developer Portal](https://developer.rbc.com/)
- [Documentation](https://www.rbcroyalbank.com/business/api/index.html)
- [GitHub Organization](https://github.com/rbc)
- [LinkedIn](https://www.linkedin.com/company/rbc)
- [Blog / Newsroom](https://www.rbc.com/newsroom/)
- [Terms of Service](https://www.rbc.com/legal/)
- [Privacy Policy](https://www.rbc.com/privacysecurity/ca/index.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
