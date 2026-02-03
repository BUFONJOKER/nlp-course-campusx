# NLP Course CampusX 🚀

Comprehensive Natural Language Processing course covering text preprocessing, vectorization techniques, word embeddings (Word2Vec), and text classification with practical hands-on notebooks and assignments using Python, NLTK, scikit-learn, and Gensim.

## 📝 Course Description

This repository contains a complete NLP learning journey with detailed Jupyter notebooks covering fundamental to advanced Natural Language Processing concepts. Each notebook includes theory, practical implementations, and real-world examples using popular NLP libraries and datasets.

## 📖 Notebooks

### 📚 Course Notebooks

#### 🧹 `01-text-preprocessing.ipynb`

This notebook provides a comprehensive guide to various text preprocessing techniques, including:

-   🔡 Lowercasing
-   🌐 Removing HTML tags and URLs
-    punctuations Removing punctuation
-    slang Converting slang to standard English
-    spelling ABC Correcting spelling mistakes
-   🛑 Removing stopwords
-   😊 Removing emojis
-   Tokenization
-   Stemming and Lemmatization

#### 🔢 `02-text-vectorization.ipynb`

This notebook covers different techniques to vectorize text data, turning text into numerical representations that machine learning models can understand. The techniques covered are:

-   **Bag of Words (BoW)**
-   **N-Grams**
-   **TF-IDF (Term Frequency-Inverse Document Frequency)**

#### ↪️ `03-word2vector.ipynb`

This notebook explains and demonstrates the Word2Vec model, a popular technique for learning word embeddings. Key topics covered include:

-   **Loading Pre-trained Models**: Using `gensim` to load and interact with the `word2vec-google-news-300` model.
-   **Word Similarity**: Finding the most similar words and calculating similarity scores between words.
-   **Semantic Relationships**: Exploring analogies and semantic relationships like "King" - "Man" + "Woman" = "Queen".
-   **Training a Custom Model**: Training a Word2Vec model from scratch on the "Game of Thrones" book dataset.
-   **Visualization**: Visualizing word embeddings in 2D space using PCA.

#### 📊 `04-txt-classification.ipynb`

This notebook demonstrates text classification using machine learning models on the IMDB dataset. It covers the complete workflow from data preprocessing to model evaluation. Key topics include:

-   **Data Loading & Exploration**: Loading the IMDB 50K movie reviews dataset and exploring its structure.
-   **Data Preprocessing**: 
    - Converting text to lowercase for consistency
    - Removing HTML tags from reviews using BeautifulSoup
    - Removing stopwords (common words that don't add meaning)
-   **Feature Engineering**:
    - Splitting data into training (80%) and testing (20%) sets
    - Label encoding for converting sentiment labels (positive/negative) to numeric values (0/1)
-   **Text Vectorization**:
    - **CountVectorizer**: Converting text to word count vectors
    - **TF-IDF Vectorizer**: Computing Term Frequency-Inverse Document Frequency scores
-   **Model Training & Evaluation**:
    - **Gaussian Naive Bayes Classifier**: Training and evaluating on both CountVectorizer and TF-IDF features
    - **Random Forest Classifier**: Training ensemble model with 100 trees on both vectorization methods
    - Calculating accuracy scores and confusion matrices for model performance analysis
    - Visualizing confusion matrices to understand prediction patterns
-   **Model Comparison**: Comparing the performance of different models and vectorization techniques on the same dataset

This notebook provides a comprehensive guide to building and evaluating text classification models for sentiment analysis.

### 📝 Assignments

#### 1️⃣ `01-assignment.ipynb`

This assignment focuses on:

-   **API Data Scraping**: Fetching movie data from The Movie Database (TMDB) API.
-   **DataFrame Creation**: Structuring the scraped data into a pandas DataFrame.
-   **Text Preprocessing**: Applying basic preprocessing techniques like lowercasing and punctuation removal to the movie data.

#### 2️⃣ `02-assignment.ipynb`

This assignment applies various concepts learned in the course, including:

1.  **Preprocessing**: Applying various text preprocessing techniques to the dataset.
2.  **Corpus and Vocabulary Size**: Calculating the total number of words and unique words in the corpus.
3.  **One-Hot Encoding**: Applying One-Hot Encoding.
4.  **Bag of Words**: Implementing the Bag of Words model.
5.  **N-grams**: Applying Bag of Bi-grams and Tri-grams.
6.  **TF-IDF**: Applying TF-IDF to the text data.

## 💾 Dataset

The notebooks in this repository use the [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) and data from [The Movie Database (TMDB)](https://www.themoviedb.org/documentation/api).
