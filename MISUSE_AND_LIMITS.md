# Misuse, Failure Modes, and Limits

This system is intentionally constrained.  
It is not a fact authority, a rating engine, or a decision tool.

The purpose of this document is to describe how the system could be misused
and how the design attempts to prevent accidental authority.

---

## Core Warning

This system does not determine truth.

It exposes:
- assumptions
- evidence structure
- contradictions
- uncertainty

Human judgment remains necessary.

---

## 1. Screenshot Authority Risk

A user may share a partial screenshot and claim the system confirmed a belief.

To counter this, every output must include visible uncertainty and conflicting
evidence when present.

No minimal “summary-only” output modes are allowed.

---

## 2. Evidence Flooding

Groups may attempt to create many low-quality sources supporting a claim.

The system does not count sources.  
Instead, sources are grouped by independence and methodology type.

Multiple derivative articles referencing the same dataset are treated as a
single evidence cluster.

---

## 3. Coverage Bias

Any retrieval system can unintentionally favor certain:
- regions
- languages
- publication ecosystems

The system must disclose:
- languages searched
- data gaps
- missing datasets

Absence of coverage is shown openly.

---

## 4. Incentive Misinterpretation

“Incentive visibility” shows impact, not motive.

Benefit does not imply:
- intent
- coordination
- wrongdoing

The feature exists only to expose structural incentives around belief.

---

## 5. Authority Capture

The most dangerous failure mode is pressure to produce a final judgment.

The system will never provide:
- truth scores
- credibility indexes
- rankings
- final reliability ratings

Any feature that creates a scalar authority output invalidates the design.

---

## 6. Over-Trust

Users may begin treating the system as a definitive source.

Every result must communicate:

Absence of evidence here does not mean false.  
The system has incomplete coverage.

The system is a transparency tool, not a referee.

---

## Design Position

The system prefers:
- visible limits over false certainty
- legibility over persuasion
- structure over conclusions

A trustworthy system must make its own limitations obvious.