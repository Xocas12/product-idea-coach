# Quality Rubric — Coach's Pressure-Test Checklist
### Per-Space must-pass rules, top failure modes, and strong-vs-weak signals grounded in a set of exemplar workbooks

> **Attribution.** This is an independent, paraphrased study reference built on the product-management method taught in CMU 17-619. It is not official course content, and every example below has been anonymized: illustrative "strong" and "weak" signals are drawn in aggregate from a set of completed exemplar workbooks, with no student or project identified.

> **How a coach uses this.** For each Space the user has worked on, run the **Must-Pass** gates first (a "no" is a blocker — stop and fix before moving on), then scan the **Top Failure Modes** (the recurring ways workbooks break), then use the **Strong vs. Weak** signals to calibrate feedback with concrete language.

> **The one meta-rule that spans all four Spaces:** *keep one golden thread of 2–3 core numbers running verbatim from the outcome gap → value → price → BCR → TAM.* Nearly every "weak" verdict below is a place where that thread broke. When in doubt, ask: **"Does this number match the same number three sections ago?"**

---

## SPACE 1 — Customer Problem

### Must-pass gates
1. **One Actor, one JTBD.** Actor is a concise label for a *class of people* (not an organization, not "user/customer," no geography). JTBD is one functional, singular, accurate task ("To [verb] [object]") with no benefit/actor/outcome baked in.
2. **Fertile Land is a label the user is genuinely familiar with** — an area of life, not a product/brand, not a sentence.
3. **≥3 well-defined Outcomes, each a paired Actual/Desired on the SAME metric** — metric is a dashboard-ready label, has a value, and has a measurement method. The gap is the difference.
4. **Problem = Gap + Causes.** Causes are actually named (via 5 Whys or fishbone) and bottom out in an *actionable root cause* — not a restated symptom.
5. **Problem is sized ≥2 ways** (per-instance → annualized-per-actor → total-impact), with the **# of Actors cited to a source** and units consistent end-to-end.
6. **Problem Statement has all 4 elements and is solution-free:** Actor + outcome gap + key cause + problem size, and names no product.
7. **Journey Map is a visualization that agrees with the JTBD** (no stages after the job is done) and carries the **Causes layer**.

### Top failure modes
- **Guessed Actor counts** dressed as data ("assuming from personal experience") behind precise-looking totals. *(A weak workbook derived segment percentages this way; another labeled load-bearing inputs "Source: None – my own experience.")*
- **Unit-labeling errors carried through the math** — e.g., "52 days" that should be 52 weeks/orders; a "billions of hours" figure ~300× off with no derivation; "1,865 million" written for 1.865 million. *(Each seen in a separate weak workbook.)*
- **Thin gap** — Desired only 5–8 points above Actual, so it isn't a "worthwhile problem." *(A weak workbook set completion 30%→35% and exploration 73%→80%.)*
- **Weak problem→solution causality** — the problem is low completion, but the eventual solution never shows *why* it beats incumbents.
- **Root cause asserted, not validated,** then a solution that never addresses why incumbents haven't already solved it *(a weak workbook asserted an inventory root cause without reconciling it against warehouse+courier unit economics)*.
- **Dropped thread** — a metric or use case introduced then never carried forward *(one workbook introduced a custom metric then abandoned it; another dropped its overhead-time outcome from the final statement)*.
- **Over-written narrative** — "beacon of change," "paradigm shift" — burying the crisp PM reasoning *(seen across several weak workbooks)*.

