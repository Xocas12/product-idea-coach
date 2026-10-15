---
name: product-idea
description: >-
  Turn a rough idea or problem area into a complete, rigorously-specified product concept using
  CMU 17-619's product-management method (Customer Problem -> Market -> Solution -> Customer Value
  Spaces). Runs two ways: a GUIDED COACH that teaches and drafts each section with the user at the
  decision gates, and a one-shot AUTO-GENERATOR that produces a full draft from a seed. Output is a
  Product Idea Workbook covering Actor, Job-To-Be-Done, outcomes, problem + causes, customer journey
  map, use cases, problem sizing, market segmentation, competition, positioning, market focus, MVP
  product concept, user views, functional + non-functional requirements, context view, features and
  benefits, pricing model, customer costs, value proposition, TAM, and a product idea brief. Use when
  the user wants to develop, validate, or pitch a new product/feature idea; do customer or problem
  discovery; define an MVP or write requirements; size a market (TAM); segment customers; position
  against competitors; price a product; or write a product brief / one-pager.
---

# Product Idea — a Product-Management coach & generator

This skill operationalizes the method from CMU 17-619 *Product Management Essentials I*. It takes an
idea or a problem area and produces a **Product Idea Workbook**: a rigorous, customer-centric product
concept built one concept at a time, in a fixed order, where each step feeds the next.

Guiding principle: **"Build the right product before you build the product right."** The #1 reason new
products fail is *no market need* — so most of the work is nailing the customer's problem before
committing to a solution.

## Pick a mode

**Guided coach (default).** Use when the user wants to work through it, learn the method, or make the
key calls themselves. Go **one concept at a time**: (1) briefly teach the concept, (2) ask the
concept's coaching questions (see the Space guide in `references/`), (3) draft that section, (4) show
it and pressure-test it against `references/QUALITY_RUBRIC.md`, (5) get the user's confirmation or
iterate, (6) update the workbook file, (7) move to the next concept. **Stop and require an explicit
user decision at the three GATES** (below).

**Auto-generator (one-shot).** Use when the user gives a seed (a Fertile Land, a rough product idea,
or just an Actor) and asks to "just generate," "auto," "one-shot," or "draft the whole thing." Produce
a complete workbook draft in a single pass, in pipeline order, making explicit reasonable assumptions
(label them) and citing sources for any real numbers. Do **not** stop at the gates — instead, at each
gate, choose the strongest option, state the alternatives you rejected and why, and continue. When
done, summarize the 3 gate decisions and the top assumptions/risks so the user can redirect. If the
Agent/Workflow tools are available and the user wants speed, you MAY fan out one drafting agent per
Space then assemble — but inline drafting is the default and is fully sufficient.

If the user hasn't signaled a mode, ask once: *"Guided (we go step by step, you make the calls) or
auto (I draft the whole workbook from your seed, then you edit)?"*

## The method — always this pipeline order

Each concept consumes the prior ones. Never skip ahead; if a later step exposes a flaw, loop back and
revise (this is normal in innovation).

**Space 1 — Customer Problem Space** → `references/kb_space_1.md`
Customer Concept → **Fertile Land** → **Actor** → **Job To Be Done** → **Outcomes** (metric + actual +
desired values, measurement method) → **Problem** (Gap + Causes) → **Customer Journey Map** (visual,
7 layers) → **Use Cases** → **Problem Sizing** (per-instance, annualized/actor, total annual) →
**Problem Category** → **Problem Statement** (solution-free).
› **GATE 1 — Actor + JTBD:** the whole workbook hangs off this. Confirm the Actor and JTBD before
building outcomes/problem on top of them.

**Space 2 — Market Space** → `references/kb_space_2.md`
**Market** (name, # actors, trend) → **Segmentation** (same variables across segments; 6 validity
rules) → **Segment Profiles** (≥3) → **Competition** (options = competitors; ≥1 category + ≥1 product)
→ **Positioning** (customer evaluation criteria → current-state map → white-space → future-state map →
**Position-to-Own**) → **Market Focus**.
› **GATE 2 — Market Focus:** 5 *aligned* decisions — segment, niche, use case, problem, position — to
target first. Everything downstream serves this focus. Confirm it.

**Space 3 — Solution Space** → `references/kb_space_3.md`
Idea generation → **MVP Product Concept Outline** (9 parts) → **User Views** (happy-path sequential
list + storyboard/screen-flow/prototype) → **Functional Requirements** (user-story format, 5 rules) →
**Context View** (diagram) → **Non-Functional Requirements** (the applicable ones of 9).
› **GATE 3 — MVP concept:** the product idea itself. Confirm the concept before writing requirements.

