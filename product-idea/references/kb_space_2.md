# Market Space — Study Reference (paraphrased from CMU 17-619, Product Management Essentials I)

> **About this file.** This is an independent, paraphrased study reference distilled from the *Product Management Essentials I* method (CMU 17-619). It is **not** official course material and contains no student work; worked examples use only public products or anonymized exemplars.

> **What this covers.** The Market Space is the second of the four Spaces in the Product Idea Workbook (Customer Problem → **Market** → Solution → Customer Value). It spans three class sessions:
> - **Session 6 (Part 1):** Markets, Market Segmentation, Market Segment Profiles
> - **Session 7 (Part 2):** Competition, Product Categories, Positioning (maps + position-to-own)
> - **Session 8 (Part 3):** Market Focus (5 aligned decisions), Product Focus / MVP
>
> **The North Star of the whole Space (memorize this — it recurs on a slide in all three sessions):**
> *The most successful new products (1) serve a **highly attractive market** — a **large** market of customers who need it and will pay for it, growing **fast**, with **low** barriers to entry — AND (2) hold a **strong, highly differentiated position** in that market — the product offers **superior value** vs. the alternatives (compelling + significant differentiated value).*
>
> Every Market Space artifact exists to test a product idea against those two axes: **Market Attractiveness** and **Market Position**.

**Sequencing note (hard rule from the workbook template):** In the Workbook, Market Space section 2 is **Total Addressable Market (TAM)** — but **"Do NOT complete this part until the last Product Assignment of this course."** TAM sizing is deliberately deferred. Everything else in the Market Space is done in Assignment No. 4. The **Product Idea Brief** roll-up is written at the very end of the course.

**The JTBD is the pivot.** You carry the **Actor** and the **Job To Be Done (JTBD)** forward from the Customer Problem Space and use them to orient every Market Space concept: your Market is everyone who matches your Actor doing the JTBD; your competitors are every option the Actor perceives for that JTBD; your positioning uses the criteria the Actor uses to choose. **Take the customer's (Actor's) perspective throughout — never a product-centric one.**

---

## 1. Market Definition

### (a) Definition
A **market** consists of **buyers** (a.k.a. consumers, customers, users) and **sellers** (a.k.a. producers, vendors, suppliers — a.k.a. competitors). **In product management, when people say "market," they usually mean the customers.**

Your **Market** = *everyone who matches your Actor and is doing the Job To Be Done.* They are similar in **who they are** and **what they are doing**. They are your **potential customers** who could "hire" your product to get the Job done better.

### (b) Rules / constraints the course enforces
For your Market you must do exactly three things:
1. **Name** your Market.
2. **Estimate the number of Actors** in it (the count of people who match your Actor = the number of potential customers/users).
3. **Identify the trend(s)** in that number of Actors — projected future, recent past, and **WHY**. Is it growing, declining, or stagnant?

- The market count is a count of **Actors/people**, not dollars (dollars = TAM, deferred).
- **Attractiveness signals to capture:** large size, fast growth, low entry barriers.
- Always cite a data source for the count and the trend.

### (c) Template (fill-in slots)
```
Market Name: ________________________________________
Actor:  ____________________     JTBD:  to ____________________
Number of Actors (size): ______ [unit: people/users]   Source: ________
Trend (growth / decline / stagnant): ______ (e.g., % per year or descriptor)
Why is it trending this way? ________________________________________
```

### (d) Worked examples (from the deck)
- **Global College Student Market.** Actor = College Student; JTBD = to get a degree. Size = **254M worldwide (2022)**. Trend: **grew 2.5× since 2000** (was 100M). Why: developing countries investing in higher education; growing middle class.
- **USA College Student Market.** Actor = USA College Student; JTBD = to get a degree. Size = **18.6M (2022)**. Trend: forecast to **20.2M by 2031 (~1%/yr)**. Why: fewer 18-yr-old grads (down ~15% by 2029), falling perceived value + rising cost.
- **Trend discussion examples:** AI & ML Engineer — #1 fastest-growing job category in the USA, **+41.8% YoY** (LinkedIn 2025). Technical Recruiter — frenetic in 2020–21, declined 2023, stabilized 2024, **~8%/yr through 2028**.

### (e) Common mistakes / anti-patterns
- Defining the market so broadly it's meaningless, or so narrowly it's already a segment.
- Sizing in **dollars** here instead of **Actor count** (dollars are TAM — deferred).
- Giving a number with **no source** and **no trend/"why."**
- Forgetting the market is defined **by the Actor + JTBD**, not by your product.

### (f) Coaching questions to ask
1. Who exactly is your Actor, and what is the one JTBD that defines this market?
2. How many people match that Actor today — and what's your source?
3. Is that number growing, flat, or shrinking over the next few years — and *why*?
4. Does this market feel large enough that a viable business could live inside just a slice of it?
5. If you widened or narrowed the Actor definition, how would the count change?

### (g) Inputs → Outputs
- **Consumes:** Actor + JTBD (from Customer Problem Space).
- **Produces:** a named, sized, trended Market — the universe you will **segment** next, and the total that all segment sizes must **sum back to**.

---

## 2. Market Segmentation

### (a) Definition
**Market segmentation** = dividing the customers in a market into **groups (segments)** such that customers **within** a segment are **similar**, and customers in **different** segments are **distinctly different**. You do it because *"it is rarely possible to satisfy all customers in a market by treating them alike"* with the same product, pricing, marketing, and place.

**Two generic approaches to a market:**
1. **Mass market** — treat everyone the same, one 4P mix. More cost-effective, but customers are less satisfied.
2. **Segmented** — different product-marketing mixes for different groups. More competitive/profitable, customers more satisfied.
> In class, **>95% of students did NOT choose a product built for everyone** — segmentation wins.

**Segment the market in the way that is most useful and insightful for product decisions:** which products/features per segment; who to design/test/deliver for; how to differentiate vs. competition; what to price; where to sell/deliver.

**Vocabulary:** a **segmentation VARIABLE** is the dividing dimension (e.g., Field of Study); its **VALUES** are the categories along it (e.g., STEM, Business, Arts & Humanities, Other). Using more variables → more granular segments (e.g., 4 values × 2 values = 8 segments).

### (b) The 5 categories of common segmentation variables
You can invent your own variables, but these five categories are the standard menu:

