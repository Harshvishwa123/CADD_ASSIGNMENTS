# 🧬 CADD Assignments – Protein Modeling and Drug Docking

## 📁 Repository Overview

This repository contains the complete submissions for two major assignments in CADD, focused on protein modeling and structure-based drug design. It includes detailed reports, model files, docking results, and visualizations.

---

## 📄 Assignment 1: Homology Modeling & Structural Analysis

### 🧪 Objectives:
- Identify a suitable template for a given wild-type protein sequence using BLAST.
- Generate homology models for the wild-type and three mutant variants.
- Visualize and analyze structural changes using Chimera.
- Compare models using DOPE score and RMSD metrics.
- Investigate biological significance of mutations via literature review.

### 🔬 Mutations Studied:
- **P227A**
- **I208V**
- **T112M**

### 🧠 Key Insights:
- **Wild-type** showed the best structural stability (lowest DOPE score).
- **T112M** mutation led to the most significant structural deviation.
- Literature supported the impact of mutations on immune-related pathways.

### 🛠 Tools Used:
- **BLAST**
- **MODELLER**
- **UCSF Chimera**
- **DOPE Score Analysis**
- **RMSD Alignment**

📄 See `CADD ASSIGNMENT 1 REPORT.pdf` for full details.

---

## 📄 Assignment 2: Drug Docking and Binding Affinity Analysis

### 🧪 Objectives:
- Perform literature review to identify small molecules targeting CD40/CD40L.
- Prepare protein models (wild-type + mutants) and ligand files.
- Perform molecular docking using AutoDock Vina.
- Compare binding affinities across protein-drug combinations.
- Visualize docked poses and interpret binding mechanisms.

### 💊 Drugs Docked:
1. Statins (e.g., Atorvastatin)
2. DRI-C21045
3. DRI-C21041
4. Compound 6877002
5. TAS-119

### 📈 Key Findings:
- **Drug3** and **Drug4** showed strongest binding across all protein forms.
- Mutations (especially M1 and M3) enhanced binding for several compounds.
- Binding pocket alterations contributed to affinity differences.

### 🛠 Tools Used:
- **Open Babel**
- **CASTp**
- **AutoDock Vina**
- **PyMOL/Chimera for visualization**
- **Bar graph for binding energy comparison**

📄 See `CADD ASSIGNMENT -2.pdf` for full details.

---

## 📚 References

- [PMC: CD40 mutation studies](https://pmc.ncbi.nlm.nih.gov/articles/PMC60102/)
- [ACS Med Chem: DRI inhibitors](https://pubs.acs.org/doi/full/10.1021/acs.jmedchem.7b01154)
- [CASTp: Active site prediction](http://sts.bioe.uic.edu/castp/)
- [MODELLER](https://salilab.org/modeller/)
- [AutoDock Vina](http://vina.scripps.edu/)

