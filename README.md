# ML-Cases-ESG-Document-Classifier
OxML 2023 | ML Cases | ESG Document Classifier
Build an ESG document classifier that can take a document as an input, classify each page to be either E,S or G related

## Introduction:
In a rating agency, your goal is to build an ESG document classifier that can take a document as an input, classify each page to be either E,S or G related. The business wants your approach to beat an existing baseline that results in 90% F-score, while having a strong 95% on environmental content.
We built a Deep Learning BERT classifier model wherein we used the BERT Tokenizer.
The model consists of 2 parts: feature extractor and classifier. Before training we used data preprocessing, augmentation and lemmatization, stemming on the unstructured data.

## Results:
Our best public score was 0.80392 using this setting and our best private score was 0.87, giving us 15th place on the leaderboard.
Reference: https://www.kaggle.com/competitions/oxml2023mlcases-esg-classifier

## Files
* sample_submission.csv - a sample submission file in the correct format with all the page ids on which you should provide a prediction
* labels.csv - the labels to train your model
* reports/*.pdf - ESG reports from both training and testing set
* Main notebook - nlp-esg-classifier.ipynb
* Output folders contains our best prediction outputs.

