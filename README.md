# Beyond Imagination

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
