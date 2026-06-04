# Eindhoven University of Technology (eindhoven-university-of-technology)

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
