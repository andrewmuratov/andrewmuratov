<div align="center">

# Andrew Muratov

### Computer Science @ UTM · Creator of Gapwise · Software, Security & Systems

Computer Science student at the **University of Toronto Mississauga** building privacy-conscious software, deterministic systems, developer platforms, and native applications. I care most about work where **correctness, security boundaries, data provenance, and user experience** all matter at the same time.

[![Portfolio](https://img.shields.io/badge/Portfolio-donotdisconnect.online-111111?style=for-the-badge)](https://donotdisconnect.online)
[![Gapwise](https://img.shields.io/badge/Gapwise-gapwise.ca-0A84FF?style=for-the-badge)](https://gapwise.ca)
[![Gapwise GitHub](https://img.shields.io/badge/GitHub-Gapwise--for--UTM-111111?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Gapwise-for-UTM)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0007--0561--2945-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0007-0561-2945)

[**Portfolio**](https://donotdisconnect.online) · [**Gapwise**](https://gapwise.ca) · [**Developers**](https://gapwise.ca/developers) · [**Docs**](https://docs.gapwise.ca) · [**Data**](https://data.gapwise.ca) · [**AI**](https://ai.gapwise.ca) · [**Status**](https://status.gapwise.ca)

</div>

---

## About

I study Computer Science at **UTM** and am especially interested in **information security, software architecture, developer tooling, deterministic systems, and applied mathematics**.

My main project is **Gapwise**, but I also work on web and native application development, open developer infrastructure, small research projects, Linux tooling, and technical writing. I prefer systems with explicit contracts, conservative failure modes, and clear ownership of truth over software that hides uncertainty behind polished output.

---

## Gapwise

> **Timetable intelligence for University of Toronto students, with a first-party campus map, routing, and open-data layer focused on UTM.**

I created **[Gapwise](https://gapwise.ca)** to turn a timetable into a usable day: what comes next, how much time is actually free between classes, where a student can realistically go, and when they need to leave.

Timetable identity supports **UTM, UTSG, UTSC, and mixed-campus schedules**. The current first-party campus map, routing graph, places layer, and open campus-data model are deliberately **UTM-focused** rather than pretending equivalent coverage exists at every campus.

The architecture follows one rule:

> **Canonical facts and deterministic calculations have an owner. Interfaces consume those contracts instead of inventing parallel truth.**

That principle carries across the web app, native clients, API and SDKs, open data, AI/MCP integration, documentation, and status infrastructure.

### Gapwise ecosystem

| Repository | Role | Current direction |
| --- | --- | --- |
| **[`gapwise`](https://github.com/Gapwise-for-UTM/gapwise)** | Core web/PWA, timetable intelligence, deterministic routing/planning, public API, OpenAPI, SDK source | Canonical product and developer-platform contracts |
| **[`android`](https://github.com/Gapwise-for-UTM/android)** | Native Android client | Kotlin + Jetpack Compose |
| **[`ios`](https://github.com/Gapwise-for-UTM/ios)** | Native iOS client | Swift + SwiftUI |
| **[`ai`](https://github.com/Gapwise-for-UTM/ai)** | Permissioned AI integration boundary | OAuth + MCP with bounded delegated context |
| **[`data`](https://github.com/Gapwise-for-UTM/data)** | Canonical public UTM campus facts | Schemas, geometry, provenance, validation, routing inputs |
| **[`docs`](https://github.com/Gapwise-for-UTM/docs)** | Public developer documentation | API, SDK, architecture, security, data and AI documentation |
| **[`status`](https://github.com/Gapwise-for-UTM/status)** | Independent operational surface | Service health and incident communication |

<div align="center">

`privacy-first` · `local-first` · `deterministic` · `source-backed` · `fail honestly` · `open contracts`

</div>

### Developer platform

- **Public API:** [api.gapwise.ca/v1](https://api.gapwise.ca/v1)
- **OpenAPI:** [api.gapwise.ca/openapi.json](https://api.gapwise.ca/openapi.json)
- **TypeScript SDK:** `@gapwise/sdk`
- **Python SDK:** `gapwise`
- **Developer docs:** [docs.gapwise.ca](https://docs.gapwise.ca)
- **Open campus data:** [data.gapwise.ca](https://data.gapwise.ca)
- **AI / MCP:** [ai.gapwise.ca](https://ai.gapwise.ca)
- **Service status:** [status.gapwise.ca](https://status.gapwise.ca)

---

## Engineering

### Languages

**TypeScript · JavaScript · Python · Kotlin · Swift · SQL · Bash**

### Platforms & tools

**React · TanStack · Next.js · Jetpack Compose · SwiftUI · Android · iOS · PostgreSQL · Supabase · OpenAPI · MapLibre · GitHub Actions · Vercel · Linux**

### What I optimize for

- clear **security and trust boundaries**;
- deterministic behavior where correctness matters;
- explicit **provenance and uncertainty** for real-world data;
- useful guest/local-first behavior before requiring accounts or cloud state;
- stable public interfaces and versioned contracts;
- accessible, responsive interfaces that do not sacrifice technical rigor;
- failure states that are visible and honest rather than silently guessed around.

---

## Beyond Gapwise

My broader work includes **mathematics, science-fair projects, research experiments, technical writing, and software tooling**. The best overview is on my portfolio:

<div align="center">

[![Open Portfolio](https://img.shields.io/badge/Open_Portfolio-donotdisconnect.online-111111?style=for-the-badge)](https://donotdisconnect.online)

</div>

I also maintain an **[ORCID record](https://orcid.org/0009-0007-0561-2945)** for research-related work.

---

<div align="center">

### Build useful systems. Keep the boundaries clear.

[**Portfolio →**](https://donotdisconnect.online) · [**Gapwise →**](https://gapwise.ca) · [**GitHub organization →**](https://github.com/Gapwise-for-UTM)

</div>
