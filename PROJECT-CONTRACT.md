# AnomalyBrand AI — Project Contract

## 1. Project Overview

AnomalyBrand AI is an explainable machine learning system for:

- SDG-aligned brand anomaly detection
- Greenwashing intelligence
- Corporate sustainability fraud analysis
- Supply-chain labour and environmental risk analysis
- Financial-SDG divergence analysis
- SDG trajectory forecasting

The project consists of five integrated modules:

1. M1 — Multi-Dimensional SDG Anomaly Detection Engine
2. M2 — Greenwashing & Claim Inconsistency Classifier
3. M3 — Supply Chain Labour & Environmental Violation Predictor
4. M4 — Financial-SDG Divergence Analyser
5. M5 — SDG Trajectory Forecasting Engine

The final system will provide explainable risk/anomaly results through an API and dashboard.

---

# 2. Team Responsibilities

## Member 1 — Data Engineering + M1

GitHub: `nehaburele08`

Responsibilities:

- Data collection
- Data preprocessing
- Data validation
- SDG feature engineering
- M1 anomaly detection
- Isolation Forest
- DBSCAN
- Autoencoder
- M1 evaluation
- M1 documentation

---

## Member 2 — NLP + M2 + XAI

GitHub: `Vaishalirahate14`

Responsibilities:

- NLP preprocessing
- Claim extraction
- Evidence processing
- BERT pipelines
- Claim-evidence discrepancy detection
- Greenwashing classification
- Greenwashing Severity Index
- SHAP
- LIME
- PDP
- ICE
- Explainability documentation

---

## Member 3 — M3 + M4

GitHub: `Vidhi-2006`

Responsibilities:

### M3
- Supplier graph construction
- Tier-1/2/3 supplier analysis
- Supply-chain risk propagation
- GNN-based analysis
- Environmental signals
- Labour risk analysis

### M4
- Financial data extraction
- SDG-capital mapping
- Stated SDG vector
- Revealed SDG vector
- Financial-SDG divergence
- Cosine divergence analysis

---

## Member 4 — M5 + Backend + Dashboard

Responsibilities:

### M5
- LSTM forecasting
- XGBoost horizon classification
- 3-month forecasting
- 6-month forecasting
- 12-month forecasting

### Backend
- FastAPI
- PostgreSQL
- API integration
- Module integration

### Frontend
- Streamlit dashboard
- Result visualization
- Explainability visualization

---

# 3. Repository Structure

The project uses five repositories:

```text
AnomalyBrand-AI/
│
├── anomalybrand-data-m1
├── anomalybrand-nlp-m2
├── anomalybrand-supply-finance-m3
├── anomalybrand-forecast-api-m5
└── anomalybrand-integration
