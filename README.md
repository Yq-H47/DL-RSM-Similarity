# DL-RSM-Similarity
Deep Learning for Regionalized Streamflow Modeling

# Advancing Deep Learning for Regionalized Streamflow Modeling: A Comparative Study of Basin Similarity Approaches

## Repository Overview
To facilitate research transparency and reproducibility while respecting original data redistribution policies, this repository provides the necessary Python scripts and processed metadata (basin IDs and cluster labels) to reproduce the similarity-based regionalization and LSTM modeling framework proposed in our study across three continents: North America (CAMELS-US), South America (CAMELS-BR), and Oceania (CAMELS-AUS).

---

## Repository Structure

```text
├── dataprocess.py        # Scripts for data preprocessing, Z-score standardization, and feature extraction
├── P_class.py            # PCA and hierarchical clustering implementation for catchment similarity grouping
├── loss.py               # Custom loss functions and evaluation metrics (including modified NSE*)
├── LSTM_T.py             # LSTM network architecture, model training, and PUB (Prediction in Ungauged Basins) evaluation
├── data/                 # Processed metadata required for reproducibility
│   ├── AUS_basins_clusters.csv  # Selected basin IDs and cluster assignments for Australia
│   ├── BR_basins_clusters.csv   # Selected basin IDs and cluster assignments for Brazil
│   └── US_basins_clusters.csv   # Selected basin IDs and cluster assignments for the United States
└── README.md
