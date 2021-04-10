# All Names Matter: Mitigating Racial Bias in Word Embeddings with Last Name-Based Counterfactual Data Substitution

This repository contains (or gives links to) the code, data sets, embeddings, models and analysis generated and used for the project <em>All Names Matter: Mitigating Racial Bias in Word Embeddings with Last Name-Based Counterfactual Data Substitution</em>.

This project is part of the requiremnts for W266: Natural Language Processing with Deep Learning, of the Master in Information and Data Science program at UC Berkeley. 

## Final Report
You can find the final paper for this project in this repo, or clicking [here](./W266_FinalProjectReport.pdf)

## Datasets
We used Wikipedia data to create the baseline corpus in our experiment. We got a dump file with over 50,000,000 articles. It is publicaly available [here.](https://dumps.wikimedia.org/enwiki/latest/) We used the dump called [enwiki-latest-pages-articles.xml.bz2.](https://dumps.wikimedia.org/enwiki/latest/)

We also used the US Census to get last names and race data. We downloaded the [Decennial Census Surname Files (2010, 2000)](https://www.census.gov/data/developers/data-sets/surnames.html) that can be found [here](https://www.census.gov/data/developers/data-sets/surnames.html)

## Corpus, Embeddings and their Code
In total we generated 8 corpora and generated 8 embeddings using word2vec and applying CDS with last name intervention. The code to generate the corpora with CDS, to train the embeddings with the resulting corpora, and the resulting files with the models are [all in this google drive](https://drive.google.com/drive/folders/1nOpc3ULXsW9aIwnMD4uZvD9Uot34RHdL?usp=sharing). 

In the drive you will also find code to generate corpora from Counterfactual Data Augmentation (CDA), we experimented with these models but did not reported on them because of the long time they required to train.

## Experiments
In the forlder [experiments](./experiments) you will find the code corresponding to [sentiment analysis](./experiments/sentiment_analysis_experiments/), [word analogies](./experiments/word_analogies_experiments/), and [direct and indirect racial bias](./experiments/direct_indirect_bias/).

In order to run these you will need to get the datasets and models described above from the [public google drive](https://drive.google.com/drive/folders/1nOpc3ULXsW9aIwnMD4uZvD9Uot34RHdL?usp=sharing) of this project

## Other Papers' Code
Before starting our project we studied the code of revelant papers in the subject. We concentrated all the relevant repositories [here](https://github.com/aditya-mengani/reducing_gender_and_racial_bias)

## Contact
For any feedback, questions or comments, please contact the authors:

Gabriela May Lagunes - g.maylagunes@berkeley.edu
Aditya Mengani - aditya.mengani@ischool.berkeley.edu
