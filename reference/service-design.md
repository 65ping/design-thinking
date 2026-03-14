# Service Design Reference

Specialized tools and templates for service designers applying Design Thinking to multi-actor, multi-touchpoint service experiences.

---

## What Makes Service Design Different

Service design applies Design Thinking across a broader scope than product design:

| | Product Design | Service Design |
|---|---|---|
| **Primary focus** | A user interacting with an interface | All actors across all touchpoints over time |
| **Key actors** | End user | End user + frontline staff + back-office + partners |
| **Prototype type** | Wireframe, clickable prototype | Service blueprint, desktop walkthrough, role-play |
| **Test method** | Usability test | Staged pilot with all actor types |
| **Implement scope** | Ship a feature | Train staff, change processes, align organization |
| **Failure mode** | Poor UX | Backstage breakdowns visible to the customer |

The critical insight: most service failures that customers experience are backstage failures — process breakdowns, information handoffs, staff training gaps — that become visible at the frontstage. Service design fixes both.

---

## Artifact 1: Service Blueprint

**Purpose**: Map the full service experience across frontstage (what the customer sees), backstage (what the organization does), and supporting processes.

**When to use**: After user research has established the customer journey; before designing any individual touchpoint.

### Structure

```
SERVICE BLUEPRINT
─────────────────────────────────────────────────────────────────────────

Service: _________________________________
Customer archetype: _________________________________
Journey scenario: _________________________________
Date: _________________________________

TIME →          │ Phase 1       │ Phase 2       │ Phase 3       │ Phase 4
                │               │               │               │
─────────────────────────────────────────────────────────────────────────
CUSTOMER        │               │               │               │
ACTIONS         │ What the      │               │               │
                │ customer      │               │               │
                │ does          │               │               │
─────────────────────────────────────────────────────────────────────────
EMOTIONAL       │               │               │               │
CURVE           │ 😰 😐 😊 😤   │               │               │
(high/low/peak) │               │               │               │
─────────────────────────────────────────────────────────────────────────
LINE OF INTERACTION (visible boundary — customer sees this)
─────────────────────────────────────────────────────────────────────────
FRONTSTAGE      │               │               │               │
STAFF ACTIONS   │ What staff    │               │               │
                │ do that the   │               │               │
                │ customer sees │               │               │
─────────────────────────────────────────────────────────────────────────
LINE OF VISIBILITY (what customers can vs. cannot see)
─────────────────────────────────────────────────────────────────────────
BACKSTAGE       │               │               │               │
STAFF ACTIONS   │ What staff    │               │               │
                │ do that the   │               │               │
                │ customer      │               │               │
                │ cannot see    │               │               │
─────────────────────────────────────────────────────────────────────────
LINE OF INTERNAL INTERACTION (internal to organization)
─────────────────────────────────────────────────────────────────────────
SUPPORT         │               │               │               │
PROCESSES       │ Systems,      │               │               │
                │ tools, data,  │               │               │
                │ 3rd parties   │               │               │
─────────────────────────────────────────────────────────────────────────
PAIN POINTS     │               │               │               │
& OPPORTUNITIES │ ❌ Where it   │               │               │
                │ breaks down   │               │               │
─────────────────────────────────────────────────────────────────────────
```

### Worked Example (Hospital Appointment)

```
SERVICE BLUEPRINT: Outpatient Appointment at a Hospital
Customer: First-time patient referred by a GP

TIME →          │ Referral      │ Booking       │ Visit         │ Follow-up
─────────────────────────────────────────────────────────────────────────
CUSTOMER        │ Receives GP   │ Calls number  │ Arrives,      │ Waits for
ACTIONS         │ referral      │ on referral   │ checks in,    │ results by
                │ letter        │ letter        │ sees doctor   │ post/phone
─────────────────────────────────────────────────────────────────────────
EMOTIONAL       │    😐         │    😤         │  😰 → 😊     │    😤
CURVE           │ Uncertain     │ Frustrated    │ Anxious then  │ Anxious,
                │               │ (hold times)  │ relieved      │ waiting
─────────────────────────────────────────────────────────────────────────
── LINE OF INTERACTION ──────────────────────────────────────────────────
FRONTSTAGE      │ —             │ Call center   │ Reception     │ Letter
STAFF           │               │ agent books   │ checks in     │ or nurse
                │               │ appointment   │ patient       │ calls with
                │               │               │               │ results
─────────────────────────────────────────────────────────────────────────
── LINE OF VISIBILITY ───────────────────────────────────────────────────
BACKSTAGE       │ GP sends      │ Agent         │ Notes         │ Doctor
STAFF           │ referral by   │ accesses      │ retrieved     │ dictates
                │ fax (!)       │ patient       │ from records  │ letter;
                │               │ record        │               │ secretary
                │               │               │               │ transcribes
─────────────────────────────────────────────────────────────────────────
── LINE OF INTERNAL INTERACTION ─────────────────────────────────────────
SUPPORT         │ Fax system    │ Patient       │ Records       │ Letter
PROCESSES       │ + manual      │ scheduling    │ system;       │ template;
                │ logging       │ software      │ lab systems   │ post system
─────────────────────────────────────────────────────────────────────────
PAIN POINTS     │ ❌ GP sends   │ ❌ Avg 18 min │ ❌ Records    │ ❌ Patients
& OPPS          │ by fax;       │ hold time;    │ sometimes     │ wait 3–4
                │ often lost    │ call only     │ missing on    │ weeks with
                │               │ (no digital   │ arrival       │ no update
                │               │ option)       │               │
─────────────────────────────────────────────────────────────────────────
```