### Strong vs. Weak signals
| Dimension | STRONG (emulate) | WEAK (flag) |
|---|---|---|
| Outcome framing | Fill-in skeleton: Actor → JTBD → Use case → Actual → Desired → Problem(gap) → Cause → Size, as a numbered list, same metric for Actual & Desired *(strong exemplars)* | Vague ideas ("little time"), metric with no measurement method, or only Desired captured (no gap) |
| Problem sizing | Explicit auditable formula, one cited/"self-made"-labeled source per factor: e.g. `91.4M × 30% × $500 = $13.7B/yr` *(a strong exemplar used an auditable single-line sizing formula, each factor sourced or labeled)*; two-level per-user + population totals *(another strong exemplar)* | One-way (per-instance only); implausible headline that doesn't reconcile; # Actors flips between sections *(a weak workbook cited 50M in one place and 265.5M in another)* |
| Root cause | Real 5 Whys landing on an actionable organizational cause, reused downstream *(strong exemplars landed on causes like "lack of collaboration tools" or "limited resources/financial constraints")* | Obvious cause stated once; snap judgment; Causes omitted entirely |
| Evidence discipline | Numbered inline citations bound to an appendix; internal estimates flagged "self-made" *(strong exemplars carried ~two dozen bound references)* | No sourcing; no validation; whole case rests on personal assumption |
| Statement | 4 elements present, solution-free, numbers matching the sizing exactly *(a strong exemplar's statement paragraph)* | Solution leaks in ("an app that…"); a size or the key cause missing; numbers contradict upstream |

---

## SPACE 2 — Market

### Must-pass gates
1. **Market is defined by Actor + JTBD, named, sized in *people* (not $), with a trend + why** and a cited source. (Dollars = TAM, deferred.)
2. **Segmentation uses the SAME variables across all segments** (only values differ), and **segment sizes reconcile to the market total** (or ≤ it if segmenting by Use Case).
3. **3 Segment Profiles**, each with a memorable name, variable(s), value(s), size + source, and a growth signal.
4. **Each segment passes the 6 Validity Rules** (Homogeneous, Distinctive, Measurable, Substantial, Actionable, Accessible) with no illegal double-counting.
5. **Competition is the Actor's *perceived options*** — ≥3 options including ≥1 product category and ≥1 branded product, mapped direct + indirect (never "we have no competitors"; the manual/do-nothing option always exists).
6. **Positioning scores options on the *customer's* criteria** (0–10, amount-offered not goodness), on current-state AND future-state maps, ending in a crisp **Position-to-Own** naming target + 1–2 differentiators.
7. **Market Focus = 5 decisions that are all ALIGNED** (segment · niche · use case · problem · position reinforce one v1.0 story), with a defined niche/early-adopter beachhead.

### Top failure modes
- **Guessed sizes dressed as data,** or a TAM that doesn't reconcile with the segmentation *(a weak workbook's per-week TAM and mismatched willingness-to-pay splits)*.
- **Segment sizes that don't add up** to the market, or a rounding/definition leak *(a weak workbook had segments summing to 100.1%, and justified a "2+ toddlers" segment with a "3+ children" statistic)*.
- **Flat competitor list** or the fatal "no competitors" — ignoring substitutes and DIY.
- **Product-centric positioning** — scoring your own features instead of the customer's criteria; **white space treated as proven demand**; maps present only as images with no 0–10 scoring; an inverted criterion *(a weak workbook scored "Price: Higher is valuable")*.
- **Overstated position** — claiming a gap without naming/scoring the real incumbents *(a weak workbook claimed "fewer competitors" in its target segment without scoring them)*.
- **Missing artifacts** — a "Positioning Analysis" heading with no actual map.
- **Unaligned or absent focus** — a niche that lacks the chosen problem, a position irrelevant to the segment, no early-adopter beachhead into a high-barrier incumbent.
- **Copy-paste labeling errors** across segment blocks *(a weak workbook described one U.S. state while quoting another state's rate)*.

### Strong vs. Weak signals
| Dimension | STRONG (emulate) | WEAK (flag) |
|---|---|---|
| Segmentation | Multi-variable, MECE-ish, sizes sum to total, then converge to ONE focus segment with size + competition rationale *(strong exemplars narrowed a large market through an explicit filter chain whose segments summed exactly to the focus number)* | Different variables per segment; sizes that don't reconcile; overlapping segments violating Distinctive |
| Segment naming | Memorable, quotable: e.g. "Express Shoppers," "Immersive Storytellers," "The Worriers" *(strong exemplars)* | "Group A"; vague or contradictory descriptions *(a weak workbook called an elderly segment "price-sensitive" then "financial strength" in the same profile)* |
| Competition | Mapped by substitution category: e.g. Direct hosts vs. DIY editors vs. file-hosting hacks; Hardware-only/Software-only/Combined; or an Actor→JTBD→category→product tree *(strong exemplars)* | Flat list; "no competitors"; category not proven with a real source (G2/Capterra/Amazon) |
| Positioning | Gap-hunt: score incumbents on customer criteria, claim the 1–2 axes where all score low; current + future maps on same axes; one-sentence Position-to-Own naming target + differentiators *(strong exemplars)* | Your features on the map; high=good assumption; jargon-y position; scores asserted with no teardown/research |
| Focus | 5 aligned decisions + deliberate beachhead + explicit deferrals *(a strong exemplar picked a single first market and a single first use case, deferring the rest)* | Building for everyone; decisions pulling different directions |

---

## SPACE 3 — Solution

### Must-pass gates
1. **Everything traces to the Market Focus.** Every feature/screen/requirement serves the targeted segment/niche/use-case/problem/position — or it doesn't belong in the MVP.
2. **Product Concept Outline** completed (name, purpose = *primary task*, category **with evidence it exists**, main attributes that *create the position-to-own*, deliverables, I/O, infrastructure from the allowed 5, external data).
3. **User Views include a disciplined Happy-Path** — explicit entry + completion point, includes decisions/info-in/info-out, and **excludes login/setup/errors/optional features** (unless that IS the product). Plus ≥1 of storyboard / screen-flow / prototype.
4. **Functional Requirements as user stories**, each obeying the 5 rules — **singular, unambiguous, verifiable, uniquely ID'd, valuable** — and **solution-free** (who/what/why, not how). Each traces to a feature.
5. **Context View shows only *external* entities** with labeled, directed data flows — no internal features, no the product's own DB, no infrastructure/architecture.
6. **NFRs cover the applicable ones of the 9** (Latency, Usability, Interoperability, Availability, Security, Privacy, Compatibility, Accuracy, Safety), each at a **course-defined level or a measurable, condition-bounded threshold or a named standard** — not a vague adjective. Interoperability derived from the Context View; Latency/Usability from the User View.

### Top failure modes
- **Concept/happy-path drift** — a broad JTBD but a solution that serves a narrower job *(a weak workbook shifted from "develop an app" to "deploy an app")*; or a happy path padded with login/setup/error steps.
- **Solution asserted to fix the root cause without addressing why incumbents haven't** *(a weak workbook proposed a warehouse+courier model without reconciling the incumbents' low-fee unit economics)*.
- **Requirements break the 5 rules** — "search by keyword, category, and brand" in one line (not singular); "should be fast/easy" (unverifiable); missing the "so that" outcome; specifying the widget (not solution-free); no ID.
- **NFRs as vague qualitative goals** ("secure," "reliable") or **generic boilerplate** (2s / 99.5% / WCAG / PCI DSS) copy-pasted regardless of the product's real nature *(a weak workbook left every NFR as boilerplate except one tailored "10s video processing" threshold that showed what good looks like)*.
- **Wrong NFR levels** — 6-nines availability for a non-critical email; a security/privacy tier that mismatches the real adversary/data.
- **Placeholder/empty views** — Context/User/Deployment views referenced but never drawn *(a weak workbook left them as empty headers)*.
- **No MVP prioritization / scope creep** — a flat list of 20–28 requirements, nothing marked v1.0, sprawling beyond the JTBD *(a weak workbook pushed ~28 requirements into mobile/perf/security beyond its web-app JTBD)*.

