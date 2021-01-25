# Text Scrapper

Text Mining on an article with Natural Language Processing(NLP) - Automatically summarize the given text using  **NLTK**  &  **Python**.

# Requirements

1.  [NLTK](https://www.nltk.org/)


## Overview

1.  Convert the input text to a list of sentences. Then, compute the number of sentences in the given Text.
2.  Calculate the frequency of words in each sentence:
    -   The output is a dictionary where each key is a sentence and the value is also a dictionary of word frequency.
3.  Calculate Term frequency for each word in a sentence:

```
TF(word) = (Number of times term “word” appears in a sentence) / (Total number of terms in the sentence)

```

4.  Create a matrix termFrequency:
    -   The termFrequency matrix is a dictionary where each key is a sentence and the value is also a dictionary of word frequency.
5.  For each word compute how many sentences contain that word.
