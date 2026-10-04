<div align="center">

# Andrew Muratov

### Computer Science @ University of Toronto · Information Security, Systems & Mathematics · Founder & Lead Engineer of Gapwise

I’m a first-year **Computer Science student at the University of Toronto Mississauga** and the founder and lead engineer of **Gapwise**, a free and open-source multi-university timetable, campus navigation, and student planning platform supporting **27 universities and 67 campuses across Canada and the United States**.

[![Portfolio](https://img.shields.io/badge/Portfolio-donotdisconnect.online-111111?style=for-the-badge)](https://donotdisconnect.online)
[![Gapwise](https://img.shields.io/badge/Gapwise-gapwise.ca-0A84FF?style=for-the-badge)](https://gapwise.ca)
[![Gapwise GitHub](https://img.shields.io/badge/GitHub-GapwiseHQ-111111?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GapwiseHQ)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0007--0561--2945-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0007-0561-2945)

[**Portfolio**](https://donotdisconnect.online) · [**Gapwise**](https://gapwise.ca) · [**Developers**](https://gapwise.ca/developers) · [**Docs**](https://docs.gapwise.ca) · [**Data**](https://data.gapwise.ca) · [**AI**](https://ai.gapwise.ca) · [**Status**](https://status.gapwise.ca)

</div>

---

## About

I study **Computer Science at the University of Toronto Mississauga**, with a strong interest in **information security, mathematics, systems, formal reasoning, and software architecture**.

My work is centered on software where correctness and trust boundaries matter: deterministic planning and routing, source-backed real-world data, privacy-preserving application design, APIs and SDKs, native clients, developer tooling, and infrastructure.

I prefer systems with explicit contracts, conservative failure modes, clear ownership of truth, visible uncertainty, and privacy and security built into the architecture rather than added afterward.

---

## Gapwise

> **Free and open-source multi-university timetable, campus navigation, and student planning infrastructure.**

I created **[Gapwise](https://gapwise.ca)** around a simple problem: a university timetable tells you when class happens, but not how to use the time around it.

Gapwise turns a schedule into a campus-aware model of the day: **what comes next, how much usable time exists between classes, where a student can realistically go, when they need to leave, and which campus the schedule belongs to.**

Today, Gapwise has a canonical registry of **27 universities and 67 campuses across Canada and the United States**. Timetable support, campus inference, university-specific editions, campus data, API/SDK contracts, documentation, AI/MCP discovery, and service monitoring are all built around that shared registry.

### Supported universities

**Canada:** University of Toronto, University of British Columbia, McGill University, University of Waterloo, Carleton University, Toronto Metropolitan University, Queen’s University, Wilfrid Laurier University, York University, McMaster University, Western University, University of Guelph, University of Ottawa, and Brock University.

**United States:** Carnegie Mellon University, University of California, Berkeley, New York University, Massachusetts Institute of Technology, Stanford University, University of Pennsylvania, Cornell University, Dartmouth College, Brown University, Columbia University, Princeton University, Yale University, and Harvard University.

Multi-campus universities are modeled as one university with canonical campus IDs and campus-aware routing/selection rather than requiring a separate public hostname for every campus. Dedicated campus editions are kept where they are useful, such as U of T’s Mississauga, St. George, and Scarborough editions and UBC’s Vancouver and Okanagan editions.

### What Gapwise includes

- university-aware timetable import, parsing, and campus inference
- gap detection, usable-time calculations, and leave-by planning
- canonical university/campus registry shared across the platform
- campus maps backed by source-traceable real-world data
- building search, building metadata, entrances, and pedestrian routing where verified data is available
- explicit partial-coverage handling instead of fabricated map or routing data
- public API and OpenAPI specification
- TypeScript and Python SDKs
- MCP / AI tooling for university, campus, timetable, building, and routing discovery
- native Android and iOS projects
- public documentation, contribution tooling, SEO/discovery surfaces, and service monitoring

Navigation coverage is **campus-dependent**: established campuses have richer building, entrance, and routing data, while newer or secondary campuses may currently have partial coverage. Gapwise keeps those limitations explicit rather than inventing geometry or routes.

### Gapwise ecosystem

| Repository | Role |
| --- | --- |
| **[`gapwise`](https://github.com/GapwiseHQ/gapwise)** | Canonical web/PWA, timetable intelligence, campus inference, planning, routing, public API, OpenAPI, and SDK source |
| **[`data`](https://github.com/GapwiseHQ/data)** | Canonical university/campus datasets, schemas, provenance, validation, OpenStreetMap-derived geometry, and contribution tooling |
| **[`android`](https://github.com/GapwiseHQ/android)** | Native Android client built with Kotlin and Jetpack Compose |
| **[`ios`](https://github.com/GapwiseHQ/ios)** | Native iOS client built with Swift and SwiftUI |
| **[`ai`](https://github.com/GapwiseHQ/ai)** | MCP/OAuth boundary and registry-aware AI integration |
| **[`docs`](https://github.com/GapwiseHQ/docs)** | API, SDK, architecture, security, data, routing, timetable, and AI documentation |
| **[`status`](https://github.com/GapwiseHQ/status)** | Service-health monitoring and incident communication |

<div align="center">

`privacy-first` · `local-first` · `deterministic` · `source-backed` · `explicit trust boundaries`

</div>

### Developer surfaces

- **App:** [gapwise.ca](https://gapwise.ca)
- **Public API:** [api.gapwise.ca/v1](https://api.gapwise.ca/v1)
- **OpenAPI:** [api.gapwise.ca/openapi.json](https://api.gapwise.ca/openapi.json)
- **Developer docs:** [docs.gapwise.ca](https://docs.gapwise.ca)
- **Campus data:** [data.gapwise.ca](https://data.gapwise.ca)
- **SDK:** [sdk.gapwise.ca](https://sdk.gapwise.ca)
- **MCP:** [mcp.gapwise.ca](https://mcp.gapwise.ca)
- **AI:** [ai.gapwise.ca](https://ai.gapwise.ca)
- **Service status:** [status.gapwise.ca](https://status.gapwise.ca)

The same canonical university/campus model is carried through the app, data, timetable adapters, campus inference, API, SDKs, MCP, AI, documentation, status monitoring, SEO, and machine-readable discovery surfaces.

The architecture follows one rule:

> **Canonical facts and deterministic calculations have an owner. Interfaces consume those contracts instead of inventing parallel truth.**

---

## Engineering

### Languages

**TypeScript · JavaScript · Python · Kotlin · Swift · SQL · Bash**

### Platforms & tools

**React · TanStack · MapLibre · Supabase · Bun · Vercel · Cloudflare · Resend · OpenAPI · MCP · Jetpack Compose · SwiftUI · PostgreSQL · GitHub Actions · Linux**

### What I optimize for

- explicit **security and trust boundaries**
- deterministic behavior where correctness matters
- clear **provenance and uncertainty** for real-world data
- local-first behavior before requiring accounts or cloud state
- stable public interfaces and versioned contracts
- maintainable multi-platform architecture
- accessible interfaces that do not sacrifice technical rigor
- failures that are visible and honest rather than silently guessed around

---

## Beyond Gapwise

My broader interests include **computer science, information security, mathematics, research, technical writing, and software tooling**.

<div align="center">

[![Open Portfolio](https://img.shields.io/badge/Open_Portfolio-donotdisconnect.online-111111?style=for-the-badge)](https://donotdisconnect.online)

[**Portfolio →**](https://donotdisconnect.online) · [**Gapwise →**](https://gapwise.ca) · [**GitHub organization →**](https://github.com/GapwiseHQ)

</div>
