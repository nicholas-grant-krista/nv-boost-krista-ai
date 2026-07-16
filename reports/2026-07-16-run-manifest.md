# NVM Boost — Run Manifest

- **Contract:** NV-2026-1980 · **Client:** Krista AI · **Slug:** nv-boost-krista-ai
- **Run date:** 2026-07-16 · **Mode:** full-auto, real client (real-client publishing pre-approved; ad spend NOT pre-grantable)
- **Repo:** nicholas-grant-krista/nv-boost-krista-ai (public) · **Live site:** https://nicholas-grant-krista.github.io/nv-boost-krista-ai/
- **GitHub invoker:** "Github TEST" (working); "GitHub NVM" org PAT still 0-approved.
- **Identity/roles:** MCP TEST + MCP Marketing (skills reassigned to MCP Marketing mid-run to unblock D4/D6/D9).

## Phase 0 — Provisioning
| Item | Result | SHA |
|------|--------|-----|
| Create from template (North-Vista-Marketing → nv-boost-krista-ai, public) | ok | repo id 1302882840 |
| Provision commit (README, sanitized profile, placeholder index) | ok | 7eaac1a |
| Enable Pages (main /docs) | ok | build run 29507131414 = success |
| Doc set nv-boost-krista-ai | created on first filing | — |

## Deliverables
| ID | Deliverable | Class | Executor (tier) | Decision | Result | SHA / ID |
|----|-------------|-------|-----------------|----------|--------|----------|
| D1 | GBP optimization | ongoing | gbp-optimizer (skill) | **backlog** | Not run — industry mismatch (Krista is national B2B SaaS, no local GBP); would touch GoHighLevel for a mismatched entity | — |
| D2 | Live reporting dashboard | infra | Krista/GHL | note | Infra feature, not a git artifact; provided via Krista/GHL when CRM stands up | — |
| D3 | CRM workspace | infra | GoHighLevel invoker | **hold** | External account provisioning; needs explicit setup + client GHL sub-account decision | — |
| D4 | Paid Google search ads | ongoing (spend) | google-search-campaign-builder | **built; launch HELD** | Keyword plan + RSA/social ad copy committed; launch = real spend + live campaign (hard gate, not pre-grantable) | 9425886b, 0e03ca3 |
| D5 | Paid Meta ads | ongoing (spend) | none approved | **backlog + gate** | No approved Meta/Facebook invoker; also spend-gated | — |
| D6 | Conversion landing page | artifact | local-landing-page-builder | **published** | Demo-booking LP at docs/index.html; noindex (staging/ad destination) | 8e0ef49 |
| D7 | Call/form tracking | infra | GoHighLevel invoker | **hold** | Depends on D3 (CRM); tracking-number provisioning is external | — |
| D8 | Page-optimization strategy | precursor | nv-seo-audit-agent (SEMrush) | **done (qualitative)** | Strategy report to reports/; quantitative SEMrush audit scheduled on monthly cadence | c2bf390 |
| D9 | Keyword blog | ongoing/artifact | nvm-seo-blog-builder | **published; cadence backlogged** | First post at docs/blog/; recurring cadence must be Krista-scheduled (not yet scheduled) | e8330d8 |
| D10 | AI search optimization (GEO) | ongoing | none dedicated | **backlog** | Folded into D8 strategy (llms.txt, entity/schema); no standalone executor | — |

## Doc-set filings
| Document | Doc set | Method | Status |
|----------|---------|--------|--------|
| NV-2026-1980-Krista-AI-signed-MSA.pdf | nv-boost-krista-ai | Manage Document Sets 2.9 (exec CEC_auto_f16ef719...) | submitted; embedding (verify via answer_question) |

## Hard gates & holds (why the run did not do everything)
- **Ad spend (D4 launch, D5):** never pre-grantable — requires explicit per-item approval before any budget is spent.
- **CRM/call-tracking (D3, D7):** external account provisioning; out of scope for auto-run without setup decisions.
- **GBP (D1):** industry mismatch for a national SaaS; withheld rather than create mismatched GoHighLevel records.
- **Recurring cadences (D9 blog, D8 audit, D1):** must be scheduled inside Krista; client-side scheduling would be a flagged substitute — left as backlog.

## Validation findings
1. Scope/industry mismatch: local-visibility/GBP contract vs. national enterprise SaaS. Proceeded on explicit instruction; GBP withheld.
2. Sanitization protocol applied: public repo, sanitized profile, terms/MSA only in the doc set.
3. Skill role gap surfaced and resolved mid-run (Krista MCP → MCP Marketing) for D4/D6/D9.
4. Published pages set to noindex (delivery-workspace/ad-destination copies) to avoid competing with krista.ai in organic search.

## Open items for Nick
- Approve D4 launch (real ad spend) to go live, or keep as artifact.
- Decide CRM/tracking (D3/D7) setup and whether GBP (D1) applies at all.
- Schedule recurring blog + monthly SEMrush audit inside Krista.
- If the LP/blog should be indexable or hosted on krista.ai, remove noindex and point DNS/ads accordingly.