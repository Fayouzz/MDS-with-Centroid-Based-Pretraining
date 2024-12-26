# Data Directory

This folder contains all datasets and intermediate files required for the project. Below is a description of each subdirectory and its purpose.

---

## 📁 Subdirectories

### 1. `raw/`
This folder contains the raw, unprocessed datasets. These datasets are required as input for the preprocessing scripts.

**Files:**
- `documents.json`: Multi-document clusters in JSON format.
- `summaries.json`: Human-written reference summaries in JSON format.


---

### 2. `processed/`
This folder contains preprocessed data ready to be used for training and evaluation.

**Files:**
- `processed_documents.pkl`: Preprocessed document clusters (tokenized and cleaned).
- `processed_summaries.pkl`: Preprocessed summaries.

**Instructions:**
- Run the preprocessing script to generate these files:
  ```bash
  python src/preprocessing.py

---
### 3. `centroids/`
This folder contains centroids generated during the pretraining phase.
