License: Creative Commons Attribution–NonCommercial 4.0 International (CC BY-NC 4.0).  
Commercial use is not permitted without explicit authorization.

---

# IRIS / MIRCF Evidence Repository

This repository contains the executable empirical evidence supporting the paper:

**IRIS — A Stability-First Mathematical Architecture for Self-Regulating Intelligence**

The artifact accompanies the theoretical and experimental results reported in Sections 4–6 of the manuscript and is provided to support transparency, inspection, and reproducibility of the reported findings.

---

## Repository Contents

- **IRIS_MIRCF_Evidence.ipynb**  
  A single, self-contained Jupyter notebook that implements all simulations, ablation studies, and diagnostic metrics used in the experimental evaluation.  
  Running the notebook reproduces the figures and summary statistics reported in the paper.

- **CITATION.cff**  
  Citation metadata for scholarly reference.

- **LICENSE**  
  Licensing terms governing reuse of this artifact.

- **IRIS_MIRCF_Appendix_Reference.pdf** (optional)  
  Supplementary mathematical reference material corresponding to Appendix A of the paper.

---

## Reproducibility

The notebook is designed to be executed top-to-bottom in a standard Python scientific environment.  
No external datasets are required.

All results are generated through controlled simulation using fixed experimental configurations and multiple random seeds, as described in the manuscript.

---

## Scope and Intended Use

This repository provides an **evidence artifact**, not a production-ready software framework.

Specifically:
- The code is intended to validate structural properties such as stability, coherence, sustainability, and diagnosability.
- No task-level optimization, benchmark performance, or semantic correctness claims are made.
- The implementation serves as a reference realization of the IRIS / MIRCF framework described in the paper.

---

## Relationship to the Paper

The notebook corresponds directly to:
- Section 4: Research Methodology  
- Section 5: Experiments  
- Section 6: Results and Discussion  

Formal mathematical definitions are provided in the paper and its appendices; the notebook operationalizes these definitions for empirical evaluation.

---

## Citation

If you use or reference this artifact, please cite the accompanying paper as specified in `CITATION.cff`.

---

## Disclaimer

The author provide this artifact to support scientific transparency and reproducibility.

The framework regulates the *dynamics* of reasoning processes and does not guarantee task correctness, safety, or alignment beyond what is explicitly discussed in the manuscript.

---

---

## ▶️ How to Run

### 1. Open the notebook
Open `IRIS_MIRCF_Evidence.ipynb` in **Jupyter Notebook** or **JupyterLab**.

### 2. Execute all cells
Run the notebook **from top to bottom** without modification.

No additional configuration, downloads, or external datasets are required.

All figures, tables, and diagnostic outputs referenced in the manuscript are generated automatically during execution.

---

## Reproducibility Statement

- All experiments are deterministic up to explicitly controlled random seeds.
- The notebook executes on standard consumer-grade hardware (CPU-only).
- No internet access is required.
- No external libraries beyond the standard scientific Python stack are used.
- All figures, tables, and summary statistics are regenerated at runtime.

This artifact is designed to satisfy common reproducibility and artifact-evaluation criteria used by ACM, IEEE, Springer, and Elsevier venues.

---

## How to Review (Editor & Reviewer Note)

**To reproduce all empirical results reported in the paper, run `IRIS_MIRCF_Evidence.ipynb` from top to bottom.**

The notebook produces:
- All figures referenced in Sections 5 and 6,
- All steady-state statistics and confidence intervals,
- All ablation and failure-mode demonstrations, and
- Empirical validation corresponding to Appendix A definitions.

No manual intervention or parameter tuning is required.

---

## Citation

If you use or reference this artifact, please cite the accompanying paper as specified in `CITATION.cff`.

**Siddarth Laxminarayanan**  
*IRIS — A Stability-First Mathematical Architecture for Self-Regulating Intelligence*, 2026.  
Reproducibility and Evidence Artifact.

Machine-readable citation metadata is provided in `CITATION.cff` (GitHub / Zenodo compatible).

---

## Scope and Limitations

This artifact validates the **structural and dynamical properties** of the IRIS / MIRCF framework, including:
- Recursive stability,
- Long-horizon sustainability,
- Distributed coherence, and
- Intrinsic diagnosability.

It does **not**:
- Optimize task performance,
- Provide semantic correctness guarantees,
- Replace learning algorithms, or
- Serve as a production-grade AI system.

The implementation is intended as a **reference realization** of the mathematical framework described in the paper.

---

## Contact

For questions related to reproducibility or artifact review, please use the GitHub issue tracker.

Author contact (for editorial correspondence only):  
**Siddarth Laxminarayanan** — l.siddarth@outlook.com

---

## Repository Structure (Single Source of Truth)

```text
IRIS_MIRCF/
├── IRIS_MIRCF_Evidence.ipynb   # Complete empirical evidence:
│                               # • Section 4 — Research Methodology
│                               # • Section 5 — Experiments
│                               # • Section 6 — Results & Discussion
│                               # • All figures (fixed numbering)
│                               # • All tables and confidence intervals
│                               # • Appendix A empirical validation
│
├── CITATION.cff                # Machine-readable citation metadata
│                               # (GitHub / Zenodo compatible)
│
├── LICENSE                     # License terms
│
├── README.md                   # Reproducibility and reviewer guidance
│
└── IRIS_MIRCF_Appendix_Reference.pdf (optional)
                                # Mathematical reference corresponding
                                # to Appendix A of the paper

No external scripts, datasets, configuration files, or preprocessing steps are required.
