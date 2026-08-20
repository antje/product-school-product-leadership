# Outcome Roadmap & Trade-off Memo: Fable

> Module 2 · Prioritization & Roadmapping for Product Leaders, ★ Deliverable 2
>
> The strategy turned into a multi-team, outcome-driven roadmap, with a memo defending the prioritization calls that cost something.

**Strategic anchor (from Deliverable 1).** Objective: become the companion our users talk to first when something feels off, and prove the relationship compounds instead of expiring. KR1: 26-week retention of companion users from 12% to 30%. KR2: share of conversations rated 4+ on "felt understood" from 38% to 65%, clinically audited. KR3: dormant graduates completing a second conversation within 30 days, from 5% to 18%. All by end of Q1 2027.

**Inputs.** The three Rocks from the Module 2 backlog audit (14-item Fable Growth backlog, scored on Impact vs Effort against the OKRs above): item 6, memory-personalized check-ins; item 9, crisis mode; item 14, sub-2-second load time. Full scoring table in the appendix below.

## 1. Outcome roadmap

Now/Next/Later format: what is in Now is committed and credibility-staked; Next is sequenced but not locked; Later is validated thinking, not a promise.

### Now (0 to 3 mo) · committed, maximum 3

| Outcome / bet | Backlog | OKR link | Owning team(s) | Success signal |
|---|---|---|---|---|
| We bet that opening every check-in with this user's own history (the trigger they logged last spring, the reframe that actually worked) will convince the graduate who thinks they finished Fable that the companion knows something a fresh start cannot, lifting felt-understood ratings from 38% to 65%. | Item 6 | KR2, feeding KR3 | Memory & Personalization; Conversation Design | "Felt understood" 4+ share climbing from 38%; personalization beats cold-LLM control in blind transcript review; returning users reach personal relevance in under 60 seconds. Guardrail: memory fidelity audited monthly alongside transcript quality (a wrong memory reads as betrayal, not a bug); retrieval precision is a ship-gate, and the companion asks rather than asserts when uncertain. |
| We bet that being demonstrably safe and useful in an acute anxiety spike will bring back the dormant graduate, the one who resolved their crisis, decided they were done with us, and quietly left, precisely when the wave returns, moving second-conversation returns from 5% to 18%. | Item 9 | KR3 entry point; safety guardrail behind KR1/KR2 | Safety & Clinical; Platform | Zero unhandled crisis incidents; 100% of flagged conversations escalated within SLA; dormant graduates entering through crisis mode convert to a second conversation. |
| We bet that a sub-2-second open with right-time notifications will make Fable the reflex, not the afterthought, for the lapsed user hesitating in the hallway before the meeting, lifting 26-week retention from 12% to 30%. | Items 14 + 4 | KR1, protecting every KR3 return | Platform; Engineering | p95 cold start under 2s on 4G; timezone notification bug at zero recurrence; KR1 cohort curves bending upward. |

### Next (3 to 6 mo) · sequenced, not locked

| Outcome / bet | Backlog | Sequencing rationale | Owning team(s) | Success signal |
|---|---|---|---|---|
| Users see their own patterns ("Sunday nights are hard for you") surfaced by the companion. | Extends item 6 | Needs months of real conversation history before patterns are honest, not guessed. | Memory & Personalization | Pattern reflections rated useful; KR2 lift among recipients. |
| Users who need more than self-serve get a warm handoff to vetted human care, and return to Fable afterward. | Item 5, therapist half | The escalation muscle from crisis mode must exist before we widen it to non-crisis referrals. | Safety & Clinical; Partnerships | Referral acceptance rate; post-care return rate. |
| A pricing pilot answers what the companion is worth and what a conversation costs. | Item 5, premium half | Pricing an unproven companion measures noise; waits for KR2 signal. Resolves the open board question on unit economics for M5. | Product; Finance | Willingness-to-pay bands; inference cost per weekly-active; contribution margin model. |
| New users' first session becomes their first conversation, not a form. | Item 1, re-scoped | The 40% onboarding drop-off is worth fixing only once there is a companion to onboard into; redesigning onto the old product wastes the work. | Conversation Design; Growth | Drop-off falling; day-7 second-conversation rate for new users. |
| Users navigating a named life transition (new parent, grief, job change) get a structured companion arc. | New, strategy-driven | Arcs are only credible once the base relationship works (KR2 signal). | Conversation Design; Clinical advisors | Arc completion; episode NPS by transition type. |

