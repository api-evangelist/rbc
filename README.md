# Royal Bank of Canada (rbc)

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