**1. Behavioral** *(often the most useful for product decisions)*
- Use Case (each use case = a value)
- Desired Outcome (each outcome = a value)
- JTBD (each job = a value)
- Usage Rate (heavy / moderate / light; frequent / occasional / infrequent)
- Operating Scenario (compatibility with X / Y / Z)
- Degree of User Sophistication (high / medium / low)
- User Status (1st-time / regular / …)
- Level of customization required (significant / moderate / light / none)
- Purchasing criteria (recyclability; social responsibility; digital payment; refundability)
- Purchasing procedure (online; contract; transactional; subscription; store)

**2. Demographic** — Age, Gender, Education, Income, Nationality, Religion, Ethnicity, Family life-cycle stage, Family size, Job status, Generation, Language, …

**3. Firmographic** *(for B2B products)* — Occupation (job title/role), Industry, Customer Size (small biz / mid / large / top tier), Company Department.

**4. Geographic** — World region, Country, Metro/City, Climate, Density (urban/suburban/rural/distance).

**5. Psychographic** — Lifestyle, Social class, Personality, Activities/Hobbies, Interests, Opinions, Values, Attitudes/Beliefs, Causes, Cultures.

### (b′) How to discover useful variables/values (discovery methods)
- **Qualitative / judgment-driven:** human judgment; customer interviews; customer interactions; customer surveys; research studies.
- **Quantitative / data-driven:** Multivariate Analysis — Factor Analysis, Cluster Analysis, Regression Analysis.

**How to choose good variables (the heuristic):** look for patterns where *some* customers clearly differ from others. The best variables **explain differences in problems, behaviors, and willingness to pay.** Ask:
- Is there a difference in **frequency** of doing the JTBD among your customers?
- Are there differences in **actual or desired outcomes**?
- Do some customers do the JTBD in a **different use case**?

### (c) Templates
**Variable/values scaffold (from the in-class exercise):**
```
Actor Name = ________     JTBD = to ________
Variable 1: __________  Values: ____, ____, ____, ____
Variable 2: __________  Values: ____, ____, ____, ____
Variable 3: __________  Values: ____, ____, ____, ____
```
Identify **≥3 candidate variables** with **≥2 values** each.

**Sizing reconciliation (single variable):** the number of Actors across all segments **= the total in the market.** (College example: 1.1M + 1.6M + 1.2M + 14.7M = 18.6M.)

### (d) Worked examples
- **USA College Student Market by Field of Study:** STEM 1.1M / Business 1.6M / Arts & Humanities 1.2M / Other 14.7M = 18.6M total. Add **Status** (full-time/part-time) as a second variable → 8 segments, still summing to 18.6M.
- **Spreadsheet users, Variable = Usage Rate:** Low → Ribbon; Moderate → Shortcut keys & Formula Builder; High → Macros. (Segmentation directly drove feature decisions.)
- **Streaming music (2014, ~60M active users), 2 segments:** *Lean Forward* listeners (know what they want → good search + playlist tools) vs. *Lean Back* listeners (need discovery help → ML-based recommendations).
- **Sports Fan:** Variable = Engagement Level → {Casual, Social, Diehard, Fair-weather}; Variable = Interest → {Football, Lacrosse, Tennis, Basketball…}.

### (e) Common mistakes / anti-patterns
- **Segmenting on demographics alone** — two people with identical demographics can need totally different products (HBR's *Prince Charles vs. Ozzy Osbourne*). Demographics ≠ segmentation.
- **Using different variables across segments.** *The same variables must be used across ALL segments — only the values differ.*
- **Choosing a variable that doesn't drive product/pricing/place decisions** (not *actionable*).
- **Assuming a heterogeneity that isn't real** (Bic "Cristal for Her" — the pen market wasn't actually split by gender).
- **Thinking you "create" segments** — you mostly **uncover** ones that already exist.
- Skipping the pre-work: *why* are you segmenting and *what decision/action* will the result drive?

### (f) Coaching questions
1. On what dimension do your customers most clearly split into "these people want a different solution than those people"?
2. Which of the 5 categories does that dimension come from — and does it explain differences in problem, behavior, or willingness to pay?
3. Are you using the **same variables** across every segment (only the values changing)?
4. What product, pricing, or distribution **decision** will each segment let you make differently?
5. Do your segment sizes add up to your total market?
6. Did you discover these by judgment, interviews, or data — and how confident are the sizes?

### (g) Inputs → Outputs
- **Consumes:** the named/sized Market; Actor, JTBD, Use Cases, Outcomes (Problem Space).
- **Produces:** a set of candidate segments with variables + values + sizes → feeds **Segment Validity Rules**, **Segment Profiles**, and ultimately **Market Focus** (segment selection).

---

## 3. The 6 Segment-Validity Rules

### (a) Definition
Six criteria that **each** market segment must satisfy to be **valid**. Use them as a checklist to accept/reject a proposed segmentation.

### (b) The 6 rules (exact, from the deck)
1. **Homogeneous** — customers within the segment are as **similar** as possible.
2. **Distinctive** — customers in the segment are as **different** from other segments as possible. *(A customer is in ONE segment only — EXCEPT when segmenting by Use Case.)*
3. **Measurable** — you can estimate the segment's size with reasonable accuracy for decision-making.
4. **Substantial** — the number of customers is **sufficiently large to be feasible**.
5. **Actionable** — you can use it to make decisions.
6. **Accessible** — you can easily find the customers, or they can easily find you.

> Course pairing with Kotler & Keller's six (same idea, different labels): Identifiable, Substantial, Accessible, Stable, Differentiable, Actionable. Barron/Hollingshead compress this into a two-part test: every variable must be both **Meaningful** (explains/predicts marketplace behavior) *and* **Actionable** (you can find and reach them). Failing "actionable-only" = you can target them but they don't buy differently; failing "meaningful-only" = you find a real needs cluster you can't locate.

### (b′) The double-counting constraint
**Be careful not to double-count Actors.** A person may appear in more than one segment — **especially if you segment by Use Case or Outcomes.** *The sum of Actors across all segments can't be greater than the total number of Actors in the market.* (This is the one explicit exception to the "one segment only" rule.)

### (c) Template — validity checklist
```
Segment: ____________
[ ] Homogeneous  — how are these customers alike? ______
[ ] Distinctive  — how do they differ from all other segments? ______
[ ] Measurable   — size estimate + source: ______
[ ] Substantial  — is it large enough to be worth serving? ______
[ ] Actionable   — what decision does it enable? ______
[ ] Accessible   — how will you find them / they find you? ______
Double-count check: Σ(segment sizes) ≤ total market?  ______
```

