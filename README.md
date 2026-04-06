# Bank Customer Churn Prediction

## Project Overview

This project investigates customer churn in the banking sector, with the goal of identifying high-risk customer segments and supporting data-driven retention strategies through statistical analysis and machine learning.

---

## Project Stages and Repository Content

### Stage 1: Project Design

This stage defines the overall research framework of the project, including:

- Problem definition: customer churn prediction
- Research questions focusing on risk identification and retention prioritization
- Conceptual design of a risk-based and value-based analytical approach

### Stage 2: Literature Review, Data Description, and Approach

This stage establishes the theoretical and methodological foundation of the project:

- Review of existing literature on churn prediction and customer retention
- Description of the dataset and key variables
- Explanation of the analytical approach, including:
  - Feature classification (categorical vs numerical)
  - Data preprocessing strategy
  - Modeling approach and evaluation plan

### Stage 3: Initial Results and Code

This stage presents the implementation and initial analytical results:

- Exploratory Data Analysis (EDA) and feature distribution visualization
- Statistical analysis of feature–churn relationships
- Data preprocessing steps:
  - Train–test split (stratified sampling)
  - One-hot encoding for categorical variables
  - Feature scaling using standardization
- Model development for churn prediction
- SHAP analysis for model interpretation
- Risk segmentation based on predicted churn probabilities
- Construction of customer value score and value segmentation
- Segment-level analysis combining risk and value
- Identification of high-priority customer groups for retention strategies

### Stage 4: Final Report

This stage consolidates all previous work into a comprehensive final report:

- Full end-to-end pipeline from data preprocessing to deployment-ready insights
- Comparison of model performance across all trained classifiers
- Final SHAP-based feature importance and model interpretability analysis
- Risk and value segmentation with actionable retention strategy recommendations
- Discussion of limitations and directions for future work

---

## Repository Contents

| File                                                        | Description                                         |
| ----------------------------------------------------------- | --------------------------------------------------- |
| `Milestone_2.ipynb`                                         | Stage 2: data description and methodological setup  |
| `Milestone_3_Initial_Results_and_Code.ipynb`                | Stage 3: data preprocessing, modeling, and analysis |
| `Milestone_3_Initial_Results_and_Code_Report.html`          | Exported report version of Stage 3 results          |
| `CIND820_Bank_Customer_Churn_Prediction_Final_Report.ipynb` | Stage 4: final report consolidating all stages      |
| `customer_churn_modelling.csv`                              | Dataset used for the analysis                       |
| `requirements.txt`                                          | Python package dependencies                         |

---

## Environment Setup

### Prerequisites

- Python 3.12

### Steps

```bash
# 1. Create a virtual environment
python3.12 -m venv churn-env

# 2. Activate the virtual environment
# macOS / Linux
source churn-env/bin/activate

# Windows
churn-env\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch JupyterLab
jupyter lab
```

Once JupyterLab opens, navigate to and open `CIND820_Bank_Customer_Churn_Prediction_Final_Report.ipynb` to run the final report.
