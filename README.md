# Beyond Imagination

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

Beyond Imagination, Inc. is a Los Angeles based robotics and artificial intelligence company founded in January 2018 by Dr. Harry Kloor and Dr. Ray Kurzweil. It builds general-purpose humanoid robots — the **Beomni** platform — and the AI software stack that runs them: **AURA** (Adaptive Unified Robotic/Human Administrator, a universal operating system coordinating robots, humans and infrastructure), **ARCANA** (an LLM-free synthetic brain architecture), **Expert Minds** (modular AI job modules for specialized roles), and **Hive Mind Intelligence** (fleet-wide skill sharing through a shared cloud memory).

Beomni is a wheeled humanoid with an articulated upper body and dexterous hands, operable through VR headsets and haptic gloves or autonomously. The company has run pilot programs in commercial kitchens, laboratory work, healthcare and pharmaceutical manufacturing, and announced a manufacturing partnership with the Korean electronics manufacturer Dreamtech.

## API surface

**As of 2026-08-02 Beyond Imagination publishes no public API.** Full contract discovery was run against every published and candidate host and found nothing:

- No developer portal, API reference, or documentation site
- No OpenAPI / Swagger / AsyncAPI / GraphQL contract (`/openapi.json`, `/swagger.json`, `/api-docs` all 404)
- No MCP server and no A2A agent card (`/.well-known/agent-card.json` and `/.well-known/agent.json` both 404)
- No `/.well-known/` document of any kind, including `security.txt`
- No first-party SDK on npm, PyPI, crates.io or RubyGems
- No first-party GitHub organization (`github.com/Beyond-Imagination` is an unrelated Korean student developer group)
- No `api.`, `developer.`, `docs.`, `app.` or `trust.` subdomain resolves

The negative probe record is kept in [`well-known/beyond-imagination-well-known.yml`](well-known/beyond-imagination-well-known.yml) so a later pass does not repeat it blindly.

## Links

- Website — https://www.beyondimagination.com/
- Products — https://www.beyondimagination.com/products/
- AI technology — https://www.beyondimagination.com/ai/
- Pilot programs — https://www.beyondimagination.com/pilot-programs/
- Founders — https://www.beyondimagination.com/founders/
- News — https://www.beyondimagination.com/news/
- LinkedIn — https://www.linkedin.com/company/beyond-imagination-inc
- Forge Global (secondary market) — https://forgeglobal.com/beyond-imagination_stock/
