# EXPLORATION-OF-CATIONS-FOR-VBH-MODEL-SYSTEM-ML
# Motivation
 As renewable energy gains momentum, efficient energy storage becomes critical for grid stability. Non-aqueous Redox Flow Batteries (NRFBs) offer promising solutions due to their wider temperature range and higher energy density. The solubility of active materials is crucial for NRFB energy density. To expedite material discovery, this project leverages computation and machine learning.

# Methods Overview
 The model system is alkylammonium vanadium bis-hydroxyiminodiacetate, and acetonitrile serves as the solvent. A surrogate model trained on 119 molecules predicts the solubility of 150 quaternary ammonium cations. Dependencies include Scikit-learn, RDKit, NumPy, Matplotlib, and Pandas.

# Training Models
Regression models, including Linear Regression, ExtraTrees Regressor, Random Forest, XGBoost, Cat Boost, and Adaptive Boost, were employed. Feature selection involved correlation analysis, and dataset split used an 80-20 train-test split.

# Evaluation and Results
 Models were evaluated using R-2 and RMSE metrics, with cross plots providing visual insights. Feature importance was ranked for tree-based models. Results showed diverse model performance, with ensemble methods outperforming linear regression.

# Predicting Solubility for New Cation Molecules
 A dataset of 500 quaternary ammonium cation molecules from the CHEMBL database was used. Predictions for 150 molecules were generated using the trained models.

Dependencies
Scikit-learn: Scikit-learn
RDKit: RDKit
NumPy: NumPy
Matplotlib: Matplotlib
Pandas: Pandas

# How to Use
Install dependencies: pip install -r requirements.txt
Run Jupyter notebooks for model training and prediction.
Explore model predictions for new cation molecules.
For detailed documentation, refer to the notebooks and dataset descriptions.