# Strange Worlds Paper

Controlled comparison of standard prompting vs. Orthogonal Insight Protocol using Claude Opus 4.5 (with extended thinking).

Toolkit: https://github.com/emergent-wisdom/orthogonal-insight-toolkit

## Problem

How do we build a retirement system for people who don't know how much they will earn next month, where 'consistency' is impossible?

**Context:** Traditional retirement systems (401k, pensions, IRAs) assume regular income and consistent contributions. This excludes ~36% of the US workforce engaged in gig work, freelancing, seasonal employment, or informal economy.

## Experiment Design

- **Model:** Claude Opus 4.5 with extended thinking
- **Runs per condition:** 5
- **Solutions per run:** 5
- **Total solutions:** 50 (25 control + 25 protocol)

## Results Summary

### Control Condition
Prompted with: "Be creative. Think outside the box. Propose 5 genuinely novel and unconventional approaches."

**Result:** All 5 runs converged on the same 5-6 archetypes:
- Windfall/Surplus Capture (5/5)
- Mutual Aid Pools (5/5)
- Time-Banking/Labor Hours (4/5)
- Platform Profit-Sharing (4/5)
- Consumption-Based Triggers (3/5)

### Protocol Condition
Used 25 randomly-drawn seed words across 5 runs (5 seeds per run).

**Result:** 25 structurally diverse mechanisms, each shaped by its seed's counterfactual physics.

## Folder Structure

```
├── README.md
├── experiment/
│   ├── control/
│   │   ├── control_run1.md
│   │   ├── control_run2.md
│   │   ├── control_run3.md
│   │   ├── control_run4.md
│   │   └── control_run5.md
│   └── protocol/
│       ├── protocol_run1.md (seeds: limelike, unwilted, cinerator, nephropyosis, fimbrillate)
│       ├── protocol_run2.md (seeds: coralline, unimpatient, pilaued, displacement, theatrical)
│       ├── protocol_run3.md (seeds: palouser, critique, bromobenzyl, gnomically, remilitarize)
│       ├── protocol_run4.md (seeds: arcual, whizgig, entempest, chalaco, paranucleic)
│       └── protocol_run5.md (seeds: phraseman, desperacy, pidan, phosis, theca)
└── paper/
    ├── strange_worlds_paper.tex
    ├── strange_worlds_paper.pdf
    ├── references.bib
    └── arxiv.sty
```

## Key Finding

Both conditions reached the same meta-insight ("design for variability, not consistency"). But:
- **Control:** Iterated within familiar territory (25 variations of 5-6 archetypes)
- **Protocol:** Forced to alien territory by counterfactual physics (25 distinct mechanisms)

The Orthogonal Insight Protocol escapes the Median Trap not by asking for creativity, but by constructing constraints that make median solutions impossible.
