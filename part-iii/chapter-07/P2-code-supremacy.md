---
id: P2
type: principle
tier: core
chapter: 7
title: Code Supremacy with NA0
short: "Violation of subjecthood is technically impossible — not merely prohibited."
formula: "SovereigntyShield: violation_impossible ∧ ¬violation_prohibited"
related: [P7, T14]
---

## Statement

Violation of subjecthood is technically impossible — not merely prohibited.

## Formal notation

```
SovereigntyShield: violation_impossible ∧ ¬violation_prohibited
```

## Detailed description

This is a fundamental distinction from a simple prohibition: a prohibition can be circumvented, technical impossibility cannot. Formal Verification (Coq) makes NA0 an invariant at the code level.

SovereigntyShield is the module that automatically blocks any action violating P0–P7. It does not warn, does not log — it _blocks technically_.

## Related elements

- P7
- T14
