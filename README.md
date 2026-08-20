# Fable: the companion bet

> Product Leadership certification, final project. The **Fable Growth** scenario (B2C, retention and engagement), taken from diagnosis to a funded business case with kill criteria across six in-class labs.
>
> Antje Barth · Product Leadership · Aug 2026 cohort

---

## The diagnosis

Fable peaked at 4.2M users by being genuinely good at one thing: helping adults through an acute anxiety episode. It works. Users resolve the thing they came for in 90 to 120 days, conclude they are done, and quietly stop opening the app.

So Fable's real competitor is not Calm or Headspace or an AI-native rival. It is the user's own conclusion that they no longer need it. You cannot fix that with engagement mechanics, because the mechanics would be arguing with a user who is correct.

## The bet

Fable becomes a clinically grounded AI companion whose value compounds through longitudinal personal memory. It wins the everyday "something feels off" moment for people it already has history with, so the second year of the relationship is worth more than the first.

**The hard no that gives it teeth:** we will not optimize the companion for attachment. No friendship or romance simulation, no time-in-app targets, no dependency mechanics. Attachment is the most profitable thing a companion can sell and it destroys the clinical trust that is the only durable moat. We measure "felt understood," never "couldn't leave."

That refusal costs real revenue, and it is what the rest of this repo is organised around defending.

## The argument in one pass

Each deliverable answers the question the previous one opens.

| | Deliverable | The question it answers | Module |
|---|---|---|---|
| 1 | [Product Strategy & OKRs](01-strategy/strategy-and-okrs.md) | What are we becoming, and what will we refuse? | M1 |
| 2 | [Outcome Roadmap & Trade-off Memo](02-roadmap/outcome-roadmap.md) | What ships first, and what did we cut to mean it? | M2 |
| 3 | [Team Charter](03-team-charter/team-charter.md) | Who decides, and what happens when the hard no meets a retention target? | M3 |
| 4 | [Financial Model](04-financial-model/financial-model.md) | Does the bet survive finance, and what number ends it? | M5 |
| 5 | [Individual Insights](05-insights/individual-insights.md) | What did building this actually teach me? | M6 |

Module 4 (Drive Alignment and Executive Influence) shaped how these land with executives rather than producing a separate artifact.

**The through-line.** The strategy sets one hard no. The roadmap cuts daily streaks, the content library, social sharing and the B2B tier to honour it, then treats sub-2-second load time as a Rock because latency is the front door for a product whose promise is "the first thing you talk to." The charter turns the hard no into a standing veto anyone can exercise, and adds a bright-line test for the one seam where it will genuinely be hard to apply. The business case then prices the bet and finds that the real product is not the return, it is $3.59 of breakeven headroom on a business currently sitting within cents of its cost of capital.

## Load-bearing assumptions

Two numbers carry this case, and both are named on the page rather than buried in it, each with a kill criterion holding a date and a threshold against it. The churn tail supplies most of the incremental value and is gated at month 12. The transfer coefficient from "felt understood" to retention is derived from the OKR pair rather than observed, so the gate that matters reads the retention outcome directly instead of trusting the sentiment score that predicts it. The ask is to judge this bet on breakeven-ARPU headroom, which it moves by $3.17, rather than on a 3:1 ratio the mechanism cannot reach at any plausible retention. Detail in [the financial model](04-financial-model/financial-model.md).

## Repo structure

```
product-leadership-final/
├── README.md
├── 01-strategy/
│   └── strategy-and-okrs.md      Playing to Win, the hard no, OKR cascade
├── 02-roadmap/
│   └── outcome-roadmap.md        Now/Next/Later, trade-off memo, backlog scoring
├── 03-team-charter/
│   └── team-charter.md           What We Own, How We Decide
├── 04-financial-model/
│   └── financial-model.md        Business case, seven kill criteria
└── 05-insights/
    ├── individual-insights.md    Friction, learnings, aha
    ├── final-presentation.md     Deck content, one section per slide
    └── product-leadership-final-antje-barth.pdf   The deck
```

## Status

| Deliverable | State |
|---|---|
| 1. Product Strategy & OKRs | Complete |
| 2. Outcome Roadmap & Trade-off Memo | Complete |
| 3. Team Charter | Complete |
| 4. Financial Model | Complete |
| 5. Individual Insights | Complete |
| Final presentation | Complete |
