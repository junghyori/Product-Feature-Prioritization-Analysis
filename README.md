# Product-Feature-Prioritization-Analysis

This repository is part of an ongoing thesis project focused on conducting a feature prioritization analysis of Disneyland based on visitor reviews sourced from the TripAdvisor platform.

## Dataset Information

The analysis operates on two specific datasets:

- **Original Dataset (`DisneylandReviews.csv`)**: This dataset encompasses a comprehensive collection of visitor reviews from the TripAdvisor platform, serving as the foundational data for the main analysis.

- **Evaluation Sampled Dataset (`Evaluation Sampled Data.csv`)**: For the purpose of evaluation, a subset of reviews from the original dataset has been extracted. This sampled dataset facilitates a comparison between the outcomes of the automated extraction process and manual extraction, affirming the model's robustness and validity.

> The dataset used in this study was sourced from Kaggle. You can access the dataset [here](https://www.kaggle.com/datasets/arushchillar/disneyland-reviews).

## Jupyter Notebook

The provided Jupyter notebook is systematically organized into several sections:

### 1. Text Preprocessing

Here, the data is prepared for analysis through various preprocessing steps such as tokenization, stopword removal, lemmatization, and other text-cleaning techniques.

### 2. Feature Extraction

This section employs a range of Natural Language Processing (NLP) techniques, including topic modelling and POS tagging, to discern and extract key features from the visitor reviews. These extracted features capture the diverse aspects of the Disneyland experience as reflected in the sentiments and observations of the visitors.

### 3. Priority Analysis

After extracting the features, this section is dedicated to their analysis and prioritization. Their significance is determined based on factors like relevance, frequency, and sentiment scores. The deep analysis aids in highlighting the most important features which could be pivotal in enhancing the Disneyland visitor experience.

### 4. Evaluation

An additional Jupyter notebook housed in the repository concentrates on the evaluation of the methodology used in the study. Topics covered include data sampling, contrasts between manual vs. automated feature extraction, and ranking comparisons. This evaluation sheds light on the methodology's effectiveness and its alignment with manual processes.

## Copyright Notice

All users are advised that the entirety of this project, including all its components, remains the exclusive intellectual property of the author. Any unauthorized replication, use, or distribution without prior written consent is strictly prohibited.

## Contact

For any further queries, issues, or feedback, please direct communications to gracejeonghyeon@gmail.com.

For a comprehensive understanding of this repository's offerings and a deep dive into the methodologies and insights, users are encouraged to refer to the full research paper associated with this project.