### (d) Worked examples
- **Streaming service (2014)** landed on **2 substantial segments** (Lean Forward / Lean Back) because they gave *useful, distinct product insights* — a positive example of Substantial + Actionable + Distinctive.
- **Failure of Actionable:** a U.S. insurance company spent heavily identifying a segment, then found no customers to serve and no actions to take — a segment that fails the rule is worthless no matter its cost.

### (e) Common mistakes
- Segments that overlap (a customer in several) — violates **Distinctive** (unless the variable is Use Case, and then you must watch double-counting).
- A segment too small to matter — fails **Substantial**.
- A "segment" you can't size — fails **Measurable**.
- A clever segment you can't locate or reach — fails **Accessible**.
- A segment that doesn't change any decision — fails **Actionable**.

### (f) Coaching questions
1. Could a single customer land in two of your segments? If so, which variable caused that, and is it Use Case?
2. Can you put a credible number and source on each segment's size?
3. Is each segment big enough to build a v1.0 business around?
4. How, concretely, would you reach the customers in each segment?
5. Do your segment sizes sum to (or under) your total market?

### (g) Inputs → Outputs
- **Consumes:** candidate segments from Section 2.
- **Produces:** a validated segment set → written up as **Segment Profiles**, then narrowed in **Market Focus**.

---

## 4. Market Segment Profiles

### (a) Definition
A **Market Segment Profile** captures the key information about **each** segment in a consistent, comparable format.

### (b) Rules / constraints
- Capture, for each segment: **Segment Name**, **Segmentation Variable(s)**, **Segmentation Value(s)**, **No. of Actors**, and (optional) **Growth Rate**.
- **The same variables must be used across all segments.**
- **Growth Rate** may be a **percentage** *or* a **descriptor**: *declining, steady, growing fast, growing hyper-fast.*
- **For Product Assignment No. 4 you create profiles for exactly 3 segments** — not every possible segment. (Final target selection comes later, in Market Focus.)

### (c) Template
```
Segment Name: ______________________ (unique, clear name you create)
Segmentation Variable(s): ______________
Segmentation Value(s):    ______________
No. of Actors:            ______ (source: ____)
Growth Rate (optional):   ______ (% per year OR declining/steady/growing fast/hyper-fast)
```

### (d) Worked examples (from the deck)
- **USA STEM Students** — Variable: Field of Study; Value: STEM; No. Actors: 1.1M; Growth: Fast.
- **USA Biz Students** — Field of Study = Business; 1.6M; Moderate growth.
- **USA Arts & Hum. Students** — Field of Study = Arts & Humanities; 1.2M; Declining.
- **USA Other Students** — Field of Study = Other; 14.7M; Steady.
- **Forklift Drivers (JTBD: to haul loads; market 2.6M):** *USA Pallet Loads* (Use Case = Loads on a Pallet; Region = USA; 1.3M; ~2%/yr) and *Asia Towed Loads* (Use Case = Loads towed by cart; Region = Asia; 0.7M; faster than USA) — note **same two variables across both**.
- **Master's students** — *"Career ROI Maximizers"* (Desired Outcome = career advancement; Ability to Pay = Med-High; Delivery = in-person; Time = full-time); *"Credential Aspirants"*; *"Flexible Skill Builders"* (Outcome = minimal life/work disruption; Delivery = online; part-time).

### (e) Common mistakes
- Naming segments vaguely ("Group A"). Give them **memorable, meaningful names** (exemplars used "Express Shoppers," "The Worriers," "Immersive Storytellers").
- Different variables in different profiles.
- Missing sizes/sources; missing growth signal.
- Profiling every possible segment instead of the required **3**.

### (f) Coaching questions
1. Does each profile use the exact same variable(s), with only the values changing?
2. Is every segment name self-explanatory to someone who hasn't read your workbook?
3. What's the size and growth of each — and which looks most attractive so far?
4. Which 3 segments are worth profiling in depth?

### (g) Inputs → Outputs
- **Consumes:** validated segments (Sections 2–3).
- **Produces:** 3 comparable profiles → the primary input to **Market Focus decision #1 (segment selection)** and the **attractiveness × position screening matrix**.

---

## 5. Competition

### (a) Definitions
> Competition is *"too often misunderstood."* The classic PM fallacies: *"We don't have any competitors!" / "Nobody has anything like our product!" / "Our product is better!"* — all wrong.

- **Option = Competitor = Alternative.** *Every option the customer perceives to be available to do the JTBD or solve the problem is a competitor* — **even if it doesn't compete intensely for the purchase.** If the customer believes it's a choice for the JTBD, it's a competitor.
- **Product Category** — a **classification/label** for a group of **similar products** that: serve a common purpose, offer the same general functionality, share format/form/material/attributes, and solve similar problems. Many categories have **sub-categories**; each (sub)category holds multiple products.
- **Product** — a discrete, **branded** offering.
- **Direct competitors** — products **within the same product category** compete directly with each other.
- **Indirect competitors (a.k.a. substitutes)** — products in **other categories** (and "manual" options like *Walk*) that the customer perceives as alternatives for the JTBD.

**Key move:** the customer's perceived options **change when the JTBD reframes.** For "to get to work," a Sedan competes with SUVs, buses, trains, motorcycles, bikes, walking. Reframe to "to visit a customer" and the options become shuttle service, personal vehicle, commercial airline, private jet, train — an entirely different competitive set.

### (b) Rules / constraints (for Assignment No. 4)
- Identify **at least 3 options** the Actor perceives as available.
  - **≥1 option must be a Product Category.**
  - **≥1 option must be a Product** (branded, with the company that makes it).
- Choose the **most noteworthy** options — the ones deserving the most attention.
- **Prove the category exists:** find a site/app/report that categorizes the products — **G2, Yelp, Amazon, Capterra, TripAdvisor, Gartner (B2B), Forrester (B2B).**
- If a competitor isn't a product, you may name it yourself (e.g., *"Walk," "Manual Testing Procedure"*).

### (c) Templates
**Competition capture (in-class form):**
```
Actor: ______   JTBD: to ______   (optionally focus 1 segment or 1 use case)
3 Product Categories:  1) ______  2) ______  3) ______
3 Products:  1) [Product] — [Company]  2) [Product] — [Company]  3) [Product] — [Company]
```
**Competitor taxonomy (used by strong exemplars):**
```
Actor → JTBD → Product Category A → {Product, Product, Product}   (Direct within A)
              → Product Category B → {…}                          (Indirect / substitute)
              → "Manual" option (e.g., Walk / DIY)                 (Indirect)
Mark each: Direct | Indirect(Substitute) + one-line competitive-positioning note
```

