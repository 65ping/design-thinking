# Design Thinking Templates

Ready-to-fill artifacts for every stage of the Design Thinking process.

---

## Template 1: Empathy Map

**Purpose**: Consolidate observations from user research into a shared understanding of one user archetype.
**When to use**: After user interviews or field observation, before affinity diagramming.

```
╔══════════════════════════════╦══════════════════════════════╗
║           SAYS               ║          THINKS              ║
║                              ║                              ║
║  Direct quotes from          ║  Beliefs and assumptions     ║
║  interviews / observations   ║  they hold (inferred from    ║
║                              ║  behavior, not stated aloud) ║
║  "                       "   ║                              ║
║  "                       "   ║                              ║
║  "                       "   ║                              ║
╠══════════════════════════════╬══════════════════════════════╣
║           DOES               ║          FEELS               ║
║                              ║                              ║
║  Observed behaviors and      ║  Emotional state across      ║
║  actions (what you watched   ║  the experience — highs,     ║
║  them do, not what they      ║  lows, anxieties, moments    ║
║  said they do)               ║  of relief                   ║
║                              ║                              ║
║                              ║                              ║
╚══════════════════════════════╩══════════════════════════════╝

USER ARCHETYPE: ________________________________
CONTEXT: ________________________________
RESEARCH DATE: ________________________________
```

**Worked Example (Caregiver)**

```
╔══════════════════════════════╦══════════════════════════════╗
║           SAYS               ║          THINKS              ║
║                              ║                              ║
║  "I never know if my mom     ║  "If something goes wrong    ║
║  actually took her pills     ║  because I missed a dose,    ║
║  when I'm not there."        ║  that's on me."              ║
║                              ║                              ║
║  "I call her but she         ║  "She doesn't understand     ║
║  doesn't always answer."     ║  how serious this is."       ║
║                              ║                              ║
║  "I try to organize them     ║  "I should be there more,    ║
║  in advance but it's not     ║  but I can't."               ║
║  foolproof."                 ║                              ║
╠══════════════════════════════╬══════════════════════════════╣
║           DOES               ║          FEELS               ║
║                              ║                              ║
║  Uses a weekly pill          ║  Anxious every morning       ║
║  organizer she fills         ║  until she hears from mom    ║
║  on Sundays                  ║                              ║
║                              ║  Guilty for not being there  ║
║  Calls her mother 2x/day     ║  in person                   ║
║  to "check in" (really       ║                              ║
║  to verify medication)       ║  Relieved when she finally   ║
║                              ║  confirms it was taken       ║
║  Photographs the pill        ║                              ║
║  organizer each week         ║  Frustrated by the          ║
║  as a paper trail            ║  uncertainty and manual      ║
║                              ║  workarounds                 ║
╚══════════════════════════════╩══════════════════════════════╝
```

---

## Template 2: Point of View (POV) Statement

**Purpose**: Frame the core human-centered problem to solve before ideating.
**When to use**: After affinity diagramming, as input to HMW question generation.

**Template**:
```
[User description] needs [need] because [insight].
```

**Blank**:
```
_____________________________________ [who they are in their context]
needs _________________________________ [what they genuinely need — not a solution]
because ________________________________ [the underlying insight from your research].
```

**Quality checklist**:
- [ ] Is the "who" described in human terms (context, situation) rather than demographic label?
- [ ] Does the "need" describe a human need, not a feature?
- [ ] Does the "because" reveal something non-obvious from research (an insight, not an observation)?
- [ ] Does the statement avoid naming any specific solution?
- [ ] Would your user recognize this as their own problem?

**Examples**:

✅ Strong POV:
> "A part-time caregiver managing her elderly mother's medication from a different city needs reliable confirmation that doses were taken as prescribed because the current phone-call system is uncertain and creates daily anxiety she cannot resolve."

❌ Weak POV (contains a solution):
> "Users need a medication tracking app because they forget whether pills were taken."

❌ Weak POV (business framing):
> "We need to increase medication adherence rates by 15% because non-adherence increases hospitalization costs."

❌ Weak POV (too broad, no insight):
> "Elderly people need help with medications because they forget things."

---

## Template 3: HMW Question List

**Purpose**: Transform your POV statement into generative ideation prompts.
**When to use**: Immediately after writing the POV statement, before Ideate.

**Generation template**:
From the POV: `[user] needs [X] because [Y]`
Generate HMW questions at multiple levels of scope:

```
Narrow (too specific, points to one solution):
HMW ________________________________________________________________?

Right scope (generative, multiple solutions possible):
HMW ________________________________________________________________?
HMW ________________________________________________________________?
HMW ________________________________________________________________?
HMW ________________________________________________________________?
HMW ________________________________________________________________?

Broad (too abstract, could apply to anything):
HMW ________________________________________________________________?
```

