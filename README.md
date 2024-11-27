# Diabetes Readmission Prediction

## Team Members
- Abhitosh
- Amit Nitin Joshi
- Naik Raghavendra Narottam
- Vignesh S
## Problem Statement
Patients,  discharged from the hospital, often face numerous challenges that can lead to unplanned readmissions, significantly impacting their health, well-being, and overall quality of life. This readmission issue is compounded by the growing volume of patients with chronic conditions, making it essential for healthcare organizations to implement effective strategies for identifying high-risk patients.​
In the healthcare space, Addressing this problem ultimately leads to a healthier population and a more sustainable healthcare system.
## Dataset
The original dataset can be downloaded from [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008).
The dataset contains 100k rows of patient's hospitalization data, with a total of 50 features. The dataset is in CSV format.
## Project Structure
- `Dataset/raw`: Contains the dataset files
    - [`diabetic_data.csv`](./Dataset/raw/diabetic_data.csv): Main dataset
    - [`IDs_mapping.csv`](./Dataset/raw/IDS_mapping.csv): Mapping file for IDs
    - [`description.pdf`](./Dataset/raw/description.pdf): Document that describes the dataset
- `Code/`: Jupyter notebooks
    - [`01-data-collection.ipynb`](./Code/01-data-collection.ipynb)
    - [`02-data-preprocessing.ipynb`](./Code/02-data-preprocessing.ipynb)
    - [`03-eda-univariate.ipynb`](./Code/03-eda-univariate.ipynb)
    - [`04-eda-bivariate.ipynb`](./Code/04-eda-bivariate.ipynb)
    - [`05-eda-multivariate.ipynb`](./Code/05-eda-multivariate.ipynb)
    - [`06-eda-summary.ipynb`](./Code/06-eda-summary.ipynb)
    - [`071-model-training.ipynb`](./Code/071-model-training.ipynb) - Ada Boost, XGB, LGBM
    - [`072-model-training.ipynb`](./Code/072-model-training.ipynb) - Logistic Regression
    - [`073-model-training.ipynb`](./Code/073-model-training.ipynb) - Random Forest
    - [`074-model-training.ipynb`](./Code/074-model-training.ipynb) - Summary
  Please execute the notebooks in the order specified. 

## Key Features
- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering
- Visualization of readmission patterns
- Predictive modeling (details to be added)

## Requirements
- Requires Python 3.12 or higher
- List of requirements can be found [here](requirements.txt).

## Setup and Installation
1. Clone this repository 
2. Install required packages: `pip install -r requirements.txt`
3. Run Jupyter notebooks in the `Code/` directory

## License
MIT License
