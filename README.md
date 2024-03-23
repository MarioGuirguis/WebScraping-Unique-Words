# WebScraping-Unique-Words
This project extract text from Html page and apply preprocessing in the text then get the unique words from the text.
<br/>
# The Code follows this steps:
## Data:
1. Use any URL.
2. Extract HTML (Web-Scraping)
3. Extract Text
## Preproccessing:
1. Data Normalization: Make all the data to lower case.
2. Cleaning data from [HTML Tags, Links and Emails, Symbols, Numbers, Emojis, Non-Ascii charachters].
3. Spell Correction.
4. Remove Stop Words.
5. Lemmatization: return each word to origin.
6. Tokenization: split the data to words.
## Unique Words:
Get Unique words after splitting the data to words by using python Set Data Structure.
<br/>
# Libiraries to Import:
- pip install BeautifulSoup
- pip install pyspellchecker
- pip install nltk
- nltk.download('stopwords')
- pip install -U scikit-learn
- pip install -U spacy
