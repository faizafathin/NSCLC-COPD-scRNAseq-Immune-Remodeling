# 🧬 Single-Cell Transcriptomic Profiling of NSCLC and COPD-Associated NSCLC Reveals Immune and Stromal Remodeling

This repository contains the complete workflow, methods, and final thesis PDF from my MSc Bioinformatics project:

**"Single-Cell Transcriptomic Profiling of NSCLC and COPD-Associated NSCLC Reveals Immune and Stromal Remodeling"**


---

## 🧪 Abstract

Chronic obstructive pulmonary disease (COPD) is a major comorbidity in non-small cell lung cancer (NSCLC), yet its role in reshaping the tumor microenvironment (TME) is underexplored.  
This study uses **single-cell RNA sequencing (scRNA-seq)** to analyze ~11,000 tumor cells from NSCLC and COPD-associated NSCLC samples. The results reveal immune cell dysregulation, stromal remodeling, and checkpoint pathway activation, with therapeutic implications.

---

## 🔬 Key Methods

- 🔹 **Data Acquisition**: Raw scRNA-seq data from NCBI SRA (BioProject ID: PRJNA1186843)
- 🔹 **Preprocessing & Alignment**: Performed using **Cell Ranger** (10x Genomics)
- 🔹 **Quality Control & Normalization**: Conducted in R using the **Seurat** package
- 🔹 **Dimensionality Reduction & Clustering**: UMAP, PCA, FindClusters
- 🔹 **Differential Expression Analysis**: FindMarkers function with Wilcoxon test
- 🔹 **Pathway Enrichment**: **clusterProfiler** for GO and KEGG enrichment
- 🔹 **Visualization**: UMAP plots, violin plots, volcano plots, dot plots, heatmaps

---

## 🌟 Highlights

- COPD-NSCLC samples show **higher infiltration** of inflammatory macrophages
- Upregulation of immune checkpoints: **PDCD1**, **CTLA4**, **LAG3**
- Enriched signaling in **NF-κB**, **IL-1**, and **neutrophil chemotaxis**
- Novel insight into **immune exhaustion** in COPD-related NSCLC microenvironments

---

## 📂 Contents

- `/data/` – Raw and processed scRNA-seq count matrices  
- `/scripts/` – R scripts for Seurat workflow, clustering, DEG analysis  
- `/enrichment/` – GO & KEGG enrichment results, gene-pathway mappings  
- `/figures/` – UMAPs, heatmaps, dot plots, violin plots, volcano plots  
- `README.md` – 📘 You are here  
- `NSCLC_COPD_scRNAseq_Thesis_FaizaFathin.pdf` – 📄 Full MSc thesis manuscript  


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

- `README.md` — 📘 Project summary & highlights (you are here)
- `NSCLC_COPD_scRNAseq_Thesis_FaizaFathin.pdf` — 📄 Full MSc thesis manuscript


> 📝 *PDF is shown first because it is the complete, official thesis document. The README is a summary for GitHub visitors.*

---

## 📫 Contact

- 👩‍💻 **Author**: Faiza Fathin  
- 📧 **Email**: faizafathin161102@gmail.com  
- 🌐 **[GitHub](https://github.com/faizafathin)**

---

_“Uncovering immune and stromal remodeling in COPD-associated NSCLC using single-cell transcriptomics.”_