### Strong vs. Weak signals
| Dimension | STRONG (emulate) | WEAK (flag) |
|---|---|---|
| Concept↔outcome fit | Main attributes create the position-to-own; a "How It Works" flow that maps 1:1 back onto the desired outcome *(a strong exemplar's ≤4-step flow matched its 4-step target outcome exactly)* | Attributes disconnected from positions; purpose written as a feature list; category with no evidence |
| Happy-Path | 4-step flow, wireframe per step, no login/error clutter, clear entry + completion *(a strong exemplar)* | Login/setup/errors in the core flow; entry or completion point dropped; no use case selected first |
| Requirements | Clean user stories split Functional/Non-Functional, each tagged to a named quality attribute with a measurable threshold *(strong exemplars used clean F1–F11/NF1–NF7 numbering, instrumentation-backed metrics, and named standards like 99.9%/<5s/ISO 25010)* | Multiple reqs per line; unverifiable; solution specified; orphaned from features |
| NFR discipline | Levels chosen to match reality (right nines, right adversary, right privacy tier); Interop derived from Context View; thresholds condition-bounded | Vague adjectives; boilerplate ignoring the product's AR/AI/latency nature; max level defaulted everywhere |
| Scope | Deliberately defers non-core features and *says so* *(a strong exemplar explicitly omitted analytics/promotion from v1.0)* | 28 flat requirements, no prioritization, scope creep beyond the focus |

---

## SPACE 4 — Customer Value

### Must-pass gates
1. **Features→Benefits table:** feature ≠ benefit (state the *change in results/experiences*), benefits phrased relatively (more/less/faster/lower), **≥1 quantified**, and the differentiators' benefits included.
2. **Customer Value = the outcome gap closed,** expressed in time and/or dollars (convert time→$ via a defensible wage/rate), summed from benefits that each map to a Desired Outcome.
3. **Customer Costs = full TCO** across acquire/use/have/dispose — including **time/effort and switching costs**, not just price. (Price is cost item #1.)
4. **Pricing Model has all 4 elements** (strategy, metric, price, payment structure), price **derived** (value-based ≈10–30% of value; or a reference price adjusted for +/− differences), metric distinct from billing frequency.
5. **Value-Prop Evaluation gives a BCR matched to the purchase's friction threshold** (3:1 low / 4–5:1 medium / 6–8:1 high / 10:1 very-high) with a verdict; if not compelling, names the lever to pull.
6. **TAM (deferred to last assignment) stated as an annual formula** `purchasing units × avg price per unit × purchases/yr`, where **purchasing units = Market Space Actors × pricing-metric units per Actor** (1 for per-user pricing; 1 ÷ Actors per family/household/organization for those metrics; usage per Actor for usage metrics), **not** multiplied by adoption/conversion % (that's SAM/SOM). The Actor count matches the Market Space, and the purchasing-unit count reconciles to it through the stated conversion factor (an Actor count multiplied by a per-family or per-organization price fails).
7. **Product Idea Brief (last):** ≤2 pages, prose (no bullets/visuals), no PM jargon (except TAM/Outcomes), executive audience, all 17 elements present and numbers consistent.

### Top failure modes
- **Numbers drift between sections** — the single most common flaw. Market/customer counts and prices that don't reconcile *(one weak workbook cited 60M vs 150M and a "$495M per week" figure; another flip-flopped between 2M/2.5M/3M active counts)*.
- **TAM confused with a forecast** — multiplying the whole market by adoption/conversion % and calling it TAM *(weak workbooks presented an adoption-discounted ceiling as a forecast, or labeled a 20%-adoption × 50%-conversion figure "TAM" when it was SOM)*.
- **Price contradicts the TAM** — TAM priced at $10/yr while the product prices at $20/yr *(a weak workbook; another put $200 in the TAM against $125/$175/$275 tiers)*.
- **Guessed inputs dressed as precision** — load-bearing benefit values asserted without evidence *(weak workbooks asserted things like "50% of deployments fail without checks" and "40% time reduction" with no source)*.
- **Value asserted, not proven** — no side-by-side price-vs-value benchmark against named competitors; or value ratios so inflated (26:1–31:1) they read as overstated willingness-to-pay from valuing time at implausible wage rates *(each seen in a separate weak workbook)*.
- **Costs = price only** — ignoring time/switching; or folding a complement's full cost into the envelope *(a weak workbook counted an entire third-party license)*.
- **Brief as marketing hype** — "beacon of innovation," "paradigm shift" instead of concrete, numbered, executive prose *(seen across several weak workbooks)*.
- **Citation-to-claim mismatch** — a benefit cites a source that doesn't support it *(a weak workbook's "15% more effective" cited an irrelevant industry paper)*.

### Strong vs. Weak signals
| Dimension | STRONG (emulate) | WEAK (flag) |
|---|---|---|
| Benefits | Feature→Benefit table, benefits relative and quantified in time AND $, differentiators included, conservative sourced assumptions *(a strong exemplar carried one dollar figure and one hours figure verbatim as an explicit lower bound)* | Feature restated as benefit ("gamification," "AI-powered"); no comparison word; nothing quantified |
| Value↔outcome | Value = the amount of the outcome gap closed, tied to Desired Outcomes *(strong exemplars anchor value to the problem's gap)* | Value computed from features not the gap; benefits not mapped to any outcome; double-counting |
| Pricing | Derived: per-tier perceived value → capture ~¼ (10–30% rule) → round to competitive → justify every deviation *(strong exemplars)*; value-based worksheet `next-best + (+diffs) − (−diffs)`, even monetizing probabilistic risk *(a strong exemplar priced a 9% risk as −$100×9%)* | Price picked arbitrarily; tiers not tied to WTP; metric confused with billing frequency; competitor reference on a different metric |
| Costs/TCO | Full TCO with time monetized *(a strong exemplar computed 115 min × $25/hr = $47.92)*; switching + soft costs named | Price only; complement's whole cost folded in *(a weak workbook)*; time/switching ignored |
| Compellingness | BCR matched to friction with named levers if weak; emotional benefits counted with real signals | BCR with no friction match; "compelling" asserted with no ratio; inflated ratios (26:1–31:1) from implausible wage rates *(a weak workbook)* |
| TAM | Explicit annual formula, segment sizes reconcile to market total, price matches the pricing model; Actors converted to pricing-metric units with the factor stated (e.g., 12M parents ÷ 1.6 per household = 7.5M households) | Adoption/conversion % applied then called TAM; per-week TAM; price contradicts tiers; Actor count × a per-family/per-organization price; tiers on different metrics averaged as listed; count drifts from Market Space beyond the stated conversion |
| Brief | Concise active prose, executive audience, 3 anchor numbers (TAM, problem size, key outcome) consistent throughout | Bullets/visuals/jargon; >2 pages; hype burying substance; numbers inconsistent with the workbook |

---

## Cross-Space coaching heuristics (use on any submission)

1. **"Show me the same number three sections apart."** The fastest coherence test. If the outcome gap, the value, the price basis, and the TAM count don't share the golden thread, the workbook is weak regardless of local polish.
2. **"Is it sourced, or is it a guess labeled as data?"** Reward transparent "self-made"/"Source: None" labels; flag precise-looking totals with hidden guesses.
3. **"Does the solution address the root cause AND why incumbents haven't?"** A solution that only asserts it fixes the cause is a red flag.
4. **"Did any thread get dropped?"** Metrics, use cases, or actors introduced then never carried forward are a recurring weakness.
5. **"Is this solution-free where it must be?"** Problem Statement and Functional Requirements must not specify the product/widget.
6. **"Do the units line up all the way through?"** Minutes vs. hours, weeks vs. days, per-instance vs. per-year, TAM annual vs. per-week, people vs. the pricing metric's unit (per family, per household, per organization) — unit slips destroy credibility even when the logic is sound.
7. **"Would a skeptical executive believe it?"** The ultimate test for Space 4 and the Brief: benefits that dwarf costs, a BCR that clears its friction bar, and a TAM that isn't a disguised forecast.
