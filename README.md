# Graduate Admission Chance Prediction Using Machine Learning

A machine learning regression project developed as part of the **YBI
Foundation -- 6-Month Live Project-Based Internship**. The project
predicts a student's chance of admission to a graduate program using
academic and profile-related features.

## Project Overview

Graduate admission decisions depend on multiple factors such as academic
scores, university rating, statement of purpose, letters of
recommendation, CGPA, and research experience. This project builds and
evaluates machine learning regression models to estimate a student's
**Chance of Admit**.

## Objective

The main objectives of this project are to:

-   Load and understand the graduate admission dataset.
-   Clean and prepare the data for machine learning.
-   Perform exploratory data analysis and correlation analysis.
-   Train multiple regression models.
-   Compare model performance using standard regression metrics.
-   Select the better-performing model.
-   Predict the admission chance for a new student profile.

## Dataset

The dataset used in this project contains **400 student records**.

### Input Features

-   GRE Score
-   TOEFL Score
-   University Rating
-   Statement of Purpose (SOP)
-   Letter of Recommendation (LOR)
-   CGPA
-   Research Experience

### Target Variable

-   Chance of Admit

## Project Workflow

1.  Import required Python libraries.
2.  Load the dataset.
3.  Understand the dataset structure and statistics.
4.  Clean column names and remove the identifier column.
5.  Check for missing values and duplicate records.
6.  Perform exploratory data analysis.
7.  Analyze feature correlations.
8.  Define features and the target variable.
9.  Split the data into training and testing sets.
10. Train Linear Regression and Random Forest Regressor models.
11. Evaluate and compare the models.
12. Select the better-performing model.
13. Compare actual and predicted values.
14. Interpret feature importance.
15. Predict the admission chance for a new student profile.

## Machine Learning Models

The following regression models were trained and compared:

-   Linear Regression
-   Random Forest Regressor

## Model Evaluation

The models were evaluated using:

-   **MAE (Mean Absolute Error):** Measures the average absolute
    prediction error.
-   **RMSE (Root Mean Squared Error):** Gives greater weight to larger
    prediction errors.
-   **R² Score:** Measures how well the model explains variation in the
    target variable.

### Final Result

  Metric                           Result
  -------------------------------- ---------------------
  Best Model                       Linear Regression
  R² Score                         Approximately 0.821
  Example New-Student Prediction   78.01%

The final comparison selected **Linear Regression** as the
better-performing model for this dataset.

## Visualizations

The notebook includes:

-   Distribution of Chance of Admit
-   Feature Correlation Matrix
-   Actual vs Predicted Values
-   Feature Importance / Model Interpretation

## Technologies Used

-   Python
-   NumPy
-   Pandas
-   Matplotlib
-   scikit-learn
-   Google Colab
-   Jupyter Notebook

## Project File

``` text
Graduate-Admission-Prediction/
├── README.md
└── YBI_Graduate_Admission_Prediction_SUBMISSION_READY.ipynb
```

## How to Run the Project

1.  Open the notebook in Google Colab or Jupyter Notebook.
2.  Run all cells in order.
3.  The dataset is loaded directly from the configured dataset URL.
4.  Review the generated analysis, model comparison, visualizations, and
    prediction results.

No manual dataset upload is required when the dataset URL is accessible.

## Conclusion

This project demonstrates a complete machine learning regression
workflow for predicting graduate admission chances. It covers data
loading, cleaning, exploratory analysis, model training, model
comparison, evaluation, interpretation, and prediction.

The project shows how machine learning can be applied to educational
data to estimate admission probability from a student's academic
profile.

## Future Scope

The project can be extended by:

-   Testing additional regression algorithms.
-   Performing hyperparameter tuning.
-   Applying cross-validation.
-   Deploying the trained model as a web application.
-   Building a user interface for real-time admission predictions.

## Internship Details

-   **Organization:** YBI Foundation
-   **Program:** 6-Month Live Project-Based Internship
-   **Project Completion Year:** 2026

## Author

**Dhruv Sanjay Ghugal**

-   GitHub: `BugsPayRentHere`
-   B.Tech in Computer Engineering
-   Bapurao Deshmukh College of Engineering, Sewagram, Wardha,
    Maharashtra

------------------------------------------------------------------------

This project was completed as part of the **YBI Foundation -- 6-Month
Live Project-Based Internship**.
