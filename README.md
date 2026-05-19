[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18175665.svg)](https://doi.org/10.5281/zenodo.18175665) 
[![Published in JAMIA Open](https://img.shields.io/badge/Published-JAMIA--Open-green)](https://doi.org/10.1093/jamiaopen/ooaf177)
[![Data DOI](https://img.shields.io/badge/Dataset-Dryad-blue)](https://doi.org/10.5061/dryad.fj6q57482)
[![Python](https://img.shields.io/badge/Code-Python%20%7C%20Stata-yellowgreen)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-lightgrey)](#)

---

# Auditing Shortcut Learning and Misclassification in AI-Based Breast Cancer Genomic Subtyping

## Harvard Medical School (HMS) – PGME  
**Global Clinical Scholars Research Training Program (GCSRT) – 2025 Cohort**  
**Capstone Author:** Julian Borges, MD, MS  

---

## Project Overview

In an era where artificial intelligence (AI) is guiding life-altering cancer treatment decisions, **trust, transparency, and safety** are no longer optional—they are essential.

This capstone audits *shortcut learning* in AI models for breast cancer subtype prediction and identifies which patients are most at risk of **misclassification**, especially in hormone-sensitive tumors.

Using the **TCGA-BRCA** dataset, this project:

- Detects risks from non-genomic “shortcut” features like age and batch ID
- Audits ML classifiers for over-reliance on confounding variables
- Introduces a lightweight, interpretable audit framework for genomic AI

---

## Objectives

1. Train machine learning models to classify PAM50 breast cancer subtypes using RNA-seq data.
2. Use SHAP explainability to identify non-biological bias.
3. Compare canonical SHAP (Python) with low-code pseudo-SHAP (Stata).
4. Explore misclassification patterns across clinical and genomic subgroups.
5. Propose a validation pipeline to flag “at-risk” predictions before deployment.

---

## Methods & Tools

- **Python (XGBoost + SHAP)**
- **Stata (Pseudo-SHAP implementation)**
- **Google Colab** for reproducible notebooks
- **Cleaned TCGA-BRCA dataset**  
- AI-BIAS Audit Protocol

---

## Repository Contents

- `PAM50_SHAP_Colab_Notebook.ipynb` – Main Google Colab notebook  
- `requirements.txt` – Python dependencies  
- `AI-BIAS cleaned_TCGA_PAM50_model_dataset.csv` – Dataset (to upload into Colab)  

---

## Summary

This pipeline provides a **model auditing toolkit** for breast cancer genomic AI:

| Aspect                 | Pseudo-SHAP (Stata) | SHAP (Python)      |
|------------------------|---------------------|--------------------|
| Models supported       | Linear only         | Tree/DL/any        |
| Captures interactions? | No                  | Yes                |
| Uncertainty estimates  | No                  | Yes                |
| Low-code compatible?   | Yes                 | No                 |
| Resource requirements  | Low                 | High               |

The tool compares traditional and low-code explainability models for fairness, transparency, and clinical relevance.

---

## Publication & Archiving

### Peer-reviewed & published:
This project was independently developed and later **evolved through multiple iterations** during peer review. It was formally accepted for publication in:

> **Borges, Julian.** “Auditing Shortcut Learning and Misclassification in AI-Based Breast Cancer Genomic Subtyping.” *JAMIA Open* (2025). [https://doi.org/10.1093/jamiaopen/ooaf177](https://doi.org/10.1093/jamiaopen/ooaf177)

### Dataset Availability:
The full dataset and scripts were archived on **Dryad** for reproducibility:

> Dryad DOI: [https://doi.org/10.5061/dryad.fj6q57482](https://doi.org/10.5061/dryad.fj6q57482)

### Supplemental & Creative Materials:
All additional materials (notebooks, documentation, slides, figures) are hosted on **Zenodo** under CC-BY 4.0:

> Zenodo DOI: [https://doi.org/10.5281/zenodo.18175665](https://doi.org/10.5281/zenodo.18175665)

---

## Citation

Borges, Julian. “Auditing Shortcut Learning and Misclassification in AI-Based Breast Cancer Genomic Subtyping.” *JAMIA Open*. Oxford University Press, 2025. https://doi.org/10.1093/jamiaopen/ooaf177

---

## Author

**Julian Borges, MD, MS**  
Health Informatics Candidate, Boston University  
GCSRT 2025, Harvard Medical School  
📧 jyborges@bu.edu

---

## Keywords

`AI auditing` • `shortcut learning` • `SHAP` • `pseudo-SHAP` • `model transparency` • `cancer genomics` • `clinical decision support` • `TCGA-BRCA` • `fairness in AI` • `low-code interpretability` • `health AI safety`

---

## License

This work is licensed under the [MIT License](LICENSE).  
- Dataset files are published under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) via Dryad  
- Supplemental materials (notebooks, slides, README) are published under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) via Zenodo

---

<div align="center">

**Frontier Translational Research Lab**

Department of Computer Science · Boston University · Harvard Medical School GCSRT Alumni

[![Lab Website](https://img.shields.io/badge/Lab-frontier--lab-002244?style=flat-square)](https://julian-borges-md.github.io/frontier-lab/)
[![BU CS](https://img.shields.io/badge/BU-Computer_Science-cc0000?style=flat-square)](https://www.bu.edu/cs/)
[![HMS](https://img.shields.io/badge/HMS-GCSRT_Alumni-a51c30?style=flat-square)](https://ghsm.hms.harvard.edu/education/global-clinical-scholars-research-training)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0001--9929--3135-a6ce39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0001-9929-3135)
[![CV](https://img.shields.io/badge/Academic_CV-research--profile-4f46e5?style=flat-square)](https://julian-borges-md.github.io/research-profile/)

*Julian Borges, MD, MS · jyborges@bu.edu*

</div>
