kinza-twitter-sentiment-analysis

A machine learning project that analyzes Twitter/X data to classify public sentiment on specific topics as Positive, Negative, or Neutral using NLP and machine learning techniques.

 Live Demo

https://orange-winner-r4rj657vgpxjh5qrg-8501.app.github.dev/

 Project Overview

This project uses Natural Language Processing (NLP) and Machine Learning to analyze tweets and determine the sentiment expressed in the text.

The system classifies tweets into three categories:

- Positive
- Negative
- Neutral

It can also analyze tweets related to a specific topic and provide an overall sentiment distribution.

 Objectives

- Analyze Twitter/X tweet data
- Clean and preprocess text data
- Apply NLP techniques
- Convert text into numerical features using TF-IDF
- Train Machine Learning models
- Compare model performance
- Predict sentiment for new tweets
- Analyze sentiment for specific topics
- Visualize sentiment results

Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- Joblib
- Streamlit
- Jupyter Notebook

 Machine Learning Models

The project uses and compares:

- Logistic Regression
- Multinomial Naive Bayes
- Linear SVM

The best-performing model is selected based on evaluation results.

 NLP & Data Processing

The tweet data goes through several preprocessing steps:

- Removing missing values
- Removing duplicate tweets
- Converting text to lowercase
- Removing URLs
- Removing user mentions
- Processing hashtags
- Removing unnecessary characters
- Removing stopwords
- Tokenizing text
- Preparing cleaned text for Machine Learning

 TF-IDF

TF-IDF (Term Frequency-Inverse Document Frequency) is used to convert tweet text into numerical features that Machine Learning algorithms can understand.

 Sentiment Analysis

The system predicts whether a tweet is:

- Positive — expresses a positive opinion
- Negative — expresses a negative opinion
- Neutral — does not express a clearly positive or negative opinion

 Topic-Based Analysis

The project can analyze sentiment related to a specific topic such as:

- Artificial Intelligence
- Education
- Technology
- Cricket
- Products
- Brands

The system can display:

- Total tweets related to the topic
- Positive tweets
- Negative tweets
- Neutral tweets
- Sentiment percentages
- Sentiment distribution

 Streamlit Application

The project includes an interactive Streamlit interface where users can enter a tweet and receive its predicted sentiment.

Users can also enter a topic and analyze the sentiment of related tweets available in the dataset.

 Project Structure

kinza-twitter-sentiment-analysis/

├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   └── twitter_sentiment_analysis.ipynb
├── src/
│   ├── data_preprocessing.py
│   ├── feature_extraction.py
│   ├── train_model.py
│   ├── evaluate_model.py
│   └── predict.py
├── models/
├── reports/
├── app.py
├── requirements.txt
├── README.md
└── .gitignore

 Installation

Install the required packages:

pip install -r requirements.txt

 Run the Application

Run the Streamlit application:

streamlit run app.py

 Jupyter Notebook

The project includes a Jupyter Notebook containing:

- Dataset loading
- Data cleaning
- Text preprocessing
- Exploratory Data Analysis
- TF-IDF
- Model training
- Model evaluation
- Model comparison
- Sentiment prediction
- Topic analysis

 Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

 Dataset

The project is designed to work with Twitter/X tweet data containing text and sentiment labels.

The dataset can be replaced with another compatible Twitter/X sentiment dataset.

 Limitations

- Sarcasm can be difficult to detect.
- Informal language can affect predictions.
- Slang and abbreviations may reduce accuracy.
- Results depend on dataset quality.
- Dataset bias can affect model performance.
- Without Twitter/X API integration, the project analyzes the provided dataset rather than live Twitter/X data.

 Future Improvements

- Twitter/X API integration
- Real-time sentiment analysis
- BERT and Transformer-based models
- Multilingual sentiment analysis
- Better sarcasm detection
- Larger datasets
- Real-time sentiment dashboards
- Cloud deployment

 Author

Kinza

Machine Learning Project — Twitter/X Sentiment Analysis

 License

This project is created for educational and academic purposes.
