# Multi-Document Summarization with Centroid-Based Pretraining

This project implements the methodology described in the paper [Multi-Document Summarization with Centroid-Based Pretraining](https://aclanthology.org/2023.acl-short.13.pdf). It focuses on improving multi-document summarization by pretraining models using centroid-based objectives and fine-tuning them for summarization tasks.

## 🚀 Features
- **Centroid-Based Pretraining**: Generates pseudo-label summaries from document clusters.
- **Fine-Tuning**: Adapts pretrained models to generate human-like summaries.
- **Evaluation**: Measures performance using ROUGE and other metrics.
- Modular code for reproducibility and experimentation.

## 📁 Repository Structure
```plaintext
├── data/                  # Datasets (raw, processed, centroids)
├── notebooks/             # Jupyter notebooks for exploratory work
├── src/                   # Modular Python scripts for implementation
├── experiments/           # Experiment configurations and logs
├── models/                # Saved models (pretrained and fine-tuned)
├── results/               # Evaluation results, logs, and generated summaries
├── docs/                  # Documentation (methodology, architecture, results)
├── images/                # Visualizations and example outputs
├── README.md              # Project overview and instructions
├── LICENSE                # License for the project
├── .gitignore             # Files and directories to be ignored by Git
└── requirements.txt       # Python dependencies

## 🛠️ Installation
