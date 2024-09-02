# Fake News Detection

This project is a machine learning-based implementation for detecting fake news using Python. The model is trained on labeled datasets of true and fake news and utilizes various text classification algorithms to predict the authenticity of news articles.

## Features:
- **Data Preprocessing**: 
  - Cleaning and preparing text data by removing punctuation, URLs, and unnecessary characters.
  - Converting text to lowercase and removing stop words.
- **Dataset**:
  - The dataset consists of two CSV files: `Fake.csv` (labeled as fake news) and `True.csv` (labeled as true news).
  - A separate dataset for manual testing is also created.
- **Model Training**:
  - **Logistic Regression**
  - **Decision Tree Classifier**
  - **Gradient Boosting Classifier**
  - **Random Forest Classifier**
- **Performance Evaluation**:
  - Models are evaluated using accuracy scores and classification reports.
- **Manual Testing**:
  - A function is provided to manually input news text and predict its authenticity using the trained models.

## How to Use:
1. Run the notebook to preprocess the data and train the models.
2. Use the `manual_testing` function to test new news articles by inputting the text.
3. The function outputs predictions from all four models.

## Getting Started:
- Install the required Python libraries: `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`.
- Load the dataset files `Fake.csv` and `True.csv`.
- Execute the notebook to train the models and evaluate their performance.

## Example:
```python
news = "The economic growth has been unprecedented this quarter."
manual_testing(news)
