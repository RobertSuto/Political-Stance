# P-stance Analysis

P-stance Analysis is a Natural Language Processing technique used to analyze and categorize text data based on political ideologies or beliefs. This project provides an example dataset of tweets related to the 2020 US Presidential Election, which are categorized as either "Pro" or "Against" a particular candidate.

## Dataset

The dataset is organized based on the candidates: Donald Trump, Bernie Sanders, Joe Biden. Each president has its own training and testing dataset, each containing 6500 and 800 tweets each. Each row of the dataset contains 3 columns:

- Tweet: A tweet concerning a user’s view on the certain candidate.
- Target: The target, being one of the candidates.
- Stance: Represented by the tweet’s opinion: Either in Favor or Against the certain candidate.

## Preprocessing

The dataset is preprocessed using various techniques such as stemming, removing mentions, and unidecoding the text. The processed data is then used to train five different models, including Support Vector Machine, Logistic Regression, Knn Neighbors, Multinomial Naive Bayes, and Decision Tree Classifier.

## Exploratory Data Analysis

The project also includes exploratory data analysis using graphs and wordclouds to visualize the dataset. The results show that there were more tweets against Donald Trump compared to Bernie Sanders or Joe Biden.

## Model Scope

The scope of the model is to conclude if a tweet is either in favor or against, no matter the candidate it is tweeted at and without using that as a feature. This adds complexity to the way features are separated in the training part of the project, as it lacks crucial information in which it can build on.

## Conclusion

Overall, this project demonstrates the application of P-stance Analysis in politics, marketing, and social media analysis. It provides an example dataset and explains the scope of the model.
