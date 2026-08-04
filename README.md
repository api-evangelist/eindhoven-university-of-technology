# Eindhoven University of Technology (eindhoven-university-of-technology)

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

Eindhoven University of Technology (TU/e) is a research-driven public technical university in Eindhoven, Netherlands, ranked #136 in the QS World University Rankings 2025. This repository catalogs TU/e's public, machine-readable developer/API footprint as an [APIs.json](https://apisjson.org) provider profile. The confirmed public surface centers on the Elsevier Pure research information system (OAI-PMH harvesting + Pure Web Service); TU/e does not operate a single consolidated public developer portal.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/eindhoven-university-of-technology/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=eindhoven-university-of-technology-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Netherlands, Europe

## APIs

- **TU/e Research Portal OAI-PMH** — OAI-PMH metadata-harvesting interface for the Pure-powered research portal. Docs: https://research.tue.nl/ (endpoint: https://pure.tue.nl/ws/oai)
- **TU/e Pure Web Service (Research API)** — Elsevier Pure REST/SOAP web service backing the research portal; generally API-key gated. Docs: https://purefaq.tue.nl/pure/faq/index.php?action=overview

## Plans / Rate Limits / FinOps

- Plans: [plans/eindhoven-university-of-technology-plans-pricing.yml](plans/eindhoven-university-of-technology-plans-pricing.yml)
- Rate Limits: [rate-limits/eindhoven-university-of-technology-rate-limits.yml](rate-limits/eindhoven-university-of-technology-rate-limits.yml)
- FinOps: [finops/eindhoven-university-of-technology-finops.yml](finops/eindhoven-university-of-technology-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.tue.nl/en/
- GitHub: https://github.com/TUEIndhoven
- LinkedIn: https://www.linkedin.com/school/eindhoven-university-of-technology/
- Review: [review.yml](review.yml)

## Notes

- All entries reflect what could be verified publicly as of 2026-06-03; no endpoints were fabricated.
- The Pure OAI-PMH and Pure Web Service paths resolve but returned server errors (500/999) to bare unauthenticated probes — consistent with Pure requiring well-formed OAI verbs/metadataPrefix or API-key authentication, not with the services being broken.
- No single consolidated public TU/e developer portal was found; course, identity (SSO), and library systems are institution-internal or vendor-mediated.
- Many departmental research-group GitHub organizations exist (e.g., tue-robotics, TUE-EE-ES, tueimage), but there is no single official university-wide GitHub org.
- The "Eindhoven Open Data" (opendatasoft) portal belongs to the municipality of Eindhoven, not the university, and was therefore excluded.

## Maintainers

- Kin Lane — kin@apievangelist.com