**Quality checklist for each HMW**:
- [ ] Does it have more than one plausible answer? (If not, too narrow)
- [ ] Is it specific to the user's real problem? (If not, too broad)
- [ ] Does it avoid naming a specific solution or technology? (If not, solution-prescribing)
- [ ] Would you genuinely want to generate ideas from this? (If not, revise)

**Worked Example (Caregiver POV)**:

POV: "A part-time caregiver needs reliable confirmation that her mother's medication was taken because the phone-call verification system creates daily anxiety she cannot resolve remotely."

Narrow (too specific):
- HMW build a pill bottle that sends a text when opened?

Right scope:
- HMW help caregivers confirm medication was taken when they were not present?
- HMW reduce the daily anxiety of remote medication management?
- HMW make medication confirmation simple for both the caregiver and the patient?
- HMW create a record of medication history that requires no tech expertise from the patient?
- HMW design a system that works even when the patient doesn't initiate it?

Broad (too abstract):
- HMW improve healthcare for elderly people?

---

## Template 4: Prototype Brief

**Purpose**: Define the question a prototype is designed to answer before building it.
**When to use**: Before beginning any prototyping work.

```
PROTOTYPE BRIEF
─────────────────────────────────────────────────────

Project / Feature: _________________________________
Date: _________________________________
Prototype type: _________________________________
  (paper sketch / wireframe / clickable / mockup / storyboard / service blueprint / other)

THE QUESTION THIS PROTOTYPE IS DESIGNED TO ANSWER:
_________________________________________________________________
_________________________________________________________________

WHAT WE ARE TESTING (the assumption at risk):
_________________________________________________________________
_________________________________________________________________

WHAT THIS PROTOTYPE INCLUDES:
_________________________________________________________________
_________________________________________________________________

WHAT THIS PROTOTYPE DELIBERATELY EXCLUDES (placeholders, not tested):
_________________________________________________________________
_________________________________________________________________

WHO WE WILL TEST WITH:
Number of participants: ______
Recruitment criteria: _________________________________
Scheduled test date: _________________________________

SUCCESS CRITERIA:
If this prototype test succeeds, we will know:
_________________________________________________________________

FAIL CRITERIA:
If this prototype test fails, we will know:
_________________________________________________________________

NEXT STEP IF IT SUCCEEDS: _________________________________
NEXT STEP IF IT FAILS: _________________________________
```

---

## Template 5: Usability Test Script

**Purpose**: Structure and guide a moderated usability test session.
**When to use**: Before any user testing session; adapt to your context.

```
USABILITY TEST SCRIPT
─────────────────────────────────────────────────────

Project: _________________________________
Prototype type: _________________________________
Session length: _________________________________
Facilitator: _________________________________

─── WELCOME & CONSENT (5 min) ──────────────────────

"Thanks for coming in today. My name is [name] and I'm working on [brief, neutral
description — avoid naming what you hope to achieve].

Before we start, a few things I want you to know:

First, we are testing the design, not you. There are no right or wrong answers, and
there's nothing you can do that would be wrong or embarrassing.

Second, I may not answer some of your questions during the session — not because I'm
being rude, but because we want to understand how the design works on its own. I'll
answer any questions you have at the end.

Third, [if recording] I'd like to record this session for our team to review later.
The recording won't be shared publicly. Is that okay with you?

Any questions before we start?"

─── WARM-UP (5 min) ────────────────────────────────

"Before I show you anything, I'd like to learn a bit about you and how you currently
handle [relevant task/problem area]."

Questions:
1. "Tell me a bit about how you [relevant context]."
2. "When was the last time you [relevant task]? What happened?"
3. "What tools or methods do you currently use for [relevant task]?"

─── TASKS (20–40 min) ──────────────────────────────

[Present prototype]

"Now I'm going to ask you to do a few things using what I'm showing you. As you work,
please think out loud — narrate what you're doing and what you're thinking, even if it
seems obvious. This is really helpful for us."

TASK 1: ________________________________________
Scenario: "Imagine that [realistic situation that motivates the task]. What would you do?"
Notes: ________________________________________
Observed: ________________________________________
Timing: ________________________________________

TASK 2: ________________________________________
Scenario: "Now imagine that [realistic situation]. What would you do next?"
Notes: ________________________________________
Observed: ________________________________________
Timing: ________________________________________

TASK 3: ________________________________________
Scenario: _________________________________
Notes: ________________________________________
Observed: ________________________________________
Timing: ________________________________________

Probing questions (use when behavior is unclear):
- "What are you thinking right now?"
- "What did you expect to happen there?"
- "What would you do next if this happened to you for real?"
- "What would you call this?"

─── DEBRIEF (10 min) ───────────────────────────────

"Thank you — that was really helpful. I have a few final questions."

1. "Looking back at the whole thing — what stood out to you, good or bad?"
2. "Was there any moment where you felt uncertain or confused?"
3. "Was there anything missing that you expected to find?"
4. "If you could change one thing, what would it be?"
5. "Is there anything you'd want to tell us that I haven't asked about?"

"That's everything. Thank you so much for your time. Do you have any questions for me?"
```

