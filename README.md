# Text Classification of COVID-19 Biomedical Literature
## Final Project for Natural Language Processing & Health, Spring 2022
### Max Chao & Yohyoh Wang

This project explores NLP approaches to multilabel text classification of COVID-19 biomedical literature. We used datasets from [LitCovid](https://www.ncbi.nlm.nih.gov/research/coronavirus/), a dataset of ~240,000 articles relating to COVID-19. Each article is annotated with one or more labels corresponding to different research topics (general, mechanism, transmission, diagnosis, treatment, prevention, case report, forecasting). 

The goal of this project is to correctly classify studies' label(s) based on the title and abstract of the studies.

We compared the following 3 models 

1. Naive Bayes (baseline) 
2. CNN 
3. RNN (alternative model)

**Project Steps**

1. Clean the data

    - Combine provided test.csv, valid.csv, and train.csv into a single csv and re-split. 

2. EDA

    - Explore how are words within the inputs clustering.

    - Identify the most frequent wordsin the corpus.

3. Preprocess 

- Tokenize words: **Yohyoh, 4/1**

- Generate word embeddings (word2vec): **Yohyoh, 4/1 (Max hops on if available)**

- Named entity Recognition (unknown) : **Max**

### Train models 

- Train Naive Bayes (baseline model): **Yohyoh, 4/4**

- CNN (our model): **Yohyoh, 4/4**

- RNN (or another alternative model, add transformer?): **Max, 4/4**

### Quantitative evaluation of each model

- Multilabel classifiers use a [confusion matrix for each label](https://towardsdatascience.com/evaluating-multi-label-classifiers-a31be83da6ea). Report accuracy, precision, recall, F1: **Max/Yohyoh for each model**

- Generate an AUC curve: **Max/Yohyoh for each model**

- tSNE with clusters - compare between predicted vs. actual: **Max/Yohyoh for each model**
