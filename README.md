# CINV Prediction Model for Gynecological Oncology Patients

## Introduction

This project focuses on the development of a predictive model for chemotherapy-induced nausea and vomiting (CINV) in patients with gynecological cancers. CINV is a common and distressing side effect that impacts patient quality of life and treatment adherence. While antiemetic guidelines help mitigate CINV, individual patient responses vary widely, influenced by numerous patient-related factors. This study aims to create a CINV risk model that incorporates these patient-specific factors, ultimately assisting clinicians in selecting personalized antiemetic prophylaxis strategies. The model is based on data from a multicenter, observational study with machine learning and statistical modeling techniques used to identify key predictive factors.

## Objective

The primary objective of this project is to develop a predictive model for CINV risk in gynecological cancer patients, leveraging both clinical and patient-reported factors to identify high-risk individuals. This model is intended to guide clinicians in selecting tailored antiemetic treatments, thereby improving patient outcomes and quality of life during chemotherapy.

## Project Structure

- **`data_output/`**: Contains the dataset used in the analysis.
- **`scr/`**: Python and Jupyter notebooks for data exploration, preprocessing, modeling, and results preparation.
- **`Output/`**: Stores the trained models, graphs, and associated output files.

## Scripts

1. **EMRISK_Prediction.ipynb**: This notebook provides a comprehensive analysis of patient-related CINV risk factors, including data exploration, preprocessing, feature selection, and model development using machine learning techniques such as XGBoost and logistic regression.

## Acknowledgements

This project is supported by the North-Eastern German Society of Gynecological Oncology (NOGGO) and participating clinical centers. We thank all patients, clinicians, and research staff involved in data collection and analysis. Special thanks to collaborators for their input on study design and project development.

## Getting Started

1. **Clone this repository:**

   ```bash
   git clone https://github.com/sschepanski/CINV_PredictiveModel_GynOnc.git
   ```

2. **Set up your enviornment using the provided requirement file:**
   ```bash
   pyenv local 3.11.3
   python -m venv .venv
   source .venv/bin/activate
   pip install --upgrade pip
   pip install -r requirements.txt
   ```

3. **Run the provided notebooks in the `scr/` directory for data preprocessing, model training, and evaluation.**

## **Contributions**

This analysis was conducted by Dr. Steven Schepanski and collaborators, contributing to a better understanding of CINV risks in gynecological cancer patients. The predictive model developed here is intended for use in clinical settings to optimize CINV management.

## **License**

This project is licensed under the MIT License.