# Krista AI — Page-Optimization Strategy (Discover phase)

**Agreement:** NV-2026-1980 · **Line:** SEO & GEO (D8) · **Date:** 2026-07-16
**Scope:** Recommendations/strategy for the client web team (per SoW — NVM provides the plan; the client's web team implements).

> Data basis: live crawl/read of https://krista.ai on 2026-07-16 plus SEO best practice.
> **Quantitative SEMrush site audit (crawl score, errors/warnings, backlink & keyword gap) is
> scheduled as the recurring `nv-seo-audit-agent` run** and will be appended here. This document
> is the qualitative strategy; the numeric audit follows on the monthly cadence.

## Snapshot (observed)
- Positioning is strong and consistent: "Enterprise Brain," Complete/Cognitive/Careful.
- Indexable (`meta-robots: index, follow`), canonical set, OG/Twitter cards present, HTTPS.
- Performance layer: NitroPack in use (good — validate it isn't stripping critical content for crawlers).
- Already publishes an `llms.txt` — a real head start on AI-search/GEO (see below).

## Priority recommendations (ranked)

### 1. Build intent-matched solution/landing pages (highest impact)
The homepage carries most of the messaging weight. Give each high-intent query its own page with a single conversion goal. Start with: "agentic AI for customer service," "AI customer service automation," "enterprise AI support platform." (These mirror the paid-search ad groups so organic + paid reinforce each other.)

### 2. Strengthen on-page structure for target pages
- One clear H1 per page containing the primary keyword; logical H2/H3 hierarchy.
- Title tags < 60 chars, meta descriptions < 160 chars, unique per page.
- Descriptive internal links (anchor text = topic, never "learn more").
- Add FAQ schema (JSON-LD) to solution pages to win rich results and feed AI answers.

### 3. Topical content cluster around agentic AI + CX
Publish a recurring cluster (this engagement's blog line) linking back to solution pages: agentic AI for customer service (shipped), AI email triage ROI, human-in-the-loop governance, agentic AI vs. chatbots, AI in regulated industries. Internal-link each post to its money page.

### 4. GEO / AI-search optimization (D10 groundwork)
- Keep and expand `llms.txt`; ensure key claims/definitions are stated in plain, quotable sentences.
- Add Organization + Product schema and clear entity definitions so ChatGPT/Perplexity/AI Overviews can cite Krista.
- Publish concise, factual "what is / how it works" answers near the top of pages.

### 5. Technical hygiene to verify (web team)
- Confirm NitroPack serves full rendered content to bots (spot-check with a fetch-as-Google).
- XML sitemap submitted and current; no orphan solution pages.
- Core Web Vitals within thresholds on mobile; image `alt` text present (several homepage images render without visible alt).

## Handoff
Recommendations are for the Krista web team to implement (per SoW Section: page-optimization strategy is advisory). NVM will re-measure against the SEMrush audit on the monthly cadence and adjust priorities.