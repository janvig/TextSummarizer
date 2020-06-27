# TextSummarizer
Summarizes texts generating pointer summary


## Methodology
- Tokenize the article into sentences
- Preprocess the data </br>
  Text Cleaner Class - 
  - Tokenize (into sentence and words)
  - Remove noise (stopwords, contractions)
  - Process for noun, verb, adjective and adverb
  - Normalize text (convert to root word)
- TextRank Algorithm: Similarity matrix using cosine distance
- PageRank Algorithm
- Sort sentences in order of importance
- Generate summary </br>
Evaluation: Compare with human summary [ROUGE Score]


