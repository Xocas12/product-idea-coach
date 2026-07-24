# Product Idea Coach

A [Claude Code](https://docs.claude.com/en/docs/claude-code) **skill** that turns a rough idea or problem area into a complete, rigorously-specified product concept — the customer-side of product management, worked end to end.

It walks (or auto-drafts) the full pipeline:

**Customer Problem → Market → Solution → Customer Value**

and produces a **Product Idea Workbook**: Actor, Job-To-Be-Done, measurable outcomes, problem + causes, customer journey map, use cases, problem sizing, market segmentation, competition, positioning, market focus, MVP product concept, user views, functional + non-functional requirements, context view, features & benefits, pricing model, customer costs, value proposition, TAM, and a two-page product brief.

> Governing principle: **"Build the right product before you build the product right."** The #1 reason new products fail is *no market need* — so most of the work is nailing the customer's problem before committing to a solution.

## Two modes

- **Guided coach** (default) — goes one concept at a time: teaches the concept, asks the coaching questions, drafts the section, pressure-tests it against a quality rubric, and stops for *your* decision at the three gates (Actor + JTBD, Market Focus, MVP concept).
- **Auto-generator** (one-shot) — give it a seed (a problem area, a rough idea, or just an Actor) and it drafts the whole workbook in one pass, stating its assumptions and the decisions it made at each gate.

## What's inside

```
product-idea/                    ← the skill (copy this into ~/.claude/skills/)
├── SKILL.md                     ← the skill: both modes, pipeline, gates, rules
├── assets/
│   └── workbook-template.md      ← the fillable Product Idea Workbook
└── references/
    ├── PM_KNOWLEDGE_BASE.md       ← master index + concept dependency map
    ├── QUALITY_RUBRIC.md          ← per-Space quality gates & failure modes
    └── kb_space_1..4.md           ← per-concept specs (definition, rules,
                                      templates, examples, coaching questions)
```

## Install

**Claude Code (user-level skill):**

```bash
git clone https://github.com/Xocas12/product-idea-coach.git
cp -r product-idea-coach/product-idea ~/.claude/skills/
```

Then in Claude Code, invoke it with `/product-idea`, or just ask to "develop a product idea," "size this market," "write requirements / a product brief," etc. — the skill is triggered by those tasks.

To update, `git pull` and copy again.

## Usage

- **Guided:** `/product-idea` → it asks for your seed and mode, then coaches you Space by Space, maintaining a `*-workbook.md` file as you go.
- **Auto:** `/product-idea auto <your seed>` → a full workbook draft in one pass, which you then edit.

The output is a Markdown workbook; export to `.docx` with `pandoc workbook.md -o workbook.docx` if you like.

## The method (at a glance)

| Space | You define… | Key gate |
|---|---|---|
| **1 · Customer Problem** | Fertile Land → Actor → JTBD → Outcomes (metric + actual/desired) → Problem (gap + causes) → journey map → use cases → problem sizing → problem statement | **Actor + JTBD** |
| **2 · Market** | Market → segmentation → segment profiles → competition → positioning (position-to-own) → market focus | **Market Focus** (5 aligned decisions) |
| **3 · Solution** | MVP product concept (9 parts) → user views (happy-path) → functional requirements → context view → non-functional requirements | **MVP concept** |
| **4 · Customer Value** | features → benefits → customer value → costs (TCO) → pricing model → value-proposition evaluation (benefit-to-cost ratio) → TAM → product idea brief | — |

The whole thing is judged on **coherence**: the same 2–3 core numbers should run verbatim from the outcome gap → quantified value → price → benefit-to-cost ratio → TAM.

## Attribution & disclaimer

This is an **independent, unofficial study aid.** The product-management method it operationalizes is credited to the **Product Management Essentials** course taught by **Prof. Jim Berardone at Carnegie Mellon University**. This project is **not affiliated with, authorized by, or endorsed by** CMU or the instructor. The reference material here is a **paraphrased synthesis** created for personal learning — it is not a copy of the course slides, readings, or any student's work, and all examples of others' work have been de-identified. Core concepts referenced (Jobs-To-Be-Done, market segmentation, positioning, value-based pricing, etc.) are widely established product-management practice. If you want the real thing, take the course.

Use it to learn and to structure your own product thinking. Verify any facts, market figures, and sources it produces before relying on them.

## License

Code and original text in this repository are released under the [MIT License](LICENSE). The disclaimer above governs the underlying methodology and attribution.
