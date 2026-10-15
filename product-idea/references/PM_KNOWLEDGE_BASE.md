# PM Knowledge Base — Master Reference
### An independent, paraphrased study reference for product-management method, adapted from the approach taught in CMU 17-619 (Product Management Essentials I). Not official course material.

> **What this file is.** The navigational spine for the whole knowledge base. It gives the end-to-end pipeline, the concept dependency map (each concept's inputs → outputs), the Product Idea Workbook section ↔ concept mapping, and how the four Spaces build **one cumulative deliverable**. It is deliberately an **index, not a textbook** — the full teaching content lives in the four per-Space guides. Read those for definitions, rules, templates, worked examples, and coaching questions.

## The four Space guides (authoritative content)

| Space | Guide file | Covers |
|---|---|---|
| 1 · Customer Problem | [`kb_space_1.md`](kb_space_1.md) | Fertile Land, Actor, JTBD, Outcomes, Problem (Gap+Causes), Journey Map, Use Cases, Problem Sizing, Problem Category, Problem Statement |
| 2 · Market | [`kb_space_2.md`](kb_space_2.md) | Market, Segmentation, Validity Rules, Segment Profiles, Competition, Positioning, Market Focus (5 decisions), Product Focus/MVP, Entry Barriers, Niche, Early Adopters, Screening Matrix |
| 3 · Solution | [`kb_space_3.md`](kb_space_3.md) | Idea Generation, Product Concept Outline (9 parts), User Views (Happy-Path), Functional Requirements, Context View, Non-Functional Requirements (the 9) |
| 4 · Customer Value | [`kb_space_4.md`](kb_space_4.md) | Value Proposition, Features→Benefits, Customer Value, Costs/TCO, Pricing Model, Value-Prop Evaluation (BCR), TAM, Product Idea Brief |

Companion file: [`QUALITY_RUBRIC.md`](QUALITY_RUBRIC.md) — the per-Space checklist a coach uses to pressure-test a user's work.

---

## 0. The governing idea

**"Build the right product before you build the product right."** The #1 reason new products fail (35–49% failure rate) is **"No Market Need."** The whole method exists to prevent that by forcing rigor *in order*: understand the customer's problem → understand the market → design a solution → prove the value — **before** committing to build.

Two North Stars run through everything:
- **Problem Space through Solution:** every artifact must be **specific, clear, and actionable** — and trace back to one **Actor + one JTBD**.
- **Market/Value axes:** the most successful products (1) serve a **highly attractive market** (large, fast-growing, low entry barriers) AND (2) hold a **strong, differentiated position** (superior value vs. alternatives).

The process is **iterative, not linear.** Reframing the JTBD (up or down the abstraction ladder) ripples through outcomes → problem → causes → journey → solution → value. Expect to loop back.

---

## 1. End-to-end pipeline (text overview)

The Product Idea Workbook is filled **front to back**, each artifact feeding the next. One continuous chain:

**SPACE 1 — CUSTOMER PROBLEM** *(who/what/why/how-big, solution-free)*
Pick a **Fertile Land** (a familiar area of life) → name one **Actor** (a class of people) → state their **JTBD** (one functional task) → define **Outcomes** as paired Actual/Desired metrics (the single most important concept) → the **gap** between them + its **Causes** (5 Whys / fishbone) = the **Problem** → visualize the **Customer Journey Map** (locates causes by stage) → name the **Use Cases** (scenarios) → compute **Problem Sizing** (per-instance → annualized → total, optionally $) → label the **Problem Category** (2–4 words) → roll it all into a 4-element, solution-free **Problem Statement**.

**SPACE 2 — MARKET** *(is the opportunity attractive, and can we win a position?)*
Carry Actor + JTBD forward → define the **Market** (name it, count the Actors, trend + why) → **Segment** it (variables → values → segments whose sizes sum back to the market) → screen each segment against the **6 Validity Rules** → write **3 Segment Profiles** → map **Competition** (every option the Actor perceives, by category, direct + indirect) → build a **Positioning** map on the customer's criteria and find the white space → assess **Entry Barriers** → run the **Attractiveness × Position screening matrix** → commit to a **Market Focus**: 5 *aligned* decisions (segment, niche, use case, problem, position-to-own), with a **Niche / Early-Adopter** beachhead → distill a **Product Focus / MVP**.

**SPACE 3 — SOLUTION** *(what is the MVP, precisely?)*
**Generate** many ideas then converge on one → write the **Product Concept Outline** (9 parts: name, purpose, category+evidence, attributes, deliverables, I/O, infrastructure, data) → draw **User Views** (a disciplined Happy-Path: no login/error clutter, explicit entry + completion) → derive product **Features** and write **Functional Requirements** as user stories (singular, unambiguous, verifiable, ID'd, valuable, solution-free) → draw the **Context View** (external entities + labeled/directed data) → specify **Non-Functional Requirements** across the course's 9 quality attributes at the right level/threshold. Result = the **PRD**.

**SPACE 4 — CUSTOMER VALUE** *(is the offer compelling?)*
Build the **Features→Benefits** table (feature ≠ benefit; quantify ≥1) → sum to **Customer Value** tied to the outcome gap (in time and $) → enumerate **Customer Costs / TCO** across acquire/use/have/dispose (price is just cost #1) → set the **Pricing Model** (strategy, metric, price ≈10–30% of value, payment structure) → run the **Value-Proposition Evaluation** (BCR vs. friction threshold; apply levers if weak) → compute the **TAM** (deferred to the last assignment; `Actors × price × purchases/yr`) → write the 2-page, jargon-free **Product Idea Brief** that rolls up all 17 elements.

**Two deliberately deferred artifacts:** the **TAM** (Space 4) and the **Product Idea Brief** are completed at the very end of the course, because both require the full workbook to be in place.

---

## 2. Concept dependency map (inputs → outputs)

Each row: a concept consumes upstream artifacts and produces the input(s) the next concept needs. This is the load-bearing chain — break it anywhere and the workbook stops reconciling.

### Space 1 — Customer Problem
| Concept | Consumes | Produces |
|---|---|---|
| Fertile Land | familiarity / interests (or a product idea worked backward) | a labeled arena → **Actor** |
| Actor | Fertile Land | one class of people → **JTBD** (and the future product's primary **User**) |
| JTBD | Actor | one functional task → **Outcomes** + **Journey Map** |
| **Outcomes** | Actor + JTBD | ≥3 paired Actual/Desired metrics (metric+value+measurement) → the **gap**, **Sizing**, **Category**, and all of Space 4's value math |
| Problem (Gap+Causes) | Outcome pairs (gap) + Journey Map (where causes occur) | the selected gap + root/contributing causes → **Statement**, and the causes the Solution must address |
| Customer Journey Map | Actor, JTBD, Use Cases, Outcomes, Causes | a visual that **locates causes by stage** → **Problem**, **Use Cases**, later user flows |
| Use Cases | Actor + JTBD | named scenarios → **Market segmentation** + **Solution** scoping |
| Problem Sizing | Outcome gaps + JTBD frequency + # Actors (cited) | 1–3 quantified sizes → **Statement**, pricing, and **TAM** setup |
| Problem Category | Outcomes + Problem | a 2–4 word label → **Statement**, Market/Value framing |
| Problem Statement | Actor + gap + key cause + size(s) | the solution-free communication artifact → **Market Space** + Product Narrative |

### Space 2 — Market
| Concept | Consumes | Produces |
|---|---|---|
| Market | Actor + JTBD | named/sized/trended market → the universe to **segment** (segments must sum back to it) |
| Segmentation | Market; Actor/JTBD/Use Cases/Outcomes | candidate segments (variable→values→size) → **Validity Rules**, **Profiles** |
| 6 Validity Rules | candidate segments | a validated segment set → **Profiles** |
| Segment Profiles | validated segments | **3** comparable profiles → **Screening Matrix** + **Market Focus #1** |
| Competition | Actor + JTBD (+ focus) | the options/competitors → the **rows on the positioning map** + position strength |
| Positioning | Actor/JTBD perspective, competitors, customer criteria | current-state map (white space) → **future-state map + Position-to-Own** = **Market Focus #5** |
| Entry Barriers | candidate segments | barrier assessment → segment **attractiveness** (Focus #1) |
| Niche / Early Adopters | the selected segment | the beachhead (extra AND-ed variables) → **Market Focus #2** + MVP first customer |
| Screening Matrix | Profiles (size/growth/barrier) + Competition/Positioning (landscape/share/severity) | the ranked segment choice → **Market Focus #1** |
| **Market Focus** | Profiles, Competition, Positioning, Problem/Outcomes | 5 *aligned* decisions (segment/niche/use case/problem/position) → **Product Focus/MVP** |
| Product Focus / MVP | the aligned Market Focus | the MVP product concept → **Solution Space** |

### Space 3 — Solution
| Concept | Consumes | Produces |
|---|---|---|
| Idea Generation | Problem, Actor/JTBD/use case, size, segment/niche, position | one chosen MVP idea → **Concept Outline** |
| Product Concept Outline (9 parts) | chosen MVP idea + Market Focus (esp. positions-to-own) | Main Attributes, I/O, Infra, Data → seeds **Features**, **Context View**, **NFRs**, Value framing |
| User Views (Happy-Path) | JTBD, desired outcome, chosen use case, Concept Outline | the core-value path → **Product Features** → **Functional Reqs**; also **Latency/Usability** reqs |
| Functional Requirements | Features (from Outline + User Views + Context View) | functional half of the **PRD** → drives UX/architecture/tests; sets up Features→Benefits |
| Context View | Concept Outline (data sources, I/O, infra) + actor set | external entities + data flows → **Interoperability/Compatibility NFRs** |
| Non-Functional Requirements (9) | User Views (→Latency/Usability), Context View (→Interop/Compat), Outline (→Avail/Security/Privacy) | non-functional half of the **PRD** → completes Solution → feeds **Customer Value** |

### Space 4 — Customer Value
| Concept | Consumes | Produces |
|---|---|---|
| Customer Value Proposition | Outcomes, Features, Positioning | the benefits-minus-costs thesis the rest of the Space defends |
| Features→Benefits | MVP Features, Outcomes, differentiators | the raw benefit list → summed into **Customer Value** |
| Customer Value | Features→Benefits + Actual/Desired outcome gap | total benefit figure (time + $) → **value-based pricing** + **BCR numerator** |
| Customer Costs / TCO | MVP/Solution, Pricing (price = cost #1) | total cost figure → **BCR denominator** + friction signals |
| Pricing Model | Customer Value (value-based), Competition (reference), differentiators | the **price** → cost item #1, BCR input, **TAM** input |
| Value-Prop Evaluation (BCR) | Customer Value, Costs/TCO, Price, friction signals | the compellingness verdict + levers → Brief's value section |
| TAM *(deferred)* | Market size / # Actors, average price | annual market opportunity (units + $) → Brief's market section |
| Product Idea Brief *(last)* | every prior Space | the 2-page executive go/no-go proposal |

---

## 3. Product Idea Workbook section ↔ concept mapping

The Workbook has four numbered sections, one per Space. TAM and the Brief are deferred to the last assignment.

| Workbook Section | Concept slots (in fill-in order) | Guide |
|---|---|---|
| **1. Customer Problem Space** | Fertile Land → Actor (+ roles) → JTBD → Outcomes (Actual+Desired) → Problem (Gap+Causes) → Customer Journey Map → Use Cases → Problem Sizing → Problem Category → Problem Statement | `kb_space_1.md` |
| **2. Market Space** | Market (name/size/trend) → Segmentation → Segment Profiles (×3) → Competition → Positioning (current+future map) → Market Focus (segment/niche/use case/problem/position) → Product Focus/MVP · *[TAM slot — DEFERRED to last assignment]* | `kb_space_2.md` |
| **3. Solution Space** | Product Concept Outline (9 parts) → User Views (Happy-Path + storyboard/screen-flow/prototype) → Functional Requirements → Context View → Non-Functional Requirements (9) | `kb_space_3.md` |
| **4. Customer Value Space** | Product Features & Benefits → Pricing Model → Customer Cost Items → Customer Value Proposition Evaluation · *[TAM + Product Idea Brief — DEFERRED to end of course]* | `kb_space_4.md` |

**Assignment cadence (for reference):** PA1 anchors the Problem Space front-end (Fertile Land, Actor, JTBD, ≥1 raw outcome). PA2 requires ≥3 *well-defined* outcomes + problem. PA3 adds the Journey Map. PA4 is the Market Space. PA5/6 span Solution + Value. The **TAM** and **Product Idea Brief** are the final assignment.

---

## 4. How the 4 Spaces build ONE cumulative deliverable

The four Spaces are not four documents — they are four passes over **one product idea**, each adding a layer that the next depends on. The whole thing succeeds or fails on **one property: coherence.**

**The single Actor + single JTBD is the trunk.** Everything branches from it. The Actor chosen in Space 1 becomes the primary **User** of the product in Space 3 and the **customer** whose value is proven in Space 4. The JTBD defines the market in Space 2 (everyone doing that job), the competitive set (every option perceived for that job), and the happy path in Space 3 (the job, done through your product).

**The "golden thread" of numbers is the proof of coherence.** The strongest workbooks pick **2–3 core metrics early** — a friction count, a frequency, a wage/value rate — and reuse them *verbatim* across all four Spaces:
- The **outcome gap** (Space 1) becomes the **customer value** (Space 4).
- The **problem size** (Space 1) sets up the **TAM** (Space 4) and grounds the **segment sizes** (Space 2).
- The **root cause** (Space 1) is what the **MVP features** (Space 3) must address and what the **position-to-own** (Space 2) differentiates on.
- The **desired outcome metric** (Space 1) is the **design/build target** for requirements (Space 3) and the **benefit** quantified in dollars (Space 4).

Exemplar proof: a strong workbook reuses `8 steps → 4 target`, `~40 episodes/yr`, and `$32/hr` across problem, MVP "how it works," requirements, pricing, and value — so the whole workbook reconciles as one argument (`68 hrs saved/yr`; `$1,664/yr = 52 hrs × $32/hr`, a lower bound that monetizes only 52 of the 68 hrs). The weakest workbooks break the thread somewhere — a market count that drifts 2M→2.5M→3M between sections, a TAM priced at $10 while the product prices at $20, a metric introduced then dropped.

**Each Space narrows the previous one's aperture:**
1. Problem Space opens wide (a whole Fertile Land) then narrows to **one measurable gap**.
2. Market Space opens wide (the whole market) then narrows to **one aligned Market Focus** (v1.0 beachhead).
3. Solution Space opens wide (many ideas) then narrows to **one minimal MVP** serving only that focus.
4. Value Space opens wide (all benefits and all costs) then narrows to **one verdict** (compelling / not) and **one number** (TAM) for the executive.

**The Product Idea Brief is the whole trunk in two pages.** Written last, it rolls up all 17 elements (Actor, JTBD, gap, causes, size / product name, category, attributes, deliverables, how-it-solves / TAM, market focus, competitor, position-to-own / benefits, pricing, compellingness). If the golden thread held, the brief writes itself and every number reconciles. If it didn't, the brief exposes the contradictions.

**The one-sentence test for the whole deliverable:** *Can a skeptical executive trace one consistent set of numbers from the outcome gap → quantified benefits → value → price (≈10–30% of value) → a BCR that clears its friction threshold → an annual TAM → a jargon-free two-page brief — with every figure reconciling to the ones before it, and every choice tracing back to one Actor doing one Job?* If yes, the four Spaces built one product.

---

## 5. Quick pipeline diagram

```
SPACE 1: CUSTOMER PROBLEM (solution-free)
  Fertile Land → Actor → JTBD → OUTCOMES (Actual/Desired pairs)
        │                              │
        │                     gap ─────┴──► + CAUSES (5 Whys) = PROBLEM
        │                              │           │
        │              Journey Map ◄───┘     Use Cases   Problem Sizing
        │                              │           │           │
        │                              └──► Problem Category → PROBLEM STATEMENT
        ▼                                                          │
SPACE 2: MARKET (attractive? + winnable position?)                 │
  Market(size/trend) → Segmentation → 6 Validity Rules → 3 Profiles │
        │                                                    │      │
        ├─► Competition ─► Positioning(white space) ─► Screening Matrix
        ├─► Entry Barriers                                   │
        └─► Niche/Early Adopters ──────────────► MARKET FOCUS (5 aligned:
                                    segment·niche·use case·problem·position)
                                                            │
                                                     PRODUCT FOCUS / MVP
        ▼                                                   │
SPACE 3: SOLUTION (the MVP, precisely)                      │
  Idea Generation → PRODUCT CONCEPT OUTLINE (9 parts)       │
        │                    │                              │
        ▼                    ▼                              │
  USER VIEWS (Happy-Path) ─► Features ─► FUNCTIONAL REQS    │
        │                                     │             │
        ▼                                     │             │
  CONTEXT VIEW ─► Interop/Compat ─► NON-FUNCTIONAL REQS (9) = PRD
        ▼
SPACE 4: CUSTOMER VALUE (compelling offer?)
  Features→Benefits ─► CUSTOMER VALUE (=outcome gap closed, time+$)
        │                    │
  Costs/TCO ◄────────── Pricing Model (≈10–30% of value)
        │                    │
        └──► VALUE-PROP EVALUATION (BCR vs friction threshold)
                             │
                    TAM (deferred) ──► PRODUCT IDEA BRIEF (deferred, 2 pages)
```

---

*Navigational note: this file intentionally does not restate definitions, templates, worked examples, common mistakes, or coaching questions — those live in the four Space guides. Use this KB to see the shape of the whole pipeline and where any one concept sits; use `QUALITY_RUBRIC.md` to pressure-test a user's work; open the relevant `kb_space_N.md` for the deep content.*
