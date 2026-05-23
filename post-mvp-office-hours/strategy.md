# Strategy (not Planning)

This is Phase 5. The founder has shipped something, has users, and has data. That changes everything about how this phase runs.

For pre-build founders, the Playing-to-Win framework is an exercise in articulating a bet. For post-MVP founders, it is an exercise in **stress-testing a bet against what actually happened**. The framework is identical. The standard of evidence is not.

This phase is **stricter** than any other in this session about *coherence* — but **more forgiving** than any other about *certainty*. The founder will produce a real bet, not a list of activities, and they will not be asked to prove the bet will work. They will only be asked to articulate it clearly, back it up with logic, and show that the trajectory is consistent with it.

---

## Strategy is not planning

Most founders — including technical ones — confuse these two. The cost of confusion is high: you spend two years executing a plan that was never going to win, while a competitor with an actual strategy quietly takes the market.

The distinction (Roger Martin):

> A strategy is an integrative set of choices that positions you on a playing field of your choice in a way that you win.

A **plan** is a list of activities — hire X, build Y, launch Z, improve customer experience, open a new channel. Plans are *comfortable* because they are about resources and costs (which you control). Plans do not have to be coherent, and most aren't.

A **strategy** specifies an *outcome* — a competitive outcome that depends on customer behavior (which you don't control). It feels riskier because you can't prove it in advance. That is the point. The angst is a feature.

Martin's bottom line:

> If you plan, that's a way to guarantee losing. If you do strategy, it gives you the best possible chance of winning.

**This rule is the strictest enforcement standard in this entire skill. It does not relax for post-MVP founders. A plan masquerading as a strategy is caught and rejected regardless of how much data the founder has.**

## Playing to play vs. playing to win

The major US air carriers were busy "planning what routes to fly," buying more planes, opening more gates. They were not trying to *win* against each other on any specific field.

Then Southwest came along with a strategy:

- **Winning aspiration:** be a substitute for Greyhound — a way more convenient way to get around at a price not extraordinarily higher than a bus.
- **Where to play:** short flights, point-to-point, secondary airports.
- **How to win:** lowest cost in the industry, by far.
- **Capabilities:** one aircraft type (737), no meals on short flights, online direct booking instead of travel agents, fast gate turnaround.
- **Management systems:** every activity reinforces every other. 737-only means cheaper training, cheaper maintenance, cheaper gate setup. Point-to-point means no hub overhead. No meals means faster turns. Direct booking means lower customer acquisition cost.

Every choice fits with every other choice. That is the *integrative* part of an integrative set of choices.

Most early startups are not Southwest. Almost no post-MVP startups bother to check whether what they actually shipped is still consistent with what they intended when they wrote the strategy down. This phase is where the founder checks.

---

## The five strategic choices

The founder must produce a clear answer to each of these five. Not eventually. Today. In the chat. In plain English. Each one is a *choice* — meaning something else was rejected. **For post-MVP founders, each choice must be grounded in observed data, not hypothesis.**

### 1. Winning Aspiration

What does winning look like for this company, specifically? Not "be a great company." Not "make customers happy." Something concrete: *"be the substitute for [specific existing behavior] for [specific customer segment] within [time horizon]."*

The aspiration is the destination. It anchors every other choice.

**Post-MVP pushback — apply this before accepting the aspiration:**

> Is the current trajectory consistent with this aspiration? Show me the cohort curve or growth rate that says you're on the path. If retention is declining, new signups are flat, or revenue is not moving, the aspiration is either wrong or the execution is. Which? Tell me now — and tell me how you know.

A founder who states a bold aspiration and cannot point to a trajectory signal confirming it is not doing strategy — they are doing wish projection. Hold the line.

### 2. Where to Play

What playing field has been chosen — and which playing fields have been *explicitly ruled out*?

A where-to-play choice is made along multiple dimensions:
- Which customer segment (be specific — a real human, as in Q3, scaled up)
- Which geography
- Which channels (where the customer finds out you exist)
- Which stage of the value chain
- Which product category — and which adjacent categories you are *not* in

If the founder cannot name what they are *not* doing, they have not made a where-to-play choice.

**Post-MVP ground rule — where-to-play is now an observed cohort, not a TAM slide:**

> Name the cohort. Which signups from which month define the segment? What does their retention shape look like — flat, declining, or genuinely sticky? Where-to-play is no longer a hypothesis about who might buy. It is a claim about who *is* buying and *coming back*. If the founder cannot name a cohort, they have not answered this question.

### 3. How to Win

Given the playing field, what is the founder's *right to win* against everyone else who is or could be on that same field?

The traditional frame: cost leadership, or differentiation. **In an AI-native world, this question has new candidates and one disqualified answer.**

**Disqualified answer:** "We'll write more code than them." Lines of code is no longer a moat. AI has collapsed software production cost by 10-100x. Code is now cheap to produce, so the moat of having a lot of it is gone (see [ai-native-context.md](ai-native-context.md) — The Defensibility Shift). If the founder says "our edge is we'll out-build them," reject it.

**Equally disqualified:** "We have AI." So does everyone else with a credit card. AI is a substrate, not a strategy. What does *your use of AI* let you do that a competitor with the same access can't?

**Real candidates** the founder must pick from (one or more):

- **Cost leadership** — genuinely lowest cost in the segment, by design choice not luck.
- **Closed-loop data flywheel** — your queryable operations produce proprietary data that makes the product smarter over time. Competitors without the loop fall behind release by release.
- **Distribution** — you reach the customer through a channel competitors can't or won't replicate.
- **Trust / regulatory access** — particularly powerful in regulated incumbent-attacking categories (healthcare, finance, defense). Hard to clone with any amount of compute.
- **Network effects** — multi-sided platform, marketplace, or community where the product is more valuable as more participants join.
- **Proprietary data** — sensors, partnerships, customer-side integrations producing data only you have access to.
- **Depth of workflow integration** — once you live inside the customer's daily workflow, switching cost is high even if your code can be cloned cheaply.
- **Speed of iteration** — a token-maxed, software-factory-running team genuinely iterates faster. The compounding wins.

A good how-to-win sounds like:

> Compliance officers at mid-market healthcare companies will choose us because we are the only product that pre-fills the HIPAA audit forms automatically from existing patient records, which saves them roughly 30 hours a quarter and means they don't have to hire a second compliance analyst. No competitor does this because the integration with the major EMRs requires a 9-month sales cycle we have already completed.

That level of specificity. If the founder cannot give you that, they don't have a how-to-win. They have a wish.

**Moat-naming requirement — gated by route:**

For **Claims-PMF** and **Fundraise-ready** routes: when a strategic bet rests on a moat, the moat type *must* be named using Helmer's taxonomy (`moats-and-network-effects/wiki/concepts/`). Generic moat claims fail the strategy check; named moats with mechanisms can be tested. "We have network effects" is not enough. "We have personal utility network effects because each user's data makes their own experience materially better, and that advantage does not transfer if they leave" is a claim that can be examined.

For **Searching** and **Approaching** routes: naming a moat is procrastination. The founder does not yet have enough retention or user evidence to know which moat is forming. See the PMF-before-moat principle: you cannot build a moat on a product that is not yet sticky. Skip the moat-naming requirement for these routes and focus on the how-to-win mechanism at the product level instead.

### 4. Capabilities Required

What specific capabilities does this company *currently have* to deliver on the how-to-win? Not a generic list. The ones that are *essential*, *hard to copy*, and **already operating**.

Southwest's list looks short but is lethally specific: one aircraft type, fast gate turnaround, direct online booking, point-to-point operations. Each capability supports the others. Take one out and the cost advantage collapses.

**Post-MVP grounding rule — capabilities must be already shipping:**

> List the 3-5 capabilities the company currently has — already built, already operating, already in use by real users. Distinguish sharply from capabilities being built or planned. If a capability is not shipping today, it does not count toward the strategy. You can note it as "in progress" in a separate line, but it cannot be cited as a current strategic asset.

The non-technical founder owns *naming* the capabilities. The technical co-founder owns *building* them. But if the founder cannot name what is actually shipping, the co-founder is building blind about what matters.

**For AI-native startups, capabilities tend to be drawn from this list:**

- Closed-loop ingestion + queryable artifact store
- Software-factory build pipeline (spec → tests → AI-generated implementation)
- Specific data partnerships or integrations
- Customer trust / brand within a specific regulated segment
- Token-budget management and AI cost discipline
- The founder's domain network or sales access
- A specific workflow integration that creates switching cost

Pick the ones that actually serve the how-to-win and are already in production. Don't list everything that sounds important. Don't list anything that isn't shipping.

### 5. Management Systems

What systems are *currently in place* to develop, support, and measure these capabilities? What gets tracked weekly? What metric tells you the strategy is working? What metric tells you it isn't?

**For AI-native companies, the closed-loop ops decisions are management systems.** See [ai-native-context.md](ai-native-context.md) for the prescriptions (AI notetakers, channels over DMs, dashboards from week one).

**Post-MVP management systems — required instrumentation:**

For a post-MVP company, "management systems" is not aspirational. These must already exist or be declared missing now. Missing instruments mean the strategy is being formed without the ability to measure it.

Post-MVP management systems must include:

**(a) Cohort retention dashboard** — new-user-per-month curves showing week-by-week or month-by-month retention for each signup cohort. Not aggregate retention. Cohort retention. If this does not exist, the founder cannot observe whether where-to-play is working.

**(b) Customer-feedback loop** — a documented cadence with a number attached. "I talk to 5 users a week" or "we run a structured interview the first Friday of each month with 3 churned users" counts. "We talk to customers when it comes up" does not.

**(c) Unit-economics tracker** — LTV/CAC and payback period, with actual numbers. Estimates are acceptable if clearly labeled as estimates. Blank is not acceptable. If the founder cannot state LTV/CAC, they are not yet measuring whether the how-to-win creates economic value.

**(d) Feature-usage instrumentation** — answering "which features are load-bearing." Which features, if removed, would cause users to churn? Which are decorative? The founder should be able to name 2-3 load-bearing features and point to usage data.

If any of (a)–(d) is missing, name it explicitly before moving on. The strategy can still proceed — but the gap is on record and goes into WHAT_TO_DO_NEXT.md as a priority.

These systems land in the operating-model section of the `WHAT_TO_DO_NEXT.md` artifact as concrete choices the founder and co-founder must act on.

---

## The "back it up all of it" gate

This is the strict gate, and it is non-negotiable.

For every strategic choice — winning aspiration, where to play, how to win, each capability, each system — the founder must articulate *what would have to be true* for that choice to be the right one. Five buckets:

| Bucket | The question | 90-day falsification prompt |
| --- | --- | --- |
| About us | What does our team / story / capability set need to be true about for us to actually execute this? | What would we observe in the next 90 days — in our own team's output, speed, or coverage — that would tell us this assumption is breaking? |
| About the industry | What does the broader industry / category need to be true about for this to be a real opportunity? | What market signal, competitive move, or regulatory development in the next 90 days would falsify our assumption about the category? |
| About competition | What does competitor behavior need to be true about — what they're doing, not doing, blind to, or unable to do? | Which competitor move or product launch, observable in the next 90 days, would invalidate the assumption that they can't or won't do this? |
| About customers | What does customer behavior need to be true about — what they value, what they will pay, how they will buy? | What customer behavior, observed in the next 90 days, would falsify the assumption that retention stays above [X]%? Or that customers will pay [Y]? Name the threshold. |
| **About our production economics** | What does our AI-native build environment need to be true about for us to actually ship and iterate at the speed we're claiming? Does our token-maxing position hold up at scale? Is the software factory we're relying on actually as productive as we're assuming? | What would we observe in the next 90 days — in actual build velocity, token costs, or deployment frequency — that would tell us our production assumptions are wrong? |

The fifth bucket is not aspirational for post-MVP founders — it is actively measurable. If you assumed your co-founder ships in 2 weeks because of the software factory, and the factory turns out to need 6 months of tooling investment first, the whole strategy is off. You have 90 days of data to check this now. Use it.

For each "what must be true" item: **what evidence in the next 90 days would falsify this assumption?** Name the threshold. Name the signal. That is the watchlist. That is how the strategy stays alive instead of becoming a plan in disguise.

Martin again:

> Lay out the logic of your strategy clearly. What would have to be true about ourselves, about the industry, about competition, about customers for this strategy to work? It'll allow you to tweak your strategy. Strategy is a journey.

If the founder cannot articulate what must be true behind a choice, the choice is not yet a choice — it's a guess wearing a hat. Push them to back it up, or remove it from the strategy.

---

## The strict / forgiving balance

### Stricter than any other phase

- **No "we'll figure it out"** on any of the five choices.
- **No vague aspirations.** "Be a great company" is not an aspiration. "Win the SMB compliance market in healthcare in 18 months by being the only product that auto-fills HIPAA forms" is.
- **No "better UX" / "AI-powered" / "more focused"** as how-to-win. Specific, comparative, customer-grounded — or nothing.
- **No "we'll out-code them"** as how-to-win. Lines of code is no longer a moat.
- **No fluffy capabilities.** Each one essential, hard to copy, already shipping, and named.
- **No capabilities that aren't shipping.** Planned capabilities are not strategic assets.
- **No skipping the "what must be true" backup.** Every choice gets backed up. Every one. All five buckets.
- **No 90-day falsification prompt left blank.** Each bucket requires a named signal and a named threshold.
- **No activities masquerading as strategy.** "Hire two salespeople" is not strategy. It might appear in an operational to-do list. It does not appear in the strategy section of the artifact unless the founder can back it up with a strategic bet.
- **No trajectory-aspiration mismatch left unexamined.** If the current data does not support the aspiration, the founder must name which one is wrong before moving on.

### More forgiving than any other phase

- **You do not require the founder to prove the strategy will work.** They can't. That is true of every strategy ever written. Saying "I cannot prove this" is not a defect.
- **You do not require certainty.** Strategy is a bet. The angst is real, and the founder should feel it.
- **You do not require the strategy to be final.** Strategy is a journey. Lay out the logic, watch the world unfold, tweak as you go. The "what must be true" list is the watchlist.
- **You do not punish the founder for picking something imperfect.** Imperfect-and-chosen beats perfect-and-undecided every time.
- **You do not require perfect data.** Estimated unit economics with labeled uncertainty are acceptable. Blank is not.

The exchange the founder is making: take the discomfort of a bet they can't guarantee, in return for the clarity that lets their technical co-founder build the right thing. The reverse exchange — comfort now, fuzzy build for nine months — costs far more.

---

## Catching planning sneaking in

The founder will slip into planning language. Catch it every time:

| What they said | Why it's planning, not strategy | How to redirect |
| --- | --- | --- |
| "We're going to hire two more salespeople." | Cost decision. You control it. | "What customer behavior does that create? What does the customer get that they didn't before?" |
| "We're going to launch a mobile app." | Activity, not bet. | "What changes for the customer? Why now? Why this segment specifically?" |
| "We're going to open an office in Bangalore." | Cost. | "What does the customer care about here? What does this enable on where-to-play or how-to-win?" |
| "We're going to improve onboarding." | Improvement is not a bet. | "*What* about onboarding? For whom? Producing what specific change in customer behavior?" |
| "Our strategy is to be AI-native." | Substrate, not strategy. | "AI is what your competitor uses too. What does *your use of AI* let you do that they can't?" |
| "Our strategy is to grow faster." | Growth is not a bet. | "Grow what? In which cohort? By which mechanism? What does the customer change their behavior to do?" |

For each activity the founder names, ask: *what is the strategic bet that backs this up?* If they cannot back it up, the activity is comfort, and it comes out of the strategy section.

---

## The one-page output

When you are done, the founder should be able to write — and read back — a single page that captures:

```
WINNING ASPIRATION
  {one-sentence bet about what winning looks like, with a time horizon}
  {trajectory signal: the data point confirming we're on the path, or
   the honest acknowledgment that we're not yet there and why}

WHERE TO PLAY
  Customer:    {specific segment, named as a cohort — which signups, which month}
  Retention:   {what the cohort curve looks like — sticky, flat-after-decay, or declining}
  Geography:   {specific, or "all" with reason}
  Channel:     {how the customer finds us}
  Scope:       {what's in — and crucially, what's out}

HOW TO WIN
  {one paragraph stating the right-to-win, drawn from the defensibility list —
   cost leadership, closed-loop flywheel, distribution, trust, network effects,
   proprietary data, depth of integration, or speed of iteration. NOT "more code"
   or "AI." Specific enough that a competitor reading it would be uncomfortable.}
  {for Claims-PMF and Fundraise-ready: moat type named from Helmer's taxonomy
   (moats-and-network-effects/wiki/concepts/) with mechanism stated.}

CAPABILITIES REQUIRED (already shipping)
  - {capability 1 — essential, hard to copy, in production today}
  - {capability 2}
  - {capability 3}
  [in progress, not yet counting: {capability being built}]

MANAGEMENT SYSTEMS
  - Cohort retention dashboard: {exists / missing — if exists, what it shows}
  - Customer-feedback cadence: {documented cadence with a number}
  - Unit-economics tracker: {LTV/CAC and payback period — actual or estimated}
  - Feature-usage instrumentation: {load-bearing features named}

WHAT MUST BE TRUE
  About us:                       {1-2 lines}
    → 90-day falsification:       {signal + threshold}
  About the industry:             {1-2 lines}
    → 90-day falsification:       {signal + threshold}
  About competition:              {1-2 lines}
    → 90-day falsification:       {signal + threshold}
  About customers:                {1-2 lines}
    → 90-day falsification:       {signal + threshold, e.g. "retention falls below X%"}
  About our production economics: {1-2 lines}
    → 90-day falsification:       {signal + threshold}
```

If the founder cannot write this on one page, in plain English, and read each line back to you in their own words, the strategy is not yet locked.

---

## The read-it-back gate (strategy edition)

Before moving to the artifact draft phase, the founder must read back, **in their own words and without re-reading the chat**:

- Their winning aspiration — and the trajectory signal that confirms (or challenges) it
- Where they are choosing to play — the cohort, its retention shape, and what they are *not* doing
- Their right to win in one sentence — and which defensibility category it comes from
- The single most important "what must be true" item across all five buckets, and what they would watch in the next 90 days to know if it's true or breaking

If they cannot, the strategy is not yet shared understanding. Loop back.

---

## Technical Redirect Protocol — strategy edition

The founder may try to outsource strategic choices to the co-founder. Almost all of them are non-delegable:

| Strategic choice | Whose call | Why |
| --- | --- | --- |
| Winning aspiration | Founder | The aspiration is a bet about market and customer. Not a build question. |
| Where to play | Founder | Customer / channel / scope is the business side. The cohort data lives with the founder. |
| How to win | Founder, with input from co-founder on what's buildable | The "right to win" is a customer claim. The co-founder can tell you what's hard to build, but cannot tell you what customers value. |
| Capabilities required | Founder names them; co-founder builds them | Naming what is already shipping is the founder's strategic act. |
| Management systems | Founder | Knowing what to watch is the founder's job. The co-founder may build the dashboards. They don't choose the metric. |

If the founder tries to defer any of the above, hold the line. Pricing is not technical, distribution is not technical, who-the-customer-is is not technical — and where-to-play and how-to-win are not technical either.

---

## After the strategy is locked

Move to **Phase 6 — Drafting the Artifacts** ([drafting-and-review.md](drafting-and-review.md)). The strategy outputs land in two places:

- **WHERE_YOU_ARE.md** — "Strategy snapshot" section. This is the one-page output above, condensed to what a cold reader needs to understand where the company is positioned and why.
- **WHAT_TO_DO_NEXT.md** — "Headline move" section. This is the single most important strategic action implied by the where-to-play / how-to-win combination, plus any management-system gaps flagged during Phase 5.

For **Fundraise-ready** routes: the "what must be true" watchlist also feeds into **WHAT_INVESTORS_WILL_ASK.md**, specifically the sections on defensibility, retention trajectory, and unit economics assumptions. Investors will probe the falsification signals the founder named here. They should have answers ready.

The "what must be true" list becomes a weekly watchlist the founder uses with their technical co-founder. The operating-model decisions (closed-loop, token-max, archetypes, management instrumentation) become sections of the `WHAT_TO_DO_NEXT.md` artifact as concrete choices the co-founder has to know about and build for.
