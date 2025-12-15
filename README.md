# Fake-News-Detection-Ml
Fake News Detection is a machine learning project that identifies whether a news article is real or fake by analyzing its text. The model cleans the data, converts text into numerical form using TF‑IDF, trains on labeled examples, and predicts news authenticity accurately.

 What this project does
Takes news text as input
Cleans and processes the text
Converts text into numbers using TF‑IDF
Uses a Logistic Regression model

Predicts →
1 = Real News
0 = Fake News

Technologies Used
Python
Pandas
NumPy
Scikit-learn
TF‑IDF Vectorizer (NLP)

Google Colab
📂 Dataset Used
Dataset from Kaggle (Fake & Real News dataset by Emine Yetim)
It contains two files:
True.csv (Real news)
Fake.csv (Fake news)

Steps Performed
Loaded dataset
Added labels (1 = real, 0 = fake)
Combined both CSV files
Cleaned the text (removed punctuation, lowercase, etc.)
Converted text to numbers using TF‑IDF
Split data into train & test
Trained Logistic Regression model
Checked accuracy (~95%+)
Tested with custom news text

Model Accuracy
The model gives around 95% accuracy (depending on dataset shuffle).

How to Use
Open the notebook in Google Colab
Upload True.csv and Fake.csv
Run all cells
Use the predict_news() function to test any news
