# Email Spam Detection Using Machine Learning

## Project Overview
This project focuses on classifying SMS messages as Spam or Ham (genuine messages) using Natural Language Processing (NLP) and Machine Learning techniques.

## Objective
To develop a machine learning model that automatically identifies unwanted or fraudulent SMS messages.

## Dataset
- Dataset: SMS Spam Collection
- File: `spam.csv`
- Contains SMS messages labelled as spam or ham.
- Columns: Category and Message.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NLP
- TF-IDF Vectorization
- Jupyter Notebook

## Project Workflow
1. Imported the required libraries.
2. Loaded and explored the dataset.
3. Checked missing values and duplicate records.
4. Cleaned and preprocessed text messages.
5. Converted categories into numerical labels.
6. Applied TF-IDF vectorization.
7. Split the dataset into training and testing sets.
8. Trained Multinomial Naive Bayes and Logistic Regression models.
9. Evaluated models using accuracy, precision, recall, F1-score, and confusion matrices.
10. Tested predictions using custom SMS messages.

## Machine Learning Algorithms
- Multinomial Naive Bayes
- Logistic Regression

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Results
The two models were compared using the evaluation metrics. The better-performing model was selected for SMS spam prediction.

*Add your actual model scores here after completing evaluation.*

## Conclusion
This project demonstrates how NLP and machine learning can be used to classify SMS messages as spam or genuine messages. It provides practical experience in text preprocessing, feature extraction, model training, and evaluation.

## How to Run
1. Clone or download this repository.
2. Open the project folder.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `Harika_Task4.ipynb` and run the cells.

## Project Files
- `Harika_Task4.ipynb` – Complete implementation.
- `spam.csv` – SMS dataset.
- `README.md` – Project documentation.

## Author
Harika Kambala
