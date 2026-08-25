<div align="center">

<img src="./assets/profile-header.svg" width="100%" alt="Andrew Muratov — Computer Science at the University of Toronto Mississauga; security, privacy, systems, software architecture, and the Gapwise ecosystem in blue, white, and purple" />

<br />

[![Gapwise](https://img.shields.io/badge/Gapwise-gapwise.ca-4EA7FE?style=for-the-badge&logo=vercel&logoColor=white)](https://gapwise.ca)
[![Developer Docs](https://img.shields.io/badge/Developer_Docs-docs.gapwise.ca-161B22?style=for-the-badge&logo=readthedocs&logoColor=white)](https://docs.gapwise.ca)
[![Gapwise AI](https://img.shields.io/badge/Gapwise_AI-ai.gapwise.ca-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white)](https://ai.gapwise.ca/api/health)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0007--0561--2945-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0007-0561-2945)

</div>

## About

I'm a Computer Science student at the **University of Toronto Mississauga** focused on information security, privacy, systems, and software architecture.

I like building software where the trust boundary is visible: source-of-truth data stays separate from derived calculations, uncertainty stays explicit, and higher-level interfaces do not quietly invent facts. Most of my current engineering work is concentrated in **Gapwise** and the infrastructure around it.

---

## Gapwise ecosystem

<table>
<tr>
<td width="33%" valign="top">

### [Gapwise](https://github.com/andrewmuratov/gapwise)
**Core product + campus-intelligence platform**

A privacy-first UTM student app that turns a local ACORN `.ics` export into timetable context, route-aware gap planning, leave-by timing, campus navigation, Day Replay, and deterministic campus intelligence.

**[Live app](https://gapwise.ca)** · **[Developers](https://gapwise.ca/developers)** · **[Source](https://github.com/andrewmuratov/gapwise)**

</td>
<td width="33%" valign="top">

### [Gapwise Docs](https://github.com/andrewmuratov/gapwise-docs)
**Public developer documentation**

The official documentation surface for the Gapwise UTM API, OpenAPI 3.1 contract, platform semantics, provenance and uncertainty model, plus the JavaScript/TypeScript and Python SDK surfaces.

**[Docs](https://docs.gapwise.ca)** · **[API](https://api.gapwise.ca/v1)** · **[OpenAPI](https://api.gapwise.ca/openapi.json)**

</td>
<td width="33%" valign="top">

### [Gapwise AI](https://github.com/andrewmuratov/gapwise-ai)
**Permissioned MCP integration layer**

A provider-neutral Model Context Protocol service for explicitly delegated student context. Gapwise remains the source of truth for schedules, routing, and gap calculations while assistants reason over bounded, permissioned data.

**[Service](https://ai.gapwise.ca/api/health)** · **[MCP](https://ai.gapwise.ca/api/mcp)** · **[Source](https://github.com/andrewmuratov/gapwise-ai)**

</td>
</tr>
</table>

<div align="center">

**One system, three surfaces:** product truth in **blue**, developer documentation in **white**, and the permissioned AI layer in **purple**.

</div>

---

## How I build

- **Privacy first.** Minimize sensitive data, keep local processing local when possible, and make optional cloud features explicit.
- **Deterministic facts before inference.** Timetable arithmetic, routes, budgets, and leave-by calculations belong in tested domain logic, not model guesswork.
- **Provenance and uncertainty matter.** Unknown, approximate, inferred, and verified states should stay distinguishable all the way to the interface.
- **Failure behavior is part of the feature.** Authentication, authorization, accessibility, degraded routing, stale data, and partial availability deserve deliberate semantics.

### Working stack

`TypeScript` · `React` · `Next.js` · `TanStack` · `Python` · `PostgreSQL / Supabase` · `MapLibre` · `Bun` · `Node.js` · `Linux` · `Vercel`

---

## Current direction

I'm strengthening my foundations in **algorithms, systems, cryptography, discrete mathematics, and rigorous software engineering** while continuing to push Gapwise from a student project toward a coherent, inspectable platform.

> **Make useful things. Minimize sensitive data. Keep the source of truth clear. Test the failure modes.**

---

<details>
<summary><strong>GitHub activity</strong></summary>
<br />

<div align="center">

<img src="./metrics.svg" width="100%" alt="Andrew Muratov GitHub activity metrics" />

</div>

</details>

---

<div align="center">

**[gapwise.ca](https://gapwise.ca)** · **[docs.gapwise.ca](https://docs.gapwise.ca)** · **[ai.gapwise.ca](https://ai.gapwise.ca/api/health)** · **[GitHub](https://github.com/andrewmuratov)** · **[ORCID](https://orcid.org/0009-0007-0561-2945)**

<sub>Toronto, Canada · Security, privacy, systems, and software.</sub>

</div>
