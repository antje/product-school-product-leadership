# Product Strategy One-Pager & OKRs: Fable

> Module 1 · Craft an Advanced Product Strategy, ★ Deliverable 1
>
> The **Playing to Win** cascade for Fable, the one deliberate **hard no** that gives it teeth, and the **OKRs** that fall out of it. Written to be specific enough that a skeptical board member could not poke a hole in it.

## 0. Chosen scenario

**Path:** Fable Growth (B2C · retention + engagement)

Fable's real competitor is the user deciding they don't need Fable at all. I chose this scenario because the growth wall can't be solved with engagement mechanics; it forces a genuine strategic reframe of what the product is.

## 0.5 Why this vision holds

**Why now?** Two things changed inside three years. Frontier models became good enough to hold a genuinely useful conversation about how someone is feeling, and the cost of retaining and retrieving personal context collapsed to the point where a companion can remember two years of someone's patterns affordably. Neither was true when Fable launched as a content library. The same vision written in 2021 would have described a chatbot nobody wanted.

**Why us?** We already hold the thing a competitor cannot start with: 4.2M people who trusted us during their worst weeks, and a record of what actually worked for each of them. ChatGPT begins every mental-health conversation cold. Calm and Headspace hold attention, not history. A new entrant with a better model still starts at zero on the only asset that compounds here.

**Why us, now?** The honest tension: we have the trust and the history, and we do not yet have the memory engine, the clinical audit bench, or evidence that content-app trust transfers to a conversational companion. That gap is the work, and it is why the first bet is a pilot with recent graduates rather than a repositioning. If we wait until the gap closes on its own, the AI-native rivals already targeting our demographic will have built the relationship instead.

## 1. Playing to Win cascade

**The bet: Fable becomes a clinically grounded AI companion whose value compounds through longitudinal personal memory.**

| Question | The choice |
|---|---|
| **Winning aspiration**: winning in the customer's terms, not internal metrics | Fable is the first thing you talk to when something feels off, before you can even name it, because it has known you for two years: your patterns, your triggers, what actually worked last time. Winning is the user who stopped thinking of Fable as "an anxiety app I finished" and started treating it as a companion whose value compounds, where the second year of the relationship is worth more than the first. |
| **Where to play**: segment, geography, channel, use case (the no's matter too) | Our existing users and recent graduates first, because they are the only people we already have history with: adults 25-45, US/English-language first. The use case is everyday mental wellbeing (the Sunday-night dread, the pre-meeting spiral, the "am I okay?" check-in), not just acute episodes. The surface is conversation: brief check-ins and reflections, not a content library. Explicitly not: clinical therapy or crisis care (we detect and hand off), and not general-purpose AI assistance. No productivity, no life admin. |
| **How to win**: your differentiator competitors can't easily replicate | Compounding personal context inside a clinically grounded companion. ChatGPT starts every mental-health conversation cold and generic; Calm and Headspace have content, not a relationship; therapy has depth but not 24/7 availability. Fable alone combines trust earned during the user's worst moments, a longitudinal record of what works for them, and responses grounded in real protocols (CBT/ACT). Every conversation deepens the moat: after a year, switching means starting over with a stranger. |
| **Capabilities required**: what you must be world-class at (build / buy / partner) | Build: the longitudinal memory engine (privacy-first, encrypted, user-ownable) and conversation design grounded in clinical protocols. Partner: frontier-model providers for the underlying LLM (we don't train foundation models), licensed clinical advisors who shape and audit model behavior, and crisis-line/telehealth partners for the escalation path. World-class or nothing: safety. Crisis detection, escalation, and red-teaming has to be our deepest bench, because one catastrophic response ends the company. |
| **Management systems**: the metrics and rituals that reinforce your choices | North star: weekly "felt understood" score (post-conversation) and 26-week retention, because a companion is only real if the relationship survives six months. Track depth over volume: meaningful conversations per week, personalization relevance (did memory make this answer better than a cold LLM's?), and safety incidents at zero tolerance. Rituals: weekly safety-incident review with escalation authority to halt the model, monthly clinical advisory audit of real transcripts, and a hard ship-gate: no conversational feature launches without passing safety evals, no exceptions for roadmap pressure. |

## 2. Your one hard no

> We will not optimize the companion for attachment: no open-ended friendship or romance simulation, no time-in-app targets, no engagement mechanics that make users emotionally dependent on Fable. Dependency is the most profitable thing a companion can sell, and it destroys the clinical trust that is our only durable moat. The companion's job is to make you more capable, not more attached; we measure "felt understood," never "couldn't leave."

## 3. OKR cascade

> **Objective:** Become the companion our users talk to first when something feels off, and prove the relationship compounds instead of expiring.
>
> - **KR1:** 26-week retention of companion users from 12% to 30% by end of Q1 2027. (The direct answer to the growth wall: does the relationship survive past the acute phase?)
> - **KR2:** Share of conversations rated 4+ on the post-conversation "felt understood" score from 38% to 65% by end of Q1 2027, audited monthly by clinical advisors against transcript quality. (Is the compounding memory producing felt value, not just stored data?)
> - **KR3:** Dormant graduates who return and complete a second conversation within 30 days of their first, from 5% to 18% by end of Q1 2027. (Does the companion reframe convert the people who already concluded they were done with Fable?)

## 4. AI pressure-test notes

| Prompt question | What the AI surfaced | Change or defend? |
|---|---|---|
| Biggest assumption that could be wrong | That trust earned as a content app transfers to a conversational AI companion. Users trusted Fable's exercises at their worst moment; that is not evidence they want to confide in a chatbot wearing the same brand. | Change: de-risk with an opt-in companion pilot for a cohort of recent graduates before any full repositioning. |
| The board question I can't yet answer | What does a conversation cost in inference, what will users pay, and what happens to both at scale? A companion is a marginal-cost product in a way a content library never was. | Change: surface it honestly as an unknown; run a pricing pilot and model inference cost per conversation in the business case. |
| KRs that are outputs in disguise | None are literal outputs, but KR2 is worse: a gameable sentiment. A sycophantic model that flatters users pushes "felt understood" up while making them worse. Nothing measures actual wellbeing. | Change: add a wellbeing guardrail (share of users arriving with elevated self-reported anxiety who improve at 8 weeks) and give the monthly clinical audit veto power over the KR2 number. |
| The "no" I should reconsider | The attachment ban. Warmth and continuity are attachment; a companion nobody bonds with retains nobody, and competitors will not hold this line. | Defend: attachment revenue is rented from the trust moat. Spending the moat to hit a retention number is how Fable becomes Replika with a meditation library. |
| Strategy or wish list? Why? | Strategy. It makes real exclusions with real costs, but it hinges on one unproven bet: that memory converts into felt value. Until KR2 moves, it is a well-structured hypothesis. | · |

## 5. Self-diagnostic (6 questions)

- [x] **Clear**: a new PM could read it and know exactly what we will and won't do
- [x] **Names the real challenge**: the diagnosis is specific enough to be uncomfortable (users leave because they feel better, and our competitor is their conclusion that they're done)
- [x] **Makes a hard bet**: it says no to something valuable (attachment, the category's proven revenue engine)
- [x] **Cascadable**: teams can translate it into their own OKRs (memory engine, safety, conversation design each own a KR driver)
- [x] **Coherent**: every choice reinforces the others (the hard no protects the differentiator; the metrics fire DAU and measure the relationship)
- [x] **Committed**: resources are now moving. The roadmap commits three Rocks and cuts four items outright; the business case funds the memory layer at ~$1.0M with seven kill criteria attached. _(Unchecked when this cascade was first written, before the roadmap and the business case existed.)_
