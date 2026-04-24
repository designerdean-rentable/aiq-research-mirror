---
tags:
  - research
---
> [!info] Scope
> Companion to [[Feedback]]. Explains the interview-craft reasoning behind each question in the template—what it's designed to elicit, what it avoids, and what weaker alternatives it beats. Draw on this when adapting the template for a new study or coaching a teammate through their first interview.

## Why These Questions, Not Others

Feedback interviews fail in predictable ways: Participants rationalize, generalize, or tell the facilitator what they think the facilitator wants to hear. The questions in this template are designed to counter those failure modes using techniques from Nielsen Norman Group's interviewing research and episodic memory science. Three principles run through every question:

- Episodic anchoring over generalization: "The last time you used X" is more accurate than "How do you use X" because episodic memory (specific events) is more reliable than semantic memory (abstracted patterns). People remember what they did; they confabulate what they "usually" do.
- Narrative before evaluation: Walk-through questions come before judgment questions. Once a participant is in story-telling mode, their evaluations are grounded in concrete context rather than generic opinion.
- Funnel from broad to narrow: Opening wide builds rapport, primes context, and avoids anchoring on a narrow topic before the participant has oriented. The first evaluative question lands only after the warm-up and walk-through have already populated the conversation.

## Per-Question Rationale

#### 1. "Tell me a bit about your role and what a typical week looks like for you."

A low-stakes opener that grounds every later response in real context. "Typical week" forces concrete specifics (meetings they sit in, tools they touch, work they own) in a way that "What do you do?" does not. It also tells the facilitator which vocabulary and domain references are safe to use for the rest of the session, and provides a last-minute check that the participant actually fits the persona the study was designed around.

Beats "Tell me about yourself" (too broad, invites a bio), "What's your job?" (answered in one noun), or jumping straight into product questions (no grounding, no rapport).

#### 2. "Walk me through the last time you used [product name]."

"Walk me through" elicits step-by-step narrative rather than summary. "The last time" forces episodic recall of a specific instance, which is far more accurate than asking for a generalized usage pattern. The probe "What were you trying to get done?" surfaces the underlying job-to-be-done rather than the feature used, so the team learns the intent the product is being bent toward rather than just the surface interaction.

Beats "How do you use X?" (invites an abstracted summary that filters out real friction), "How often do you use X?" (answers a frequency question but loses the texture of the actual work), or "Do you like using X?" (evaluative before narrative; the answer is nearly meaningless out of context).

#### 3. "When [product name] can't help you, where do you go?"

Assumes gaps exist without requiring the participant to accuse the product first. Surfaces the competitive landscape, the fallback workarounds, and—by extension—the adjacent problem space the product could credibly expand into. The probes ("What does that source give you…", "How often does that happen?") pull out the specific capability being substituted for and the frequency of the substitution, which together size the opportunity.

Beats "What does X do poorly?" (puts the participant in a defensive evaluative stance), "What competitors do you use?" (leading, and many participants don't think of their workarounds as competitors), or "What's missing from X?" (invites feature laundry lists disconnected from real tasks).

#### 4. "Tell me about the most recent time [product name] let you down."

"Most recent" anchors to a specific episode rather than inviting a generalized complaint. "Let you down" is a soft evaluative frame that normalizes the existence of failure, which makes it socially easy to criticize the product—something participants otherwise avoid out of politeness toward the team that built it. The follow-up "What did you do instead?" reveals whether the fallback was another tool, a colleague, or abandonment, which is the signal that matters for prioritization.

Beats "What do you dislike about X?" (abstract, yields canned complaints), "What bugs have you hit?" (narrows to technical defects and misses workflow gaps), or "Rate your satisfaction with X" (quantitative masking of qualitative signal).

#### 5. "Are there situations where you'd expect [product name] to help, but it doesn't today?"

Explores the scope boundary between what the participant thinks the product is for and what it actually covers—the richest source of mental-model mismatches, and a signal the product is being interpreted as broader than it is (a good problem). "Today" implies the gap is addressable rather than a permanent complaint, which keeps the participant constructive instead of resigned.

Beats "What features should we build?" (outsources product strategy to users, who are reliably bad at it) or "What's missing?" (invites features without anchoring in the participant's actual situations).

#### 6. "If you could change or add one thing about [product name], what would it be?"

The "one thing" constraint forces prioritization—participants have to reveal what matters most rather than produce a wish list. The probe "Why is that important to you?" is the question that earns its keep: The stated request is often a symptom; the underlying need is what informs design decisions. Without the why, the team ends up building the literal request and missing the actual problem.

Beats "What features do you want?" (wish lists without priority signal), "What should we work on next?" (asks the participant to do the team's job), or "Rank these features" (forces a frame the participant didn't choose).

#### 7. "If [product name] went away tomorrow, what would you miss most?"

A qualitative cousin of Sean Ellis' product-market-fit test: Instead of asking how disappointed they'd be, ask what they'd mourn. This surfaces the true value proposition, which often differs from what the participant claims to use most. Features used daily are frequently not the features that would be missed—the question cuts through habit to what the product is actually providing.

Beats "What's your favorite feature?" (shallow, rewards polish over value), "Why do you use X?" (abstract self-justification), or a generic NPS-style "How likely are you to recommend X?" (stanced and rehearsed).

#### 8. "Is there anything else you'd like to share about [product name]?"

A catch-all closer that respects the participant's agency to raise what matters to them rather than only what fits the facilitator's questions. Often surfaces the most valuable signal of the entire session because it's the moment the participant controls the frame—and the moment they've had the most time to warm up, so inhibitions are lowest.

Beats ending on the last scripted question (participants often have something they wanted to say but weren't asked about, and without a closer they leave it unsaid).

## What's Deliberately Avoided

- Leading questions: "Don't you find X frustrating?" plants the answer. "How do you feel when X happens?" lets the participant choose their own framing.
- Hypothetical future behavior: "Would you use X if we built Y?" is notoriously unreliable—people are bad at predicting their own future behavior, and polite participants over-commit.
- Feature-first framing: "Do you use feature Y?" collapses the session into yes/no checklists. The template asks about tasks and outcomes instead; features emerge naturally when they're load-bearing.
- Yes/no binaries: Any question answerable with "yes" or "no" puts all the work on the follow-up. Open-ended phrasing invites story.
- Satisfaction scales inside a qualitative interview: "On a scale of 1 to 10…" interrupts narrative mode and yields a number without meaning. Save scales for surveys.
- Why questions asked directly: "Why do you use X?" triggers post-hoc rationalization. The template gets at the why indirectly through narrative ("walk me through", "what were you trying to get done"), which is more truthful than self-reported reasoning.