### How to build it

1. **Start with the customer journey** — map what the customer does, step by step, from first contact to final outcome
2. **Add the emotional curve** — mark highs, lows, peaks of anxiety, and moments of relief based on research
3. **Add frontstage staff** — what staff actions are visible to the customer at each step?
4. **Add backstage staff** — what do staff do that enables the frontstage, invisible to the customer?
5. **Add support processes** — what systems, tools, and third parties enable the staff actions?
6. **Mark pain points** — where does the blueprint break? Where do customer experience failures originate?
7. **Mark opportunities** — where can a small change produce outsized improvement?

---

## Artifact 2: Customer Journey Map

**Purpose**: Visualize the customer's full experience over time — what they do, think, and feel — across all touchpoints and channels.

**When to use**: After research; as input to the service blueprint. The journey map is customer-POV only; the blueprint adds the organizational perspective.

```
JOURNEY MAP
─────────────────────────────────────────────────────────────────────────

Customer archetype: _________________________________
Journey: _________________________________
Goal: What the customer is trying to accomplish: _________________________________
Research basis: _________________________________

─────────────────────────────────────────────────────────────────────────

PHASES           │ Awareness    │ Consideration│ Decision     │ Use         │ Loyalty
─────────────────┼──────────────┼──────────────┼──────────────┼─────────────┼──────────
CUSTOMER         │              │              │              │             │
ACTIONS          │ What they    │              │              │             │
                 │ do           │              │              │             │
─────────────────┼──────────────┼──────────────┼──────────────┼─────────────┼──────────
TOUCHPOINTS      │              │              │              │             │
& CHANNELS       │ Where they   │              │              │             │
                 │ interact     │              │              │             │
─────────────────┼──────────────┼──────────────┼──────────────┼─────────────┼──────────
THOUGHTS         │              │              │              │             │
(what they       │ "            │              │              │             │
think and say)   │             "│              │              │             │
─────────────────┼──────────────┼──────────────┼──────────────┼─────────────┼──────────
EMOTIONAL        │              │              │              │             │
CURVE            │ Positive ↑   │              │              │             │
                 │──────────────│──────────────│──────────────│─────────────│──────────
                 │ Negative ↓   │              │              │             │
─────────────────┼──────────────┼──────────────┼──────────────┼─────────────┼──────────
PAIN POINTS      │              │              │              │             │
                 │ ❌           │              │              │             │
─────────────────┼──────────────┼──────────────┼──────────────┼─────────────┼──────────
OPPORTUNITIES    │              │              │              │             │
                 │ ✅           │              │              │             │
─────────────────────────────────────────────────────────────────────────

MOMENTS THAT MATTER (peak and valley moments that define the overall experience):
1. _________________________________________________________________
2. _________________________________________________________________
3. _________________________________________________________________

KEY INSIGHT FOR DESIGN:
_________________________________________________________________
```

### Reading the emotional curve

The emotional curve is the most important line on the journey map for service design.

- **Peak moments** (highest positive) → protect these at all costs; they drive loyalty and word-of-mouth
- **Valley moments** (lowest negative) → these are the highest-priority design opportunities
- **"Cliff" drops** (sharp sudden negative) → these are usually process failures that become visible to the customer
- **Flat sections** (neutral, no emotion) → these are opportunities to add delight without high investment

The goal is not to make every moment excellent. It is to eliminate the cliff drops, raise the valleys, and protect the peaks.

---

## Artifact 3: Ecosystem Map

**Purpose**: Visualize all actors in a service ecosystem, their relationships, and the information and value flows between them.

**When to use**: At the start of a service design project to understand the full scope before narrowing focus.

```
ECOSYSTEM MAP
─────────────────────────────────────────────────────────────────────────

Service: _________________________________

Place actors on the map:
- Center: your organization
- Inner ring: actors in direct contact with the customer
- Outer ring: actors that support the service but don't touch the customer directly

Draw relationships as lines:
- Solid line: direct relationship (regular contact, information, money)
- Dashed line: indirect relationship (occasional, mediated through others)
- Arrow direction: flow of value, information, or money

Label each relationship:
- What flows across this relationship? (information, money, goods, trust)
- How frequently? (real-time, daily, monthly)
- How reliable is it? (always, sometimes, rarely)

─────────────────────────────────────────────────────────────────────────

         [3rd Party A]         [Partner B]
               │                    │
               └──────────┬─────────┘
                          │
         [Channel C] ─── [YOUR ORG] ─── [Channel D]
                          │
               ┌──────────┴─────────┐
               │                    │
         [CUSTOMER]         [Frontline Staff]
               │
         [Channel E: Customer's own ecosystem actors]
         (family, colleagues, other services they use)

─────────────────────────────────────────────────────────────────────────

KEY RELATIONSHIPS TO INVESTIGATE (highest friction or dependency):
1. _________________________________________________________________
2. _________________________________________________________________
3. _________________________________________________________________

ACTORS NOT CURRENTLY INCLUDED WHO AFFECT THE EXPERIENCE:
1. _________________________________________________________________
2. _________________________________________________________________
```

