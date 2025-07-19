# 🧬 TCGA RNA-Seq Analysis Workflow (Mock Project)

![Python](https://img.shields.io/badge/Built%20With-Python-blue?style=flat&logo=python)
![Project Status](https://img.shields.io/badge/Status-Demo%20Project-success?style=flat)

---

## 🔎 Overview

This mock project demonstrates a simulated workflow for analyzing RNA-seq data from ~1,000 TCGA samples. It emulates key bioinformatics steps involved in transcriptome analysis, including:

- Read alignment with STAR
- File processing using SAMtools
- Mutation profiling (mock)
- Differential gene expression using DESeq2 (simulated)
- Visualization with volcano plots and heatmaps

This is a portfolio-ready Python project that showcases a typical NGS RNA-seq pipeline using realistic structure and outputs.

---

## ✨ Features

- 🧬 Workflow structure that mimics real TCGA-scale RNA-seq analysis
- 🧪 Simulated results for mutation profiles and DEGs
- 📈 Pre-generated plots (volcano plot and heatmap)
- 🐍 Python script that ties it all together
- 📂 Clean folder structure and mock input data

---

## ▶️ How to Run

```bash
git clone https://github.com/yourusername/tcga-rnaseq-analysis.git
cd tcga-rnaseq-analysis
pip install -r requirements.txt
python rnaseq_pipeline.py
```

---

## 📁 Output Files

- `results/deseq2_results.tsv`: Simulated differential expression results
- `results/mutations.txt`: Mock mutation list
- `output/plots/volcano_plot.png`: Pre-rendered volcano plot
- `output/plots/heatmap.png`: Pre-rendered gene expression heatmap

---

## 📂 Project Structure

```
tcga-rnaseq-analysis/
├── data/                     # Simulated raw FASTQ and metadata
├── output/plots/             # Volcano plot & heatmap
├── results/                  # Simulated result files
├── rnaseq_pipeline.py        # Main script
├── requirements.txt
└── README.md
```

---

## 📌 Notes

This project uses fake input/output to simulate an RNA-seq analysis pipeline for demonstration. No real TCGA data or processing was done.

---

## 👩‍💻 Author

Dhanyashri A/P Guruparan  
Bioinformatics & Data Science Enthusiast
