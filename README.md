# 🧬 Single-Cell Transcriptomic Profiling of NSCLC and COPD-Associated NSCLC Reveals Immune and Stromal Remodeling

This repository contains the complete workflow, methods, and final thesis PDF from my MSc Bioinformatics project:

**"Single-Cell Transcriptomic Profiling of NSCLC and COPD-Associated NSCLC Reveals Immune and Stromal Remodeling"**

📄 [`NSCLC_COPD_scRNAseq_Thesis_FaizaFathin.pdf`](./NSCLC_COPD_scRNAseq_Thesis_FaizaFathin.pdf)

---

## 🧪 Abstract

Chronic obstructive pulmonary disease (COPD) is a major comorbidity in non-small cell lung cancer (NSCLC), yet its role in reshaping the tumor microenvironment (TME) is underexplored.  
This study uses **single-cell RNA sequencing (scRNA-seq)** to analyze ~11,000 tumor cells from NSCLC and COPD-associated NSCLC samples. The results reveal immune cell dysregulation, stromal remodeling, and checkpoint pathway activation, with therapeutic implications.

---

## 🔬 Key Methods

| Technique | Tool Used |
|-----------|-----------|
| Data Acquisition | NCBI SRA (BioProject ID: PRJNA1186843) |
| Single-cell Processing | `Seurat`, `NormalizeData`, `FindClusters`, `UMAP` |
| DEG Analysis | `FindMarkers`, Wilcoxon test |
| Pathway Enrichment | `clusterProfiler`, GO & KEGG |
| Visualization | UMAP, violin plots, dot plots, volcano plots |

---

## 🌟 Highlights

- COPD-NSCLC samples show **higher infiltration** of inflammatory macrophages
- Upregulation of immune checkpoints: **PDCD1**, **CTLA4**, **LAG3**
- Enriched signaling in **NF-κB**, **IL-1**, and **neutrophil chemotaxis**
- Novel insight into **immune exhaustion** in COPD-related NSCLC microenvironments

---

## 📚 Contents

| Section | Description |
|---------|-------------|
| Introduction | Background on NSCLC, COPD, and immune-stromal interplay |
| Methods | Detailed scRNA-seq workflow using Seurat |
| Results | DEG analysis, pathway insights, visual plots |
| Discussion | Interpretation, immunological impact of COPD in NSCLC |
| Conclusion | Therapeutic implications and future directions |

---

## 🎯 Ideal For

- MSc/Bioinformatics students working on cancer genomics or scRNA-seq
- Researchers studying tumor immunology, TME, or inflammation-driven cancer
- Computational biologists exploring COPD or lung cancer biology

---

## 📊 Key Results

- COPD-NSCLC tumors showed:
  - Increased exhausted T cells & inflammatory macrophages
  - Strong activation of immune-suppressive pathways
  - ECM remodeling & neutrophil-related chemotaxis pathways
- Proposed checkpoint inhibitors and anti-inflammatory pathways as potential drug targets

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `NSCLC_COPD_scRNAseq_Thesis_FaizaFathin.pdf` | 📄 Full thesis PDF |
| `README.md` | 📘 Project summary & highlights (this file) |

> 📝 *PDF is shown first because it is the complete, official thesis document. The README is a summary for GitHub visitors.*

---

## 📫 Contact

- 👩‍💻 **Author**: Faiza Fathin  
- 📧 **Email**: faizafathin161102@gmail.com  
- 🌐 **[GitHub](https://github.com/faizafathin)**

---

_“Uncovering immune and stromal remodeling in COPD-associated NSCLC using single-cell transcriptomics.”_
