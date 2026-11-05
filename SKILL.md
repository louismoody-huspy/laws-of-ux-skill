---
name: laws-of-ux
description: The 54 Laws of UX cards (Jon Yablonski, lawsofux.com) as a working reference for coding and design agents. Use when designing a screen or flow, reviewing or critiquing a design, writing a usability test or research plan, explaining a design decision to stakeholders, or when anyone names a law, effect or principle (Hick's Law, Fitts' Law, Peak-End Rule, cognitive load, affordances, Jakob's Law and the rest). Pick the laws that apply, cite them by name, and say what each one changes in the work.
---

# Laws of UX

A reference, in four decks, from the Laws of UX cards by Jon Yablonski (lawsofux.com, 2022). The takeaways are paraphrased and credited; the cards themselves are his product. Each law has its own page at lawsofux.com for anyone who wants the source.

| Deck | Cards | File |
|---|---|---|
| UX theory | 29 laws and effects, Aesthetic-Usability to Principle of Least Effort | `references/ux-theory-1.md`, `references/ux-theory-2.md` |
| Psychology concepts | 10, Cognitive Load to Short-Term Memory | `references/psychology-concepts.md` |
| Interaction principles | 7, Don Norman's set: Discoverability to Conceptual Model | `references/interaction-principles.md` |
| UX methods | 8, Card Sorting to UX Survey | `references/ux-methods.md` |

## How to use it

1. Name the moment. Designing, reviewing, testing, or explaining. The table below says which deck to open first.
2. Open that deck file and read the cards that fit. Never cite a law from memory; read its entry so the takeaways are the card's, not a guess.
3. Follow the Related line. The cards chain: a UX theory card points to the psychology behind it, the interaction principle it rests on, and the method that tests it. Peak-End Rule, Cognitive Bias, Conceptual Model, Journey Mapping is one chain.
4. Write the law into the work. In a design, a line per law naming what it changed ("Hick's Law: the sheet shows two actions, the rest sit under More"). In a review, the law as the reason for each finding. In a test plan, the law as the hypothesis the task checks.
5. Keep it to the laws that bite. Three to five per screen or flow. A list of all 54 is noise.

| Moment | Open first | Then |
|---|---|---|
| Designing a screen or flow | UX theory (Hick, Fitts, Miller, Jakob, Proximity, Common Region, Prägnanz, Tesler, Doherty) | Interaction principles for every control: affordance, signifier, feedback, mapping, constraint |
| Notifications, alerts, nudges | Von Restorff, Zeigarnik, Peak-End, Serial Position, Selective Attention, Cognitive Load | Doherty Threshold for timing, Goal-Gradient for progress |
| Onboarding and first use | Jakob, Paradox of the Active User, Principle of Least Effort, Mental Model, Conceptual Model | Hick's Law, progressive onboarding takeaway |
| Forms and input | Postel, Tesler, Chunking, Short-Term Memory, Constraints | Fitts for targets, Feedback for errors |
| Reviewing or critiquing | Interaction principles as the checklist, then Aesthetic-Usability (does polish hide a usability gap) | Each finding names its law |
| Usability testing or research | UX methods: Usability Test, User Interview, Contextual Inquiry, Card Sorting | Campbell's Law before picking a metric, Paradox of the Active User for task design |
| Explaining a decision to stakeholders | The law behind the decision, its origin line | Design Principles card for writing the team's own principles |
| Metrics and targets | Campbell's Law, Pareto Principle, Parkinson's Law | Goal-Gradient for what to show users |

## Output shape

When this skill drives a review or a design note, write:

- The law, in bold, then one sentence on what it changes here.
- At most five laws.
- A source line at the end: "Laws of UX, Jon Yablonski, lawsofux.com."

## Limits

- The cards describe tendencies, not rules. Say "tends to" where the law is probabilistic, and test anything that matters with the UX methods deck.
- A law never overrides what users said in research or what the business agreed. It explains, it does not decide.
- The deck is from 2022. Newer findings exist; the laws here are the stable ones.