---

## Artifact 4: Desktop Walkthrough

**Purpose**: Prototype a multi-actor service interaction physically on a tabletop using simple props, before building anything.

**When to use**: After service blueprint; before pilot testing. Ideal for understanding how multiple actors' actions interrelate.

### Setup

- Print or sketch simple representations of each actor (icons or photos)
- Print or sketch representations of touchpoints (a phone, a desk, a form)
- Create simple props for key artifacts (a referral letter, a ticket, a form)
- Clear a table to act as the service environment

### Running a walkthrough

1. **Assign roles**: Each team member takes one actor's perspective
2. **Read the scenario**: Facilitator narrates: "The customer has just arrived at [starting point]. What happens?"
3. **Step through the blueprint**: Move through each phase, acting out the actions with props
4. **Call out breakdowns**: When an actor doesn't have information they need, or can't do what the blueprint says — stop. This is a design problem.
5. **Capture**: Film the walkthrough or have a scribe document every breakdown

### What to look for

- **Information gaps**: What does Actor A need from Actor B to proceed? Is that reliably provided?
- **Timing mismatches**: When Actor A finishes their step, is Actor B ready? What happens during wait times?
- **Exception handling**: What does the staff member do when the expected thing doesn't happen? (Customer didn't bring their ID. System is down. Form is missing.)
- **Handoff moments**: Every time an item passes between actors is a failure risk. Scrutinize all handoffs.

---

## Service Design: Design Thinking Application Notes

### Empathize — expanded scope

In service design, empathy must extend to all actors:

**Customer empathy** — standard empathy research: interviews, observation, empathy maps

**Frontline staff empathy** — equally important. Frontline staff are the service in the customer's eyes. Understanding their constraints, pressures, and workarounds is essential.

Research methods for frontline staff:
- Shadow a frontline staff member through a full shift (not just their "typical" day)
- Interview about the hardest cases, not the average ones
- Ask: "What do you do when the system doesn't work?" (Workarounds reveal system failures)
- Ask: "What do customers complain about that you can't fix?" (Backstage constraints visible at frontstage)

**Back-office and partner empathy** — less common but often the source of the most impactful insights. The person who processes the form that the customer never sees shapes the customer experience.

### Define — system-level POV

Service design POV statements must address system-level failures, not just individual touchpoints:

✅ System-level POV:
> "A customer managing a complex insurance claim needs a single consistent point of contact because the current system routes them between departments with different information, creating contradictory guidance and repeated explanation of their case."

❌ Touchpoint-level POV (too narrow for service design):
> "Customers calling the claims line need shorter hold times because they get frustrated waiting."

The touchpoint POV describes a symptom. The system-level POV describes the cause.

### Prototype — service-specific approaches

**Role-play simulation**
Have team members play all actors in the service and walk through a real customer scenario. Cheaper than a pilot, more revealing than a blueprint review.

Setup: Recruit 3–5 people, assign roles, set up a simple physical space, run through 3–4 customer scenarios including at least one exception/failure case.

**Staged pilot**
A limited real-world test of a new service in one location, with one team, for a limited time.

Design the pilot to answer the same question you would ask a prototype: "What is the riskiest assumption this service design makes?"

**Wizard of Oz for digital service components**
Before building the system that automates a step, have a human do it manually for real customers. If the manual version doesn't work, the automated version won't save it.

### Implement — change management is design

In service design, implementation is an organizational design challenge, not just a deployment:

**Training design**: Frontline staff cannot deliver a new service experience without new mental models and new skills. Training is a design artifact.

**Process documentation**: The backstage processes that support the service must be documented clearly enough for staff who weren't part of the design process to execute them.

**Incentive alignment**: If frontline staff are measured on speed and the new service requires them to take more time with each customer — the service will fail regardless of design quality. Measure and reward the behaviors the new service requires.

**Organizational readiness assessment**: Before launch, check:
- Do all actor groups understand their role in the new service?
- Are support systems (IT, logistics, partners) aligned?
- Is there an escalation path when the new service fails?
- Is there a feedback mechanism for frontline staff to surface problems?

**Post-launch pilot review**: 4–6 weeks after launch, run a blueprint review with frontline staff:
- Where is the service not working as designed?
- What workarounds have staff invented? (These reveal design gaps)
- What customer complaints are they hearing? (These reveal frontstage failures)
- What backstage problems are they hiding from customers? (These are the next design priorities)