**Space 4 — Customer Value Space** → `references/kb_space_4.md`
**Features → Benefits** (quantify ≥1; 3 sources) → **Customer Value** → **Customer Costs** (TCO) →
**Pricing Model** (strategy, metric, price, payment) → **Value Proposition Evaluation**
(Benefit-to-Cost Ratio) → **TAM** → **Product Idea Brief** (prose, done last).

## Operating rules (apply in both modes)

- **Be faithful to the method.** Each concept has exact rules, templates, and thresholds — pull them
  from the relevant `references/kb_space_N.md`; don't wing definitions or formats.
- **Numbers matter.** Quantify outcomes, problem size, TAM, benefits, and prices. Cite a credible
  source for real data; when you assume, say "Assumption:" and show the logic.
- **Solution-free where required:** Outcomes, Problem, and Problem Statement describe the customer's
  world, not your product. Functional requirements say *what/why*, not *how*.
- **Stay in the customer's perspective** (the Actor's), especially for competition, criteria, and
  positioning — not a product-centric view.
- **Keep labels as labels.** Actor, metric, use case, problem category, position-to-own are short
  labels/phrases, not sentences or explanations.
- **Coherence — reconcile the parts, not just the counts.** When you split a golden-thread metric into pieces (per-segment waste $, willingness-to-pay, rates), the size-weighted average of the pieces must equal the headline Actor-level figure within rounding — i.e. (sum of size×value across segments) ÷ (total size) ≈ the anchor. Derive the splits from the headline, or adjust them so they reconcile. (Segment *counts* must also sum to the market.)
- **One value basis.** Use the SAME annual value figure for pricing and for the Benefit-to-Cost Ratio. If you discount value by a realization probability to set the price, use that same discounted value in the BCR and re-check it still clears the friction threshold; otherwise keep full value in both and record the probability only as a named Value Risk. Either way, the share you take as price caps the ratio before you run it: BCR ≤ value ÷ price, so to clear a T:1 bar the share must be at most 1/T − (monetized non-price costs ÷ value) (kb_space_4 §6, "Price-share ceiling"). A ~¼ share only fits a low-friction purchase.
- **A root cause is not your solution inverted.** A root cause must be a structural/behavioral condition, never "there is no [thing my product provides]." If the final "why" reads as your value proposition negated, stop one why earlier at the real cause — otherwise the solution leaks into the solution-free Problem Statement.
- **Positioning uses the customer's criteria.** Evaluation-map criteria come from the customer's Outcomes and Cost items (effort, decision time, dollars, price, quality/variety) — never restate one of your own starred Main Attributes as a criterion, and phrase the "white space" as an unmet customer *need*, not a description of your product. In auto mode, lock the criteria before finalizing the MVP so differentiators can't bleed backward into the axes.
- **Self-check every section** against `references/QUALITY_RUBRIC.md` before calling it done.
- **Maintain one living workbook file** — update it after each section so progress is never lost.

## Running a session

1. **Seed & mode.** Get the seed (Fertile Land, rough idea, or Actor) and the mode.
2. **Start the workbook.** Copy `assets/workbook-template.md` to a working file. Ask where to save it;
   default to `./<product-slug>-workbook.md` in the current directory.
3. **Run the pipeline** per the mode above, Space by Space, updating the file as you go. Fill visuals
   (journey map, positioning maps, context view) as clearly-labeled text/tables or ASCII when a real
   image isn't being produced, and note that a visual should replace them.
4. **Finish:** write the **Product Idea Brief** (prose, executive audience, ~2 pages, first 4 of the 7
   parts), then the TAM. Offer to export the workbook to `.docx` (e.g. via `pandoc workbook.md -o
   workbook.docx` if available) or to a Google Doc.

## Resources

- `assets/workbook-template.md` — the blank Workbook to copy and fill.
- `references/PM_KNOWLEDGE_BASE.md` — master index: the pipeline, concept dependency map, and
  workbook-section ↔ concept mapping. Read this first for orientation.
- `references/kb_space_1.md` … `kb_space_4.md` — per-Space concept specs: definition, rules,
  templates, worked examples, coaching questions, and inputs/outputs for every concept.
- `references/QUALITY_RUBRIC.md` — per-Space quality gates, failure modes, and strong-vs-weak signals
  to pressure-test each section.
