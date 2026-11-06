# OIBSIP
Oasis Infobyte Data Science Internship Projects

# Sales Prediction Using Machine Learning

## Project Overview
This project focuses on predicting product sales based on advertising expenditure across three marketing channels: TV, Radio, and Newspaper.

Machine learning regression algorithms are used to understand the relationship between advertising investment and sales performance.

## Objective
- Analyze advertising expenditure and sales data.
- Explore relationships between advertising channels and sales.
- Build regression models to predict sales.
- Compare model performance using evaluation metrics.
- Identify the most important advertising channel.

## Dataset
**File:** `Advertising.csv`

The dataset contains the following columns:

| Column | Description |
|---|---|
| TV | Advertising expenditure on TV |
| Radio | Advertising expenditure on Radio |
| Newspaper | Advertising expenditure on Newspaper |
| Sales | Product sales (target variable) |

## Technologies and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Import required libraries.
2. Load and explore the dataset.
3. Handle unnecessary columns and duplicate records.
4. Perform Exploratory Data Analysis (EDA).
5. Visualize sales distributions and advertising relationships.
6. Analyze feature correlations.
7. Split the data into training and testing sets.
8. Train Linear Regression and Random Forest Regression models.
9. Evaluate both models.
10. Visualize residuals.
11. Analyze advertising channel importance.

## Machine Learning Algorithms
- Linear Regression
- Random Forest Regression

## Model Evaluation Results

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 1.275 | 1.705 | 0.906 |
| Random Forest | 0.914 | 1.183 | 0.955 |

Random Forest Regression achieved the best performance based on the evaluation results.

## Feature Importance

| Feature | Importance |
|---|---:|
| TV | 0.844376 |
| Radio | 0.136431 |
| Newspaper | 0.019193 |

TV advertising had the highest predictive importance, followed by Radio and Newspaper.

## Conclusion
The project successfully demonstrates sales prediction using machine learning regression algorithms.

Random Forest Regression performed better than Linear Regression, achieving an R² score of 0.955. The feature importance analysis showed that TV advertising was the strongest predictor of sales in this dataset.

This project demonstrates how machine learning can support data-driven analysis of advertising and sales performance.

## How to Run the Project

1. Clone or download this repository.
2. Open the project folder in Visual Studio Code.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

4. Open `Harika_Task5.ipynb`.
5. Select your Python environment and run all notebook cells.

## Project Files

- `Harika_Task5.ipynb` – Complete analysis, model training, evaluation, and visualizations.
- `Advertising.csv` – Dataset used for sales prediction.
- `README.md` – Project documentation.

## Author
Kambala Harika
