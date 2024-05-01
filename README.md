# English Premier League Match Outcome Prediction

## Introduction
This repository contains the code and documentation for my final data science project, which focuses on predicting the outcome (win/not win) of English Premier League (EPL) football matches. The project utilizes machine learning techniques, including various classification algorithms, feature selection methods, and feature engineering.
The repository consists of 3 main files 
- `Scraping data and data preprocessing.ipynb` : The python notebook for scraping data from fbref website.
- `prediction.ipynb` : The main prediction file
- `all_matches3.csv` : The csv file consisting the scraped file

## Data Collection
The data for this project was scraped from the [fbref.com](https://fbref.com/en/comps/9/Premier-League-Stats) website, extracting match statistics such as team performance metrics, player statistics, and match venue information for each EPL match.

## Preprocessing
Prior to modeling, the data underwent preprocessing steps including handling missing values, encoding categorical variables, and normalizing numerical features. The dataset was then split into training and testing sets.

## Feature Engineering
Feature engineering techniques were applied to enrich the dataset and improve predictive performance. This involved creating new features such as goal difference, average goals scored/conceded per match, and incorporating historical performance metrics.

## Feature Selection
To enhance model interpretability and efficiency, feature selection techniques were implemented. Methods such as Recursive Feature Elimination (RFE), Feature Creation, and Principal Component Analysis (PCA) were employed to identify the most relevant features.

## Model Selection
Several classification algorithms were explored and compared, including Logistic Regression, Random Forest, XGboost and Gradient Boosting. The models were evaluated using various metrics such as accuracy, precision, recall, and F1-score.

## Conclusion
This project demonstrates the feasibility of predicting EPL match outcomes using machine learning. By leveraging feature engineering, feature selection, and model selection strategies, we were able to build predictive models with promising performance. Further optimization and fine-tuning could potentially enhance the accuracy of the predictions.

## Usage
To use this project:
1. Clone the repository.
2. Install the required dependencies listed in the `requirements.txt` file.
3. To freshly collect data using webscraping, run the jupyter notebook named `Scraping data and data preprocessing.ipynb`.
4. Run the Jupyter notebook named `prediction.ipynb` to execute the project pipeline.

## Dependencies
- Python 3
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Pytorch

## Contributors
- Donal Loitam(AI21BTECH11009)
- Ankita Kumari(EP21BTECH11008)
