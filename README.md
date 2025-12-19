# Bridge Paper 4 (BP4): Effective Dynamics of Stabilised Geometry in Emergent Gravity Frameworks

**Title:** *On the Effective Dynamics of Stabilised Geometry in Emergent Gravity Frameworks (BP4)*  
**Date:** December 4, 2025  
**Author:** Lee Smart (Vibrational Field Dynamics Institute)  
**Contact:** contact@vibrationalfielddynamics.org  
**X:** @vfd_org

---

## What this paper is

BP4 derives the **effective dynamics** of **stabilised geometric configurations** introduced in BP3.5, within the **emergent gravity framework** established in BP3. Concretely, BP4 shows how:

- **Mass** arises as the rest-energy of stabilised geometry  
- **Inertia** arises from resistance to **time-dependent translation** (collective-coordinate dynamics)  
- **Interaction** arises via **geometric backreaction**  
- **Newtonian gravity** appears as an **infrared / weak-field effective limit**  
- **Inertial and gravitational masses** share a common geometric origin (with proportionality governed by stabilisation class)

BP4 is intentionally **classical and effective**: it does **not** attempt Standard Model reproduction, gauge structure, fermions, or quantum superposition.

---

## Repository contents

- `paper/` — LaTeX source (Overleaf-ready)
- `figures/` — figure assets (if external) or TikZ sources (if embedded)
- `build/` — optional build scripts
- `releases/` — tagged PDF releases

---

## Download the paper

- Latest PDF: see **Releases** (recommended)
- Or build from source (below)

---

## Build instructions (LaTeX)

### Option A — Overleaf
Upload the contents of `paper/` to Overleaf and compile `main.tex`.

### Option B — Local build
Requirements:
- TeX Live (or MikTeX) with standard packages

Build:
```bash
cd paper
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
If using biber, replace the bibtex step accordingly.

Related papers
BP3: Emergent Gravity (foundation for the IR gravitational limit used here)

BP3.5: Geometric Origin of Matter (stabilised geometry criterion and ontology)

(Links will be added once repositories/releases are final.)

How to cite
See CITATION.cff. A BibTeX entry is also provided in paper/references.bib.

License
Paper text and figures: Creative Commons Attribution 4.0 (CC BY 4.0)

Any accompanying code (scripts/build helpers): MIT License

See LICENSE and LICENSE-CODE.

Versioning
v1.0 — Initial public release (Dec 4, 2025)

Subsequent releases will be tagged under GitHub Releases.

Contributing / Issues
If you spot typos, LaTeX issues, or clarity improvements:

open an Issue with the section + equation/figure reference

include minimal reproduction steps if it’s a build problem

Substantive scientific extensions should be proposed as separate issues and will be triaged against the scope of BP4.

Acknowledgements
This work is part of the Vibrational Field Dynamics (VFD) bridge-paper series.

yaml
Copy code

---

# LICENSE (paper) — CC BY 4.0

Create `LICENSE` with:

```text
Creative Commons Attribution 4.0 International (CC BY 4.0)

This repository’s paper text and figures are licensed under the Creative Commons Attribution 4.0 International License.

You are free to:
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose, even commercially

Under the following terms:
- Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made.

Full license text:
https://creativecommons.org/licenses/by/4.0/legalcode
