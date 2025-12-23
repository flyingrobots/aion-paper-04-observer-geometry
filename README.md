# AIΩN Foundations — Paper IV

## WARP Graphs: Rulial Distance & Observer Geometry

|  |  |  |
|--|--|--|
| **DOI** | `10.5281/zenodo.18038297` | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18038297.svg)](https://doi.org/10.5281/zenodo.18038297) |

**Status:** Published (Zenodo)

### Front Matter

WARP Graphs: Rulial Distance & Observer Geometry
James Ross (ORCID: [0009-0006-0025-7801](https://orcid.org/0009-0006-0025-7801))
Independent Researcher
AIΩN Foundations Series — Paper IV
December 2025

---

## Overview

Overview

This repository contains the LaTeX source and compiled PDF for Paper IV of the AIΩN Foundations Series.

Building on deterministic worldlines (Paper II) and holographic provenance payloads (Paper III), Paper IV develops a formal geometry of observers for deterministic, provenance-carrying computation. Observers are modelled as resource-bounded functors from a history category induced by multiway WARP graph rewriting into spaces of traces. Differences between observers are treated not as semantic disagreement but as translation problems under explicit time and memory budgets.

The paper introduces a translation framework equipped with Minimum Description Length (MDL) as a measure of translator complexity and a lifted trace distortion metric. From these ingredients it defines the rulial distance, a budgeted, MDL-regularised distance on observer space. Under standard assumptions, the directed translation cost admits a Lawvere-metric (enriched-category) interpretation, and the symmetrised distance is a quasi-pseudometric satisfying the triangle inequality up to constant additive slack.

Paper IV further formalises the Chronos–Kairos–Aion triad as a three-layer time model (committed linear time, branch events, and the encompassing possibility space) and develops a minimal temporal logic over histories aligned with this structure. The resulting observer geometry provides a computable notion of frame separation: the cost of translating between different descriptions of the same computation under resource constraints.

This paper concludes the mathematical core of the AIΩN Foundations Series and prepares the ground for subsequent work on ethics (Paper V) and system architecture (Paper VI).

---

## Contents

- `paper/main.tex` — Primary LaTeX manuscript (Paper IV)
- `paper/aion.cls` — AIΩN Foundations class file
- `paper/macros.tex` — Notation and helper macros
- `paper/diagrams.tex` — TikZ diagrams and global styles
- `paper/refs.bib` — Bibliography
- `Makefile` — Convenience build (latexmk + jobname/output directory)
- `pdf/` — Compiled PDF + LaTeX build artifacts

---

## Build Instructions

Requires:
- TeX Live or MiKTeX
- `latexmk` recommended (used by the Makefile)

Build from the repo root with:

```bash
make
```

Clean + rebuild:

```bash
make clean
make
```

The compiled paper appears in `./pdf/` as `aion-paper-04-observer-geometry.pdf`.

---

## AIΩN Foundations Series

This paper is part of a six-paper foundational series:

1. [WARP Graphs: A Worldline Algebra for Recursive Provenance](https://github.com/flyingrobots/aion-paper-01-warp)
2. [WARP Graphs: Canonical State Evolution and Deterministic Worldlines](https://github.com/flyingrobots/aion-paper-02-worldlines)
3. [WARP Graphs: Computational Holography & Provenance Payloads](https://github.com/flyingrobots/aion-paper-03-holography)
4. **WARP Graphs: Rulial Distance & Observer Geometry *(this repo)***
5. WARP Graphs: Ethics of Deterministic Replay & Provenance Sovereignty
6. The AIΩN Computer: Architecture & OS (JITOS)

---

## License

This repository contains the Paper IV manuscript, figures, compiled PDF, and documentation. These materials are © 2025 James Ross and licensed under **Creative Commons Attribution 4.0 (CC BY 4.0)**; see `LICENSE` for details.

The AIΩN Runtime and JITOS software projects referenced by the paper are *not* part of this repository; they live in separate repositories under their own licenses.

---

## More on AIΩN

For updates, see the main AIΩN repository:
[github.com/flyingrobots/aion](https://github.com/flyingrobots/aion)
