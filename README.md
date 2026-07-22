# portal_peptide_exploration
Exploratory analysis of peptide LC retention times, investigating the drivers of retention behaviour

## Background
Data from https://www.kaggle.com/competitions/peptide-lc-retention-time-prediction/overview

Inital exploration of data and feature engineering is done in 01_exploration.ipynb and modelling is done in 02_modelling.ipynb

## Reproducing the analysis 
**1. Clone the repo**
```bash
git clone https://github.com/Ben-J-Whitehead/portal_peptide_exploration.git
cd portal_peptide_exploration
```

**2. Create and activate conda environment**
```bash
conda create -n peptide-rt python=3.11
conda activate peptide-rt
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

