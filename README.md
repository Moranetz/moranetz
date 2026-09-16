### Marion Moranetz
San Francisco

I build instruments for things that are usually argued about instead of measured — how an interface holds attention, when a conversation is working on someone, whether a claim in the persuasion literature survives contact with its own evidence.

Most of it ships as software: iOS apps and web tools, and the measurement tooling underneath them.

**[Selected work →](https://moranetz.github.io/selected-work/)** · ~35 projects across iOS, web, and research instrumentation.

---

### Cognitive security

- [cognitive-attack-surface](https://github.com/Moranetz/cognitive-attack-surface) — A defensive taxonomy mapping a documented influence technique to the cognitive mechanism it exploits, each entry paired with a countermeasure and a testable audit criterion. Campaign-detection frameworks classify what an adversary does and stop at observable behavior; this one goes down a layer and attaches a check a reviewer can run. Includes a published citation pass that corrected three of my own errors and pulled two citations that turned out not to resolve to any real publication. Assessment 001 is in the repo: two adverse findings, and no composite score, because only one of six criteria was settleable from public evidence.
- [mechanism-detector](https://github.com/Moranetz/mechanism-detector) — Names which psychological mechanism an AI conversation is using, turn by turn. Labels manipulation, never generates it.
- [clearframe-public](https://github.com/Moranetz/clearframe-public) — A Chrome extension that names the persuasion techniques in a headline and steelmans both sides without ideology labels.

---

### Measurement and method

- [closing-evidence-atlas](https://github.com/Moranetz/closing-evidence-atlas) — A pre-registered systematic review with Bayesian meta-analysis over 39 named persuasion techniques. 11,785 records screened across 7 databases, 44 extracted. 15 of the most-taught techniques have zero peer-reviewed studies behind them. The protocol and the deviation log are committed before the results, so the work can be checked against what I said I would do.
- [apca-gate](https://github.com/Moranetz/apca-gate) — A contrast gate that does not lie in the dark. WCAG 2's ratio false-passes dark interfaces; measured against a dark ground, a colour that clears 4.5:1 lands at APCA Lc 35, under the floor for text at any size. One file, no dependencies, and `--selftest` reproduces the four published reference values before you trust a number from it.
- [pam1-bandit](https://github.com/Moranetz/pam1-bandit) — A fruit-fly mushroom-body model playing a slot machine, and a sweep for which payout schedule hooks it hardest.
- [lsm-discovery](https://github.com/moranetz/lsm-discovery) — A Python replication of Pennebaker's Language Style Matching, validated on persuasive dialogue.

---

### Shipped iOS

Native SwiftUI, shipped solo, App Store live.

- [weight-and-watt](https://github.com/Moranetz/weight-and-watt) — Your real maintenance number, computed from your own data rather than a formula.
- [WeighIt](https://github.com/Moranetz/WeighIt) — Decision analysis built on Analysis of Competing Hypotheses.
- [closer-gym-ios](https://github.com/Moranetz/closer-gym-ios) — Daily drills, SwiftUI, iOS 17+.
- Three training apps drilling one operator skill each: [reality-distortion-ios](https://github.com/Moranetz/reality-distortion-ios), [mindcraft-ios](https://github.com/Moranetz/mindcraft-ios) (56 questions, each cited — Cialdini, Kahneman, Langer 1978), [viraliq-ios](https://github.com/Moranetz/viraliq-ios).

The third app cost less to ship than the second.

---

### Tooling

- [raroque-repo-audit](https://github.com/Moranetz/raroque-repo-audit) — A pre-publish security-audit skill that catches the Supabase RLS and Stripe-webhook failures policy-level audits miss.
- [linkedin-optimizer](https://github.com/Moranetz/linkedin-optimizer) — Scores a draft, then rewrites it for a chosen audience. 1,200 lines, single file, no build step.
- [post-bridge-mcp](https://github.com/Moranetz/post-bridge-mcp) — A 50-tool MCP server for solo-dev marketing.
- [ae-playbook](https://github.com/Moranetz/ae-playbook) — The same mechanism work pointed at commercial conversations: annotated outbound, a discovery framework, an objection matrix, each carrying the mechanism under the move.

---

[LinkedIn](https://linkedin.com/in/marionmoranetz) · [Portfolio](https://moranetz.github.io)
