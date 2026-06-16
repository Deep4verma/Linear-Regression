# Graduate Admission Prediction Using Linear Regression

## Project Overview

Developed a machine learning regression model to predict a student's probability of admission to graduate programs based on academic performance, test scores, and research experience. The project helps universities and applicants estimate admission chances using data-driven insights.

## Objective

Build a predictive model that:

- Estimates the probability of graduate admission.
- Analyzes factors influencing admission decisions.
- Identifies the most significant admission criteria.
- Supports informed decision-making for applicants.

## Dataset

The dataset contains academic and profile information of graduate school applicants.

### Features

- GRE Score
- TOEFL Score
- University Rating
- Statement of Purpose (SOP)
- Letter of Recommendation (LOR)
- CGPA
- Research Experience

### Target Variable

- Chance of Admit

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Data Preprocessing

- Checked for missing values and duplicates.
- Removed unnecessary columns.
- Performed feature scaling where required.
- Analyzed correlations among variables.

## Exploratory Data Analysis

Conducted detailed analysis to understand relationships between applicant profiles and admission chances:

- GRE Score vs Admission Probability
- TOEFL Score vs Admission Probability
- CGPA Distribution Analysis
- Research Experience Impact
- Correlation Heatmap

## Model Development

### Linear Regression

Implemented Linear Regression to predict admission probability based on applicant characteristics.

### Feature Importance Analysis

Evaluated the contribution of each feature toward admission outcomes.

## Workflow

### Data Collection

Imported and explored the admission dataset.

### Data Cleaning

Prepared data by handling inconsistencies and irrelevant attributes.

### Feature Selection

Selected academic and profile-related features affecting admission chances.

### Model Training

Trained the Linear Regression model using historical admission records.

### Prediction

Predicted the probability of admission for new applicants.

## Evaluation Metrics

Model performance was evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## Results

- Successfully built a regression model for graduate admission prediction.
- Identified CGPA, GRE Score, and TOEFL Score as major influencing factors.
- Generated accurate admission probability estimates.
- Provided valuable insights into admission decision patterns.

## Business Impact

- Helps students evaluate admission prospects.
- Supports academic planning and university selection.
- Provides data-driven admission insights.
- Assists educational consulting services.

## Future Improvements

- Implement Ridge and Lasso Regression.
- Compare performance with Random Forest Regressor and XGBoost.
- Hyperparameter tuning for improved accuracy.
- Deploy as a web application using Flask or Streamlit.

## Author

**Deepti Verma**

GitHub: [https://www.linkedin.com/in/deeptiverma1004/]

LinkedIn: [https://github.com/Deep4verma/]
