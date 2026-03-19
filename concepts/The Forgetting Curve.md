---
date: 2024-09-05
description: Ebbinghaus's discovery that we forget most of what we learn within days — and what to do about it.
tags: [concept, memory, ebbinghaus]
---

Hermann Ebbinghaus spent years memorizing nonsense syllables and testing himself. In 1885 he published *Über das Gedächtnis* and gave us the forgetting curve — one of the most replicated findings in psychology.

## The Core Finding

Without review, we forget approximately:
- **40%** within 20 minutes
- **60%** within an hour
- **75%** within 24 hours
- **90%+ ** within a week

```mermaid
xychart-beta
    title "Ebbinghaus Forgetting Curve"
    x-axis ["0 min", "20 min", "1 hr", "9 hrs", "1 day", "2 days", "6 days", "31 days"]
    y-axis "Retention (%)" 0 --> 100
    line [100, 58, 44, 36, 33, 28, 25, 21]
```

> [!info] These numbers are for *meaningless* material
> Real-world learning of meaningful content decays more slowly. But the shape of the curve — steep initial drop, then leveling off — holds.

## The Good News: Review Resets the Curve

Each time you successfully review material, the curve flattens. After enough spaced reviews, retention becomes near-permanent.

```mermaid
xychart-beta
    title "Effect of Spaced Reviews on Retention"
    x-axis ["Day 0", "Day 1", "Day 3", "Day 7", "Day 14", "Day 30", "Day 60"]
    y-axis "Retention (%)" 0 --> 100
    line [100, 40, 80, 50, 85, 60, 90]
```

*Each spike is a review session. The baseline rises each time.*

> [!tip] The optimal review moment
> Review just as you're about to forget — not before (wastes the opportunity) and not after (you've already lost it). This is exactly what [[Spaced Repetition]] systems like Anki calculate for you.

## Spacing Effect

The **spacing effect** is the flip side of the forgetting curve: distributed practice is dramatically more effective than massed practice (cramming).

Cramming works for tomorrow. Spacing works for next year.

This finding directly motivates:
- [[Spaced Repetition]] — systematic scheduling of reviews
- [[Interleaving]] — mixing topics rather than blocking them

## Connection to Retrieval

The forgetting curve assumes *passive* exposure. [[Active Recall]] — actually testing yourself — produces a different curve entirely. The retrieval effort itself strengthens the memory in a way that re-reading simply doesn't.

See [[How We Learn]] for the full picture.
