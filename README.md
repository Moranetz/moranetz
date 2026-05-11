### Marion Moranetz

Indie builder and AE candidate. San Francisco.

**For CROs and founder-buyers:** I build the systems other AEs use intuitively. For every move I make on a deal, I can show you the mechanism behind it — and the evidence either holding it up or quietly failing to. The repos below are the proof.

I build at the intersection of payments, persuasion, and product. Most of what I make is software for one of three buyers: a founder who needs revenue infrastructure, a salesperson who wants discovery superpowers, or a team that needs better data to decide.

---

### The Closer Foundation series

A five-repo research program building the empirical foundation for "best closer someday." Pre-registered methodology. Transparent deviation logs. Autonomous-compute friendly.

- [closing-evidence-atlas](https://github.com/Moranetz/closing-evidence-atlas) — Pre-registered systematic review and Bayesian meta-analysis of 39 named sales-closing techniques. 11,785 records screened across 7 public databases. 572 included after Stage-1; 44 records extracted. **15 techniques classified as empirical deserts** — zero peer-reviewed studies despite high practitioner prominence. PRISMA 2020 conformant. **Six per-technique posteriors public, five sensitivity-stable:** gain-framing μ=0.354 [0.280, 0.429] (k=9), loss-framing μ=0.327 [0.249, 0.410] (k=7), regulatory-fit μ=0.484 [0.346, 0.632] (k=3), commitment-consistency μ=0.590 [0.331, 0.782] (k=2), extreme-anchor μ=0.435 (k=2). All five clear d=0.2 with P>0.99.
- [sales-instrument](https://github.com/Moranetz/sales-instrument) — Pre-registered 4-arm A/B test on my own cold outreach. Salt + protocol committed to git before the first send so reviewers can verify the design wasn't mid-study altered. Results published whichever direction they land.
- Three sister repos release through Q3 2026: *delta-mechanics* (independent replication of Tan et al. 2016 *Winning Arguments*), *close-detector* (transformer technique classifier), *closer-sparring* (local-first practice agent).

If you screen for "operator who can audit her own claims, not just make them" — start with Atlas. If you're hiring an AE for founder-to-founder commerce at a Series A–C company, the series is the application.

---

**What's worth your 30 seconds:**

- [ae-playbook](https://github.com/Moranetz/ae-playbook) — An open AE playbook with the **behavioral-science mechanism behind every move**. Annotated outbound templates by recipient archetype, a four-phase discovery framework, five-role multi-threading map, top-14 objection-handling matrix with mechanism notes, and an annotated MEDDPICC. The playbook I'd hand a new-hire AE on day one.
- [gtm-teardowns](https://github.com/Moranetz/gtm-teardowns) — Public GTM teardowns of three target companies (Stripe / Clay / Linear) — ICP decomposition, pricing analysis, messaging audit, observable vulnerabilities, and a 30-60-90 day plan for the new-business AE seat at each. The teardown is the application.
- [poseprompter-stripe-teardown](https://github.com/moranetz/poseprompter-stripe-teardown) — Production Stripe integration (Payment Intents + Elements + signed webhooks + Firestore credit ledger). The architecture diagram, the four mistakes I made in production, and the patterns I'd share with another founder.
- [Persuasion-Max](https://github.com/moranetz/Persuasion-Max) — Open-source 5-layer behavioral measurement engine. Calibrated on 126,288 human interactions; identifies a 21.8 point lift when message framing matches persona type.
- [lsm-discovery](https://github.com/moranetz/lsm-discovery) — Replication of Pennebaker's Language Style Matching research, validated on persuasive dialogue. Open Python implementation. Includes a "What this means for sales-discovery calls" section that translates the research for AE readers.

---

---

### Persuasion-training iOS suite — three apps, one quarter

Three companion games released as native SwiftUI ports of my own React/HTML source. Each teaches a different operator skill — composition, recognition, calibration. App Store submissions pending; full source + scaffolding public.

- [reality-distortion-ios](https://github.com/Moranetz/reality-distortion-ios) — Frame-stacking game against eight named buyer archetypes (skeptical investor, corporate gatekeeper, burned founder, etc.). Player composes a six-fragment response targeting each NPC's documented persuasion weakness. [Support + privacy](https://moranetz.github.io/reality-distortion-docs/).
- [mindcraft-ios](https://github.com/Moranetz/mindcraft-ios) — Duolingo-style mechanism drilling across seven persuasion techniques. 56 practice questions with literature citations (Cialdini, Kahneman, Langer 1978). [Support + privacy](https://moranetz.github.io/mindcraft-docs/).
- [viraliq-ios](https://github.com/Moranetz/viraliq-ios) — Hook-writing practice across seven distinct interaction modes (assemble, swipe-instinct, surgery, rank, A/B, roast, fix). 56 exercises that train the thumb-stop response. [Support + privacy](https://moranetz.github.io/viraliq-docs/).

Same scaffold replicated three times. Third ship cost less than the second.

---

**Operator tools (newly public):**

- [linkedin-optimizer](https://github.com/Moranetz/linkedin-optimizer) — Single-file React app that scores a LinkedIn draft on virality dimensions, then rewrites it for one of five named audience profiles (founders / developers / executives / creators / sales) with one of five rewrite levers (more vulnerable / more controversial / add data / make it funnier / more specific). 1,200 lines of HTML/JSX, no build step.
- [post-bridge-mcp](https://github.com/Moranetz/post-bridge-mcp) — 50-tool MCP server for solo-dev marketing — viral scoring before publishing, persuasion email sequences, competitive intelligence, Reddit authority building. Python + Supabase + Claude. Runs hands-free.
- [raroque-repo-audit](https://github.com/Moranetz/raroque-repo-audit) — Pre-publish security-audit skill for Claude Code. Aligned to OWASP ASVS 5.0, OWASP Top 10 2025, MASVS 2.0, CWE Top 25, and OWASP LLM Top 10, plus the specific Supabase RLS / Stripe-webhook / AI-tool-budget failure modes Chris Raroque has cataloged. Catches the schema-level vulnerabilities that pass policy-level audits.
- [clearframe-public](https://github.com/Moranetz/clearframe-public) — Chrome extension + React app that identifies the specific persuasion techniques in any headline, steelmans both sides without ideology labels, and surfaces common ground. Built on the four-layer Behavioral Influence Architecture (BIA) framework, 14 peer-reviewed sources.

These were gatekept private because they were "too powerful." The technique is not the moat — the calibration and the voice are. Publishing is the credibility halo.

---

Currently: AE roles at Series A–C founder-led startups, where the buyer is the founder or near-founder. The repos above are the application.

[LinkedIn](https://linkedin.com/in/marionmoranetz) · [Portfolio](https://moranetz.github.io)