### (d) Worked examples
- **Actor: Office Worker; JTBD: "to get to work."** Product categories: Sedans, SUVs, Buses, Trains, Motorcycles, Bicycles + "Walk." Products in *Sedans*: Nissan Altima, Toyota Camry, Honda Accord, Chevy Malibu, Tesla Model 3, Hyundai Elantra. **Sedans compete directly** with each other; **other categories + Walk are indirect/substitutes** to Sedans.
- **Video Conferencing Software** (category proven via G2): Zoom, Microsoft Teams, Google Meet, GoTo Meeting, Cisco Webex, FaceTime.
- **Exemplar taxonomies:** Podcast tool — Direct (Libsyn, Anchor.fm, Blubrry) + Indirect (Audacity/GarageBand editors; Dropbox/Drive file hosting; self-hosting). EV charging — Hardware-only (ClipperCreek) vs. Software-only (PlugShare, EV Trip Planner) vs. Combined (ChargePoint, Tesla, Electrify America).

### (e) Common mistakes
- "**We have no competitors.**" (There is always at least the *manual/do-nothing* option.)
- Forcing a **product-centric** view of competition instead of the **customer's perceived options.**
- Listing only **direct** competitors and ignoring **substitutes**.
- Not proving the category exists with a real categorization source.
- A flat, unstructured competitor list instead of a **category → product** taxonomy.

### (f) Coaching questions
1. Put yourself in the Actor's head for this JTBD — what are ALL the options they believe they have, including doing nothing / doing it manually?
2. Which of those are product categories, and which are specific branded products?
3. Where does your idea sit — which category are you *in*, and who are your direct rivals there?
4. Which substitutes (other categories) might the customer pick instead?
5. Can you cite a G2/Capterra/Amazon page proving your category exists?
6. If the JTBD were framed slightly differently, would the competitive set change?

### (g) Inputs → Outputs
- **Consumes:** Actor + JTBD (+ optional focus segment/use case).
- **Produces:** the list of **options/competitors** → these become the **rows/lines plotted on the positioning map**; and the competitive landscape feeds **Market Focus (position strength)**.

---

## 6. Positioning

### (a) Definitions
- **Product position (Kotler):** *"The place a product occupies in the minds of customers relative to competing alternatives."*
- **Positioning:** *identifying a desirable position for your product so that its unique, relevant difference is easy to understand and recall.* Customers are overloaded with product information; it's hard to stand out. **Decide the position you want up front, conceive a product to fill it, then build it.** A clear position makes it easier to **choose** your product, **sell** it, and **keep** customers (loyalty).

### (b) The 6 Steps to a Product Position
1. **Take the CUSTOMER's (Actor's) perspective.**
2. **Identify the options** the customers perceive to be available. *(→ Competition, Section 5.)*
3. **Identify the criteria** the customers use to evaluate/select an option for their JTBD.
4. **Create a current-state positioning map** to identify currently available positions (without your product).
5. **Create a future-state positioning map** with your product's desired **position-to-own.**
6. **Implement** the position via product requirements, pricing, marketing, services, distribution.
> Steps 4 (current-state map) live in Session 7; Step 5 (future-state map + position-to-own) is Market Focus decision #5 in Session 8. Step 6 spans Solution + Customer Value Spaces.

### (b′) Customer Evaluation Criteria (Step 3)
- **Criteria** = the **factors customers use to evaluate and select** products for the JTBD. A.k.a. **evaluation criteria = purchasing criteria = factors of competition.** They are the **basis of differentiation** — the reasons a customer will choose you.
- **Not every customer places the same importance on each criterion.**
- **Price can be a criterion** — or use **Total Cost to the customer.**
- Example criteria sets:
  - *Video conferencing:* Call Quality, Call Reliability, Ease of Use, Feature Set, Security, Privacy, Integrations, Capacity, Admin Controls, Pricing.
  - *Groceries:* Price, Convenience, Quality, Available Selection, Experience, Food Safety Confidence.
  - *Smartphones:* Performance, Price, Brand, Battery Life, Features, Camera Quality, Design/Appearance.
  - *Cloud services:* Security, Reliability, Availability, Performance, Support, Scalability, Compliance, Disaster Recovery, Technical Capabilities, Reputation, Long-Term Fit, Cost.
  - *Wireless (with importance %):* Cost 21.4%, Reliability 19.2%, Network Quality 18.3%, Coverage 17.4%, Customer Service 9.1%, Speed 6.5%.

### (b″) The Positioning Map (Step 4)
Also called **perceptual map, "snake plot"/"snake chart," or Strategy Canvas** (Kim & Mauborgne, *Blue Ocean Strategy*).

**A positioning map has 3 elements:**
1. **X-axis: Evaluation Criteria** — the criteria customers use.
2. **Y-axis: Score** — the **RELATIVE AMOUNT** each option offers on each criterion.
3. **Plotted lines** — one line per option (competitor) across the criteria.

**How to build the current-state map:**
1. **Score each option on each criterion, 0–10.** Higher = **offers more** of that criterion; lower = offers less.
2. Decide scores via **judgment** (experience/knowledge), **collective judgment** of a small group who know the customer, a **customer survey**, or **math** (conjoint / multivariate — regression, factor, cluster analysis).
3. Plot the options and **identify the most attractive available positions — the "white spaces"** (mark with green ovals).

- **WHITE SPACE** = an **unfilled position** in customers' minds — a possible position to occupy, differentiate on, and "own."
- **WARNING: High ≠ good, Low ≠ bad.** Some customers prefer **less** of a criterion (less screen size, fewer features, lower price). Score the *amount offered*, not "goodness."

**Positioning guidance:**
- Identify the **most noteworthy competitors** (direct and/or indirect): which options do customers choose most often? which is most economical? which is emerging?
- You **can (and should) plot a Product Category** on the map if customers see it as a key option — plot the **"average"/"median"** product in the category.
- **Stay in the customer's perspective** — use the criteria *they* use. **Do NOT force your product's features onto the current-state map** if customers don't use them to evaluate.
- **A gap in the market doesn't mean there's a *market* for the gap** — white space is *possible*, not *proven*, demand. Gaps also shift as competitors/entrants change.

