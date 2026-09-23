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

Eindhoven University of Technology (TU/e) is a public technical university in Eindhoven, the Netherlands, and one of the four institutions of the 4TU federation. This repository catalogs TU/e's public, machine-readable footprint as an [APIs.json](https://apisjson.org) provider profile.

**Re-profiled 2026-08-30 under the API Evangelist university pipeline, which puts operator attribution ahead of artifact volume.** A university is a federation of buyers, not a producer. TU/e publishes no institution-authored API contract and operates no developer portal. Every machine-readable surface carrying the TU/e name is a vendor's product running under the institution's name — and this profile now says so.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/eindhoven-university-of-technology/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=eindhoven-university-of-technology-api-evangelist&utm_content=repo

## Type

- University / Technical University — Index / Consumer / 3rd-Party

## Tags

University, Higher Education, Education, Technical University, Netherlands, Europe, 4TU, Research Data, Research Information, Research Repository, Identity Federation, OAI-PMH, Open Metadata

## Surfaces, by who actually operates them

Every entry carries an `x-operator`. `institution` means the contract is theirs. `tenant` means the deployment is theirs and the contract is somebody else's. `vendor` means neither, and it is not listed here at all.

| Surface | Operator | What it actually is |
|---|---|---|
| [TU/e Research Portal OAI-PMH](https://pure.tue.nl/ws/oai) | `tenant` | Live, keyless OAI-PMH 2.0 on TU/e's own domain, served by Elsevier Pure. Seven metadata formats, OpenAIRE CERIF 1.2, real records returned. The one genuinely open surface. |
| [TU/e Pure Web Service](https://pure.tue.nl/ws/api/documentation/index.html) | `tenant` | TU/e's deployment of Elsevier Pure 5.35.3-4. API-key gated. The OpenAPI is Elsevier's and is deliberately not stored here. |
| [TU/e SAML IdP in SURFconext / eduGAIN](https://metadata.surfconext.nl/idps-metadata.xml) | `tenant` | TU/e's federation identity, entityID resolving to a Microsoft Entra ID tenant, SSO proxied by SURFconext. |

## What was removed, and why

Thirty-eight OpenAPI documents and ninety derived artifacts were removed from this repository on 2026-08-30. They were **Elsevier's Pure product contract**, not TU/e's:

- `info.title` read `Pure API` / `Pure activity <Resource> API`
- `info.contact.email` was `pure-support@elsevier.com`
- `servers` was the relative `/ws/api` — no host at all, so a hostname-based ownership check was blind to it
- nine other universities in this catalog shipped the byte-equivalent document

One vendor contract split by tag into thirty-seven files is thirty-seven times the apparent footprint for one thing TU/e did not write. Removed with it: 73 Postman/OpenCollection files, 3 JSON Schemas, 3 JSON Structures, 3 examples, 2 Spectral rulesets, a vocabulary, a JSON-LD context, an authentication profile, an agentic-access profile and a capability map — every one of them derived from that spec and inheriting its provenance.

**The tenant relationships were not deleted.** They are real institutional facts and they are recorded above. Removing a misattribution is not the same as erasing a relationship.

## Domain-standard conformance (Kin Score `education` regime)

Probed live, recorded with evidence, reward-only: [conformance/eindhoven-university-of-technology-conformance.yml](conformance/eindhoven-university-of-technology-conformance.yml)

- **oai-pmh** — conformant. Verified by real harvest, not link presence.
- **saml** — conformant. TU/e EntityDescriptor present in the SURFconext federation metadata.
- Probed and **not** found, so recorded as measured absences rather than silence: `orcid` (CERIF person records carry ScopusAuthorID, no ORCID), `shibboleth` (the IdP is Entra ID, not Shibboleth), `lti`, `datacite` (4TU consortium's, not TU/e's), and OOAPI (TU/e is a named SURF participant but no public endpoint exists).

## Measured absences

These were probed and do not resolve in DNS — they are not gated, they do not exist: `data.tue.nl`, `api.tue.nl`, `developer.tue.nl`, `opendata.tue.nl`, `ooapi.tue.nl`, `api.ooapi.tue.nl`, `idp.tue.nl`, `login.tue.nl`, `sts.tue.nl`, `sis.tue.nl`, `mytimetable.tue.nl`, `rooster.tue.nl`.

- `purefaq.tue.nl` returns TU/e's own **"Off-site access blocked"** page — VPN/campus-only. It was a Documentation pointer in the June 2026 profile; it is now recorded as coverage evidence and removed as a pointer, because a pointer nobody outside the campus can read is not a pointer.
- `osiris.tue.nl` is a Caci Osiris SPA shell; its own CSP names the vendor backend `rontw.osiris-student.nl`.
- `tue.on.worldcat.org` is an OCLC WorldCat Discovery SPA shell.
- `github.com/TUEIndhoven` resolves but holds **zero public repositories**. Departmental research-group orgs exist (`tue-datastewards`, `tue-robotics`, `tue-mdse`, `tue-aga`, `TUe-ICTLab`, `3DCP-TUe`) but there is no institutional API programme behind them.
- The "Eindhoven Open Data" Opendatasoft portal belongs to the **municipality** of Eindhoven, not the university, and is excluded.

## Plans / Rate Limits / FinOps

- Plans: [plans/eindhoven-university-of-technology-plans-pricing.yml](plans/eindhoven-university-of-technology-plans-pricing.yml)
- Rate Limits: [rate-limits/eindhoven-university-of-technology-rate-limits.yml](rate-limits/eindhoven-university-of-technology-rate-limits.yml)
- FinOps: [finops/eindhoven-university-of-technology-finops.yml](finops/eindhoven-university-of-technology-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-30

## Common Properties

- Website: https://www.tue.nl/en/
- Research Repository: https://research.tue.nl/ (Elsevier Pure, tenant)
- Research Repository: https://data.4tu.nl/ (4TU.ResearchData Figshare consortium)
- Identity Federation: https://metadata.surfconext.nl/idps-metadata.xml
- Course Catalog: https://educationguide.tue.nl/ (rendered guide; no public API)
- AI Policy: https://www.tueindhoven.ai/education/guidelines/index.html
- Terms of Service: https://www.tue.nl/en/storage/disclaimer
- Privacy Policy: https://www.tue.nl/en/our-university/about-the-university/support-services/library-and-information-services/privacy
- GitHub: https://github.com/TUEIndhoven
- GitHub Organization: https://github.com/tue-datastewards
- LinkedIn: https://www.linkedin.com/school/eindhoven-university-of-technology/
- Review: [review.yml](review.yml)

## Notes

- Every URL in this profile was probed on 2026-08-30 and its status code recorded in `apis.yml` under `x-coverage.evidence`. Status codes, not link presence.
- No endpoints were fabricated. A university that publishes nothing institution-authored, and says so, is a correct profile — not a failed one.
- A correction that lowers this repository's Kin Score is the pipeline working. The June 2026 score was earned by Elsevier's engineering.

## Maintainers

- Kin Lane — kin@apievangelist.com
