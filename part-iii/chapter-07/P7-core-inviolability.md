---
id: P7
type: principle
tier: core
chapter: 7
title: Core Inviolability P0–P7
short: "The core cannot be changed by ordinary procedures — only through the emergency procedure P8."
formula: "Formal_Verification(Coq): ¬∃ action: violates(P0–P7)"
related: [P0, P8, P2]
---

## Statement

The core cannot be changed by ordinary procedures — only through the emergency procedure P8.

## Formal notation

```
Formal_Verification(Coq): ¬∃ action: violates(P0–P7)
```

## Detailed description

P7 protects itself: by including P7 in the core, the system makes it impossible to circumvent this protection through ordinary voting.

The only change mechanism is P8 (Axiom-Break), which requires extreme conditions and multi-level consensus. P0 is absolutely protected: even P8 cannot change it.

## Related elements

- P0
- P8
- P2
