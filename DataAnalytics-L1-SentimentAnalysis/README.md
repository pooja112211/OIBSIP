# Sentiment Analysis

## Overview

This project was completed as part of the **Oasis Infobyte Data Analytics Internship (Task 4)**.

The objective of this project is to build a machine learning model that classifies tweets into **Positive, Negative, and Neutral** sentiments. The project uses Natural Language Processing (NLP) techniques for text preprocessing and Machine Learning algorithms for sentiment classification.

---

## Objective

- Analyze text data and identify sentiments.
- Perform text preprocessing using NLP techniques.
- Convert text into numerical features using TF-IDF Vectorizer.
- Train machine learning models for sentiment classification.
- Compare model performance using evaluation metrics.
- Visualize sentiment distribution and WordClouds.
- Analyze misclassified examples.
- Draw conclusions and suggest real-world applications.

---

## Dataset

**Dataset:** Twitter Entity Sentiment Analysis Dataset

The dataset contains tweets with sentiment labels. Since the internship requires only **Positive, Negative, and Neutral** classes, the **Irrelevant** class was removed before model training.

The project uses:

```
twitter_training.csv
```

The provided `twitter_validation.csv` file was not used because the internship requires performing an **80:20 Train-Test Split** using `train_test_split()`.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn
- WordCloud

---

## Project Workflow

1. Load the dataset.
2. Inspect the dataset structure.
3. Remove missing values.
4. Remove the "Irrelevant" sentiment class.
5. Perform text preprocessing:
   - Convert text to lowercase
   - Remove punctuation
   - Remove numbers
   - Remove extra spaces
   - Remove stopwords
   - Lemmatization
6. Convert text into numerical features using TF-IDF Vectorizer.
7. Split the dataset into training and testing sets (80:20).
8. Train two machine learning models:
   - Naive Bayes
   - Logistic Regression
9. Evaluate both models using:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - Classification Report
   - Confusion Matrix
10. Create visualizations:
    - Sentiment Distribution
    - Positive WordCloud
    - Negative WordCloud
    - Neutral WordCloud
11. Perform error analysis.
12. Compare both models and select the best-performing model.

---

## Project Results

- Successfully classified tweets into Positive, Negative, and Neutral sentiments.
- Compared Naive Bayes and Logistic Regression models.
- Selected the better-performing model based on evaluation metrics.
- Generated useful visualizations for sentiment analysis.

---

## Business Insights

- Positive tweets indicate customer satisfaction.
- Negative tweets help identify customer complaints.
- Neutral tweets provide general opinions.
- Businesses can use sentiment analysis to improve products, services, and customer experience.

---

## Visualizations

The project includes:

- Sentiment Distribution Bar Chart
- Positive WordCloud
- Negative WordCloud
- Neutral WordCloud
- Naive Bayes Confusion Matrix
- Logistic Regression Confusion Matrix

---

## Project Structure

```
DataAnalytics-L1-SentimentAnalysis/
│
├── datasets/
│   └── twitter_training.csv
│
├── images/
│
├── notebook/
│   └── Sentiment_Analysis.ipynb
│
├── README.md
└── requirements.txt
```

---

# Installation

Clone or download the repository.

Install all required libraries.

```bash
pip install -r requirements.txt
```

If you do not have the required libraries installed, install them manually.

```bash
pip install pandas
pip install matplotlib
pip install seaborn
pip install nltk
pip install scikit-learn
pip install wordcloud
pip install contractions
```

Or install everything together.

```bash
pip install pandas matplotlib seaborn nltk scikit-learn wordcloud contractions
```

---

## Download Required NLTK Resources

Before running the notebook, download the required NLTK resources.

```python
import nltk

nltk.download("stopwords")
nltk.download("wordnet")
```

Run these only once. NLTK will save them locally for future use.

---

## How to Run the Project

1. Clone or download this repository.
2. Install all required libraries.
3. Download the NLTK resources.
4. Open the notebook:

```
notebook/Sentiment_Analysis.ipynb
```

5. Run all notebook cells from top to bottom.

---

## requirements.txt

```
pandas
matplotlib
seaborn
nltk
scikit-learn
wordcloud
contractions
```

---

## Conclusion

This project successfully built a sentiment analysis model to classify tweets into Positive, Negative, and Neutral sentiments. Text preprocessing and TF-IDF feature extraction improved the quality of the data before training the machine learning models. After evaluating both Naive Bayes and Logistic Regression, the better-performing model was selected based on its performance metrics.

---

## Real-World Applications

- Customer feedback analysis
- Product review analysis
- Social media monitoring
- Brand reputation management
- Market research
- Customer satisfaction analysis

---

## Author

**Pooja Kumari**


