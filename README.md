# Overwing

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

Overwing provides AI agent‑operated guardrails and decision layers for legacy business systems such as IBM i and SAP. Their Tower product decides whether each write is allowed, needs human review, or is rejected, and signs a receipt for every step. Guardrails check text before an agent sends it, and the platform offers open data on agents (Atlas) and product reachability (Beacon).

**Areas:** AI · Agents · Guardrails · LegacySystems · IBM · SAP

## Overwing on APIs.io

Everything profiled for Overwing is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/overwing-ai/](https://apis.io/providers/overwing-ai/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [Overwing Account API](https://apis.io/apis/overwing-ai/overwing-ai-account-api/) — Keys, usage, webhooks, identity
- [Overwing Atlas API](https://apis.io/apis/overwing-ai/overwing-ai-atlas-api/) — Overwing Atlas: open data on AI agents. Registry, user-agent lookups, datasets, and reports. Separate product, same API key.
- [Overwing Beacon API](https://apis.io/apis/overwing-ai/overwing-ai-beacon-api/) — Overwing Beacon: is a site reachable by agents? One paid lookup that checks robots.txt, llms.txt, MCP, A2A and OpenAPI and how the home page reads to a…
- [Overwing Billing API](https://apis.io/apis/overwing-ai/overwing-ai-billing-api/) — Plans and subscriptions (Stripe)
- [Overwing CAD API](https://apis.io/apis/overwing-ai/overwing-ai-cad-api/) — Overwing CAD: describe a mechanical part, get a parametric model and STEP and STL files. Paid per part over x402.
- [Overwing Evaluate API](https://apis.io/apis/overwing-ai/overwing-ai-evaluate-api/) — Score text against a rule set
- [Overwing Meta API](https://apis.io/apis/overwing-ai/overwing-ai-meta-api/) — Health and discovery
- [Overwing Onboarding API](https://apis.io/apis/overwing-ai/overwing-ai-onboarding-api/) — Self-serve account creation
- [Overwing Preflight API](https://apis.io/apis/overwing-ai/overwing-ai-preflight-api/) — Overwing Preflight: should an agent sign this Solana transaction? Simulates the unsigned transaction, compares what it would take from the wallet against…
- [Overwing Rule sets API](https://apis.io/apis/overwing-ai/overwing-ai-rule-sets-api/) — Prebuilt and custom rule sets
- [Overwing Tower API](https://apis.io/apis/overwing-ai/overwing-ai-tower-api/) — Overwing Tower: clearance for agents operating legacy systems. Typed operations, per-agent keys, policy decisions (auto / review / reject), human review,…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Overwing Agentic Access](https://apis.io/agentic-access/overwing-ai/overwing-ai-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [AtlasAgent](https://apis.io/schemas/overwing-ai/overwing-ai-atlas-agent/)
- [BeaconReport](https://apis.io/schemas/overwing-ai/overwing-ai-beacon-report/)
- [EvaluateRequest](https://apis.io/schemas/overwing-ai/overwing-ai-evaluate-request/)
- [Evaluation](https://apis.io/schemas/overwing-ai/overwing-ai-evaluation/)
- [PreflightRequest](https://apis.io/schemas/overwing-ai/overwing-ai-preflight-request/)
- [PreflightVerdict](https://apis.io/schemas/overwing-ai/overwing-ai-preflight-verdict/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Overwing Ai Context](https://apis.io/jsonld/overwing-ai/overwing-ai-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Overwing API Rules](https://apis.io/rules/overwing-ai/overwing-ai-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Overwing Authentication](https://apis.io/security/overwing-ai/overwing-ai-authentication/)
- [Overwing Domain Security](https://apis.io/security/overwing-ai/overwing-ai-domain-security/)
- [Overwing Trust Center](https://apis.io/security/overwing-ai/overwing-ai-trust-center/)
- [Overwing Vulnerability Disclosure](https://apis.io/security/overwing-ai/overwing-ai-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Overwing Plans Pricing](https://apis.io/plans/overwing-ai/overwing-ai-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://overwing.ai/)
- [API reference](https://overwing.ai/docs)
- [Pricing](https://overwing.ai/pricing)
- [Security](https://overwing.ai/security)
- [Terms of service](https://overwing.ai/terms)
- [Privacy policy](https://overwing.ai/privacy)

## API Evangelist rating

**Kin Score 53.8** — developing · rubric 0.28.0 · scored 2026-11-20

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 58.9 |
| Contract governance | 79.1 |
| Operational transparency | 9.5 |
| Developer ergonomics | 25.5 |
| Access clarity | 65.5 |

**Agent readiness 57.6** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | verified |
| Event Surface Described | — |
| Agent Skills | unknown |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | conformant |
| Dry Run Mode | yes |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 32.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/overwing-ai/](https://apis.io/providers/overwing-ai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Overwing: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/overwing-ai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