---

## Template 6: Test Findings Synthesis Table

**Purpose**: Organize and prioritize findings from user testing sessions.
**When to use**: After completing all test sessions, before deciding to iterate or proceed.

```
TEST FINDINGS SYNTHESIS
─────────────────────────────────────────────────────────────────────────────

Project: _________________________________
Prototype tested: _________________________________
Test dates: _________________________________
Number of participants: _______

SEVERITY KEY:
  Critical   = prevents task completion or causes significant distress
  Moderate   = significant difficulty, participant eventually recovers
  Minor      = slight friction, participant succeeds without notable difficulty

─────────────────────────────────────────────────────────────────────────────
ISSUE            │ SEVERITY  │ FREQ  │ OBSERVATION (behavioral)    │ DIRECTION
─────────────────┼───────────┼───────┼─────────────────────────────┼──────────
                 │           │       │                             │
                 │           │       │                             │
                 │           │       │                             │
                 │           │       │                             │
                 │           │       │                             │
─────────────────────────────────────────────────────────────────────────────

FREQ = number of participants who experienced the issue (out of total tested)
OBSERVATION = what you saw happen (not interpretation)
DIRECTION = the design direction suggested (not a specific solution)

─── DECISION ───────────────────────────────────────────────────────────────

Based on findings:

[ ] Return to PROTOTYPE — critical issues must be fixed and re-tested
[ ] Return to IDEATE — concept is fundamentally wrong, explore other directions
[ ] Return to DEFINE — problem statement was incorrect, reframe before ideating
[ ] Proceed to IMPLEMENT — only moderate/minor issues, plan is to fix in next iteration

Rationale: _________________________________________________________________

Known issues to address before next test or release:
1. _________________________________________________________________
2. _________________________________________________________________
3. _________________________________________________________________

Issues deferred to backlog:
1. _________________________________________________________________
2. _________________________________________________________________
```

---

## Template 7: Brainstorming Session Brief

**Purpose**: Prepare the team for a structured ideation session.
**When to use**: Before running any brainstorming or ideation workshop.

```
BRAINSTORMING SESSION BRIEF
─────────────────────────────────────────────────────

Project: _________________________________
Date / Duration: _________________________________
Facilitator: _________________________________
Participants: _________________________________

THE HMW QUESTION(S) WE ARE IDEATING AGAINST:
1. HMW _________________________________________________________________?
2. HMW _________________________________________________________________? (optional)
3. HMW _________________________________________________________________? (optional)

WHAT PARTICIPANTS SHOULD KNOW BEFORE ARRIVING:
(POV statement, key research findings, constraints)
_________________________________________________________________
_________________________________________________________________

IDEA GENERATION GOAL: _______ ideas in _______ minutes

METHOD(S) TO USE:
[ ] Brainstorming (silent then vocal)
[ ] Worst Possible Idea
[ ] SCAMPER
[ ] Brainwrite 6-3-5
[ ] Mind mapping
[ ] Other: _________________

CONVERGENCE METHOD:
[ ] Dot voting (each person gets _____ votes)
[ ] 2×2 matrix (axes: _____________ vs. _____________)
[ ] Rose, Bud, Thorn per concept
[ ] Other: _________________

NUMBER OF CONCEPTS TO SELECT FOR PROTOTYPING: _______

MATERIALS NEEDED:
[ ] Sticky notes (multiple colors)
[ ] Sharpies / pens
[ ] Large paper / whiteboard / Miro / FigJam
[ ] Timer
[ ] Printed HMW questions (one per participant)
[ ] Printed research summary (one per participant)
[ ] Dot stickers for voting

GROUND RULES TO READ ALOUD AT START:
1. Defer judgment — no criticism during generation
2. Build on others' ideas — "yes, and" not "yes, but"
3. Aim for quantity — quantity over quality right now
4. Encourage wild ideas — wild ideas often contain the seed of great ones
5. Stay visual — sketch, don't just write
6. One idea per sticky note
```
