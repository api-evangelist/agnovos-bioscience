# AgNovos Bioscience

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

AgNovos Bioscience is a privately held medical technology company developing novel treatments for
bone disease, founded in 2012 with offices in New York, Rockville (Maryland), Frankfurt and Dallas.
Its lead technology is AGN1, a proprietary triphasic, calcium-based, osteoconductive implant material
delivered through the OSSURE Local Osteo-Enhancement Procedure (LOEP) — a minimally invasive procedure
intended to increase the density and strength of osteoporotic bone at sites of highest fracture risk.
The company runs an active clinical program (CONFIRM, RECONFIRM, RESTORE and GRACE trials).

## API surface

**None.** AgNovos Bioscience ships a physical implant and surgical kit, not software. Contract
discovery on 2026-08-06 found no public API, developer program, SDK, or machine-readable interface:
the company's own 432-URL sitemap covers only corporate, clinical and careers pages; `api.`,
`developers.`, `docs.` subdomains do not resolve; `/openapi.json`, `/llms.txt`, `/.well-known/*`
all return a genuine 404; and there is no `agnovos` GitHub organization or package on npm, PyPI or
RubyGems. `ossure.com` is a parked lander that answers HTTP 200 with HTML for every path — a false
positive, not an API. See `x-coverage` in `apis.yml`.

- https://www.agnovos.com/
- https://forgeglobal.com/agnovos-bioscience_stock/ (secondary-market listing — the harvest source)
