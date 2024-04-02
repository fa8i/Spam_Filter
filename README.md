Spam Filter Examples

This repository contains two notebooks demonstrating different approaches to building spam filters using web scraping techniques and natural language processing (NLP) tools.

Example 1: Token-Based Spam Detection

The notebook titled "Token-Based_Spam_Detection.ipynb" illustrates a token-based approach to spam detection. It demonstrates how to download a webpage, extract its text content using BeautifulSoup, tokenize the text, and analyze it for spam patterns. The example uses a predefined set of spam patterns and checks for their occurrence in the tokenized text. If any of the spam patterns are found, the page is labeled as spam.

Example 2: NLP-Based Spam Detection

The notebook titled "NLP-Based_Spam_Detection.ipynb" showcases an NLP-based approach to spam detection using Spacy and NLTK. It downloads a webpage, extracts its text content using BeautifulSoup, tokenizes the text using Spacy, and then performs lemmatization and removal of stopwords using NLTK. The notebook then identifies the most frequent lemmas and compares them to a predefined set of spam patterns. If any of the spam patterns are found among the most frequent lemmas, the page is labeled as spam.

Usage

To use the spam filter examples:

Open the respective notebook ("Token-Based_Spam_Detection.ipynb" or "NLP-Based_Spam_Detection.ipynb") in Jupyter Notebook or JupyterLab.

Follow the instructions provided within each notebook to execute the code and observe the spam detection results for the provided URL.

Dependencies
Both notebooks require the following libraries:
  
  1. requests: For making HTTP requests to download web pages.
  2. BeautifulSoup: For parsing HTML content.
  3. spacy: For NLP tasks such as tokenization and lemmatization.
  4. nltk: For additional NLP tasks such as stopwords removal.
  5. Ensure these libraries are installed before running the notebooks.

Contributors

1. Fabián Melchor.
Contributions are welcome! If you have any enhancements, bug fixes, or additional spam filter examples, feel free to submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

