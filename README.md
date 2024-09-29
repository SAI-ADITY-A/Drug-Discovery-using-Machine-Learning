# Title: Drug Discovery Targeting Tyrosine Kinase (EGFR) for Lung Cancer
This project aims to develop novel drug candidates targeting the Epidermal Growth Factor Receptor (EGFR), a key player in the pathogenesis of lung cancer. Utilizing machine learning techniques, we analyze bioactivity data to identify potent inhibitors of EGFR, ultimately accelerating the drug discovery process.

## Objectives:
To predict the inhibitory potency (pIC50) of potential drug candidates against EGFR.
To analyze molecular descriptors using machine learning models for efficient lead compound identification.
To validate the predicted results through experimental methods.
## Project Workflow
### Target Identification:

Selection of Tyrosine Kinase (EGFR) as the therapeutic target based on its role in lung cancer.
### Data Collection:

Gathering bioactivity data (IC50/pIC50 values) from sources like ChEMBL.
Collecting relevant molecular descriptors using tools such as Lipinski and PaDEL.
### Data Preprocessing:

Cleaning and filtering the data for accuracy.
Selecting significant features from molecular descriptors.
### Exploratory Data Analysis (EDA):

Performing visualizations to explore data distributions and correlations.
Generating hypotheses about structural properties affecting drug activity.
### Model Development:

Implementing machine learning models (e.g., LazyPredict, LazyRegressor) for pIC50 prediction.
Splitting data into training and validation sets to ensure model robustness.
### Model Evaluation:

Assessing model performance using metrics like RMSE, MAE, or R².
Analyzing feature importance to guide further drug design.
### Lead Compound Identification:

Selecting lead compounds with promising pIC50 values for experimental testing.
Optimizing chemical structures based on model insights.
