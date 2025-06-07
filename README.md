# ASO-Design-PVL-S.aureus
# 🧬 ASO Design Against PVL mRNA in Staphylococcus aureus

## 🔍 Overview
This project involves the computational design and molecular evaluation of antisense oligonucleotides (ASOs) targeting the **Panton-Valentine Leukocidin (PVL)** toxin mRNA in *Staphylococcus aureus*. The work spans from sequence retrieval and structural prediction to molecular docking and dynamics simulations.

## 🎯 Objective
- Design ASOs targeting PVL mRNA using thermodynamic and accessibility filters.
- Validate ASO binding via RNAcofold and HADDOCK.
- Perform molecular dynamics (MD) simulations using AMBER to assess stability.

## 🛠️ Tools & Technologies
- ViennaRNA (RNAfold, RNAplfold, RNAcofold)
- sOligo for ASO design
- RNAComposer for 3D structure modeling
- MolProbity & ERRASER for validation
- HADDOCK for RNA-ASO docking
- AMBER 24 for MD simulation
- Python (BioPython, matplotlib) for analysis

## 📈 Results
- Designed 11 ASOs, selected top 5 based on ΔG, GC content, and accessibility.
- Best ASO (Target 83–102) showed ΔG = -10.4 kcal/mol and excellent duplex stability.
- Docking confirmed strong binding at the targeted mRNA loop.
- 30 ns MD simulation validated RNA-ASO complex stability with minimal RMSD drift.

## 📂 Folder Guide
- `data/` — Input sequences & NCBI IDs
- `scripts/` — Design & simulation scripts
- `results/` — All output figures & tables
- `figures/` — Key graphs for easy viewing
- `notebooks/` — Jupyter-based summaries
- `thesis/` — Final project report (PDF)

## ✨ Highlights
- RNA tertiary structure refinement using MolProbity + ERRASER
- Full RNA-ASO dynamics in AMBER with OL3 force field
- Detailed accessibility and thermodynamic evaluation pipeline

---
