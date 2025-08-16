---
description: |
  This dataset contains scraped data from IslamQA.
  It includes the original questions and embeddings of the answers.
  Various metadata scraped from the website, such as the category of the question, are also included.
  The following two models were used to generate embeddings:
  1. bert-base-multilingual-uncased
  2. bert-base-uncased

  We provide embeddings of the truncated answer (to fit model limits) and the embeddings of every sentence. Sentences are tokenized using spaCy.
  The embeddings of the responses were provided to allow evaluation.
  The dataset was collected in April 2024.
language:
  - en
  - fr
  - ar
  - fa
  - tr
  - ru
  - id
  - es
  - pt
  - hi
  - ur
size_categories:
  - 10K<n<100K
