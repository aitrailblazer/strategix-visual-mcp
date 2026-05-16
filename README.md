# StrategiX Visual MCP

Reproducible visual infrastructure for agents.

StrategiX Visual MCP turns contracts, reasoning, and source material into deterministic, auditable visual artifacts with fit reports, receipts, provenance, and searchable metadata.

## Identity

- Publisher: AITrailblazer
- Repository: `aitrailblazer/strategix-visual-mcp`
- Public page: `https://aitrailblazer.github.io/strategix-visual-mcp/`
- AITrailblazer MCP umbrella: `https://aitrailblazer.github.io/aitrailblazer-mcp/`
- MCP endpoint: `https://api.aitrailblazer.net/mcp`
- Tool prefix: `strategix_`
- Launch state: public-discoverable, API-key gated beta

## Positioning

StrategiX Visual MCP is not a diagram generator, canvas editor, Mermaid clone, or renderer backend.

It is a contract-first visual infrastructure layer for agent workflows.

## Core Artifact Chain

```text
contract -> render -> fit report -> receipt -> searchable artifact
```

## Output Classes

- diagrams
- architecture maps
- payment flows
- trust boundaries
- ERDs
- sequence flows
- dashboards
- scorecards
- charts
- visual reports
- self-contained HTML artifacts

## Access

`tools/list` is public for discovery. `strategix_` `tools/call` requires an authorized first-party API key during beta.

Public discovery, health, capabilities, and pricing metadata are available so registries and agents can inspect the product before execution access is approved.

## Canonical Tool Surface

Canonical product names use the `strategix_` family. Some beta endpoint aliases may remain visible during migration.

| Canonical tool | Purpose | Beta alias / note |
| --- | --- | --- |
| `strategix_visual_contract_create` | Create a normalized visual contract from source material, reasoning, or an artifact request. | Planned canonical create surface |
| `strategix_visual_contract_validate` | Validate canonical visual contracts before rendering. | `strategix_diagram_validate` |
| `strategix_contract_repair` | Repair a contract that fails validation while preserving the original source intent and artifact class. | Planned repair surface |
| `strategix_render_artifact` | Render validated contracts into deterministic visual artifacts with fit reports and receipt metadata. | `strategix_diagram_render` |
| `strategix_render_html_artifact` | Package contract, rendered artifact, source digest, fit report, receipt, and metadata into self-contained HTML. | `strategix_visual_spec_package` |
| `strategix_fit_report` | Check artifact fit against the source contract, visual class, viewport, and accessibility constraints. | Included in render/package outputs |
| `strategix_visual_audit` | Inspect a visual artifact for contract drift, missing provenance, layout risk, and publish readiness. | Planned audit surface |
| `strategix_receipt_create` | Create auditable receipt metadata with input, contract, output, route, renderer, and timestamp hashes. | Included in render/package outputs |
| `strategix_artifact_search` | Search compact visual artifact metadata. | `strategix_visual_spec_search` |

## Approved Pricing

Discovery is free. Execution is API-key gated during beta. Public x402 pricing metadata is published so registries and agents can understand the commercial surface before public paid execution is enabled.

| Route / workflow | Public price |
| --- | ---: |
| Discovery, metadata, pricing, health, tool listing | `$0.00` |
| Contract create | `$0.25` |
| Contract validate | `$0.10` |
| Contract repair | `$0.15` |
| Render artifact | `$0.60` |
| Render HTML artifact | `$0.85` |
| Fit report | `$0.30` |
| Visual audit | `$0.45` |
| Receipt, provenance, deterministic index | `$0.03-$0.08` |
| Full visual artifact workflow | `$1.25` |
| Full visual report workflow | `$1.75` |
| Dashboard full workflow | `$2.50` |
| Heavy or large source bundle | `$4.00-$6.00` |

## DeltaSignal Intelligence Deliverables

StrategiX Visual MCP can package DeltaSignal ATLAS-7 evidence into polished, branded, auditable investor documents. These finished artifacts are priced separately from the underlying DeltaSignal data calls.

| Product | Public price | Gross margin target | Notes |
| --- | ---: | ---: | --- |
| Single Daily Morning Brief PDF | `$4.50` | `~68-72%` | One ready-to-use PDF per market day |
| Monthly Subscription | `$79` | `~71%` | 22 daily briefs, auto-delivered with archive access |
| Heavy / Multi-Issuer Deep Brief | `$9.00` | `~62%` | Includes extra issuer drilldowns |

Recommended bundled workflow:

```text
strategix_delta_brief_pdf_full -> $4.50
```

Source intelligence: `https://aitrailblazer.github.io/deltasignal-atlas-codex-plugin/`

## Public Reference URLs

- Landing page: `https://aitrailblazer.github.io/strategix-visual-mcp/`
- AITrailblazer MCP umbrella: `https://aitrailblazer.github.io/aitrailblazer-mcp/`
- DeltaSignal ATLAS-7: `https://aitrailblazer.github.io/deltasignal-atlas-codex-plugin/`
- MCP endpoint: `https://api.aitrailblazer.net/mcp`
- Pricing metadata: `https://api.aitrailblazer.net/mcp/pricing`
- Health metadata: `https://api.aitrailblazer.net/mcp/health`
