# News_Summarization_ML_Python
News Summarizer Application  This repository contains a Python application for summarizing news articles using NLP. The app uses Tkinter for the GUI, Newspaper3k for article extraction, and TextBlob for sentiment analysis.
Features
Article Extraction: Uses Newspaper3k to extract and process news articles from a provided URL.
Summarization: Generates concise summaries of extracted articles.
Sentiment Analysis: Performs sentiment analysis using TextBlob, providing polarity and overall sentiment (positive, negative, neutral).
GUI: Interactive interface built with Tkinter for easy user interaction.
Requirements
Python 3.x
nltk
textblob
newspaper3k
tkinter (part of Python standard library)
Installation
Clone the repository:


git clone https://github.com/yourusername/news-summarizer.git
cd news-summarizer
Install the required Python packages:

pip install nltk textblob newspaper3k
Download the NLTK 'punkt' package:

python -m nltk.downloader punkt
Usage
Run the application:


python news_summarizer.py
Enter a news article URL in the provided text field and click "Summarize".

View the extracted title, author, publication date, summary, and sentiment analysis in the respective fields.


Acknowledgements
Newspaper3k
TextBlob
NLTK