### (b‴) Future-state map + Position-to-Own (Step 5, Assignment)
- **Future-state positioning map** = the same map **with your product idea plotted** and the position(s) you intend to **"own."**
- **Position = a place on a criterion.** You may select **more than one** position, but **each additional position requires additional investment** in features, marketing, and selling — so **focus**: pick the position(s) that give you the **strongest basis for differentiation.**
- **Position-To-Own statement** = a **clear, concise phrase** that communicates the 1–2 key positions you want to own. Examples:
  - Apple MacBook Pro — *"Power to create, built to last."*
  - Tesla Model 3/Y/S/X — *"Drive Smarter, Drive Safer."*
  - NVIDIA GeForce RTX — *"Next-level graphics, ultimate performance."*
  - Dropbox Dash for Business — *"Find anything. Protect everything."*
  - Duolingo — *"Learn a language, effortlessly."*
- **New innovations can change the criteria themselves.** Pre-iPhone criteria (Email/Browser, Ease of typing, Battery, Connectivity, Form factor, Multimedia, Price) shifted post-iPhone to **Apps Ecosystem, Ease of interacting, Design/Aesthetics** — Apple's innovations (touchscreen, app platform) rewrote the evaluation criteria.

### (c) Templates
```
STEP 3 — Criteria: the Actor uses these to choose:  1)__ 2)__ 3)__ 4)__ 5)__ (Price/Total Cost optional)
STEP 4 — Current-state map:
  X-axis = criteria above; Y-axis = 0–10 (relative amount offered)
  Options (≥3; ≥1 category + ≥1 product):  Option A ______  Option B ______  Option C ______
  Score matrix:            crit1 crit2 crit3 …
     Option A               __    __    __
     Option B               __    __    __
  White spaces (green ovals): ________________
STEP 5 — Future-state map: add [Your Product] line; circle position(s)-to-own.
POSITION-TO-OWN statement (clear, concise, 1–2 positions): "________________________"
```

### (d) Worked examples
- **IT Business Analyst; JTBD: to elicit software requirements** (problem: avg elicitation = 416 hrs/yr) — current-state map with green-oval gaps identified for a new product.
- **Podcast creator; JTBD: to create a podcast episode** (cause: too many steps across multiple apps) — the map reveals gaps on **Ease of Use** and **Audio Editing Features**; those became the positions-to-own for a new podcast-creation product.
- **Short-haul trips (600–800 mi):** map mixes product categories (car types) with a specific product (Southwest Airlines) — shows you can plot categories and products together.

### (e) Common mistakes
- **Product-centric perspective** (biggest mistake) — scoring on *your* differentiators instead of the customer's criteria.
- Treating **High as good / Low as bad** (ignoring customers who want *less*).
- Confusing a **white space** with **proven demand** ("a gap in the market ≠ a market for the gap").
- Forcing your not-yet-real features onto the **current-state** map.
- Choosing **too many** positions-to-own (each one costs investment).
- A vague, jargon-filled position statement (should be crisp and customer-facing).
- Presenting the map as an image with no underlying 0–10 scoring shown (a common exemplar weakness).

### (f) Coaching questions
1. List the criteria the Actor *actually* uses to choose — not your feature list. Where did you get them?
2. Score each option 0–10 on each criterion. Are you scoring *amount offered*, remembering low can be attractive?
3. Where are the white spaces — the criteria on which every incumbent scores low?
4. Which 1–2 of those gaps can you genuinely own, and why is that your strongest differentiation?
5. Write your position-to-own in one crisp line — would a customer instantly get it?
6. Does owning this position require an innovation that would change the criteria customers use?

### (g) Inputs → Outputs
- **Consumes:** Actor + JTBD (perspective), the **options/competitors** (Section 5), and customer **criteria**.
- **Produces:** current-state map (white spaces) → **future-state map + Position-to-Own** → this is **Market Focus decision #5**, and it drives Solution Space (requirements) and Customer Value Space (value prop, pricing).

---

## 7. Market Focus (the 5 aligned decisions)

### (a) Definition
> *"Trying to create something for everyone leads to nothing for no one."* **Focus, focus, focus** is a critical success factor for startups/entrants: efficient use of scarce resources, faster to market, faster traction + proof of value before expanding, and reduced competitive reaction. *"Good-to-great companies focused on what NOT to do."*

**Market Focus** = deciding, for your **v1.0**, the specific slice of the market to serve first. **Think big, act small.**

### (b) The 5 decisions — and they must be ALIGNED
1. **Which MARKET SEGMENT to target first?**
2. **Which MARKET NICHE to target first?**
3. **Which USE CASE to serve first?**
4. **Which PROBLEM to solve first?**
5. **Which POSITION-TO-OWN first?**

> **Alignment is the whole point:** the segment, niche, use case, problem, and position must all reinforce each other. Build **product v1.0** for that single, coherent Market Focus.

**Decision 1 — Segment attractiveness (what makes a segment attractive):**
1. **Size** — large is attractive.
2. **Growth rate** — fast/positive attractive; declining/flat unattractive.
3. **Entry barriers** — small/none attractive; significant obstacles unattractive.

**Decision 3 — Use-case selection factors:** how many customers have it vs. others; how often it occurs; whether competitors serve it well; simple vs. complex to serve; whether it opens a pathway to other use cases. *(Stripe: segment = small biz, niche = startups, first use case = **Card Payments on Website** — simplest API, fast time-to-value.)*

**Decision 4 — Problem selection factors:**
- If multiple **outcome gaps:** pick the most attractive by **Magnitude** (bigger gap), **Frequency** (more frequent), **No. of Actors** (more affected), **Growth Rate** (faster increase in any of the above).
- If multiple **causes:** pick the cause that is **Most Feasible** to solve cost-effectively AND **Most Impactful** on the gap.
- Use the **problem-selection matrix** (each circle = a problem; most attractive = **large + frequently occurring**).

**Decision 5 — Position strength (what makes a position strong):**
1. **Competitive landscape** — strong = few alternatives in the segment.
2. **Market share of options** — strong = incumbents' share of sales/customers is low.
3. **Problem severity** — strong = frequent, large "pain" in the segment.

### (c) Templates
```
MARKET FOCUS (v1.0)
1. Segment to target first:   ______ (why: size ___ / growth ___ / low barrier ___)
2. Niche within it:           ______ (extra segmentation vars/values defining it: ___)
3. Use case to serve first:   ______ (why: # customers / frequency / competitor gap / simplicity / pathway)
4. Problem to solve first:    ______ (gap magnitude/frequency/#actors/growth; cause = feasible + impactful)
5. Position-to-own first:     ______ (why strong: few alternatives / low incumbent share / severe problem)
ALIGNMENT CHECK: do all five reinforce one coherent v1.0 story?  ______
```