### Later (6 to 12 mo) · bets, not commitments

| Outcome / bet | Backlog | Honest confidence label | Success signal |
|---|---|---|---|
| The companion is available where the moment happens: voice, web, watch signals for recurrence detection. | Items 8, 11 + voice | Strategic bets; each inherits a proven relationship rather than creating one. Partnership pull (item 11) is not user pull; user pull decides. | Opt-in rates among retained users; no KR2 regression per surface. |
| The companion works in Spanish and Portuguese markets. | Item 7 | Right eventually, not resourceable now; clinical grounding does not translate for free. | Per-market KR2 parity with US baseline. |
| The people around a struggling user get their own supporter track; users can export a clinician-ready summary to their own therapist, fully user-controlled. | New, strategy-driven | Depends on privacy architecture holding and regulatory review; validated demand from stepped-care thinking. | Household accounts active; export usage with clinician feedback. |

Also resourced this quarter, outside the roadmap's bet structure: item 10 (WCAG 2.1 compliance, scheduled with a deadline as both legal necessity and care ethos) and a standing ~15% capacity reserve for stability sand.

This table is the source of truth for sequencing.

## 2. Trade-off memo

> I chose to sequence **memory-grounded check-ins (item 6), crisis mode (item 9), and instant availability (items 14 and 4)** first because they are, in order, the differentiator, the license to operate, and the promise made physical. Cost-of-delay reasoning drove all three: every quarter without memory-grounded conversations is a quarter our "felt understood" claim is indistinguishable from ChatGPT's; every conversational feature shipped before the safety gate exists is uninsurable downside risk; and the dormant-graduate cohort decays with time, so anything that makes returning harder, a 4.2-second load, a notification that fires at the wrong hour, is a wasting-asset problem. The unconventional call is treating performance as a Rock rather than sand: for a product whose winning aspiration is "the first thing you talk to when something feels off," latency is not polish, it is the front door.
>
> I pushed out **pattern insights, the therapist handoff, the pricing pilot, the onboarding redesign, and life-transition arcs** because each has a hard dependency on a Now bet proving out first. WSJF (scored in the second appendix) drove the sequencing: pattern insights have high value but an inflated job size until the memory engine accumulates real history; the therapist handoff (the strategic half of the CEO's premium-tier request, item 5) waits for the escalation muscle that crisis mode builds; the pricing pilot (its other half) has enormous risk-reduction value but zero validity before KR2 shows the companion is worth paying for; and the onboarding redesign (item 1) would currently onboard users into the product we are leaving behind. Splitting item 5 rather than building it as bundled was the quarter's most politically expensive call, and the right one: both halves survive, sequenced where each can succeed.
>
> I cut **daily streaks (item 2)** entirely because they violate the strategy's one hard no: attachment revenue is rented from the trust moat, and we do not rent out the moat. I cut **content library expansion (item 12)** because it deepens the product users graduate out of; investment in yesterday's value prop has negative strategic return whatever its matrix score says. I cut **the social sharing layer (item 3)** because mental-health progress is not social currency and sharing pressure works against the privacy promise the memory engine depends on. And I cut **Fable for Teams (item 13)** for this cycle, the genuinely uncomfortable call given the revenue attached, because employer reporting incentives point directly at both our hard no and our privacy promise. It is the first candidate for reconsideration once KR2 proves the companion works; the other three cuts are permanent.

## Appendix: 14-item backlog scoring (Impact vs Effort)

Scale: Impact 1-5 where 5 = strongly moves the north star and 1 = barely moves it; Effort 1-5 where 5 = most expensive across engineering, design, and PM. Scores already apply the lab's reality check (effort doubled, impact halved, re-bucketed). Impact is scored against the north star OKRs, not generic engagement; that distinction decides items 2, 5, and 13.

| # | Backlog item | Source | Impact | Effort | Quadrant | Verdict |
|---|---|---|---|---|---|---|
| 1 | Redesign onboarding flow (40% drop-off) | Product analytics | 2 | 4 | Avoid (for now) | Pushed out; re-scope as the "first conversation" redesign once the companion exists to onboard into. |
| 2 | Daily streak feature | Growth team | 1 | 2 | Do Now by raw DAU logic, Avoid by strategy | ❌ Hard No #1: manufactures attachment, violates the M1 hard no. |
| 3 | Social layer: share progress with friends | User research | 1 | 4 | Avoid | Cut: mental-health progress is not social currency; conflicts with the privacy promise. |
| 4 | Fix notification system (timezone bug) | Engineering | 3 | 2 | Fill Gaps | Early sand, scheduled now: right-time outreach underpins every reactivation bet. |
| 5 | Premium tier with therapist-matching | CEO | 4 | 5 | Plan Carefully | Split and sequenced: therapist handoff to Next after crisis mode; pricing to Next after KR2 signal. |
| 6 | AI check-in prompts personalized to user history | Product | 5 | 4 | Plan Carefully | 🪨 Rock #1 → KR2. Ships without the daily-guilt cadence; context triggers, never streak logic. |
| 7 | Localize into Spanish and Portuguese | Sales (LATAM) | 1 | 4 | Avoid | Later: clinical grounding does not translate for free. |
| 8 | Web version | Community | 2 | 4 | Avoid | Later: the companion moment is mobile-first. |
| 9 | Crisis mode flow for acute anxiety moments | Clinical advisor | 5 | 3 | Do Now | 🪨 Rock #2 → KR3 + safety guardrail. The safe return moment and the license to operate. |
| 10 | WCAG 2.1 accessibility compliance | Legal | 3 | 3 | Fill Gaps (deadline) | Scheduled this quarter: legal necessity and care ethos. |
| 11 | Apple Watch integration | 3 partnership requests | 2 | 3 | Avoid | Later signal: partnership pull is not user pull. |
| 12 | Content library expansion | Content team | 2 | 3 | Avoid | ❌ Hard No #2: deepens the value prop users graduate out of. |
| 13 | "Fable for Teams" B2B play | Business dev | 1 on north star | 5 | Avoid | ❌ Hard No #3: employer reporting incentives conflict with the hard no and privacy promise; revisit after KR2 proves out. |
| 14 | Load time 4.2s to under 2s on 4G | Engineering | 4 | 2 | Do Now | 🪨 Rock #3 → KR1. Instant availability is trust made physical. |

## Appendix: WSJF scoring for the Next queue

WSJF = (Time Criticality + Feature Value + Risk Reduction) / Job Size, each component 1 to 5. Used here rather than Impact vs Effort because the Next queue is a sequencing problem, and sequencing turns on what it costs to wait.

| Next item | Time criticality | Feature value | Risk reduction | Job size | WSJF |
|---|---|---|---|---|---|
| Pricing pilot | 4 | 3 | 5 | 2 | **6.00** |
| Therapist handoff | 3 | 4 | 4 | 4 | **2.75** |
| First-conversation onboarding | 2 | 3 | 1 | 4 | **1.50** |
| Pattern insights | 2 | 3 | 2 | 5 | **1.40** |
| Life-transition arcs | 1 | 3 | 1 | 4 | **1.25** |

The pricing pilot scores highest and it is not close, on the component the other frameworks ignore. Risk reduction is a 5 because it is the only item that answers the open board question about what a conversation costs and what a user will pay, and job size is a 2 because a willingness-to-pay study needs a survey and a cohort, not the memory engine. That result is why the business case sets its price gate at 30 November 2026 rather than waiting for the retention read: the roadmap and the funding case agree that this number has to arrive before the next acquisition budget is committed.

Where judgment overrides the score: pattern insights ranks fourth and still ships earlier in the Next block, because its job size is inflated only until the memory engine has accumulated real history, and it extends a Now bet rather than starting a new one. Life-transition arcs rank last and belong last. The one score I would defend hardest is the therapist handoff at 2.75, held behind crisis mode not because of its value but because widening an escalation path before the escalation muscle exists is how safety incidents happen.
