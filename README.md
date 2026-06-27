# CAFA6 Protein Function Prediction

Protein function prediction experiments for CAFA6.

## Overview

This repository organizes CAFA6 experiments into GitHub-safe scripts, notebooks, reference files, and ignored local data artifacts. It separates raw data, embeddings, derived outputs, and results to keep the public repository clean.

## Folder Structure

```text
.
|-- scripts/
|   |-- analysis/
|   |-- data_prep/
|   |-- evaluation/
|   |-- experimental/
|   |-- pipeline/
|   |-- qa/
|   `-- training/
|-- notebooks/
|-- data/
|   |-- reference/
|   |-- raw/
|   |-- embeddings/
|   |-- derived/
|   `-- metadata/
|-- results/
`-- artifacts/
```

## Methods

- protein embeddings such as ESM/ProtBERT-style representations
- Gene Ontology graph/reference features
- scikit-learn/XGBoost models
- stacking and validation pipelines
- prediction and evaluation scripts

## Install

```bash
pip install -r requirements.txt
```

## Public Sharing Notes

Include scripts, notebooks, `data/reference`, README, and requirements. Exclude raw data, embeddings, derived outputs, results, temporary DBs, and generated artifacts.