### (d) Worked example — Dropbox MVP market focus
- **Segment:** "Young Professionals" (USA, multiple computers, used USB drives + emailing files to self) *and* "Software Developers" (USA, home+work computers, juggling source/config/docs).
- **Niche (Young Professionals):** those who were **frequent travelers** + **willing to try new tools.**
- **Niche (Software Developers):** those **willing to try new tools** + **very active on Hacker News.**
- Aligned to a simple sync/backup MVP and a "it just works" position.

### (e) Common mistakes
- Building for **everyone** (no focus).
- Five decisions that **don't align** (e.g., a niche that doesn't have the chosen problem, or a position that doesn't matter to the chosen segment).
- Picking an **unattractive** segment (small/declining/high-barrier) or a **weak** position (crowded, high incumbent share, mild problem).
- Confusing **Market Focus** with **Market Access** — you focus product *decisions* on the focus, but the product *could* still be accessible to people outside it. Don't conflate the two.

### (f) Coaching questions
1. Of your 3 profiled segments, which is most attractive on size, growth, and entry barriers — and which will you serve first?
2. Within that segment, who has the *greatest* demand for a solution (your niche)?
3. Which single use case gives the fastest time-to-value and a pathway to more?
4. Which problem/outcome-gap is biggest and most frequent, and which cause is both feasible and impactful?
5. Which position is strongest (few alternatives, low incumbent share, severe problem)?
6. Do all five choices tell one coherent story for v1.0 — or are any pulling in different directions?

### (g) Inputs → Outputs
- **Consumes:** Segment Profiles, Competition, Positioning map, and the Problem/Outcomes from the Problem Space.
- **Produces:** a single, aligned **Market Focus** → the direct input to **Product Focus / MVP** and the whole **Solution Space**.

---

## 8. Product Focus / MVP (Minimum Viable Product)

### (a) Definitions
- **Product Focus** = deciding the **MVP** that serves the Market Focus. It becomes **version 1.0** of your product.
- **Course MVP definition:** *the **minimum set of features** that creates **enough value** for the target customers to want to **acquire and use** it.*
  - **M**inimum = no unnecessary features.
  - **V**iable = provides *just enough* value that they'll want it.
  - **P**roduct = customers can actually use it.
  - Goal: **prove it's worth further investment.**
- **Original (Lean Startup, Eric Ries) definition:** *"that version of a new product that allows a team to collect the maximum amount of learning about customers with the least effort."* In this sense **it's NOT a product** — it's a **tool to TEST/VALIDATE** the problem+solution and **LEARN/REVISE** until it "hits the spot": a prototype, web page, brochure — *a tool for learning and reducing risk.*

> Coaching nuance: hold **both** definitions. The course "v1.0 minimum feature set" and the Ries "maximum-learning/least-effort experiment" are complementary — the MVP is the smallest thing that both **delivers enough value to the focus customer** and **maximizes validated learning.**

### (b) Rules / constraints
- The MVP serves **only the Market Focus** (segment/niche/use-case/problem/position) — resist adding features for customers outside it.
- Minimum ≠ low quality; it means **no unnecessary features.**
- Every feature should trace back to the **chosen problem** and **position-to-own.**

### (c) Template
```
MVP (v1.0) for Market Focus
Product name: ______   Product category: ______
Target (from Market Focus): segment ___ / niche ___ / use case ___ / problem ___ / position ___
Minimum feature set (each feature → the problem/position it serves):
  - Feature 1  → serves ______
  - Feature 2  → serves ______
Why viable: the value it creates that makes the focus customer want to acquire + use it: ______
What it deliberately does NOT include (deferred to v2/v3): ______
Learning goal / what the MVP validates: ______
```

### (d) Worked example — Dropbox MVP (2008, v1.0)
Exactly these and *"that's all they built"*: desktop client (Mac + Windows), Web UI, Dropbox folder on desktop, drag-and-drop upload/download, automatic syncing to cloud + computers, file backup, **2 GB storage.** Minimal, viable, focused on the sync/backup problem for the chosen niches.

### (e) Common mistakes
- **Scope creep** — cramming features for segments outside the focus; building "everything and every edge case."
- No **MVP prioritization** — a flat list of 20+ requirements with nothing marked as v1.0 (a repeated exemplar weakness).
- Features that don't trace to the chosen **problem/position.**
- Treating the MVP as a polished final product rather than a **learning/validation** vehicle.

### (f) Coaching questions
1. What is the *smallest* feature set that still delivers enough value for your focus customer to adopt?
2. Does every MVP feature trace to the one problem you chose to solve and the position you want to own?
3. What are you deliberately *not* building in v1.0 — and can you defend each cut?
4. What's the single biggest risky assumption this MVP will validate?
5. Could a cheaper experiment (landing page, prototype, concierge) generate the same learning?

### (g) Inputs → Outputs
- **Consumes:** the aligned Market Focus.
- **Produces:** the **MVP Product Concept** → the seed of the **Solution Space** (user views, functional + non-functional requirements, context view).

---

## 9. Market Entry Barriers

### (a) Definition
A **market entry barrier** is *an obstacle in a market that makes it difficult or costly to compete with a new product* — an obstacle to **getting customers** or to **achieving profitability**, and crucially one that **existing competitors no longer have.** *When you have a choice, choose a segment with **no or low** barrier to entry.* (Barriers are the third pillar of segment attractiveness.)

### (b) The common barrier list (from the deck)
Advertising (incumbents outspend); **Capital**; **Control of resources**; **Cost advantages independent of scale** (proprietary tech/know-how, favorable access/location, learning-curve); **Customer/brand loyalty**; **Channel agreements** (exclusive/limited-capacity distributors); **Economy of scale**; **Government regulations** (licenses/permits); **Inelastic demand** (incumbents can undercut price); **Intellectual Property** (patents/trademarks); **Network Effect** (value depends on existing user base); **Predatory pricing**; **Restrictive practices** (e.g., airport landing slots); **R&D costs** (large upfront investment); **Supplier agreements**; **Switching costs**; **Tariffs**; **Zoning.**

