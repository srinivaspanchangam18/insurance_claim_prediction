# Insurance Claim Prediction

## Project Overview

This project focuses on predicting insurance claims using machine learning techniques. It demonstrates a structured approach to data preprocessing, feature engineering, handling class imbalance, classification modelling, hyperparameter tuning, and model evaluation.

## Objectives

- Explore and understand insurance-related data.
- Perform data cleaning and preprocessing.
- Apply feature engineering techniques.
- Handle imbalanced data using SMOTE.
- Build and compare classification models.
- Perform hyperparameter tuning.
- Evaluate model performance using appropriate metrics.

## Technologies Used

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Imbalanced Data Handling:** Imbalanced-learn (SMOTE)
- **Development Environment:** Jupyter Notebook

## Project Workflow

1. **Data Loading:** Load the dataset and inspect its structure.
2. **Exploratory Data Analysis:** Examine distributions, missing values, and class balance.
3. **Data Preprocessing:** Clean and prepare the data for modelling.
4. **Feature Engineering:** Prepare relevant features for model training.
5. **Class Imbalance Handling:** Apply SMOTE as implemented in the notebook.
6. **Model Training:** Train the classification models.
7. **Hyperparameter Tuning:** Optimize model parameters.
8. **Model Evaluation:** Compare performance using appropriate evaluation metrics.

## Repository Structure

```text
insurance-claim-prediction/
│
├── README.md
├── requirements.txt
├── INSURANCE_CLAIM_PREDICTION.ipynb
└── data/
    └── (dataset stored locally)
```

## How to Run the Project

### 1. Clone the Repository

```bash
git clone <YOUR-REPOSITORY-URL>
cd insurance-claim-prediction
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate the environment on Windows:

```bash
.venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Prepare the Dataset

Place the authorized dataset in your local `data/` directory. Update the data path in the notebook if necessary.

The dataset is not included in this repository. Do not upload private or restricted data without permission.

### 5. Run the Notebook

```bash
jupyter notebook
```

Open `INSURANCE_CLAIM_PREDICTION.ipynb` and execute the cells in sequence.

## Key Learnings

- Exploratory data analysis
- Data cleaning and preprocessing
- Feature engineering
- Classification algorithms
- Handling class imbalance using SMOTE
- Hyperparameter tuning
- Model evaluation and comparison

## Limitations

Model performance depends on data quality, class distribution, feature selection, and validation strategy. This project is intended for educational and portfolio purposes and should not be considered a production-ready insurance decision system without further validation.

## Author

**Srinivas Panchangam**

- **LinkedIn:** [Your LinkedIn Profile](YOUR-LINKEDIN-PROFILE-URL)
