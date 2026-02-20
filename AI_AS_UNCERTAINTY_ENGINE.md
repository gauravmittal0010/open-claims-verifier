# AI as an Uncertainty-Reducing System  
## Not a Decision Authority

### Abstract
Most AI systems are designed to replace judgment by producing answers, rankings,
or recommendations. This system treats AI as infrastructure for uncertainty
reduction only.

It explicitly refuses authority: it does not decide truth, recommend actions,
or optimize persuasion. Its sole function is to expose evidence structure,
contradictions, gaps, and incentives around human claims.

---

## Core Design Constraint

> AI must reduce uncertainty without replacing human judgment.

Any system that removes the need for judgment is already exercising authority.
This design prevents that by construction.

---

## Scope (Deliberately Narrow)

The system processes one unit of input:

A human-written public claim expressed in natural language.

The system produces no conclusions, only structured context.

---

## Permitted AI Operations

The AI layer is restricted to four functions:

### 1. Claim Structuring
Decompose a claim into explicit components:
- subject
- metric
- claim type (e.g. causal, descriptive)
- time frame (if stated)
- location (if stated)
- unstated assumptions and definitions

Purpose: make hidden assumptions visible.

---

### 2. Evidence Mapping
Retrieve publicly available sources and classify them as:
- supporting
- contradicting
- insufficient or missing
- unrelated

All sources are shown. None are collapsed into conclusions.

---

### 3. Uncertainty Explanation
Enumerate reasons certainty is limited, including:
- conflicting definitions
- non-overlapping time frames
- correlation versus causation
- incomplete population coverage

Uncertainty is treated as first-class output, not an error.

---

### 4. Incentive Visibility
Identify who benefits if the claim is believed, using coarse categories only:
- government
- corporation
- political group
- public
- unclear

No intent is inferred. No accusations are made.

---

## Explicitly Forbidden Operations

The system must never:
- label claims as true or false
- rank people, groups, or beliefs
- recommend actions or decisions
- predict behavior or outcomes
- optimize engagement or persuasion
- nudge users toward conclusions

If a feature reduces the need for human judgment, it is rejected.

---

## Worked Example

**Input claim:**
“This policy reduced poverty.”

**AI output:**

**Claim structure**
- Subject: unspecified policy
- Metric: poverty
- Claim type: causal
- Time frame: not specified
- Location: not specified
- Definition of poverty: not specified

**Evidence mapping**
- Supporting:
  - Study A (urban population only, 2018–2020)
  - Government report (national average)
- Contradicting:
  - Study B (rural poverty unchanged)
  - NGO report (different poverty definition)
- Missing:
  - informal sector data
  - post-implementation comparison

**Uncertainty factors**
- poverty defined differently across sources
- urban and rural outcomes diverge
- correlation does not establish causation
- incomplete population coverage

**Incentive visibility**
- Government: high
- Political groups: medium
- Public: unclear
- Corporations: low

No verdict is produced.

---

## Design Rationale

Systems that claim authority over truth become:
- attack surfaces
- tools of persuasion
- objects of capture

A system that exposes structure only:
- remains legible under scrutiny
- scales without central control
- resists ideological alignment

Uncertainty does not weaken trust. Hidden assumptions do.

---

## Hard Refusal

This system is designed to remain limited even if that reduces adoption or utility.

Any extension that grants authority to AI invalidates the design.