# Predicting Mortality in Sepsis Patients with Machine Learning

## Team Information
- **Team ID**: Team 2
- **Team Member**: Mohammad Tamim

## Project Overview
This project aims to predict the 30-day mortality rate of sepsis patients in ICU settings using the XGBoost algorithm. Leveraging the MIMIC-III database, this study builds upon the work of Hou et al. (2020) and extends it by comparing XGBoost's performance with Logistic Regression and Random Forest models. Our goal is to improve prognostic tools for sepsis patients, enhancing early intervention and patient care.

## Background
Sepsis remains a significant challenge in healthcare due to its high mortality rates in ICUs. Despite advancements, existing clinical scoring systems and analyses fall short in accurately predicting mortality. This project explores machine learning algorithms as a solution to these limitations, focusing on their potential to enhance prognostic accuracy.

## Data Source
The dataset is derived from the MIMIC-III V1.4 database, encompassing de-identified data of patients admitted to ICUs at Beth Israel Deaconess Medical Center from 2001 to 2012. The study utilizes a subset of this data, following IRB approval, to ensure ethical compliance and data privacy.

## Supplemental Data Information
the raw data used in the study is also publicly available in the supplemental information of the 'Predicting 30-days mortality for MIMIC-III patients with sepsis-3: a machine learning approach using XGboost' paper. The data in the supplemental information can be found at:
[Translational Medicine Article Supplemental Information](https://translational-medicine.biomedcentral.com/articles/10.1186/s12967-020-02620-5#Sec14)

## Methodology
The project methodology includes:
- **Data Preprocessing**: Handling missing values, feature selection based on the original study, and data normalization.
- **Model Development and Training**: Implementation and training of XGBoost, Logistic Regression, and Random Forest models using a train-test split of 70/30.
- **Evaluation**: Comprehensive model assessment using metrics such as AUC, accuracy, precision, recall, F1-Score, and confusion matrices.

## Models and Performance
- **XGBoost**: Demonstrated superior performance with the highest AUC, accuracy, and F1-Score among the models tested.
- **Logistic Regression and Random Forest**: Showcased competitive performance, underscoring the potential of machine learning in clinical settings.

## Repository Structure
- `notebook/DL4H_Team_2_Jupyter_Notebook_template.ipynb`: Main project notebook detailing the workflow from data preprocessing to model evaluation.
- `models/`: Contains trained models (XGBoost, Logistic Regression, Random Forest) for reproducibility.
- `data/`: Directory for processed datasets (note: The data in the supplemental information of the paper can be found at: https://translational-medicine.biomedcentral.com/articles/10.1186/s12967-020-02620-5#Sec14).

## Usage
1. Clone the repository to your local machine or Google Colab environment.
2. Install required Python packages: `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`, `xgboost`, `pickle`.
3. Run the Jupyter Notebook to replicate the experiment or utilize the pre-trained models for evaluation.

## Future Work
- In the next phase of our project, we will focus on completing the final report and video presentation.
- Integration of the project with the PyHealth library for broader application in healthcare analytics.

## Contributions to PyHealth
Plans include contributing datasets, tasks, and machine learning models developed during this project to the PyHealth repository, promoting open-source collaboration in healthcare analytics.

## References
- Hou, N., Li, M., Hé, L., Xie, B., Wang, L., Zhang, R., Yan, Y., Sun, X., Pan, Z., & Wang, K. (2020, December 1). Predicting 30-days mortality for MIMIC-III patients with sepsis-3: a machine learning approach using XGboost. Journal of Translational Medicine.
