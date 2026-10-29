# Eindhoven University of Technology

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

Eindhoven University of Technology (TU/e) is a public technical university in Eindhoven, the Netherlands, and one of the four institutions of the 4TU federation. It operates no public developer portal, publishes no institution-authored API contract, and offers no self-serve API keys — and this profile says so rather than padding the gap. Everything machine-readable that carries the TU/e name is a deployment of somebody else's software: the TU/e Research Portal and its Pure Web Service REST API are Elsevier Pure 5.35.x running at pure.tue.nl, the student mobile app at osiris.tue.nl is Caci Osiris, library discovery is OCLC WorldCat, and research datasets are minted through the 4TU.ResearchData Figshare consortium. What TU/e genuinely operates on its own domain is narrower and real: a live, fully conformant OAI-PMH 2.0 harvesting endpoint at pure.tue.nl/ws/oai serving seven metadata formats and the OpenAIRE CERIF 1.2 CRIS profile, and a SAML 2.0 identity-provider entity registered in the SURFconext federation and so reachable through eduGAIN. Thirty-seven OpenAPI documents previously attributed to TU/e in this repository were Elsevier's Pure product contract (info.title "Pure …", contact pure-support@elsevier.com, relative servers "/ws/api", shipped identically by nine other universities) and have been removed; the tenant relationships they described are recorded here instead. Departmental research groups publish open source across many separate GitHub organizations, but the university runs no single official engineering org.

**Areas:** University · Higher Education · Education · Technical University · Netherlands · Europe · 4TU · Research Data · Research Information · Research Repository · Identity Federation · OAI-PMH

## Eindhoven University of Technology on APIs.io

Everything profiled for Eindhoven University of Technology is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/eindhoven-university-of-technology/](https://apis.io/providers/eindhoven-university-of-technology/)** — or go straight to one of the APIs or properties below.

### APIs (3)

- [TU/e Research Portal OAI-PMH](https://apis.io/apis/eindhoven-university-of-technology/research-oai-pmh/) — Live OAI-PMH 2.0 harvesting interface for the TU/e Research Portal, served by Elsevier Pure at TU/e's own pure.tue.nl. Verified with a real harvest, not…
- [TU/e Pure Web Service (Elsevier Pure deployment)](https://apis.io/apis/eindhoven-university-of-technology/pure-web-service/) — TU/e's deployment of the Elsevier Pure Web Service REST API, the research-information (CRIS) interface behind the TU/e Research Portal. The deployment's own…
- [TU/e SAML Identity Provider (SURFconext / eduGAIN)](https://apis.io/apis/eindhoven-university-of-technology/surfconext-saml-idp/) — TU/e's SAML 2.0 identity-provider entity as published in the SURFconext federation metadata, which feeds eduGAIN. The EntityDescriptor carries…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Vocabulary (1)

The provider's domain terms, defined.

- [TU/e Pure Web Service Vocabulary](https://apis.io/vocabularies/eindhoven-university-of-technology/eindhoven-university-of-technology-vocabulary/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Eindhoven University Of Technology Domain Security](https://apis.io/security/eindhoven-university-of-technology/eindhoven-university-of-technology-domain-security/)
- [Eindhoven University Of Technology Vulnerability Disclosure](https://apis.io/security/eindhoven-university-of-technology/eindhoven-university-of-technology-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Eindhoven University Of Technology Plans Pricing](https://apis.io/plans/eindhoven-university-of-technology/eindhoven-university-of-technology-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Eindhoven University Of Technology Rate Limits](https://apis.io/rate-limits/eindhoven-university-of-technology/eindhoven-university-of-technology-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Eindhoven University Of Technology Finops](https://apis.io/finops/eindhoven-university-of-technology/eindhoven-university-of-technology-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.tue.nl/en/)
- [Documentation](https://pure.tue.nl/ws/api/documentation/index.html)
- [Terms of service](https://www.tue.nl/en/storage/disclaimer)
- [Privacy policy](https://www.tue.nl/en/our-university/about-the-university/support-services/library-and-information-services/privacy)
- [GitHub](https://github.com/tue-datastewards)

## API Evangelist rating

**Kin Score 16.7** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 1.9 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 9.5 |
| Access clarity | 26.3 |

**Agent readiness 0.6** — human-only

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
| Rate Limit Signal | derived (partial credit) |
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

**Regulatory alignment 24.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/eindhoven-university-of-technology/](https://apis.io/providers/eindhoven-university-of-technology/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Eindhoven University of Technology: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/eindhoven-university-of-technology/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
