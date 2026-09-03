<div align="center">

# Andrew Muratov

### Software · Cybersecurity · Platform Engineering

**Computer Science at the University of Toronto Mississauga.**  
Creator and lead engineer of **[Gapwise](https://gapwise.ca)** — a privacy-first campus-intelligence ecosystem spanning student software, deterministic routing and gap planning, public APIs and published SDKs, open campus data, permissioned AI, developer documentation, native mobile clients, and independent service monitoring.

[![Gapwise](https://img.shields.io/badge/Gapwise-gapwise.ca-4EA7FE?style=for-the-badge)](https://gapwise.ca)
[![GitHub](https://img.shields.io/badge/GitHub-andrewmuratov-111111?style=for-the-badge&logo=github)](https://github.com/andrewmuratov)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0007--0561--2945-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0007-0561-2945)

**[App](https://gapwise.ca)** · **[Data](https://data.gapwise.ca)** · **[AI](https://ai.gapwise.ca)** · **[Docs](https://docs.gapwise.ca)** · **[Status](https://status.gapwise.ca)** · **[API](https://api.gapwise.ca/v1)**

</div>

---

## What I build

My work sits at the intersection of **software engineering, cybersecurity and privacy engineering, platform architecture, data systems, developer tooling, mobile engineering, and AI integration**.

Gapwise is the main expression of that work: one product identity split across deliberately separate execution and trust boundaries. The web app owns canonical student-state behavior and deterministic campus calculations; the API and published SDKs expose reusable campus intelligence; Data documents provenance and schemas; Mobile consumes the same contracts natively; AI adds a permissioned OAuth/MCP boundary; Docs describes released behavior; and Status communicates operational health independently.

I care about systems that are useful without being careless about user data: local-first flows where possible, explicit permission boundaries, deterministic logic for safety-critical calculations, visible uncertainty, small public interfaces, and infrastructure that fails honestly instead of pretending to know more than it does.

---

## Gapwise ecosystem

| Surface | What it does |
| --- | --- |
| **[Gapwise](https://github.com/andrewmuratov/gapwise)** | Core web/PWA, timetable intelligence, Today, deterministic gap planning, campus routing, leave-by timing, encrypted sync, public API, OpenAPI contract, and SDK source |
| **[Gapwise Mobile](https://github.com/andrewmuratov/gapwise-mobile)** | Native iOS and Android client built on the canonical Gapwise product and platform contracts |
| **[Gapwise AI](https://github.com/andrewmuratov/gapwise-ai)** | Permissioned OAuth/MCP integration layer for explicitly delegated student context and bounded AI actions |
| **[Gapwise Data](https://github.com/andrewmuratov/gapwise-data)** | Open data and provenance layer for the campus map, including collection, schemas, verification, attribution, and reuse |
| **[Gapwise Docs](https://github.com/andrewmuratov/gapwise-docs)** | Developer documentation for the API, SDKs, platform semantics, security boundaries, and AI/MCP integration |
| **[Gapwise Status](https://github.com/andrewmuratov/gapwise-status)** | Independent service-health, monitoring-freshness, and incident-history surface for the ecosystem |

The architectural rule across the ecosystem is straightforward: **Gapwise owns the facts and deterministic calculations; every other interface consumes or explains those contracts instead of inventing a parallel source of truth.**

### Published developer packages

The first public Gapwise SDK release is live in both ecosystems:

```bash
npm install @gapwise/sdk@0.1.0
python -m pip install gapwise==0.1.0
```

The Python package was released through PyPI Trusted Publishing and independently verified from a clean environment against the production Gapwise API. Both SDKs target the canonical `https://api.gapwise.ca/v1` contract.

---

## Engineering areas

**Cybersecurity & privacy**  
OAuth boundaries · explicit delegation · browser-side encryption · Supabase RLS · secret separation · abuse protection · threat modeling · fail-closed behavior · responsible disclosure

**Platform & backend**  
TypeScript · API design · OpenAPI 3.1 · SDK design · Python packaging · PostgreSQL · Supabase · Vercel · Cloudflare · Resend · GitHub Actions · OIDC trusted publishing

**Product & frontend**  
React · TanStack Start/Router · Next.js · React Native · Expo · Astro · accessibility · responsive UI · PWA architecture

**Data & campus systems**  
MapLibre · GeoJSON · routing graphs · provenance · schema design · deterministic planning · uncertainty modeling · reusable public datasets

**AI integration**  
Model Context Protocol · OAuth-protected MCP · permissioned context delegation · bounded mutations · grounding deterministic data for assistants

**Languages & environment**  
TypeScript · JavaScript · Python · SQL · Linux

---

## Current focus

I am continuing to harden Gapwise as a cohesive platform rather than treating each surface as a separate demo: improving real-device validation, campus-data quality, accessibility evidence, API/SDK release quality, privacy and security boundaries, monitoring, documentation, and the connections between the web, mobile, data, AI, docs, and operational layers.

<div align="center">

**Security · privacy · systems · software.**

[Gapwise →](https://gapwise.ca)

</div>
