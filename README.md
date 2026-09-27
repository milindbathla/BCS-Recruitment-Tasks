# BCS Secretary Recruitment Tasks

Submissions for the Brain and Cognitive Society (BCS) Secretary Recruitment at IIT Kanpur. The recruitment involved two independent open-ended tasks, each requiring the implementation of a complete project.

## Tasks

### Task 1 — NeuroDecoder

An EEG-based cognitive load classification project. The notebook processes multi-channel EEG recordings from the STEW dataset, applies signal filtering and feature extraction, and builds machine learning models to distinguish low and high cognitive workload states.

### Task 2 — The Ledger of Shadows

A fraud detection and anomaly classification project. The notebook analyzes transaction data, explores class imbalance, applies SMOTE for resampling, compares Logistic Regression, Random Forest, and XGBoost models, and optimizes classification thresholds for detecting fraudulent transactions.

## Repository Structure

| File / Folder | Description |
| --- | --- |
| `Milind_NeuroDecoder/` | EEG cognitive workload prediction pipeline and dataset |
| `Milind_TheLedgerOfShadows/` | Fraud detection workflow with imbalance handling and model comparison |
| `README.md` | Project overview and task summary |

### Included notebooks

- `Milind_NeuroDecoder/Code.ipynb` — EEG analysis and classification notebook
- `Milind_NeuroDecoder/STEW Dataset/` — dataset files for the cognitive workload task
- `Milind_TheLedgerOfShadows/Code.ipynb` — transaction fraud detection notebook

## Requirements

Dependencies vary by task, but the general setup is:

- Python 3.8+
- NumPy, pandas, Matplotlib, Seaborn
- SciPy
- scikit-learn
- imbalanced-learn (SMOTE)
- XGBoost
- MNE (EEG processing)

## Context

These tasks were submitted as part of the BCS Secretary Recruitment process at IIT Kanpur.