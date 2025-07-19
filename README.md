# 🧬 TCGA RNA-Seq Analysis Workflow (Mock Project)

![Python](https://img.shields.io/badge/Built%20With-Python-blue?style=flat&logo=python)
![Project Status](https://img.shields.io/badge/Status-Demo%20Project-success?style=flat)

---

## 🔎 Overview

This project presents a reproducible workflow for large-scale RNA-seq data analysis using ~1,000 samples from The Cancer Genome Atlas (TCGA). The pipeline integrates RNA-seq alignment, mutation profiling, and differential expression analysis to identify significantly dysregulated genes and recurrent mutations in cancer datasets.

#This is a portfolio-ready Python project that showcases a typical NGS RNA-seq pipeline using realistic structure and outputs.

---

## 🧭 Objective

To process and analyze high-throughput RNA-seq data from TCGA to uncover differentially expressed genes and mutational signatures that could inform cancer biology and biomarker discovery.

---

## 🎯 Why This Project?

RNA sequencing (RNA-seq) data holds immense potential for understanding the transcriptomic changes in cancer. With the growing scale of public datasets like TCGA, it becomes crucial to build automated and reproducible pipelines that can efficiently extract meaningful biological insights.

This project simulates a complete NGS pipeline tailored for RNA-seq analysis and downstream interpretation to showcase core bioinformatics skills, such as:
- Workflow integration
- Statistical modeling
- Genomic data visualization

---

## ✨ Features

- 🧬 Workflow structure that mimics real TCGA-scale RNA-seq analysis
- 🧪 Simulated results for mutation profiles and DEGs
- 📈 Pre-generated plots (volcano plot and heatmap)
- 🐍 Python script that ties it all together
- 📂 Clean folder structure and mock input data

---

## 🧬 Data Source

- **Source:** Simulated subset of The Cancer Genome Atlas (TCGA) RNA-seq data.
- **Format:** Expression count matrix, sample metadata, and simplified mutation calls.
- **Note:** Real TCGA data is typically retrieved from [GDC Data Portal](https://portal.gdc.cancer.gov/) using GDC tools or Bioconductor packages like `TCGAbiolinks`.

---

## 🧪 Methods

1. **Preprocessing & Alignment**
   - Simulated STAR alignments and quality control.
   - Handled with `SAMtools` format conventions.

2. **Mutation Profiling**
   - Simulated somatic variant calls.
   - Aggregated and summarized mutations across samples.

3. **Differential Expression Analysis**
   - Expression data normalized using mock DESeq2 logic.
   - Statistical testing for log fold-change and p-value.

4. **Visualization**
   - **Volcano Plot**: Highlights significantly dysregulated genes.
   - **Heatmap**: Displays clustering of expression across conditions.

---

## ▶️ How to Run

```bash
git clone https://github.com/yourusername/tcga-rnaseq-analysis.git
cd tcga-rnaseq-analysis
pip install -r requirements.txt
python rnaseq_pipeline.py
```

---

## 📊 Results

- **1,230** genes identified as significantly dysregulated (FDR < 0.05).
- Key mutated genes extracted from simulated variant calls.
- Visual outputs:
  - 📌 `volcano_plot.png`
  - 📌 `heatmap.png`
  - 📄 `mutation_summary.txt`
  - 📄 `results/deseq2_results.tsv`: Simulated differential expression results


---

## ⚠️ Limitations

- TCGA data here is simulated; real RNA-seq workflows involve significantly more complexity (e.g., GTF parsing, batch effects).
- DESeq2-like statistical modeling is mimicked in Python; actual DESeq2 is best implemented in R/Bioconductor.
- Mutation data is simplified for demonstration; no VCF parsing or variant annotation was performed.

---

## 🚀 Future Directions

- Expand to real TCGA data via GDC API or `TCGAbiolinks`.
- Incorporate functional annotation (e.g., GO/KEGG) for dysregulated genes.
- Integrate survival analysis with expression/mutation features.
- Deploy via Snakemake or Nextflow for scalable reproducibility.

---

## 📌 License

This project is for educational and portfolio use only.
