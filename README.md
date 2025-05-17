# Sentiment Analysis Using Bag-of-Words

This project demonstrates how to perform sentiment analysis on text data using the Bag-of-Words (BoW) model. It includes text preprocessing, feature extraction, and classification using machine learning techniques.

## 📌 Overview

The goal of this project is to classify text data (e.g., movie reviews) into positive or negative sentiments. The steps involved are:

- Data preprocessing: cleaning and preparing the text data.
- Feature extraction: converting text into numerical features using the BoW model.
- Model training: training a classifier to predict sentiments.
- Evaluation: assessing the performance of the model.

## 🗂️ Project Structure
sentiment-analysis-bow/
├── Dataset/ # Contains the dataset used for training and testing
├── sentiment-analysis-BoW.ipynb # Jupyter Notebook with the implementation
└── README.md # Project description and instructions


## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- scikit-learn
- pandas
- numpy
- nltk

## 📊 Methodology

1. **Data Preprocessing**:
   - Lowercasing text
   - Removing punctuation and stopwords
   - Tokenization

2. **Feature Extraction**:
   - Implementing the Bag-of-Words model using `CountVectorizer` from scikit-learn.

3. **Model Training**:
   - Splitting the dataset into training and testing sets.
   - Training a classifier (e.g., Naive Bayes, Logistic Regression) on the training data.

4. **Evaluation**:
   - Predicting sentiments on the test data.
   - Calculating accuracy, precision, recall, and F1-score.

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.x
- Jupyter Notebook
- Required Python libraries (see below)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/maia-leelapisuth/sentiment-analysis-bow.git
   cd sentiment-analysis-bow
   ```
2. Install the required libraries:
   
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open and run the sentiment-analysis-BoW.ipynb notebook.

## 📬 Contact
Feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/chonlada-leelapisuth) or via GitHub issues for any questions or feedback.
