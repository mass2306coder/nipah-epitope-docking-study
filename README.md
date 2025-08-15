# 🧬 Identifying Epitope-Based Peptide Vaccine Candidates from F and P Proteins of Nipah Virus Using In Silico Methods

## 📌 Project Overview
Nipah virus (NiV) is an emerging zoonotic pathogen with high mortality rates and no approved vaccines. This study uses **immunoinformatics approaches** to identify potential **T-cell and B-cell epitope-based peptide vaccines** targeting the **F (fusion) and P (phosphoprotein) proteins** of NiV.

The workflow integrates **protein sequence retrieval, epitope prediction, antigenicity/allergenicity/toxicity screening, population coverage analysis, 3D modeling, and molecular docking** to propose promising vaccine candidates.

## 🎯 Objectives
- Identify **non-allergenic, non-toxic, antigenic epitopes** from F and P proteins of NiV.
- Model 3D structures of selected epitopes and HLA alleles.
- Validate epitope-HLA interactions through **molecular docking**.
- Evaluate **global population coverage** of the selected epitopes.

## 🛠 Tools & Databases
| Step | Tool / Database | Purpose |
|------|----------------|---------|
| Protein Retrieval | NCBI | Retrieve NiV protein sequences |
| Allergenicity Prediction | AllerTOP v2.0 | Identify non-allergenic proteins |
| Sequence Alignment | Clustal Omega, MEGA5 | Identify conserved regions |
| Antigenicity Prediction | VaxiJen v2.0 | Predict antigenic peptides |
| T-cell Epitope Prediction | NetMHCII 2.3, IEDB | Predict MHC Class I epitopes |
| B-cell Epitope Prediction | BepiPred 2.0 | Identify linear B-cell epitopes |
| Toxicity Analysis | ToxinPred | Predict toxicity |
| Population Coverage | IEDB | Assess global epitope coverage |
| 3D Structure Modeling | PEP-FOLD3, AlphaFold | Model peptides & HLA structures |
| Molecular Docking | AutoDock Vina | Dock epitopes to HLA alleles |
| Visualization | PyMOL, Chimera | View docking interactions |

## 📂 Workflow Summary
1. **Protein Retrieval** → Download NiV protein sequences from NCBI.
2. **Allergenicity Filtering** → Remove allergenic proteins using AllerTOP.
3. **Conserved Region Identification** → Perform MSA with Clustal Omega & MEGA5.
4. **Antigenicity Screening** → Select antigenic sequences using VaxiJen.
5. **Epitope Prediction** → Identify T-cell & B-cell epitopes.
6. **Toxicity & Allergenicity Check** → Ensure safety using ToxinPred & AllerTOP.
7. **Population Coverage Analysis** → Evaluate global relevance of epitopes.
8. **3D Structure Modeling** → Model epitopes & HLA-A*31:01.
9. **Molecular Docking** → Assess binding affinity (-6.1 kcal/mol for top epitope).

## 📊 Key Results
- **Top Candidate Epitope (T-cell)**: `SFIIVEKKRNTYSRLE` (F protein)
  - Antigenicity Score: **1.0766**
  - Binding Affinity: **-6.1 kcal/mol** with HLA-A*31:01
  - Population Coverage: **49.7% (Global)**

- **Top B-cell Epitopes**:
  - `KSSIESTNEAVVKLQE` (F protein) – Highest BepiPred score: **0.94**
  - `AVSKEDRETDLVHLEK` (P protein) – Highest antigenicity: **1.1564**

## 📈 Future Work
- Extend analysis to **MHC Class II** epitopes for broader immune coverage.
- Perform **molecular dynamics simulations** for binding stability.
- Validate computational findings via **wet-lab experiments**.

## 👩‍💻 Author
**Masha S**  
📧 [mashasrinivasan23@gmail.com](mailto:mashasrinivasan23@gmail.com) | 🌐 [LinkedIn](https://www.linkedin.com) | 🐙 [GitHub](https://github.com)
