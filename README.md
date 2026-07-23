# VyStar Credit Union (vystar)

VyStar Credit Union is a member-owned, not-for-profit financial cooperative headquartered in Jacksonville, Florida. Founded in 1952 as Jax Navy Federal Credit Union and renamed VyStar in 2002, it is one of the largest credit unions in the United States, with roughly $14 billion in assets, more than 950,000 members, and approximately 80 branches across Florida and Georgia. It is state-chartered and federally insured by the NCUA.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vystar/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vystar/refs/heads/main/apis.yml)

## Open Finance & API Posture

VyStar Credit Union publishes **no public, first-party developer API**. There is no live developer portal, no downloadable OpenAPI/Swagger definition, and no documented first-party data-access API.

- `developer.vystarcu.org` → HTTP 403 (host present but not publicly served)
- `developers.vystarcu.org` → HTTP 404
- `api.vystarcu.org` → does not resolve
- `vystarcu.org/developers` → HTTP 200, but a Radware/ShieldSquare captcha bot-wall, not an API portal

US open finance is voluntary and fragmented — there is no single mandated open-banking contract as in the UK or Australia. VyStar's honest posture is **aggregator-mediated**: consumer-permissioned account data is shared with third parties through financial-data aggregators (e.g. Plaid/MX/Finicity/Akoya) rather than through a first-party API. No FDX (Financial Data Exchange) participation and no CFPB Section 1033 data-access implementation could be confirmed from public documentation. The emerging Section 1033 Personal Financial Data Rights rule is the relevant regulatory horizon.

## Tags

- Financial Services
- Banking
- Credit Union
- United States
- Open Finance
- Consumer Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

None. VyStar exposes no public API surface; account data access is aggregator-mediated. See [review.yml](review.yml) for the full reviewer finding.

## Common Properties

- [Website](https://www.vystarcu.org/)
- [LinkedIn](https://www.linkedin.com/company/vystar-credit-union)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
