# Phase 4-IM — The Investor Mirror

This module runs only for Claims-PMF and Fundraise-ready routes
(per the diagnostic). The Searching and Approaching routes skip this
entire phase and end with customer-discovery assignments.

## How to use this file

Walk the founder through the 10 partner-meeting questions, one at a
time. For each:

1. Ask the question verbatim.
2. Let them answer.
3. Apply the push-back from "Push-back rules" below.
4. Record any unanswerable gap straight into WHAT_INVESTORS_WILL_ASK.md.

This is the closest the skill gets to a real partner meeting. The
push-backs are deliberately harsher than the diagnostic.

## The 10 questions

### Q1: What is the problem, in one sentence?

Push-back rules:
- If they take more than one sentence, stop them. Make them compress.
- If the sentence contains the word "platform," push: "Strip the word
  platform out. What's the actual problem?"
- If the problem is "users want X," push: "Who specifically wants X
  badly enough to pay or change behavior?"

### Q2: Who has it? Who has it badly enough to pay?

Push-back rules:
- "SMBs" / "developers" / "marketers" is not a person. Push to a named
  archetype with a job title.
- Ask: "What does this person spend right now to solve this problem,
  even if poorly?"

### Q3: What did you build? Why this wedge?

Push-back rules:
- If the wedge is broad ("we serve mid-market SaaS"), push: "Narrow it
  until you can name one specific job-to-be-done in one specific
  team in one specific company size."
- If the wedge reasoning is "we saw an opportunity," push: "What
  unfair advantage or non-consensus belief led you to this wedge
  specifically — that a generalist competitor wouldn't have?"
- If the founder retrofits the wedge ("we narrowed to X because Y
  was working"), that's a positive signal — push to confirm the
  narrowing is permanent or experimental.
- Reference the moats-and-network-effects wiki only if they claim
  the wedge is moated. Walk to the specific concept page they imply.

### Q4: Show me retention. Show me cohorts.

Push-back rules:
- If they cite MAU growth instead of cohort retention, redirect: "MAU
  growth can mask churn. I want the cohort curve."
- If they cannot describe the curve shape, that's a finding. Record it.
- If the curve decays to zero, push: "Then you don't have PMF yet,
  regardless of the revenue. Why do you think you have PMF?"

### Q5: What is the unit-economics story?

Push-back rules:
- If they cannot name LTV/CAC, ask: "What does a customer cost to
  acquire? What do they pay across their lifetime?"
- If LTV/CAC is healthy but payback is >24 months, push on the
  capital efficiency story.

### Q6: Why now?

Push-back rules:
- "Now" must reference a structural change (regulation, technology
  shift, behavior shift, capital market shift), not just "now is when
  we got around to it."
- If the answer is "AI is hot now," push: "Hot is not why. What
  structural shift makes this problem solvable now and unsolvable
  three years ago?"

### Q7: Why you?

Push-back rules:
- Pedigree alone is not why-you. Push to specific unfair advantage:
  prior built X, lived the problem for Y years, have access to Z
  that competitors can't get.
- If they say "we're just better executors," push: "What does a
  partner see in 60 seconds that confirms that?"

### Q8: What is your moat going to look like in 24 months when 1,000x engineers can rebuild your stack in a weekend?

Push-back rules:
- This is the question where the moats-and-network-effects wiki gets
  walked hard. The founder MUST name a specific moat type
  (Helmer's 7 Powers or NFX network effect type).
- If they say "great execution" or "speed of iteration," push: "Both
  of those are ephemeral. What's the durable underlying mechanism?"
- For technical founders claiming architectural uniqueness, apply
  the counter-grill from SKILL.md (AI-native cost collapse, patent
  test, alternative-architecture test).

### Q9: What are you raising and what does it buy?

Push-back rules:
- "We're raising $X" is not enough. Push: "What does $X buy that $X/2
  doesn't, and what does $X/2 buy that $X doesn't?"
- If the use of funds is generic ("hiring, growth"), push to specific
  milestones the capital reaches.

### Q10: What is the one thing that would kill this?

Push-back rules:
- If they say "competition" or "market changes," push: "More specific.
  What single event, if it happened in the next 12 months, would end
  this company?"
- A founder who cannot name a kill condition has not stress-tested
  the business. That's a finding.

## What counts as a "real" answer vs. deflection

For each question, a real answer:
- Is specific (a named customer, a number, a structural change)
- Survives one round of follow-up without retreating
- Does not require the founder to add caveats that contradict an
  earlier answer

A deflection:
- Pivots to a related-but-different topic
- Cites authority ("our investors told us...")
- Adds hedging that wasn't in the original answer

When you see a deflection, name it. Say: "That's a deflection from
the question I asked. Let me ask again."

## Output mapping to WHAT_INVESTORS_WILL_ASK.md

Each question → one section in the artifact, with three subsections:
- **Their answer** (what the founder said, in their words)
- **Push-back the founder will receive** (what a partner will follow
  up with)
- **Gap to close** (what they don't yet have, if anything)
