# Hoplite

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

Hoplite is a cloud coding-agent platform (Y Combinator S26). You connect a GitHub repository, describe a task in a thread, and an autonomous agent does the work inside an isolated, cloned dev environment (a "sandbox") — reading and editing code, running your test suite, starting your dev server, verifying changes in a built-in browser, and opening a pull request when it's done. Runs stream live into the thread with inline approvals for sensitive actions, a diff view, and a PR rail that tracks checks, reviews, and unresolved comments. Hoplite runs a lineup of OpenAI (GPT-5.6 family, GPT-5.3 Codex) and Anthropic (Fable 5, Opus 4.8, Sonnet 4.6, Haiku 4.5) models, bills on prepaid credits via Stripe, and integrates with GitHub, Slack, Linear, and customer-hosted MCP servers. It also exposes its own hosted MCP server and a CLI so you can drive Hoplite from Claude Code, Cursor, or any MCP client. Founded 2026 in San Francisco by Ryan Morrissey and Bence Redmond.

**Areas:** Company · Coding Agents · Developer Tools · AI Agents · Cloud Development Environments · DevOps · MCP · Pull Requests · Software Automation · GitHub

## Hoplite on APIs.io

Everything profiled for Hoplite is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/hoplite/](https://apis.io/providers/hoplite/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Hoplite API](https://apis.io/apis/hoplite/hoplite-api/) — The Hoplite platform API at api.hoplite.sh. Documented through the developer docs (no public OpenAPI published as of this profiling). Surfaces include…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Hoplite Webhooks](https://apis.io/asyncapis/hoplite/hoplite-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [hoplite](https://apis.io/servers/hoplite/hoplite/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Hoplite Authentication](https://apis.io/security/hoplite/hoplite-authentication/)
- [Hoplite Domain Security](https://apis.io/security/hoplite/hoplite-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://hoplite.sh)
- [Documentation](https://hoplite.sh/docs)
- [Getting started](https://hoplite.sh/docs/getting-started)
- [Pricing](https://hoplite.sh/pricing)
- [Sign up](https://hoplite.sh/signup)
- [Blog](https://hoplite.sh/blog)
- [Status](https://status.hoplite.sh)

## API Evangelist rating

**Kin Score 36.3** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 39.0 |
| Contract governance | 4.5 |
| Operational transparency | 23.7 |
| Developer ergonomics | 52.4 |
| Access clarity | 23.7 |

**Agent readiness 47.8** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | documented (partial credit) |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 16.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/hoplite/](https://apis.io/providers/hoplite/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Hoplite: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/hoplite/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
