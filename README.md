# VyStar Credit Union (vystar)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
