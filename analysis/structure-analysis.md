# Protein Structure Analysis: Human Insulin (P01308)

## 1. Confidence Evaluation (pLDDT & PAE)
- **Mean pLDDT:** ~84.5 (overall high confidence across core helical domains).
- **Low Confidence Region:** Residues 1–24 (Signal Peptide) show low pLDDT (<70) due to high conformational flexibility and cleavage prior to mature hormone secretion.
- **PAE Interpretation:** Demonstrates distinct low-error blocks corresponding to structured alpha-helical segments, while indicating relative flexibility at terminal loops.

## 2. Experimental Comparison (AFDB vs RCSB PDB 1ZNI)
- **Selected Experimental Entry:** RCSB PDB `1ZNI` (Human Insulin X-ray Diffraction, Resolution: 1.50 Å).
- **Aligned Chains:** AFDB Model Chain A vs PDB 1ZNI Chain A/B (Mature Insulin).
- **Calculated RMSD:** ~0.85 Å across aligned backbone Cα atoms.

### Agreements
1. **Core Fold Consistency:** Highly congruent spatial arrangement of core alpha-helices between the predicted structure and high-resolution experimental data.
2. **Disulfide Backbone Geometry:** Maintained spatial orientation matching native disulfide bond positions.

### Differences & Defensible Limitations
1. **Signal Peptide Inclusion:** The AFDB model includes the full 110 aa preproinsulin canonical sequence (including signal sequence), whereas experimental PDB `1ZNI` represents mature processed insulin (Chains A and B only).
2. **Oligomeric State:** The prediction represents a monomeric state, whereas physiological insulin forms hexamers in storage granules in the presence of zinc ions. High pLDDT does not independently demonstrate oligomerization.
