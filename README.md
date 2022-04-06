# Text Classification of COVID-19 Biomedical Literature
## Final Project for Natural Language Processing & Health, Spring 2022
### Max Chao & Yohyoh Wang

This project explores NLP approaches to multilabel text classification of COVID-19 biomedical literature. We used datasets from [LitCovid](https://www.ncbi.nlm.nih.gov/research/coronavirus/), a dataset of ~240,000 articles relating to COVID-19. Each article is annotated with one or more labels corresponding to different research topics (general, mechanism, transmission, diagnosis, treatment, prevention, case report, forecasting). 

The goal of this project is to correctly classify studies' label(s) based on the title and abstract of the studies.

We compared the following 3 models 

1. Multinomial Naive Bayes (baseline) 
2. Support Vector Machine trained on Word2Vec embeddings
3. Support Vector Machine trained on TF-IDF vectors
