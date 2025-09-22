## 1. Introduction

Natural Language Processing (NLP) is a field of Artificial Intelligence
(AI) that enables computers to understand, interpret, and generate human
language. It combines linguistics, computer science, and AI techniques.

## 2. Tokenization

Breaking down text into smaller units such as words or sentences.

-   **word_tokenize**: Splits text into words.\
-   **sent_tokenize**: Splits text into sentences.\
-   **blankline_tokenize**: Splits text into paragraphs.\
-   **WhitespaceTokenizer**: Splits based on spaces.\
-   **wordpunct_tokenize**: Splits words and punctuations separately.

## 3. N-grams

N-grams are contiguous sequences of n items from a text. For example:

-   Bigrams: pairs of words.\
-   Trigrams: sequences of three words.\
-   Custom n-grams (e.g., 7-grams).

## 4. Stemming

Process of reducing words to their root form.

-   **PorterStemmer**: Traditional stemmer.\
-   **LancasterStemmer**: More aggressive.\
-   **SnowballStemmer**: Supports multiple languages (e.g., English,
    German).

## 5. Lemmatization

Unlike stemming, lemmatization returns actual dictionary words (lemmas).
Example:

-   running → run\
-   better → good

## 6. Stopwords

Stopwords are common words often removed in text processing (e.g., 'is',
'and', 'the').\
NLTK provides stopwords in multiple languages: English, French, German,
Chinese, Tamil, Bengali, etc.

## 7. Part-of-Speech (POS) Tagging

Assigning grammatical labels to words. Example:

`Sam is a natural when it comes to drawing` →\
- Sam (NN)\
- is (VBZ)\
- a (DT)\
- natural (JJ)\
- drawing (VBG)

## 8. Named Entity Recognition (NER)

NER identifies named entities like persons, organizations, and
locations.

Example:\
`The US president stays in the WHITEHOUSE` →\
- US (GSP)\
- WHITEHOUSE (ORGANIZATION)

## 9. WordCloud Visualization

A WordCloud represents word frequency visually, where more frequent
words appear larger.\
Created using the **WordCloud** library and **matplotlib**.

## 10. Applications

NLP is applied in:

-   Chatbots\
-   Sentiment analysis\
-   Translation\
-   Speech recognition\
-   Text summarization\
-   Search engines

