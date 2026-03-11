---
id: P12
type: principle
tier: governance
chapter: 9
title: Temporal Lock — Time-Weighted Commitment
short: "Governance weight increases with duration of participation, preventing flash-governance attacks."
formula: "VIC⊥_eff(c,t) = VIC⊥(c) × min(log₂(t_months+1), lock_cap)"
related: [P10, P11, P15, T11, T12]
---

## Statement

Governance weight increases with duration of participation, preventing flash-governance attacks.

## Formal notation

```
VIC⊥_eff(c,t) = VIC⊥(c) × min(log₂(t_months+1), lock_cap)
```

## Detailed description

A rational actor in a liquid system can borrow capital, capture a governance vote, then exit — without any long-term stake in the outcome. P12 closes this attack vector by making governance weight a function of time as well as capital.

VIC⊥_effective(c, t) = VIC⊥_base(c) × min(log₂(months + 1), lock_cap). A participant of 12 months receives a multiplier of ~3.7×. A flash attacker who enters for one day receives a multiplier of ~0. The cap prevents excessive concentration through time alone.

P12 is the constitutional answer to governance financialization: participation in the republic is not a commodity that can be rented.

## Related elements

- P10
- P11
- P15
- T11
- T12
