---
last-reviewed: 2026-04-21
owner: Josh
tags:
  - research
---
## Purpose

A decision tool for choosing which research approach to emphasize at any given moment. Four concurrent lenses—Discovery, User Testing, Feedback, Experimentation—each answering a different core question. Not sequential phases; all four apply throughout product work. Informed by Christian Rohrer's [Landscape of User Research Methods](https://www.nngroup.com/articles/which-ux-research-methods/) (NN/g), which maps 20 UX research methods across three dimensions: attitudinal vs. behavioral, qualitative vs. quantitative, and context of product use.


---

## The Four Lenses

#### Discovery

*"Are we solving the right problem?"*

Grounds the team in the user's actual work, decisions, and context before designing solutions. Observes behavior and surfaces unmet needs.

- **Focus areas:** What users actually do, what needs are unmet, whether the project is worth doing
- **Typical methods:** User interviews, field studies, diary studies, contextual inquiry, competitive analysis
- **Delivers:** Problem statement (qualitative, generative)
- **Addresses risk:** Value, viability
- **Rohrer dimensions:** Primarily behavioral and qualitative, natural or near-natural context of use
- **Templates:** [[Discovery]] (plan) · [[Discovery Results]] (results)

#### User Testing

*"Can people actually use this?"*

Observes real people interacting with a design or prototype to identify usability problems before launch.

- **Focus areas:** Where people get confused, why they abandon tasks, what the design gets wrong
- **Typical methods:** Think-aloud tests, task scenarios, moderated and unmoderated remote testing, usability benchmarking
- **Delivers:** Usability fixes (behavioral, evaluative)
- **Addresses risk:** Usability, value
- **Rohrer dimensions:** Behavioral, qualitative, scripted or limited context of use
- **Templates:** [[User Test]] (plan) · [[User Test Results]] (results)

#### Feedback

*"What do users say they think and want?"*

Collects self-reported attitudes and reactions at any stage of product work—post-launch, mid-beta, or concept phase.

- **Focus areas:** Self-reported attitudes and reactions, stated pain points and desires, satisfaction and sentiment trends
- **Typical methods:** Surveys, NPS/CSAT, concept tests, beta feedback, support logs, product reviews, feedback interviews
- **Delivers:** Sentiment signal (attitudinal, continuous)
- **Addresses risk:** Value, viability
- **Rohrer dimensions:** Attitudinal, mixed qualitative and quantitative, decontextualized
- **Templates:** [[Feedback]] (plan) · [[Feedback Results]] (results)

#### Experimentation

*"Which option performs better?"*

Measures which design option performs better with live users, using controlled comparison.

- **Focus areas:** Which variant moves the metric, statistical significance of a change, measurable impact on business KPIs
- **Typical methods:** A/B testing, multivariate testing, feature flags, holdout experiments
- **Delivers:** Winning variant (quantitative, evaluative)
- **Addresses risk:** Value, feasibility
- **Rohrer dimensions:** Behavioral, quantitative, natural context of use
- **Rigor framework:** Drawn from Ron Kohavi's *Trustworthy Online Controlled Experiments* (2020), since NN/g's guidance on experimentation focuses on the role of A/B testing alongside UX research rather than the statistical methodology (hypothesis format, primary vs. guardrail metrics, sample-size calculation, decision rule)
- **Templates:** [[Experiment]] (plan) · [[Experiment Results]] (results)


---

## Key Distinctions

#### Discovery vs. Feedback

Both can use interviews as a method, but the target signal differs. [Attitudinal vs. Behavioral Research in UX](https://www.nngroup.com/articles/attitudinal-behavioral/) (NN/g) defines the split as self-report versus observation.

- **Discovery** observes behavior and probes the user's world without requiring product context. The question is "what problems do you have?"—product may not come up at all.
- **Feedback** collects self-reports anchored to a product. The question is "what do you think about X, how does X serve you, what do you want from X?"

Feedback interviews still use behavioral anchoring (critical-incident technique, "walk me through the last time you used X") to reduce recall bias and ground self-report. The behavioral anchor is technique; the target is attitudes, reactions, and stated desires. Don't let the "Feedback = self-report" framing push concrete-event questions into Discovery where they don't belong.

#### User Testing vs. Experimentation

Both observe behavior, but differ in method and scale.

- **User Testing** is qualitative and moderated (or unmoderated with small N). Typically five to eight participants, observing behavior in context of use. Outputs are usability issues and friction points.
- **Experimentation** is quantitative and at scale. Typically thousands of participants via A/B split. Outputs are conversion or engagement metrics.


---

## Common Mistake

Treating the four lenses as sequential phases instead of concurrent lenses. Strong teams apply all four continuously—choosing which to emphasize based on the biggest uncertainty right now. Teams that skip Discovery succeed at barely better than chance. Teams that run experiments without first understanding the problem optimize the wrong thing.
