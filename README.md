# English Premier League Match Outcome Prediction

## Introduction
This repository contains the code and documentation for my final data science project, which focuses on predicting the outcome (win/not win) of English Premier League (EPL) football matches. The project utilizes machine learning techniques, including various classification algorithms, feature selection methods, and feature engineering.

## Data Collection
The data for this project was scraped from the fbref.com website, extracting match statistics such as team performance metrics, player statistics, and match venue information for each EPL match.

## Preprocessing
Prior to modeling, the data underwent preprocessing steps including handling missing values, encoding categorical variables, and normalizing numerical features. The dataset was then split into training and testing sets.

## Feature Engineering
Feature engineering techniques were applied to enrich the dataset and improve predictive performance. This involved creating new features such as goal difference, average goals scored/conceded per match, and incorporating historical performance metrics.

## Feature Selection
To enhance model interpretability and efficiency, feature selection techniques were implemented. Methods such as Recursive Feature Elimination (RFE), Feature Importance using Random Forest Classifier, and Principal Component Analysis (PCA) were employed to identify the most relevant features.

## Model Selection
Several classification algorithms were explored and compared, including Logistic Regression, Random Forest, Support Vector Machines (SVM), and Gradient Boosting. The models were evaluated using various metrics such as accuracy, precision, recall, and F1-score.

## Conclusion
This project demonstrates the feasibility of predicting EPL match outcomes using machine learning. By leveraging feature engineering, feature selection, and model selection strategies, we were able to build predictive models with promising performance. Further optimization and fine-tuning could potentially enhance the accuracy of the predictions.

## Usage
To use this project:
1. Clone the repository.
2. Install the required dependencies listed in the `requirements.txt` file.
3. Run the Jupyter notebook or Python script to execute the project pipeline.

## Dependencies
- Python 3
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Contributors
- Ankita Kumari
- Donal Loitam

## License
This project is licensed under the MIT License. Feel free to use and modify the code according to the terms of the license. Contributions are welcome!
