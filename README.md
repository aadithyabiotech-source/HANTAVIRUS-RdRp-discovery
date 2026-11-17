# AI-Guided HTNV L-Protein Inhibitor Discovery

This repository contains the computational workflow, datasets, scripts, and results for an AI-guided drug-discovery project focused on the identification and optimization of Hantaan virus (HTNV) L-protein/RNA-dependent RNA polymerase inhibitor candidates.

## Project Title

**Drug Repurposing, Lead Optimization, and Cytoskeleton-Directed Target Exploration**

## Overview

Hantaviruses are zoonotic negative-sense RNA viruses associated with severe diseases such as hemorrhagic fever with renal syndrome and hantavirus pulmonary syndrome. Despite their clinical importance, no licensed virus-specific antiviral therapy is currently available for Hantaan virus infection.

This project uses an integrated computational workflow combining:

- FDA-approved drug repurposing
- Molecular docking
- Molecular dynamics simulation
- ADMET prediction
- Pharmacophore modeling
- Explainable AI
- Generative AI
- Scaffold hopping
- Cytoskeleton-directed target exploration

## Targets

| Target | PDB ID | Purpose |
|---|---|---|
| HTNV L-protein/RdRp | 8C4T | Primary antiviral target |
| Tubulin–colchicine complex | 1SA0 | Exploratory cytoskeleton target |

## Workflow

1. Literature survey and target selection  
2. Protein preparation  
3. Ligand preparation  
4. Molecular docking  
5. Docking validation  
6. Lead identification  
7. Generative analogue design  
8. Candidate prioritization  
9. Scaffold hopping  
10. Dual-target docking  
11. Target-profile classification  
12. Molecular dynamics simulation  
13. ADMET and drug-likeness analysis  

## Key Outcomes

- Baloxavir was identified as a promising HTNV-focused lead scaffold.
- Approximately 600 baloxavir-inspired analogues were generated.
- Gen-2_Trifluoromethyl was selected as an optimized lead candidate.
- Twenty true scaffold-hopped candidates were generated across ten scaffold classes.
- Scaffold-hopped candidates were evaluated against HTNV 8C4T and tubulin 1SA0.
- Analog_10B_Biphenyl, Analog_7A_Coumarin, and Analog_7B_Coumarin showed predicted dual-target profiles.
- Analog_3B_Quinoline and Analog_2A_Indole showed HTNV-retained profiles.

## Tools Used

- Python
- RDKit
- Open Babel
- AutoDock Vina
- MGLTools
- REINVENT
- SELFIES
- SMIRKS
- SHAP
- GNNExplainer
- GROMACS
- Google Colab
- PyMOL
- Discovery Studio / PLIP

## Repository Structure

```text
AI-Guided-HTNV-L-Protein-Inhibitor-Discovery/
│
├── README.md
├── workflow/
├── code/
├── data/
├── docking/
├── scaffold_hopping/
├── results/
└── figures/
```

## Important Note

All findings are computational and hypothesis-generating. They do not confirm antiviral, cytotoxic, or dual-target biological activity. Experimental validation is required.

## License

This project is licensed under the MIT License.
