# Team Charter: Fable Core

> Module 3 · Lead and Develop High-Performing Teams, ★ Deliverable 3
>
> The two components the charter turns on: What We Own and How We Decide. Both are written to be specific enough to be tested against a real decision or conflict.

**Scope.** "We" is the Fable Core product team (14 people) that I lead. PM 1, PM 2, and PM 3 are named because the AI check-in layer sits across two surfaces, which is the reason this charter exists.

**Anchored in the strategy (Deliverables 1 and 2).** The AI check-in layer is our current strategic bet (the memory-grounded companion, Rock 1). The one hard no from the strategy, no optimizing for attachment or dependency, is encoded below as a standing decision right, not a value to aspire to.

## What We Own

**In one line:** we own the whole companion relationship (memory, conversation, safety); three PMs split the surfaces, and where the AI check-in layer crosses surfaces, the surface owner owns the frame and PM 3 owns the content.

**What this team owns.** The companion relationship end to end. Owned centrally, not split by surface: the privacy-first memory engine (the moat), conversation design grounded in CBT/ACT (so a user gets one coherent companion), and the safety system (crisis detection, escalation, ship-gate evals). The three current bets, split across sub-teams:
- **PM 1, Onboarding:** arrival through the first felt-understood conversation.
- **PM 2, Retention:** 26-week retention, right-time notifications, sub-2-second open, dormant reactivation after the relationship has begun.
- **PM 3, AI check-in layer:** the memory-grounded check-in content and intelligence, a single shared capability invoked inside both surfaces.

**The crux rule:** surface owners own the frame, the check-in layer owns the content. PM 1 and PM 2 decide where and when a check-in fires in their surface; PM 3 decides what it says and how it uses memory.

**What is out of scope.** Clinical therapy and crisis-care delivery (we detect and hand off); general-purpose AI assistance; attachment optimization (the hard no, out of scope for every sub-team including retention, which is won by compounding value not hooks); the frontier LLM and the clinical protocols themselves (integrated via partners); net-new acquisition and paid growth (Growth owns bringing new people to the door, we own activating and retaining people we already have history with); voice, web, watch, localization, and the supporter track (all later, not active work). We do not build meditation or sleep-content packs.

**Cross-boundary decisions that need a joint call.** (1) Any change to check-in content, timing, or frequency inside a surface: PM 3 and the surface owner. (2) The onboarding-to-retention handoff seam, including the dormant-graduate second-conversation flow: PM 1 and PM 2 jointly. (3) Growth asks that touch the companion experience or target our base: surface owner and Growth lead, product leader tiebreak. (4) Anything touching memory, privacy, or data use: memory-engine owner and safety, always. (5) Any change with a plausible safety implication: safety review before action.

## How We Decide

**In one line:** whoever owns the metric decides, whoever owns the affected capability can veto it, safety and the hard no can stop anything outright, and no cross-team conflict stays open more than three business days.

**Default principle.** The person accountable for the metric decides; the person who owns the affected capability holds a veto on that capability. A decision only becomes joint when it changes a metric one PM owns by acting on a surface or capability another PM owns.

**Who decides what.**

| Decision | Decider | Must consult / co-sign |
|---|---|---|
| Onboarding / first-session design | PM 1 | PM 3 if it changes check-in content |
| Retention triggers, notifications, app-open perf | PM 2 | PM 3 if it changes check-in content or cadence |
| Check-in content, memory use, clinical grounding | PM 3 | Surface owner for where/when; clinical advisor |
| Memory engine architecture, privacy model | Memory-engine owner | Safety; product leader |
| Safety: detection, escalation, evals, halt | Safety lead | Non-overridable |
| Growth campaigns touching our base | Growth lead + affected surface owner | Product leader tiebreak |
| Roadmap sequencing, OKR trade-offs | Product leader | Affected PMs |
| Pricing pilot | Product leader | PM 2, Growth |

**Two non-negotiable overrides.** (1) Safety halt: the weekly safety review, or the safety lead at any time, can halt the model or a feature; not consensus, not overridable by any PM, Growth, or a deadline; it routes to the product leader only to confirm and plan the fix, never to reverse under pressure. (2) The hard no: any proposal optimizing for attachment or dependency is rejected at the point it is raised, by whoever notices; only disagreement about whether something crosses the line escalates.

**How cross-team conflicts escalate** (time-boxed so a bet cannot quietly stall). (1) Direct, within 24 hours: the two owners try to resolve it; whoever raised it writes a two-line summary (the decision, the disagreement, the metric each is protecting). (2) Joint working session, within 48 hours: the two owners plus any affected-capability owner decide with the data in front of them, against the OKR most at risk and the how-to-win, not by seniority. (3) Product leader decides, within 72 hours of first raise, in writing so it sets precedent. Skip the clock and escalate immediately if safety, memory or privacy, or the hard no is involved. Tiebreak at 72 hours: the surface owner's call stands provisionally unless safety or the hard no is implicated, logged for the next OKR review. Movement beats a perfect answer everywhere except safety.

**External escalations.** The product leader owns all escalations from outside the team (Growth, Sales, Clinical, executive); a PM never negotiates our roadmap alone against another team's leader. Response within 48 hours.

## Known risk this charter must close

The seam most likely to cause repeat conflict is retention / check-in / hard-no. Retention's fastest-looking levers (more notifications, stickier nudges) sit exactly on the line the hard no forbids, and "compounding value" versus "engagement mechanic" will feel identical in a specific ticket. Proposed bright-line test (to ratify with the clinical advisor): a check-in is **earned return** if it is triggered by a signal specific to this user (a pattern in their own history, a self-reported state) and justified by a felt-understood improvement; it is **manufactured dependency** if it is triggered by time-since-last-open or a fixed global cadence, or justified primarily by a frequency or retention number. Retention may ask for the first, never the second.

## Full charter (optional components, beyond the two required)

- **What Success Looks Like:** 26-week retention 12% to 30%; "felt understood" 4+ share 38% to 65%; graduate second-conversation rate 5% to 18%; zero unhandled safety incidents. Miss retention and felt-understood together: replan the check-in roadmap before next quarter.
- **How We Work:** We ship no conversational feature without passing safety evals, no exceptions for roadmap pressure. We measure "felt understood," never time-in-app. We bring memory-field and engagement-mechanic proposals to the room early, not after they are built. We disagree in the joint call, not in Slack afterward.
