# Task 1 – Iris Flower Classification Using Machine Learning

## Project Overview
This project uses supervised Machine Learning classification algorithms to predict the species of an Iris flower based on its physical measurements.

## Objective
To classify Iris flowers into three species:
- Iris Setosa
- Iris Versicolor
- Iris Virginica

## Dataset Description
The project uses the built-in Iris dataset from Scikit-learn.

- Total observations: 150
- Input features: 4
- Target classes: 3
- Missing values: None

### Input Features
1. Sepal Length (cm)
2. Sepal Width (cm)
3. Petal Length (cm)
4. Petal Width (cm)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Loaded the Iris dataset.
2. Explored the dataset using Pandas.
3. Checked missing values and statistical summaries.
4. Visualized the data using species distribution charts, pairplots, and boxplots.
5. Examined feature correlations using a heatmap.
6. Split the dataset into 80% training data and 20% testing data.
7. Trained Logistic Regression and K-Nearest Neighbors classifiers.
8. Evaluated both models using accuracy, confusion matrices, precision, recall, and F1-score.
9. Tested the selected model with new flower measurements.

## Machine Learning Algorithms
- Logistic Regression
- K-Nearest Neighbors (KNN), with 5 neighbors

Both models use feature standardization through Scikit-learn pipelines.

## Model Performance

| Model | Accuracy |
|---|---:|
| Logistic Regression | 93.33% |
| K-Nearest Neighbors (KNN) | 93.33% |

Both models achieved equal test accuracy on the selected train/test split. Logistic Regression was selected by the notebook's tie-breaking rule.

## Prediction Example
A new flower was tested using these measurements:

- Sepal length: 5.1 cm
- Sepal width: 3.5 cm
- Petal length: 1.4 cm
- Petal width: 0.2 cm

Predicted species: **Setosa**

## How to Run
1. Install Python.
2. Install the required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

3. Open `Harika_Task1.ipynb` in VS Code or Jupyter Notebook.
4. Select a Python kernel.
5. Run all notebook cells.

## Conclusion
The project successfully demonstrates the use of supervised machine learning algorithms for Iris flower classification. Logistic Regression and KNN both achieved 93.33% accuracy on the test dataset. Their performance was evaluated using multiple classification metrics, and the selected model was used to predict the species of a new flower.

## Future Improvements
- Experiment with Decision Tree and Random Forest classifiers.
- Perform hyperparameter tuning.
- Apply cross-validation.
- Develop a simple web application for flower prediction.

## Internship
Oasis Infobyte – Data Science Internship

## Author
Harika Kambala
