# Prediction of Side Effects Due to Polypharmacy Using Machine Learning

This work was inspired by the [TIP](https://github.com/NYXFLOWER/TIP) project of NYXFLOWER on GitHub. This project utilizes machine learning in order to predict the side effects of polypharmacy. If the user inputs the names of two drugs, the program predicts possible side effects that these drugs can bring.

## Background of the Proposal

Currently, South Korea does not have a drug side effect prediction system. It is possible to find the name, efficacy, and side effects of one drug on portal sites such as Naver, but the combination of the two drugs and the side effects that the combination brings are difficult to predict. Therefore, most people have no common sense of side effects when taking more than one drug without the attention of a specialist. This idea was proposed to predict the side effects that people who have underlying diseases or who have medication they usually take (such as contraceptives, depression drugs, diabetes drugs, allergy drugs, etc.) would be wary of when taking more than one drug.

## Overview

Predicting drug side effects through machine learning has not yet been fully implemented despite the very high need. Therefore, this idea has a clear differentiation because it solves frequently occurring problems in a new way. When the user puts two drug names into the system, this app predicts possible side effects through algorithms. 

Machine learning is necessary to identify the interaction and side effects of the two drugs. It is the principle that a computer learns the drugs and side effects of a given dataset and then identifies the interaction of newly input drugs. If this idea is developed and commercialized, accidents caused by ignorance about the side effects of taking two drugs together can be prevented. 

## Prototype Design

### 1. Data Collection

There were multiple drug data sets that could be used for free, but the collection was narrowed down when taking two or more drugs since most drug data sets were structures that contained a detailed explanation of one drug. In order to predict side effects, we needed a dataset connected not only to drugs but also to proteins. In conclusion, we decided to use the data published in [Decagon](https://github.com/mims-harvard/decagon) ([Modeling polypharmacy side effects with graph convolutional networks](https://academic.oup.com/bioinformatics/article/34/13/i457/5045770?login=false)) as it was utilized by other algorithms multiple times and suited our situation. 

### 2. Data Processing

Although there was little to modify because the data set was preprocessed, it needed additional development processes such as data type unification and drug-drug, drug-protein, and protein-protein map separately as it was improved to a more efficient model (described in #3) during development. 

### 3. Algorithm Utilization/Model

![Alt text](/path/to/tipmodel.jpg)
