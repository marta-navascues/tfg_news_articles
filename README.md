# Marta Navascués Peña - Bachelor Thesis 👩‍🏫
# ⭐ Analysis of gender bias in sports press through the use of automatic means ⭐

This README file provides an overview of a code that performs four different tasks: web scraping news articles from the Marca newspaper online repository, NLP preprocessing of the extracted data, training and analysis of a Word2Vec model, and training and testing a text classifier for gender classification.

## Task 1: Web Scraping 📰

The code utilizes web scraping techniques to extract news articles from the Marca newspaper online repository. It accesses the website, retrieves the HTML content, and extracts relevant information such as article titles, authors, publication dates, and article contents. The extracted data is then stored in a dataframe for further processing.

## Task 2: NLP Preprocessing 💬

Once the news articles are extracted, the code performs NLP preprocessing on the textual data. This preprocessing step involves cleaning the extracted text by removing HTML tags, special characters, stopwords, and performing lemmatization or stemming. The preprocessed text is then transformed into a tokenized dictionary, where each token represents a word or a meaningful unit.

## Task 3: Word2Vec Model Training and Analysis 🪄

After preprocessing, the code trains a Word2Vec model using the tokenized dictionary. Word2Vec is a popular technique for word embedding, which represents words in a continuous vector space. The trained model allows for various analyses, such as finding similar words, calculating word similarities, or even visualizing word embeddings using techniques like t-SNE or PCA.

## Task 4: Text Classifier for Gender Classification 🏷️

The final task of the code involves training and testing a text classifier specifically designed for gender classification. This classifier takes preprocessed text data as input and aims to predict the gender associated with the text. The training data should be labeled with the corresponding gender. The classifier is trained on a portion of the data and then evaluated on a separate test set to assess its performance.

## Dependencies 📚

The code relies on the following dependencies:

- Python 3.x
- Beautiful Soup 
- Requests
- Gensim 
- Scikit-learn
- Numpy
- Pandas
- Datetime
- Spacy
- Time
- Re
- String
- Pickle
- Seaborn
- Scipy
- Joblib
- Matplotlib

Please ensure that these dependencies are installed before running the code.

## Usage 🚀

To use the code, follow these steps:

1. Install the required dependencies listed in the Python libraries section.
2. Download or clone the notebook to your local machine or editor.
3. Execute the desired pieces of code with the corresponding changes regarding data sources.

Please note that the code provided here is a high-level overview and does not include the complete implementation details. You may need to refer to the actual code files for a more comprehensive understanding and to make any necessary modifications.