### (c) Template
```
For the target segment:
Barrier(s) present: ______   Type (from list): ______
Severity (high/low): ______
How incumbents are shielded / how you'd overcome or avoid it: ______
Chosen segment barrier level:  none | low | (avoid: high)
```

### (d) Worked examples (from the deck)
- **Google+** — high **network effects** of Facebook (users' friends were already on FB).
- **Character.AI** — limited data + high compute/infra costs vs. OpenAI/Google → targeted storytelling niche.
- **Lucid Air EV** — incumbents' economies of scale → targeted **luxury** segment to avoid price competition.
- **ALung Hemolung** — heavy regulation (7-yr FDA clearance).
- **Huel** — lack of distribution/shelf space → **direct-to-consumer.**
- **Quibi** — catalog too small vs. Netflix/YouTube → shut down in 6 months.

### (e) Common mistakes
- Ignoring barriers entirely when picking a segment.
- Entering a **network-effect** or **high-loyalty** segment head-on with no plan to overcome it.
- Failing to note that a barrier is one incumbents already cleared (so it hits *you* specifically).

### (f) Coaching questions
1. In your target segment, what would make it hard or costly for a *new* entrant to win customers?
2. Which named barrier(s) apply — network effects, switching costs, regulation, capital, IP…?
3. How do incumbents currently benefit from that barrier, and how would you avoid or neutralize it (niche, DTC, luxury, new tech)?
4. Is there an adjacent segment with a *lower* barrier you should enter first?

### (g) Inputs → Outputs
- **Consumes:** the candidate segments.
- **Produces:** a barrier assessment → feeds **segment attractiveness** (Market Focus decision #1) and the **screening matrix** Y/X placement.

---

## 10. Market Niche

### (a) Definition
A **market niche** = *a specialized segment **of** a market segment.* It recognizes that even within one segment, **some customers have greater demand/need** for a solution than others. Identify those customers and **focus on them initially.** To target a niche you must **identify additional segmentation variables and values** that define it.

### (b) Rules / benefits
- A niche is *narrower* than a segment — defined by **extra** segmentation variables on top of the segment's.
- **Benefits (if chosen well):** customers are *much more willing* to acquire/use a solution → **faster to customer success**, builds **credibility before scaling up**; **specialized marketing resonates better** → faster customer acquisition; **less competition** → your product **stands out.**

### (c) Template
```
Actor: ______   Market Segment: ______
Niche = segment  +  [extra variable(s)/value(s)]: ______
Why these customers have the *greatest* demand for a solution: ______
```

### (d) Worked examples
- **Facebook (2004):** college students at **"elite" universities** (Harvard, Yale, Stanford) first → then broader college segment → then others.
- **Peloton:** **affluent, fitness-conscious** people who **preferred home workouts** first.
- **CrossFit:** **hardcore** enthusiasts (military, first responders) wanting intense workouts + community.
- **Apple Vision Pro:** loyal Apple customers **AND** (immersive-media enthusiasts **OR** creative professionals).

### (e) Common mistakes
- Treating a whole segment as the niche (no additional narrowing).
- Picking a niche that *isn't* the highest-demand slice.
- Not stating the *extra* variables/values that define the niche.

### (f) Coaching questions
1. Within your target segment, which customers feel the pain *most* and would adopt *soonest*?
2. What additional segmentation variable(s)/value(s) define that group?
3. Why will serving them first build credibility and momentum before you scale?
4. Is competition genuinely thinner in this niche?

### (g) Inputs → Outputs
- **Consumes:** the selected segment.
- **Produces:** the **niche** (Market Focus decision #2) — often expressed as **early adopters** (Section 11).

---

## 11. Early Adopters

### (a) Definition
**Early adopter:** *someone who acquires and uses an innovation **before the rest of the market.*** Early adopters **can be the niche** within your target segment (they sit at the front of the **Technology Adoption Life Cycle**, before "the chasm").

**Characteristics:** like to try new (unproven) things; seek the **benefits of being first**; enjoy exclusive status / advantages / being seen as a **trendsetter**; have **high tolerance for risk**; are **social opinion-shapers.**

### (b) Rules / how they're used
- Early adopters are a *specific* niche — define them with **AND-ed segmentation variables** on top of the segment.
- They deliver the niche benefits: willing to adopt unproven products, provide feedback, and spread word-of-mouth.

### (c) Template
```
Early-adopter niche = target segment  AND  [trait 1]  AND  [trait 2]  AND  [trait 3]
Why they'll adopt before the rest of the market: ______
```

### (d) Worked examples
- **Apple 1st iPhone (2007):** Apple fanatics **AND** young (25–44) **AND** urban **AND** income >$100K (48%).
- **Salesforce CRM (1999, early SaaS):** salespeople at small, tech-focused businesses **AND** working remotely **AND** using mobile phones.
- (Dropbox niches — frequent travelers / Hacker-News-active — are early-adopter niches.)

### (e) Common mistakes
- Confusing "early adopters" with your *whole* target segment.
- Not specifying the **AND-ed traits** that make them adopt first.
- Choosing risk-averse mainstream customers as your first target.

### (f) Coaching questions
1. Who in your segment loves trying unproven new products and tolerates rough edges?
2. What specific traits (AND-ed) identify them?
3. Are they social/opinion-shapers who'll pull the next customers in?
4. Will their feedback meaningfully de-risk your product before you scale?

### (g) Inputs → Outputs
- **Consumes:** the segment/niche.
- **Produces:** a concrete first-customer definition for the **MVP** and go-to-market entry.

---

## 12. Attractiveness × Position Screening Matrix

### (a) Definition
A 2×2 **screening matrix** used to **select a segment to target first.** It plots **your product in each candidate segment** on two axes:
- **X-axis: Market Position** (Weak → Strong)
- **Y-axis: Market Attractiveness** (Low → High)

Each plotted point = *your product in segment N.* This visualizes both halves of the North Star (attractive market **and** strong position) at once.

### (b) Rules / how to place points
- **Market Attractiveness (Y)** is driven by: **segment size** (larger = higher), **growth rate** (faster = higher), **entry barriers** (lower = higher).
- **Market Position (X)** is driven by: **competitive landscape** (fewer alternatives = stronger), **incumbents' market share** (lower = stronger), **problem severity** (more severe/frequent = stronger).
- **Target the segment(s) that land toward High attractiveness AND Strong position** (top-right).

### (c) Template
```
                 Market Attractiveness (size↑, growth↑, low barriers↑)
                 High │  [seg?]        [★ target: High + Strong]
                      │
                 Low  │  [avoid]        [seg?]
                      └───────────────────────────────
                        Weak            Strong
                              Market Position
                        (few alternatives, low incumbent share, severe problem)

Plot "My product in Segment 1..N". Pick the top-right segment first.
```

### (d) Worked example
The deck plots *"My product in segment 1 / 2 / 3 / 4"* across the grid and instructs: **use this screening matrix to help select a segment to target first** — choosing the segment that is both highly attractive and where you'd hold a strong position.

### (e) Common mistakes
- Scoring only **attractiveness** (big market) while ignoring **position** (you'd be weak there) — or vice versa.
- Placing points by gut with no link to the underlying attractiveness (size/growth/barrier) and position (landscape/share/severity) factors.
- Chasing the biggest segment even when your position there is weak.

### (f) Coaching questions
1. For each candidate segment, is it attractive (large, growing, low-barrier) — high or low on Y?
2. In each, would you hold a strong position (few rivals, low incumbent share, severe problem) — weak or strong on X?
3. Which segment sits top-right (attractive **and** strong)? Is that your v1.0 target?
4. Any segment that's tempting on one axis but disqualified on the other?

### (g) Inputs → Outputs
- **Consumes:** Segment Profiles (size/growth/barriers) + Competition/Positioning (landscape/share/severity).
- **Produces:** the ranked segment choice → **Market Focus decision #1**, feeding the rest of the focus decisions and the MVP.

---

## How the Market Space flows (end-to-end)

```
Actor + JTBD (from Problem Space)
   │
   ▼
[1] Market: name it, size the Actors, trend + why
   │
   ▼
[2] Segmentation: pick variables (5 categories) → values → segments (sizes sum to market)
   │           discovery: interviews/judgment (qual) or multivariate (quant)
   ▼
[3] 6 Validity Rules: Homogeneous, Distinctive, Measurable, Substantial, Actionable, Accessible
   │           (+ no double-counting Actors)
   ▼
[4] Segment Profiles: 3 segments (name, variable, value, #actors, growth)
   │
   ├────────────────────────────┐
   ▼                            ▼
[5] Competition:            [9] Entry Barriers (per segment)
   options=competitors,         │
   categories, direct/indirect  │
   │                            │
   ▼                            │
[6] Positioning:                │
   criteria → current-state map │
   → white space                │
   │                            │
   ▼                            ▼
[12] Attractiveness × Position Screening Matrix ──┐
   │                                              │
   ▼                                              │
[7] MARKET FOCUS (5 aligned decisions):           │
   1 Segment  ◄──────────────────────────────────┘
   2 Niche  [10] ── Early Adopters [11]
   3 Use case
   4 Problem
   5 Position-to-own  ◄── future-state map + Position-to-Own statement [from 6]
   │
   ▼
[8] PRODUCT FOCUS / MVP (v1.0)  →  Solution Space
   (deferred: TAM — do at the last assignment)
```

---

## Strong vs. Weak — calibrated against anonymized exemplar workbooks

**What a STRONG Market Space looks like (patterns across the strongest exemplar workbooks):**
- **Segment sizes reconcile to the total market.** Strong workbooks size *every* segment and make them **sum back to the market total** (one strong workbook's three segmentation variables each reconcile to 150M; another's filter-chain narrowed 130.59M households → 21.74M DIY decorators, with segment sizes 9M+7.5M+5.24M = 21.74M).
- **The same variables across all segments; memorable names.** "Express Shoppers," "Immersive Storytellers," "The Worriers" — named, comparable, one variable set with only values changing.
- **Multi-variable segmentation then convergence to ONE focus segment** with an explicit size + competition rationale (one strong workbook converges on a 60M "Express Shoppers" segment; another uses a clean 2-variable matrix — delay severity × family size — then picks the largest low-barrier segment).
- **Competition mapped by category/substitution, not a flat list** — Direct hosts vs. DIY editors vs. file-hosting hacks (one podcast-tool exemplar); Hardware-only vs. Software-only vs. Combined (one EV-charging exemplar).
- **Positioning by gap-hunting:** score incumbents on the customer's criteria, then claim the 1–2 axes where **all** incumbents score low (one exemplar → Ease of Use + Audio Editing; another → price + long-term value; a third → charger availability + route updates + accurate range). Current-state **and** future-state maps on the *same* axes.
- **A crisp, single-sentence Position-to-Own** naming the target customer **and** the differentiators (one strong exemplar: *"premier choice among Hispanic patients in the U.S. for dental medical tourism, distinguished by exceptional safety and competitive pricing."*).
- **Aligned Market Focus + focused MVP:** the segment/niche/use-case/problem/position all reinforce one story, and v1.0 is deliberately scoped (one exemplar's beachhead = US Tesla BEVs; Stripe-style single first use case). Scope discipline — explicitly listing what is **deferred** to v2/v3.
- **A golden thread:** the same 2–3 core numbers recur across Problem, Market, Solution, and Value so the whole workbook reconciles as one argument.

**What a WEAK Market Space looks like:**
- **Guessed sizes dressed as data** — "assuming from personal experience" percentages, or a TAM that doesn't reconcile with the segmentation (one weak workbook's per-week TAM and mismatched WTP splits). *Cite sources; label estimates as estimates.*
- **Segment sizes that don't add up** to the market, or overlapping segments that violate **Distinctive** without a Use-Case justification.
- **A flat competitor list** or the fatal "we have no competitors" — ignoring substitutes and the manual/do-nothing option.
- **Product-centric positioning** — scoring on your own features instead of the customer's criteria; maps present only as images with no 0–10 scoring shown; **white space treated as proven demand.**
- **An overstated position** — claiming a gap ("fewer competitors in the 2-hour segment") without naming/scoring the real incumbents.
- **Unaligned or absent focus** — a niche that doesn't have the chosen problem; a position irrelevant to the segment; a 20-requirement MVP with **no prioritization** and scope creep beyond the focus.
- **Missing artifacts** — a "Positioning Analysis" heading with no actual map (one weak workbook), or empty view placeholders.
- **No niche / early-adopter definition** — targeting the whole segment head-on into a high-barrier, high-loyalty incumbent instead of an early-adopter beachhead.

**The one-line test for any Market Space:** *Does this product idea serve a segment that is genuinely attractive (large, growing, low-barrier) AND where it can hold a strong, differentiated position (few rivals, low incumbent share, severe problem) — with every focus decision aligned and every number sourced or honestly labeled?* If yes, it's strong.
