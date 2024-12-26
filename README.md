# Multi-Document Summarization with Centroid-Based Pretraining

This project implements the methodology described in the paper [Multi-Document Summarization with Centroid-Based Pretraining](https://aclanthology.org/2023.acl-short.13.pdf). It focuses on improving multi-document summarization by pretraining models using centroid-based objectives and fine-tuning them for summarization tasks.

## 🚀 Features
- **Centroid-Based Pretraining**: Generates pseudo-label summaries from document clusters.
- **Fine-Tuning**: Adapts pretrained models to generate human-like summaries.
- **Evaluation**: Measures performance using ROUGE and other metrics.
- Modular code for reproducibility and experimentation.

## 🛠️ Installation
01. **Clone the repository:**
git clone https://github.com/username/Multi-Document-Summarization.git
cd Multi-Document-Summarization
**02. Install dependencies:** pip install -r requirements.txt
**03. Download and prepare datasets:**
- Place raw datasets in data/raw/.
- Follow instructions in data/README.md for preprocessing.
