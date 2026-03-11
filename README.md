# VIRTUBLIC — Content Repository

**Digital Sovereignty as Constitutional Form**

This repository contains the full content of the VIRTUBLIC interactive system, organized as Markdown files with YAML frontmatter. The web interface at [virtublic.html] loads content from this repository via the GitHub Raw API.

## Structure

```
/
├── meta/
│   ├── preambula.md          # Π₀ — The Primary Distinction
│   └── closing.md            # Ω — System Closure
├── part-i/                   # Part I — Digital Capital
│   ├── chapter-01/           # Chapter 1: Attention Substrate
│   │   ├── README.md
│   │   ├── T1-pribavochnoe-vnimanie.md
│   │   ├── T2-temporalny-barier.md
│   │   └── T3-net-korekcii.md
│   ├── chapter-02/           # Chapter 2: Platform Anthropology
│   │   ├── README.md
│   │   ├── T4-otvetstvennost-bez-vlasti.md
│   │   ├── T5-neutralizacia.md
│   │   ├── T6-kognitivnoe-razoruzhenie.md
│   │   └── T7-neobhodimost-formy.md
│   └── chapter-03/           # Chapter 3: Algorithmic Dominion
│       ├── README.md
│       ├── T8-razryv-suverenitetov.md
│       ├── T9-sistemny-kollaps.md
│       └── T10-konstitucionnaia-neobhodimost.md
├── part-ii/                  # Part II — Blockchain
│   ├── chapter-04/           # Chapter 4: Blockchain Ontology
│   │   └── README.md
│   ├── chapter-05/           # Chapter 5: Blockchain Anthropology
│   │   └── README.md
│   └── chapter-06/           # Chapter 6: Blockchain + Constitution
│       ├── README.md
│       ├── T11-plutokratia-pos.md
│       ├── T12-legitimnost-dao.md
│       ├── T14-code-is-law.md
│       ├── T15-trilemma-sybil.md
│       ├── T16-absorbcia-kritiki.md
│       └── T17-kalibrovochny-filtr.md
└── part-iii/                 # Part III — Constitutional Republic
    ├── chapter-07/           # Chapter 7: Core P0–P7
    │   ├── README.md
    │   ├── P0-narodny-suverenitet.md
    │   ├── P1-odin-grazhdanin.md
    │   ├── P2-verhovenstvo-koda.md
    │   ├── P3-soulbound.md
    │   ├── P4-dvoinoi-suverenitet.md
    │   ├── P5-otkryty-kod.md
    │   ├── P6-pravo-na-vyhod.md
    │   └── P7-neprikosnovennost.md
    ├── chapter-08/           # Chapter 8: Emergency Procedures
    │   ├── README.md
    │   ├── P8-axiom-break.md
    │   └── P9-convention.md
    └── chapter-09/           # Chapter 9: Governance
        ├── README.md
        ├── P10-madison-mode.md
        ├── P13-grazhdanskaia-strazha.md
        ├── P14-proof-of-offline.md
        ├── P15-quorum-decay.md
        ├── P17-sovereignty-shield.md
        └── P18-conflict-resolution.md
```

## Markdown format

Each file follows this structure:

```markdown
---
id: T1
type: theorem
part: I
title: Surplus Attention
short: "One-line statement"
formula: "Formal notation"
related: [T2, T3, P4]
resolved_by: "P4 + P16"
---

## Content in standard Markdown

Special directives:

::formula
// code block styled as formula box
::

::crisis{Δ1}
Crisis transition text
::

::callout{Label}
Callout text
::
```

## Connecting to the web interface

In the VIRTUBLIC HTML interface, open the **GitHub Content** panel at the bottom of the sidebar and enter:

- **Repository**: `your-username/virtublic-content`
- **Branch**: `main`

The interface will load all content from this repository, with local caching.

---

_VIRTUBLIC — Digital Sovereignty as Constitutional Form_
