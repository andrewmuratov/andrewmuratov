<div align="center">

# Andrew Muratov

### Computer Science · Software Engineering · Cybersecurity · Platform Systems

**Computer Science student at the University of Toronto Mississauga** building privacy-conscious software, developer platforms, campus systems, and security-minded infrastructure.

Creator and lead engineer of **[Gapwise](https://gapwise.ca)** — a campus-intelligence platform for UTM spanning a student web app, deterministic routing and gap planning, public APIs and SDKs, open campus data, native mobile, permissioned AI, developer documentation, and independent service monitoring.

[![Gapwise](https://img.shields.io/badge/Gapwise-gapwise.ca-0A84FF?style=for-the-badge)](https://gapwise.ca)
[![GitHub](https://img.shields.io/badge/GitHub-andrewmuratov-111111?style=for-the-badge&logo=github&logoColor=white)](https://github.com/andrewmuratov)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0007--0561--2945-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0007-0561-2945)

**[App](https://gapwise.ca)** · **[Developers](https://gapwise.ca/developers)** · **[API](https://api.gapwise.ca/v1)** · **[Docs](https://docs.gapwise.ca)** · **[Data](https://data.gapwise.ca)** · **[AI](https://ai.gapwise.ca)** · **[Status](https://status.gapwise.ca)**

</div>

---

## About

I like building software where **product design, systems thinking, privacy, security, and infrastructure meet**.

My main project is Gapwise. What started as a way to make the time between classes more useful has grown into a connected software ecosystem with deliberately separated trust boundaries, reusable public platform contracts, native and web clients, open campus data, independent monitoring, and an AI integration layer that does not replace deterministic product logic.

The engineering principles I care about most are straightforward:

- **deterministic logic where correctness matters**;
- **local-first and data-minimizing flows where possible**;
- **explicit permission and trust boundaries**;
- **small, well-defined public interfaces**;
- **visible uncertainty instead of false confidence**;
- **systems that fail honestly and can be operated in the real world**.

---

## Flagship project — Gapwise

> **A privacy-first campus-intelligence ecosystem for UTM.**

Gapwise turns a student's timetable into practical campus context: what comes next, where to go, how long a route takes, how much time is actually usable between classes, when to leave, and whether a destination is realistically reachable before the next class.

The platform now includes:

| Surface | Role |
| --- | --- |
| **[gapwise](https://github.com/andrewmuratov/gapwise)** | Core web/PWA, timetable intelligence, Today, deterministic gap planning, routing, leave-by timing, account/sync features, public API, OpenAPI contract, and SDK source |
| **[gapwise-mobile](https://github.com/andrewmuratov/gapwise-mobile)** | Native iOS and Android client built with Expo and React Native |
| **[gapwise-ai](https://github.com/andrewmuratov/gapwise-ai)** | OAuth-protected MCP layer for explicitly delegated student context and bounded AI actions |
| **[gapwise-data](https://github.com/andrewmuratov/gapwise-data)** | Open campus-data, provenance, schemas, validation, attribution, and reuse |
| **[gapwise-docs](https://github.com/andrewmuratov/gapwise-docs)** | Public developer documentation for APIs, SDKs, security boundaries, data semantics, and AI/MCP integration |
| **[gapwise-status](https://github.com/andrewmuratov/gapwise-status)** | Independently deployed service-health, monitoring-freshness, and incident-history surface |

<div align="center">

**Web / PWA** → **deterministic platform contracts** → **API & SDKs**  
↙︎ **Mobile** · **Open Data** · **Permissioned AI** · **Docs** · **Status** ↘︎

</div>

The architectural rule is simple: **Gapwise owns canonical facts and deterministic calculations; other surfaces consume, expose, monitor, or explain those contracts instead of inventing parallel truth.**

### What it currently covers

- Browser-side ACORN `.ics` timetable import and guest-first usage
- Timetable intelligence and route-aware gap planning
- Today view, leave-by timing, arrival estimates, and transition protection
- Campus map, route confidence, and fail-closed step-free routing behavior
- “Can I go there?” two-leg destination feasibility checks
- Day Replay for browser-side simulation of a campus day
- Optional encrypted sync and account continuity
- Public campus API with an OpenAPI 3.1 contract
- Versioned campus building/place data with provenance and uncertainty metadata
- Official TypeScript and Python SDKs
- Native mobile client
- Permissioned OAuth/MCP integration for compatible assistants
- Independent public documentation, data, and operational-status surfaces
- Auth and transactional-email infrastructure, including an in-product mail workflow

---

## Public developer platform

Gapwise exposes deterministic campus intelligence through a public API rather than private student data.

```text
API       https://api.gapwise.ca/v1
OpenAPI   https://api.gapwise.ca/openapi.json
Docs      https://docs.gapwise.ca
Data      https://data.gapwise.ca
```

### SDKs

```bash
npm install @gapwise/sdk@0.1.1
python -m pip install gapwise==0.1.0
```

The TypeScript SDK is published for modern JavaScript runtimes and the Python SDK is published through PyPI Trusted Publishing. Both consume the canonical Gapwise public API contract.

---

## Engineering focus

<table>
<tr>
<td valign="top" width="50%">

### Security & privacy

OAuth and delegated authorization  
Supabase RLS and caller-scoped access  
Browser-side encryption  
Secret separation and safe client/server boundaries  
Abuse protection and fail-closed behavior  
Threat modeling and responsible disclosure

</td>
<td valign="top" width="50%">

### Platform & backend

TypeScript and API design  
OpenAPI 3.1 and SDK design  
PostgreSQL / Supabase  
Python packaging  
Vercel / Cloudflare / Resend  
GitHub Actions and OIDC publishing

</td>
</tr>
<tr>
<td valign="top" width="50%">

### Product & mobile

React and TanStack  
Next.js  
React Native / Expo  
MapLibre  
PWA architecture  
Accessibility and responsive interfaces

</td>
<td valign="top" width="50%">

### Data, systems & AI

GeoJSON and routing graphs  
Provenance and schema design  
Deterministic planning  
Uncertainty modeling  
Model Context Protocol  
Permissioned AI context and bounded mutations

</td>
</tr>
</table>

### Languages & daily environment

`TypeScript` · `JavaScript` · `Python` · `SQL` · `Linux`

---

## Current work

Right now I am focused on taking Gapwise from a broad, working ecosystem to a **more deeply validated and operationally mature platform**.

That means continuing to improve:

- real-device and cross-surface validation;
- campus routing, accessibility evidence, and data quality;
- privacy and security boundaries;
- CI, release engineering, and SDK publishing;
- documentation quality and source-of-truth consistency;
- monitoring and failure visibility;
- mobile parity with canonical product contracts;
- authenticated product workflows and transactional communication;
- the connection between web, mobile, data, AI, docs, and operations without duplicating core logic.

Gapwise is an **independent student software project** and is not affiliated with, endorsed by, or an official service of the University of Toronto.

---

<div align="center">

### Build useful systems. Keep the boundaries clear.

**Security · privacy · software · systems**

[**Explore Gapwise →**](https://gapwise.ca)

</div>
