# Rapid Testing (Timeboxed Experiments) — What it is, why it matters, how to use it

## Executive takeaway
If you’re waiting months to reach a tiny MDE, you’re using the wrong tool for early learning.

**Rapid Testing** is a timeboxed experiment (usually **1–2 weeks**) designed to produce a **directional signal fast** with lightweight setup and clear guardrails.  
It does **not** replace powered A/B testing — it complements it by helping teams iterate quickly and reserve long tests for decisions that truly need them.

## What Rapid Testing is
A **Rapid Test** is an online experiment where you:
1) Fix the timebox first (typically 1 week; max 2 weeks)
2) Use simple, balanced allocation (often 50/50)
3) Use a stable primary metric + guardrails
4) Interpret results as **directional**, because it’s not sized to detect small effects

## What Rapid Testing is NOT
Rapid Testing is not:
- a shortcut to claim confidence on small lifts
- a method for early stopping by “peeking”
- appropriate for high-downside changes without rollback

## Why I recommend Rapid Testing
Powered A/B tests are great for launch decisions — but they slow iteration when:
- traffic is limited
- variance is high
- desired MDE is very small
- teams need faster learning cycles (copy, UX, targeting, ranking tweaks)

Rapid Testing changes the question from:
- “Can we detect a tiny lift with high power?”
to:
- “In 1–2 weeks, is this clearly better/worse or not worth pursuing?”

## When to use Rapid Testing vs Powered A/B
Use Rapid Testing when you need:
- fast iteration
- early directional signal before investing further
- de-risking (does this obviously break something?)
- quick prioritization

Use Powered A/B when:
- you must detect a small effect reliably
- you need decision-grade confidence for rollout
- impact is high and rollback is costly
- you need subgroup precision

## Decision tree (simple)
1) Is the change reversible + low downside?
- Yes → Rapid Test candidate
- No → Powered A/B (or staged rollout with strict guardrails)

2) Do you need confidence on a small lift?
- Yes → Powered A/B
- No → Rapid Test

## How to run a Rapid Test (1–2 weeks)
1) Write the decision rule (before launch)
2) Choose primary metric + guardrails
3) Fix timebox and allocation (default 1 week, extend to 2 only if needed)
4) Monitor data quality only during the run (balance, tracking, guardrails)
5) Interpret results with directional language and define the next step

## Recommended reporting language
- Positive: “Directional improvement within the timebox; recommend follow-up.”
- Null: “Inconclusive for small effects; iterate or run powered A/B if important.”
- Negative: “Directional downside; revert and investigate.”
