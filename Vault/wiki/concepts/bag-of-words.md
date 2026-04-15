---
type: concept
aliases: [Bag-of-Words]
relationships:
  - target: feature-vector
    type: creates
  - target: neural-network-input-preparation
    type: is_a_method_of
  - target: text-data
    type: processes
  - target: tokenization
    type: includes_step
  - target: vocabulary-building
    type: includes_step
  - target: encoding-bag-of-words
    type: includes_step
  - target: countvectorizer
    type: is-implemented-by
  - target: vocabulary-in-text-processing
    type: uses
  - target: sparse-matrix
    type: is-represented-by
  - target: sentiment-analysis
    type: is-used-for
  - target: text-classification
    type: used_for
  - target: stopwords
    type: is_related_to
tags: [text-representation, feature-extraction, nlp, text-processing, text-analysis, feature-engineering, natural-language-processing, data-representation]
sourced_from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content
---

# Bag-of-Words

A representation for text that discards most of the input's structure and only counts how often each word from a vocabulary appears in a document. A method for representing text data by creating a feature for each word in the vocabulary and counting its occurrences in each document. A model for representing text data by counting word occurrences, which can be extended to use sequences of more than one word (n-grams). A simple and powerful text representation for text classification tasks such as spam and fraud detection or sentiment analysis. A representation for text data that describes a document by the words it contains, disregarding grammar and word order.

## Relationships

- **processes**: [[text-data|Text Data]]
- **includes_step**: [[tokenization|Tokenization]]
- **includes_step**: [[vocabulary-building|Vocabulary Building]]
- **includes_step**: [[encoding-bag-of-words|Encoding Bag Of Words]]
- **is-implemented-by**: [[countvectorizer|Countvectorizer]]
- **uses**: [[vocabulary-in-text-processing|Vocabulary In Text Processing]]
- **is-represented-by**: [[sparse-matrix|Sparse Matrix]]
- **is-used-for**: [[sentiment-analysis|Sentiment Analysis]]
- **used_for**: [[text-classification|Text Classification]]
- **is_related_to**: [[stopwords|Stopwords]]

---
*Extracted from: Introduction To Machine Learning With Python   A Guide For    Andreas C  MüLler And Sarah Guido    1 Content*

---
*Also referenced in: ǂThe ǂHundred Page Machine Learning Book    Andriy Burkov    Lugar De PublicacióN No Identificado, 2 Content*