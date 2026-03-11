---
id: P15
type: principle
tier: governance
chapter: 9
title: Quorum Decay
short: "The quorum requirement decreases over time, preventing paralysis at low turnout."
formula: "Quorum(t)=Q_init·e^{−λt}, lim(t→∞)=Q_min>0"
related: [P8, P10, P16, P18]
---

## Statement

The quorum requirement decreases over time, preventing paralysis at low turnout.

## Formal notation

```
Quorum(t)=Q_init·e^{−λt}, lim(t→∞)=Q_min>0
```

## Detailed description

Quorum(t) = Q_initial × e^{−λt}, but with a lower bound Q_min > 0. This prevents two pathological states: (1) paralysis at low turnout; (2) capture by a small group at an excessively low threshold.

Invariance: the result depends only on parameters Q and λ, not on the specific voting path.

## Related elements

- P8
- P10
- P16
- P18
