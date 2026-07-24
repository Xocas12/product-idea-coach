# Coaching Guide — Solution Space (Product Management Essentials)

> *Independent study reference. This is a paraphrased, independently written guide to the Solution Space method taught in CMU 17-619 (Product Management Essentials I). It is not official course content, and all examples here are either public products or anonymized composites.*

**Scope:** This is a coaching guide for the **Solution Space**, the third of the method's four Spaces (Customer Problem → Market → **Solution** → Customer Value). It covers everything from Sessions 9 and 10 ("Solution Space – part 1" and "Solution Space – part 2: Context View and Requirements"), reinforced with the Idea-Generation reading, the "Common Categories of Requirements" and "11 Common Non-Functional Requirements" quick references, the Happy-Path prototyping workshop, and patterns pulled from a set of completed practice workbooks.

**What the Solution Space produces (its 5 artifacts, in order):**
1. **MVP Product Concept Outline** (9 parts)
2. **User Views** (Happy-Path list + at least one of: storyboard / screen-flow / prototype)
3. **Functional Requirements** (user stories)
4. **Context View** (context diagram)
5. **Non-Functional Requirements** (the course's 9 quality attributes)

**The gate you enter from — the Market Focus.** Before Solution Space begins, the student has committed to a **Market Focus**: targeted market segment(s), targeted niche(es), targeted use case(s), targeted problem(s), and targeted position(s)-to-own. The instructor's exact framing:

> "With a Market Focus, we can create a **Product Focus** = a **Minimal Viable Product** to serve the Market Focus."

So the whole Solution Space answers one question: **"What will your first product (MVP) be that solves the problem you stated, for the market focus you chose?"** Every artifact below must trace back to that focus. If a feature, screen, or requirement doesn't serve the targeted problem/position/segment, it doesn't belong in the MVP.

**Course product constraints (from Session 9, slide 11) — enforce these on any idea:**
- It **must be a technology-based product idea** (software tech and/or physical tech — smart wearable, robot, etc.).
- It does **not** have to be technically feasible today (for this course).
- It **cannot be**: a data-only product, a model-only product, or an API-only product. (It must be a usable product a customer interacts with, not just a dataset/model/endpoint.)

---

## 0. Idea Generation (generate-then-judge)

### (a) Definition
Idea generation is the divergent front-end of the Solution Space: producing **many** candidate product ideas that could solve the stated customer problem, *before* narrowing to one MVP. The governing principle is **generate first, then judge/select later** — separate *conceiving* solutions from *selecting* them (diverge, then converge). The design-thinking funnel is **Customer → Problem → Solution → Idea** (attributed to Tim Brown, *Change by Design*).

### (b) Rules / constraints the course enforces
- **Generate many ideas.** Course rationale (Session 9, slide 8): "Initial ideas are usually obvious and familiar. More ideas leads to more variations → higher chance of a strong idea. Innovation often is the result of combining fragments of ideas. Bad ideas can lead to good ideas."
- **Defer judgment.** "Evaluation shuts down the creative process. Keep it open longer." Do not critique during generation.
- **Diverge then converge** — never mix conceiving and selecting in the same breath.
- **Anchor with a specific prompt.** Vague sessions fail. Start every session from the problem artifacts you already have: Problem (gap + cause), Actor/JTBD/use case, problem magnitude, target segment/niche, target position(s).
- You may generate ideas **on your own, by asking others, in a group, or with one or several genAI tools.**
- Building rule (from the readings): say **"yes, and"** to build on ideas; never **"yes, but"** — the built-in negative comment stifles creativity.

### (c) Templates / methods (the course's idea-generation menu)
The course lists these methods; the ones with exact recipes are the ones to drill.

| Method | Recipe / numeric spec |
|---|---|
| **Brainstorming** (Osborn) | Quantity over quality; no criticism; build on others' ideas; welcome unusual ideas. Anchor to a specific prompt. |
| **SCAMPER** | Examine an existing solution from 7 angles: **S**ubstitute, **C**ombine, **A**dapt, **M**odify, **P**ut to another use, **E**liminate, **R**everse. One fill-in question per letter (e.g., "What if we combined X and Y?"). |
| **Crazy Eights** | 8 boxes, 8-minute timer, 8 quick sketched ideas per person; then share and repeat. |
| **6-3-5 (brainwriting)** | 6 people × 3 ideas × 5 minutes, pass to the right, repeat 6 rounds = **108 ideas in 30 min**. Post-process: delete duplicates → cluster → vote on top cluster. Gives individual work during divergence, group work during convergence, and deliberately slows the process. |
| **Round Robin** | One person shares an idea; each person in turn adds one that builds on prior ideas ("yes, and"). |
| **Structured Brainstorming** (Coyne/Clifford/Dye) | Take an existing solution → pose a concrete question about it → probe the answer (e.g., "Can we productize it? What technology has changed most since it was created?"). |
| Also named (menu): TRIZ, Six Hats Thinking, Storyboarding, Prototyping, Welcome unusual ideas, Flip bad ideas, Wishing. |

**GenAI prompts the course suggests (Session 9, slide 10):**
- "How might you (we) solve this problem?"
- "How might you change the customer journey to get better outcomes?"
- "How could you use the latest technology to change how the JTBD gets done?"

### (d) Worked examples
- *SCAMPER on a grocery-delivery product:* Eliminate → "What if we removed the store visit entirely?" → warehouse-to-door micro-fulfillment. Reverse → "What if the courier arrives before the order is finalized?" → predictive dispatch.
- *6-3-5 payoff:* the course's own math — 6 rounds → 108 ideas in 30 minutes, then dedupe → cluster → vote.

### (e) Common mistakes / anti-patterns
- **Anchoring on one idea too early** — locks you onto a costly, hard-to-change path and hides a better idea.
- Running a **vague** session (no specific prompt).
- **Criticizing during generation** ("yes, but") — kills flow.
- **Discarding crazy/bad ideas** instead of toning them down or flipping them.
- Skipping straight to a single obvious solution (the first idea is usually the familiar one).
- **Not using the problem artifacts as the seed** (generating in a vacuum).

### (f) Coaching questions
1. "You've written the problem, actor, JTBD, and position-to-own — read them back. Now, *how might we* solve this? Give me 10 ways, no filtering."
2. "Pick your favorite existing solution to this problem and run SCAMPER on it — what happens if you *eliminate* its most central step?"
3. "What's the craziest, most infeasible version of this? Now tone it down one notch — is that feasible?"
4. "How could agentic AI or the newest tech change *how the JTBD gets done*, not just make the old flow faster?"
5. "Which two of your ideas could combine into a stronger third?"
6. "Which idea best serves your *targeted position-to-own* — and which are you keeping only because it was first?"

### (g) Inputs it consumes / outputs it produces
- **Consumes:** Problem (gap + cause), Actor/JTBD/use case, problem size, target segment/niche, target position(s) — all from the Customer Problem and Market Spaces.
- **Produces:** one chosen MVP product idea, which feeds directly into the **Product Concept Outline** (§1). The instructor notes the end of idea generation is a **Product Concept** expressed as: concept outline + requirements + Context View + User Views.

---

## 1. Product Concept Outline (the 9 parts)

### (a) Definition
The Product Concept Outline **captures the key characteristics of your MVP product idea** in a fixed 9-part structure. It's the first Solution Space artifact — a compact spec that names the product and defines what it is, what it does, what you deliver, how users interact with it, where it runs, and what data it needs.

### (b) Rules / constraints per part
The 9 parts (Session 9, slide 48), with the course's rule for each:

1. **Product Name** — a unique temporary or permanent name. Make it memorable, distinct, easy to say. Consider future product-line expansion. Trademarks are valuable/protectable *within a product class*; in the USA register with USPTO; the Madrid System covers international registration. Names build brand identity.
2. **Purpose** — the **primary task** for which the product will be used. *Could* be the same as your JTBD. Ask: "What is the primary task this product is used to do?" (Examples: Zoom Meetings = conduct video meetings; Uber Ride = hail a ride to a destination.)
3. **Product Category** — the existing category your product fits into (contains products *most similar* to yours; needn't be a perfect match — you differentiate *within* it). **Rule: submit evidence the category exists (e.g., a screenshot).** Or create a new category (advantage: you're the only one; disadvantage: huge cost/time to build awareness of both the category and the product). Category names evolve ("Peer-to-Peer taxi" → "e-Hail" → "Ride Sharing" → "Ride Hailing").
4. **Main Attributes** — the key **capabilities** (core functionality + information produced, including the unique functions/features that create the desired **positions**), plus **properties and form** for physical products (size, material, weight, color, shape, arrangement, packaging).
5. **Software Deliverables** — the digital items you'll produce (if applicable). A deliverable is *something that is produced*.
6. **Physical Deliverables** — the physical items you'll produce (if applicable).
7. **Input/Output Methods** — the method(s) customers use to interact with the product. Each one affects UX and dev complexity/cost.
8. **Product Infrastructure** — the computing environment(s) the product runs in to serve customers. **Choose from the fixed list.**
9. **Product Data** — the sources and characteristics of **external** data used by the product (external = originates outside the product). Data can be structured/unstructured, static/live. Using existing external data is often more cost-effective than collecting internally.

**Course menus you select from (these are the allowed choice-sets):**
- **Software Deliverables:** iOS app, Android app, Web app (runs in browser), Windows desktop app, macOS desktop app, browser extension/plug-in, cross-platform/hybrid mobile app, cross-platform desktop app, smart-TV app, smart-wearable app, AR/VR app, smart-glasses app, gaming-platform app, API service (+ your own).
- **Physical Deliverables:** smart wearable, smart-home device (needs IoT), domestic task robot, drone, personal transportation device, wellness device (non-prescription), medical device (prescribed), professional-grade monitoring device, fleet/asset tracking device, gaming console, gaming/entertainment accessory, point-of-sale hardware (+ your own).
- **Input/Output Methods:** digital keyboard, physical keyboard, mouse/trackpad, touchscreen, visual display, joystick/gamepad, voice commands, voice conversational, text conversational, motion/gestures (contactless), haptic feedback, biometric inputs, camera/scanning, audio output, LED indicator, AR overlay, VR (+ your own).
- **Product Infrastructure (choose from this list only):** **Public cloud** (shared) / **Private cloud** (dedicated, high-security/regulatory) / **On-Premise** (customer's own servers) / **Hybrid** (cloud + on-prem for complex enterprise) / **Standalone** (runs on a device, mostly without cloud).
- **Key Product Capabilities (a bank to select/add from):** Identity/Doc Verification, Search & Discovery, Workflow Automation, Collaboration & Sharing, Community/Social, Gamification, Scheduling & Booking, Communication & Messaging, Notifications & Alerts, Automated Reporting/Updating, Analytics & Insights, Behavioral Tracking & Pattern Analysis, Live Data Streams, Content Management, Media Content & Editing, Purchase Transactions, Subscription/Membership Management, Personalization, Advanced Math Computations, Educational/Learning Management, Multi-device Sync, Offline Functions, ML, Autonomous Navigation, Location & Proximity, Location & Mapping, Speech & Voice AI, Standard GenAI, Custom GenAI, Robotic Process Automation, Autonomous AI Agents.
- **Product Data characteristics to assess:** Sources (where from), Completeness (sufficient/consistent? needs cleaning/validation/transform?), Timeliness (update frequency; static vs live feed), Usage (legal right to use for the purpose; restrictions?), Technical (access method — API/bulk load; format — JSON/XML).

### (c) Template (fill-in-the-slots)
```
1. Product Name:            [unique, memorable name]
2. Purpose:                 [the primary task the product is used to do]
3. Product Category:        [existing category + EVIDENCE it exists]  (or: new category + name)
4. Main Attributes:         [capabilities/features that create the positions] + [properties/form if physical]
5. Software Deliverables:   [pick from menu, or "None"]
6. Physical Deliverables:   [pick from menu, or "None"]
7. Input/Output Methods:    [pick from menu]
8. Product Infrastructure:  [Public cloud | Private cloud | On-Premise | Hybrid | Standalone]
9. Product Data:            [external source(s)] + [source/completeness/timeliness/usage/technical notes]
```

### (d) Worked examples (from the course)
**Google Maps:**
1. Google Maps · 2. To find and navigate to places · 3. Digital Navigation & Mapping Services · 4. Turn-by-turn nav (drive/walk/bike/transit), real-time traffic, incident reporting, Street View, immersive 3D, offline maps, place search, user contributions, Google-services integration · 5. iOS/Android/Web apps + API service · 6. None · 7. Text, voice, touch, GPS signals, audio output, AR overlays · 8. Public cloud (GCP) · 9. NASA satellite imagery, live Waze traffic, Google Business Profiles/business-data providers/reviews, US DOT boundary data.

**iRobot Roomba S9:**
1. iRobot Roomba S9 · 2. To automate household floor cleaning · 3. Robotic Vacuum Cleaners (under Smart Home Appliances) · 4. vSLAM+LiDAR nav, self-emptying Clean Base, high suction, smart room mapping, app+voice integration, scheduling, Dirt Detect · 5. iOS/Android apps + Alexa/Google Home integrations · 6. Robot unit, Clean Base station, charging dock, replaceable bags/filters/brushes · 7. Text, voice, device buttons, audio beeps, LED, cameras, sensors, Wi-Fi · 8. Standalone (embedded firmware) + Public cloud (apps/updates) · 9. Cleaning schedules from smart-home products.

**Strong exemplar pattern:** one strong workbook used a labeled spec block — Name, Category, Purpose, Main Attributes, Key Technology (all-in-one record/edit + ML editing + secure cloud + CDN), Operating Requirements, Form/Format (web app) — plus a short "How It Works" flow that maps 1:1 back onto the desired ≤4-step outcome. This is the model: the concept outline's attributes and the "how it works" must reconcile with the problem's desired outcome.

### (e) Common mistakes / anti-patterns
- **Purpose written as a feature list**, not the *primary task* ("does X, Y, Z" instead of "to [verb] [object]").
- **Product Category with no evidence** it exists — the course explicitly requires a screenshot/proof.
- **Inventing a new category casually** without acknowledging the awareness-building cost.
- **Main Attributes disconnected from positions-to-own** — attributes should create the differentiation you chose in Market Focus.
- Picking infrastructure that isn't one of the 5 allowed choices.
- Listing **internal/derived** data under Product Data (it must be *external* — originating outside the product).
- A generic name that isn't distinct/protectable within its class.

### (f) Coaching questions
1. "State your Purpose as one primary task: 'to [verb] [object].' Is that the same as your JTBD, or narrower?"
2. "Which existing product category do you fit — and can you show me a screenshot proving that category exists?"
3. "Which of your Main Attributes actually *creates* your position-to-own? Cross out the ones that don't."
4. "What exactly are you delivering — an iOS app? a web app? a physical device? Pick from the menu."
5. "Where does this run — public cloud, private cloud, on-prem, hybrid, or standalone — and why that one for *this* customer?"
6. "What *external* data does it need, and can you legally use it for this purpose? Is it static or a live feed?"

### (g) Inputs / outputs
- **Consumes:** the chosen MVP idea (from §0) + Market Focus (positions-to-own especially).
- **Produces:** the concept scaffold that seeds every downstream artifact. In particular, **Main Attributes → Product Features → Functional Requirements**; **Input/Output Methods + Infrastructure + Product Data → Context View entities + Interoperability/Compatibility NFRs**; **Purpose + Category → Value Proposition framing** (in the next Space).

---

## 2. User Views

### (a) Definition
User Views are **artifacts created to communicate what the user will *see, do, and get* while using your product to achieve their desired outcome.** They convey the **path** the user takes through the product. Used by: the **product team** (to begin designing/architecting/developing), **potential customers** (to validate the idea and deepen problem understanding), and **business leaders** (to gain support).

**Types the course names:** Sequential list, Storyboard, Screen/page flow diagram (sketch → wireframe → mockup), Journey map, Task-flow/flowchart, Swimlane, UML Use-Case diagram, Interactive Prototype, and physical-product views.

### (b) Rules — the Happy-Path (the spine of all User Views)
The **Happy-Path** is "the ideal, most straightforward sequence of steps a user takes with your product to successfully achieve their desired outcome. It's the best-case scenario — assumes no errors or issues." Its purpose: **get started** before addressing complex situations, and **focus on the core value** and the key items to design/develop.

**Happy-Path construction rules (Session 9, slide 17):**
- **Focus on the core flow** through your product.
- **Do NOT include** account setup, login, or personalization preferences, or alternative flows — *unless they are the focus of your product* (e.g., a password-management app).
- **Do NOT include** errors, exceptions, or optional features.
- **DO include:** the **decisions** a user makes, the **info the user provides**, and the **info the user gets back**.
- **Seek to minimize the steps** the user needs to take.

**Product-idea requirement (assignment):** the deliverable is a **Happy-Path list + at least ONE of {Storyboard, Screen/page flow diagram, Interactive Prototype}.**

### (b1) Sub-artifact — Sequential List
A written, **sequentially numbered** sequence of steps to achieve the desired outcome. Includes: the **entry point**, each numbered **step**, the **product's responses**, and the **completion point**.

**Steps to create (Session 9, slide 22):**
1. Identify the JTBD and Desired Outcome.
2. Select **a use case**.
3. Identify the **entry point** (where does the user begin?).
4. List the **sequence of actions** to achieve the desired outcome.
5. Determine the **product's behavior (response)** for each action.
6. Identify the **completion state**.

**Tips:** Be complete ("Will this lead to the desired outcome / solve the problem?"). Don't forget the product's responses. Multiple use cases → build one per use case, then abstract into one flow covering most. Multiple actors or multiple JTBDs → each likely takes a different path.

*Course example — Google Maps happy-path:* 1. Launch app (opens to current location) → 2. Search for destination → 3. View destination details (location card) → 4. Start directions → 5. Choose mode of travel (defaults to driving) → 6. Confirm route (app shows ETA; tap Start) → 7. Follow navigation (turn-by-turn voice+visual) → 8. Arrive ("You have arrived").

### (b2) Sub-artifact — Storyboard
A **visual narrative** (comic-strip panels) illustrating the steps the user takes; conveys what the journey *feels* like and *why the product matters*; shows how the product solves a real problem ("like a short movie"). **Builds on the Sequential List.**

**Typical structure (8):** Introduce the user → Show context → Present the problem → (optional) current workaround → Introduce your product → Show how it's used → Show outcome → Reinforce the change in outcome.
**Tips:** Draw a grid; **8–16 panels** is common at this stage; go top-left → bottom-right; from the user's perspective ("how will they get the Job done?"); consider starting from the first moment they *hear about* your solution.

### (b3) Sub-artifact — Screen/Page Flow Diagram
A visualization of the screens/pages the user sees, including: **entry point, each step, product responses, the navigation path (arrows/connectors), completion point.** Three types by increasing fidelity:
1. **Sketches** — quick (paper + photos).
2. **Wireframes** — structural, low-detail (Balsamiq-style).
3. **Mockups** — detailed, realistic; helps when sharing with key stakeholders.

The course explicitly notes wireflow gaps to avoid: don't drop the **entry point** or the **completion point** (e.g., a shopping-cart wireflow "is missing the entry point" and "the completion point is missing — get payment confirmation"). "These lead to product features and requirements."

### (b4) Sub-artifact — Interactive Prototype
"A simulation of your product that allows a user to interact with it during their path, as if it were the real product. It looks real, feels real, but it's not ready to work properly." Built with Figma/Proto.io/Miro, or increasingly LLM tools (Google AI Studio, Replit, Claude Code, Lovable, Copilot Studio). Purpose: **validate the flow** ("Is this the right flow?"). Includes: entry point, each step **with realistic content**, **interactive** (clickable/touchable) actions, **realistic responses**, completion point.

**Happy-Path prototype workshop discipline (from the workshop reading):** canonical shape = **entry screen → small input → meaningful output → confirm/save/finish.** Tight scope = **3–5 screens, one core flow.** Minimum prompt structure for an AI build: App idea (2–3 sentences), Happy path (3–8 steps), Screens, Data + examples, Constraints (what you're NOT building in v0). Success test: **"Can someone understand the product and see the happy path work?"** Deliverable options: a short **storyboard PDF** (one screenshot/step, 2–3 line captions) or a **2–3 min screen recording.**

### (b5) User Views for physical products
Physical products need User Views too. Common types (Session 9, slides 39–43):
- **Sketches** — freehand/digital drawing of shape, appearance, key features (e.g., a bike helmet sketch conveying key form, its 3 parts — helmet/strap/fastener — and how it's worn; "these lead to product requirement statements").
- **Exploded-view diagrams** — components pulled apart.
- **Orthographic projections** — front/side/top views (conveys key form, parts, properties, handling).
- **Isometric renderings** — product in perspective.
- **Context-of-Use diagrams** — the product in its use environment (a use case illustration).
- **Instructional views** — how to operate/handle (e.g., a webcam).

### (c) Templates (fill-in)
**Sequential List:**
```
Use case: [chosen use case]   JTBD: [__]   Desired outcome: [__]
Entry point: [where the user begins]
1. [User action] → [product response]
2. [User action / decision + info provided] → [product response / info returned]
...
n. Completion: [the user is done — desired outcome achieved]
```
**Screen-flow:** `[Entry screen] →(arrow)→ [Input screen] →→ [Result screen] →→ [Edit/adjust] →→ [Confirmation]`, each box labeled with what the user sees/does and the product's response.

### (d) Worked examples
- **Google Maps sequential list** (above) and its wireframe screen-flow: Search for destination → View destination details → Start directions (tap Start) → Follow directions (on-screen + voice) → Arrival announced.
- **YouTube happy-path:** Start app → Video discovery/search → Select a video → Video playback → (optional) adjust settings → (optional) engage (like/comment/subscribe) → Video ends (recommendations shown). Note how *optional* steps are marked optional — the required spine is what matters.
- **Strong exemplar (a dental-appointment booking MVP):** a 4-step storyboarded flow with a wireframe per step — Home/appointment selection (3 ranked date preferences) → Choose your dentist → Personal & billing details + medical checklist → Confirmation & summary with emailed receipt. Clean happy-path: no login screen, no error handling, exactly the core value path.

### (e) Common mistakes / anti-patterns
- **Including login/setup/personalization** in the happy path (unless that IS the product).
- **Including errors/exceptions/optional features** — clutters the core flow.
- **Dropping the entry point or completion point** (the two most-forgotten pieces — the course flags both explicitly).
- **Forgetting the product's responses** — a list of user actions with no system feedback isn't a User View.
- **Too many steps** — not minimizing the path.
- **Not selecting a use case first** — the flow becomes vague/generic (the course discussion question: "What was the significance of selecting a use case?").
- Prototype prompts that are **too vague** ("make an app that helps students") or **too big** ("handle every feature and edge case").

### (f) Coaching questions
1. "Which single use case are we drawing the happy path for? (Pick one.)"
2. "Where does the user *begin* — the entry point — and where are they *done*? Name both explicitly."
3. "Walk me through each step: what does the user do, what info do they give, and what does the product show back?"
4. "Which steps here are login/setup/error handling? Unless the product IS about those, cut them."
5. "Can you make this shorter? Imagine a simpler journey — could agentic AI collapse two steps into one?"
6. "Which one visual view will you add — storyboard, screen-flow, or interactive prototype — and who's the audience (team, customers, or leaders)?"

### (g) Inputs / outputs
- **Consumes:** JTBD, desired outcome, chosen use case, and the Product Concept Outline (Main Attributes, I/O methods).
- **Produces:** the primary source for **Product Features** (Session 10, slide 15: "Identify product features by using your Product Concept Outline, User Views, and Context View diagram"), which become **Functional Requirements**. User Views also surface **Latency** requirements (which steps feel instantaneous vs. can wait) and **Usability** requirements.

---

## 3. Functional Requirements

### (a) Definition
**Two classes of product requirements:** *Functional* and *Non-functional*.
- **Functional requirements** state the specific **tasks, behaviors, activities, and information** the product must do or enable the user to do — **"what the product must do."**
- (Non-functional requirements state **"how well the product must perform"** — see §5.)

Requirements are **buildable instructions for how features must work.** A complete set is needed to create the product; the built product must satisfy them before release; they're collected in a **PRD (Product Requirements Document).** Used by the whole team: PM (create/prioritize), UX Designer (translate to flows), Software Architect (design system), Software Engineer (implement + unit-test), Test Engineer (write test cases + verify).

**Feature vs. requirement:** *Product Features become Product Requirements.* The course uses "feature" loosely for functionality/features/capabilities/properties (a feature = a characteristic of the product). You **identify features from your Product Concept Outline, User Views (Sequential List, screen-flow, prototype), and Context View**, then write **≥1 functional requirement (user story) per feature.**

### (b) The 5 rules (Session 10, slide 33) + solution-free tip
Every requirement statement must be:
1. **Singular** — no multiple requirements packed into one statement.
2. **Unambiguous** — "if it isn't, you won't get what's needed."
3. **Verifiable** — you must be able to prove it was completed and satisfied.
4. **Uniquely identified** — a unique number to trace development and testing.
5. **Valuable** — satisfying it creates value for the customer.

**Solution-free tip (critical):** "Be **solution-free**. Avoid specifying the solution or feature. Focus on **who, what, why** — not on *how* it should be implemented." This leaves room for potentially better ideas. (Write *what the user needs and why*, not the widget.)

### (c) Templates — user-story format (5 variants)
A user story is a short requirement written **from the user's perspective**, focusing on what the customer wants/needs to do and why.

**Primary template:**
> **As a `<actor>`, I need `<action>` so that `<outcome>`.**
> *Example:* "As an automobile driver, I need to know the remaining fuel so that I can minimize trip delays."

**Legend:** `<Actor>` = your actor's label · `<Action>` = something they want to do/be/have · `<Outcome>` = the result/experience they want when the action completes (the *why*).

**The 4 additional templates:**
1. `As a <actor>, I need <action> so that <outcome>.`
2. `As a <actor>, I want <action> so that <outcome>.`
3. `When <use case>, I want to <action>, so I can get <outcome>.`
4. `As a <actor>, I want to <action> so that some <outcome>.`

**Numbering:** give each a unique ID (e.g., F1, F2 … or 1.1, 1.2 for sub-requirements under one feature).

### (d) Worked examples (from the course)
- Feature *Share screen* → "As a meeting host, I want to share my screen so attendees can follow me."
- Duolingo — Feature *Initiate a new lesson* → "As a language learner, I want to start a new lesson to develop my skills." Feature *View word meanings* → "As a language learner, I want to view the meaning of a word so I can save time searching for a translation."
- Google Maps — Feature *Display routes* → "2. As a driver, I want to see up to 3 possible routes to my destination so that I can choose the best path for me."
- Amazon — Feature *Search for products* → "1.1 As a shopper, I want to search for products **by keyword** so that I can quickly find items that meet my needs." (1.2 by category, 1.3 by brand — note singular requirements split rather than "by keyword, category, and brand" in one line.)
- More: "As a Pricing Manager, I need to drill-down into a pricing-scatter diagram so I can decide on a price in less than 2 minutes." (Note the *verifiable* threshold.)

**Strong exemplar pattern:** one workbook wrote "As a shopper, I want a search option, so that I can get a filtered list of items I want to buy," with requirements tagged F1–F11 and grouped under feature themes. Several strong workbooks split into Functional (Fn) vs Non-Functional (NFn) and tag each to a feature subgroup.

### (e) Common mistakes / anti-patterns
- **Multiple requirements in one statement** (violates *singular*) — e.g., "search by keyword, category, and brand" should be three.
- **Specifying the solution/implementation** (violates solution-free) — "I want a dropdown that…" instead of "I want to filter results so that…".
- **Unverifiable/vague** — "the app should be fast/easy" (no way to prove satisfaction).
- **No unique ID** — can't trace to tests.
- **No outcome ("so that…")** — a feature restated, not a requirement (no *why*/value).
- **Writing from the system's perspective** instead of the user's.
- **Requirements orphaned from features/User Views** — every requirement should trace to a feature identified from your concept outline / User Views / Context View.
- (From the "15 categories" reading) considering only functional/performance needs and **missing whole categories** (operational, compliance, emotional, etc.). A functional requirement usually has **inputs → task → output.**

### (f) Coaching questions
1. "List your product's features straight from your User Views and Concept Outline — then we'll write ≥1 requirement per feature."
2. "Rewrite this as `As a [actor], I need [action] so that [outcome].` What's the *outcome* — the why?"
3. "Does this statement contain more than one requirement? If yes, split it."
4. "How would a Test Engineer *prove* this is satisfied? If you can't state that, it's not verifiable yet."
5. "Are you describing *what the user needs* or *how you'll build it*? Strip out the 'how' — stay solution-free."
6. "What's the unique ID, and which feature does it trace back to?"

### (g) Inputs / outputs
- **Consumes:** Product Features (derived from Product Concept Outline + User Views + Context View).
- **Produces:** the functional half of the **PRD**; drives UX flows, system design, code, and test cases. Sets up the **Value Proposition** (features → benefits) in the Customer Value Space.

---

## 4. Context View (Context Diagram)

### (a) Definition
A **Context View diagram** is a **product-centric visualization that shows all the *external* entities that will interact with the product and the data exchanged.** (a.k.a. Context Diagram.) It's a big-picture view of **your product in the context of the ecosystem it interacts with.** It **clarifies scope** (what's inside vs. outside the product). It answers three questions:
- **Who** interacts with the product? (users)
- **What other systems** interact with the product?
- **What information flows in and out** of the product?

### (b) Rules — how to create it, and what it EXCLUDES
**How to create (3 steps, Session 10, slide 5):**
1. Place **your product idea in the center.**
2. Add a **box for each external entity** that will interact with your product. *Entity = users, systems, AI agents.*
3. Add a **connecting line for the data** that flows between your product and each entity, **with an arrow for direction** and **a label summarizing the data.**

**A Context diagram does NOT show (Session 10, slide 6):**
- Product features and functionality
- Internal people or departments
- **Databases for the product** (the product's own DBs)
- Technical architecture / technical implementation
- Product infrastructure

Rationale: "These are *part* of the product that is offered to customers." The diagram is about the **boundary** — what's external — not internals. (Note the nuance: an *external* datastore another party owns can appear as an entity; your product's *own* database does not.)

### (c) Template (fill-in)
```
                 [External User A] --(data + direction label)--> [ YOUR PRODUCT ] <--(data)-- [External System X]
[External User B] --(data)-->        [ (center) ]         --(data)--> [External System Y]
                 [AI Agent / partner] <--(data)-->
```
For each connector, label: **what data**, and **which direction** (arrowhead). Entities are grouped as **Users** and **Systems** (and AI agents).

### (d) Worked examples (from the course)
- **Instructure Canvas:** Center = Canvas. Entities: Instructor (↔ course materials, gradebook/roster files), Student (↔ assignment submission, scores/feedback, notifications), TA (↔ submission notification), Panopto (↔ student credentials, recording link), OLI (↔ student credentials). Data labeled on each arrow.
- **Google Maps:** Center = Google Maps. Users: Driver (→ destination, route selection, reviews, suggested edits; ← map, routes, directions, Street Views, places). Systems: DOT (→ roads, area boundaries), Business Data Providers/Yelp (→ place details, reviews), NASA (→ satellite images), Google Business Profiles (→ verified place info), Waze (→ traffic reports; ← route/places).
- **Library Management System:** Product in center; Users = Students/Staff/Management; Organizations = Supplier; External systems = Student Database, Book Database; Data exchanged = Stock, Reports, Student info, Book Details, Requests, Replies.

### (e) Common mistakes / anti-patterns
- **Showing internal features/functionality** or internal departments — those are inside the product.
- **Drawing the product's own database** as an external entity (it's internal).
- **Showing technical architecture/infrastructure** — wrong diagram.
- **Unlabeled connectors** or **missing arrow directions** — the whole value is knowing *what data* flows *which way*.
- **Forgetting AI agents / partner systems** as entities.
- Confusing it with a data-flow or architecture diagram — it's strictly the *boundary* view.

### (f) Coaching questions
1. "Put your product in the center. Now, *who* are the human users that touch it — list every one."
2. "What *external systems* must it exchange data with to work? (Payment? Maps? Auth? A partner's DB?)"
3. "For each connector, what's the data and which direction does it flow — in, out, or both?"
4. "Is anything you've drawn actually *inside* your product (a feature, your own database, your infra)? Remove it."
5. "Does every external system you listed appear later as an **interoperability** or **compatibility** requirement? They should."
6. "Are there AI agents or third-party providers that interact with it that you haven't drawn?"

### (g) Inputs / outputs
- **Consumes:** Product Concept Outline (esp. Product Data sources, I/O methods, infrastructure) and the actor set.
- **Produces:** the primary source for **Interoperability requirements** (each external-system connector → an interoperability NFR) and input to **Compatibility** requirements; also helps identify additional **features**. The course pairs them explicitly: "Use your Context View to identify Interoperability Requirements."

---

## 5. Non-Functional Requirements (the course's 9)

### (a) Definition
**Non-functional requirements (NFRs)** state **how the product should perform and the properties it must have — "how well the product must perform."** a.k.a. **Quality Attributes / Quality-of-System Attributes.** (Also includes business requirements — branding, aesthetics, packaging, trial versions.) Each NFR is **driven by the customers' needs and expectations.** One or more may **not apply** to a given product (e.g., safety, accuracy). NFRs significantly impact **architecture design, dev/operating cost, maintenance cost, and user experience.**

The course focuses on **exactly these 9**: **Latency, Usability, Interoperability, Availability, Security, Privacy, Compatibility, Accuracy, Safety.** (Many others exist — scalability, reliability, maintainability, sustainability, etc. — but these 9 are the course scope.)

### (b) The 4 NFR-writing templates (apply the same 5 requirement rules from §3b)
1. `The <product/feature> shall <have property or capability> so that <outcome>.`
2. `The <product/feature> shall not <have property or capability> so that <outcome>.`
3. `The <product/feature> should <have property or capability>.`
4. `When <situation>, the product/feature should <have property or capability>.`

**Legend:** **"Shall" / "Must"** = *mandatory to satisfy.* **"Should"** = *desirable, a goal.* You may adapt the templates; the 5 requirement rules (singular, unambiguous, verifiable, uniquely identified, valuable) still apply.

### (b1) The 9 NFRs — definition + the course-specific level choices/targets

**1. Latency** — the ability of a product to react to user inputs/events within an acceptable time frame (time from request to response; affected by server, network, application). **The 4 course targets:**
| Tier | Range | Feel / examples |
|---|---|---|
| High latency | 1–4 s for initial data | user's thought may shift but stays patient; chatbots |
| Medium (normal) | 200 ms – 1 s | normal flow of thought maintained; news/corporate/retail full-page loads |
| Low | 2–200 ms | feels instantaneous; multiplayer games |
| Ultra-Low | < 2 ms | feels instantaneous; automated trading, industrial control, emergency response |
*Assignment rule:* identify the latency requirement for **3 key features**, selecting one tier for each. Use your **User View** to decide where users need faster/slower than normal and where they'll wait.
*Examples:* "While working on a language exercise in Duolingo, the Latency shall be **low (2–200 ms)** so it feels instantaneous to the Language Learner." / "Displaying the results of the entire lesson could have **medium** latency (200 ms–1 s) as this won't interrupt the flow of thought."

**2. Usability** — the ease with which users can learn, operate, and use a system effectively and efficiently. Factors: **Efficiency** (how fast/how many steps), **Learning** (ease of first-time basic task), **Errors** (how many/how severe/how recoverable), **Cognitive Load** (reliance on memory/mental effort). *Write as a measurable "shall."*
*Examples:* "Google Maps shall enable first-time users to begin navigation within **2 minutes** without prior instruction." / "The product shall enable first-time users to complete account setup **within 10 minutes** without external assistance." / "The app shall let users add a product to the cart within **3 clicks or less** from the homepage." / "…provide autocomplete suggestions displaying the **top 5** most relevant queries."

**3. Interoperability** — the ability of a product to interact with other systems (share/get info, or use external functionality). **Use your Context View to identify these** (each external-system connector → an interoperability requirement).
*Examples:* "Canvas shall exchange student credentials with Panopto so that multiple sign-ins are unnecessary." / "Google Maps shall get traffic reports from Waze for a provided route." / "The app shall have an API integration with a maps provider so it can provide turn-by-turn directions." / "The payment feature shall exchange payment requests with banks using the Secure Electronic Transaction (SET) protocol." *(Name the specific standard/system — HL7, FHIR, SET, a named API — not "industry standards.")*

**4. Availability** — the degree to which the product is operational and accessible when required for use (the probability it works when users need it). Expressed as a **percentage**; always < 100% due to **planned** (preventive maintenance/upgrades) and **unplanned** (corrective maintenance) downtime. **The 6 course choices ("the nines"):**
| Level | Downtime/year | Example product class |
|---|---|---|
| 90% (1-nine) | 36.5 days | internal tools, dev/test — not business-critical |
| 99% (2-nines) | 3.65 days | corporate websites, internal apps/wikis, dev/test envs |
| 99.9% (3-nines) | 8.76 hours | e-commerce, SaaS, business-critical apps |
| 99.99% (4-nines) | 52 minutes | payment processing, high-traffic web, critical APIs, financial, healthcare, mobile comms |
| 99.999% (5-nines) | 5 minutes | emergency response, telco infra, critical DB, cloud infra, HFT, med devices, industrial control, railway signaling, fly-by-wire |
| 99.9999% (6-nines) | 21 seconds | emergency response, HFT, med devices, fly-by-wire, nuclear power |
*Examples:* "Duolingo shall be available **99.99%** of the year as its Language Learners are worldwide…" / "A Duolingo exercise module shall be available **99.999%**…" / "The Duolingo Weekly Reports e-mail shall be available **99%** as this is not critical…" (Different parts of one product can have different availability requirements.)

**5. Security** — the ability to protect against unauthorized access, use, disclosure, or destruction of information and system resources. Higher security = more complex to develop/test/operate. **The 3 course choices** (chosen by *likely adversary*):
1. **LOW** — likely target of *unorganized hackers.*
2. **MEDIUM** — likely target of *organized hacker groups.*
3. **HIGH** — likely target of *nation-state actors.*
*Course examples:* "The product shall enforce a **medium-level of security** to minimize risk from organized hacker groups." *Business examples (for grounding):* MFA on all logins; log all admin actions with timestamps, retain ≥ 12 months; auto-terminate inactive sessions after 15 minutes.

**6. Privacy** — the ability to control how personal information is shared, stored, and accessed (a.k.a. data privacy). About protecting personal/organizational data and letting individuals determine who can access it. Regulations may apply: **GDPR** (EU), **HIPAA** (health), **FERPA** (education), **COPPA** (children). **The 3 course choices** (chosen by *data sensitivity*):
1. **LOW** — product will **NOT** contain PII or regulated data.
2. **MEDIUM** — product **WILL** contain **PII** and may fall under HIPAA/FERPA/COPPA etc., **but no actionable financial information.**
3. **HIGH** — product will contain **actionable financial data** (and may fall under **PCI DSS**).
*Course examples:* "The product shall have a **medium-level of data privacy** as it contains PII that falls under **HIPAA** regulations and does not contain actionable financial information." *Business examples:* anonymize/aggregate location data before analytics; let users set profile visibility to public/friends-only/private; encrypt financial data with AES-256 in transit and at rest.

**7. Compatibility** — the ability of a product to perform effectively in its **intended operating environment** (OS, device, platform, machine, network, adapters, equipment, electrical systems, and other software like browsers). Customers need to know it works on *their* systems; testing every compatibility requirement before release is critical. **Backward compatibility** = newer versions support older versions'/older data. **Common approach = N-2** (support the 3 latest releases: N, N-1, N-2; e.g., VMware supports N-2 for ≥ 12 months each).
*Examples:* "Canvas shall support the current and 2 previous major releases of the leading browsers: Chrome, Edge, Firefox, Safari." / "Canvas Mobile App shall operate on iOS versions **N-2**." / "As an Uber rider, I need the UberPool app to be compatible with the latest 2 major versions of Android OS." / "The EV Charging App shall be compatible with **Level 1** EV charging stations." / "The EHR software shall be compatible with the **FHIR** standard."

**8. Accuracy** — the correctness of the information or operation the product provides (*if applicable*). How close is the result to the true value? **Accuracy = correct classifications ÷ all classifications**, expressed as a **percentage.** True value determined manually or via a published benchmark.
*Examples:* "Google Maps shall provide navigation guidance with a positional accuracy within **5 meters** under open-sky conditions." / "…estimated travel times accurate within **±10%** of actual." / "ChatGPT's percentage of correct answers vs. the correct-answer set shall be **≥ 85%**." / "The spam model shall correctly classify **≥ 98%** of emails, with a false-positive rate **≤ 1%**." / "…calculate tax amounts to **2 decimal places** based on the most recent tax codes."

**9. Safety** — the product's ability to operate without causing unacceptable risk of harm to people, property, or the environment (*if applicable*). Crucial where failures have serious consequences; leads to rigorous design/testing/certification. **The 4 course choices:**
1. **General** — failures unlikely to injure or damage the environment; might involve financial/data loss or lower-value property damage.
2. **Moderate** — failures could lead to minor injuries, discomfort, or minimal environmental impact.
3. **High** — failures could lead to injuries or moderate environmental damage.
4. **Critical** — failure can result in death, serious injury, or significant environmental damage.
*Course examples:* "The product will operate in situations where failures **could lead to minor injuries, discomfort or minimal environmental impact**." (Pick the level matching the product's real-world risk.)

### (c) Template application
For each of the 9 (skip those that don't apply), pick the **level/tier** where the course defines one (Latency 4 tiers, Availability 6 nines, Security 3, Privacy 3, Safety 4) or set a **measurable threshold** (Usability, Accuracy) or **name the external system/standard/environment** (Interoperability, Compatibility). Then write it with one of the 4 templates, give it a unique ID, and tie it to an outcome.

### (d) Worked examples (integration)
Duolingo across three NFRs (course): Latency — low (2–200 ms) during exercises; Availability — 99.999% for an exercise module, 99% for the weekly-report email; and Usability, etc. Several strong exemplars each tag every NFR to a named attribute (Performance/Throughput/Interoperability/Compatibility/Reliability/Security/Availability) **with concrete thresholds** — e.g., "order received within 1 min," "maps-API integration," "99.9% uptime," "<5 s automated-run response," "100 concurrent users," "ISO/IEC 25010."

### (e) Common mistakes / anti-patterns
- **Vague qualitative goals** — "the app should be fast/secure/easy." Every NFR needs a **measurable threshold, a named level, or a named standard.**
- **Omitting the scope/condition** — bound the number with a window/context ("during each calendar month," "under open-sky conditions," "of all submitted transactions").
- **Conflating pairs:** Availability (uptime %) vs. Reliability (consistent correctness over time); Security (defend against threats) vs. Privacy (lawful/consented data handling + user control); Compatibility (runs in its environment) vs. Interoperability (exchanges with other systems).
- **Citing "industry standards"** instead of the specific standard (HL7, FHIR, AES-256, SET, "latest 2 versions of Chrome/Firefox/Safari").
- **Applying an NFR that doesn't fit** (forcing Safety/Accuracy onto a product with no such risk) — the course says one or more may not be applicable.
- **Not deriving Interoperability from the Context View** or **Latency/Usability from the User View.**
- Picking a security/privacy/availability level that mismatches the real adversary/data/criticality (e.g., 6-nines for a non-critical email).

### (f) Coaching questions
1. "Of the 9 — Latency, Usability, Interoperability, Availability, Security, Privacy, Compatibility, Accuracy, Safety — which genuinely apply to *your* product, and which don't?"
2. "For your 3 key features, which latency tier — high, medium, low, or ultra-low — and why, based on your User View?"
3. "Who's the likely adversary — unorganized hackers, organized groups, or nation-states? That sets your Security level. And does it hold PII or actionable financial data? That sets Privacy."
4. "What availability level ('nines') matches how critical this is, and how much downtime/year does that allow?"
5. "From your Context View, which external systems must you interoperate with — and what *named* protocol/API/standard for each?"
6. "For Accuracy/Usability, what's the exact number and the condition it's measured under? How would you verify it?"

### (g) Inputs / outputs
- **Consumes:** User Views (→ Latency, Usability), Context View (→ Interoperability, Compatibility), Product Concept Outline (infrastructure, I/O, data → Compatibility, Availability, Security, Privacy), and the problem/market context (→ which NFRs matter and at what level).
- **Produces:** the non-functional half of the **PRD**; heavily shapes architecture, cost, and UX. Completes the Solution Space, which then feeds the **Customer Value Space** (features & benefits, pricing, value proposition).

---

## How the 5 artifacts chain together (the Solution-Space pipeline)

```
Market Focus (segment/niche/use case/problem/position-to-own)
      │  + Idea Generation (generate-then-judge)
      ▼
1. Product Concept Outline (9 parts) ──► Main Attributes, I/O, Infra, Data
      │
      ▼
2. User Views (Happy-Path list + storyboard/screen-flow/prototype)
      │   ├──► Product Features ──► 3. Functional Requirements (user stories)
      │   └──► Latency & Usability requirements
      ▼
4. Context View (external entities + data) ──► Interoperability & Compatibility reqs
      ▼
5. Non-Functional Requirements (the 9) ──► completes the PRD
      ▼
   → Customer Value Space (features→benefits, pricing, value proposition)
```
Feature identification pulls from **all three** of Product Concept Outline + User Views + Context View. Requirements are the convergence point: functional from features/User Views; interoperability/compatibility from Context View; latency/usability from User Views.

---

## Strong vs. Weak — grounded in the exemplar workbooks

**What a STRONG Solution Space looks like (patterns drawn from several strong exemplar workbooks):**
- **A golden thread of consistency.** The strongest workbook reuses the *same* core numbers (8 steps → 4 target; ≈40 episodes/yr; $32/hr) across problem, MVP "how it works," requirements, and value — so the concept outline's attributes literally reconcile with the desired outcome and the happy path is the ≤4-step flow the problem demanded.
- **A disciplined, minimal Happy-Path** with no login/error clutter and an explicit entry and completion point (a strong exemplar's 4-step dental-booking flow with a wireframe per step is the model).
- **Requirements as clean user stories** — "As a [actor], I want [X] so that [Y]" — split Functional vs. Non-Functional, **each tagged to a named quality attribute with a measurable threshold** (one exemplar's NF1–NF7 tagged Performance/Throughput/Interoperability/Compatibility; another's instrumentation-backed metrics; another's 99.9% uptime / <5 s / ISO 25010).
- **Interoperability derived from a real Context View**, and NFR *levels chosen to match reality* (right "nines," right security adversary, right privacy tier) rather than defaulting to the maximum.
- **Scope discipline** — the MVP deliberately defers non-core features (a strong exemplar omits analytics/promotion and *says so*), keeping the concept outline honest to "minimal viable."

**What a WEAK Solution Space looks like:**
- **Concept outline / happy-path drift** — a "develop an application" JTBD but a solution that only serves "deploy an app" (altitude mismatch), or a happy path padded with login/setup/error steps.
- **A solution asserted to fix the root cause without addressing why incumbents haven't** (a weak exemplar's warehouse+courier fix never touches the unit economics of the low delivery fees) — the concept looks complete but isn't grounded.
- **Requirements that break the 5 rules** — multiple requirements in one line, unverifiable ("should be fast/easy"), missing the "so that" outcome, no unique ID, or specifying the *how* instead of staying solution-free.
- **NFRs as vague qualitative goals** ("secure," "reliable") with no level/threshold/named standard, or a security/privacy/availability level that mismatches the product's real risk, or generic boilerplate NFRs (2 s / 99.5% / WCAG) copy-pasted regardless of the product's actual AR/AI/latency-critical nature (a weak AR-interior-design exemplar gets flagged for exactly this — only the one *tailored* NFR, "10 s video processing," shows what good looks like).
- **Placeholder/empty views** — a Context View, User View, or Deployment View referenced but never actually drawn (a weak exemplar leaves User/Context/Deployment views as empty headers), so the scope claim can't be verified.
- **Context View that shows internals** — features, the product's own database, or infrastructure drawn as if external, defeating the boundary-clarifying purpose.

**The one-line test for each artifact:** *Concept Outline* — do the Main Attributes create your position-to-own and reconcile with the desired outcome? *User Views* — could a stranger see the core value work in ≤5 screens with no login/error clutter? *Functional Reqs* — is each one singular, verifiable, solution-free, ID'd, and traceable to a feature? *Context View* — is everything on it genuinely *external*, with labeled/directed data? *NFRs* — does each applicable attribute carry a course-defined level or a measurable, condition-bounded threshold?
