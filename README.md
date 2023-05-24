---
# Natural Language Processing with Disaster Tweets
#### Predict which Tweets are about real disasters and which ones are not
---

### **Problem Statement**

Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

**In this [competition](https://www.kaggle.com/competitions/nlp-getting-started/overview), you’re challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. You’ll have access to a dataset of 10,000 tweets that were hand classified.**


### Data Fields

The [Dataset](https://www.kaggle.com/competitions/nlp-getting-started/data) for the Natural Language Processing with Disaster Tweets on Kaggle competition consists of tweets that are labeled as either referring to a real disaster or not. The dataset includes the following information:

- **Text:** The actual content of the tweet, which contains information about a particular event or incident.

- **Target:** The target variable indicating whether the tweet is about a real disaster (1) or not (0). This is the label that participants need to predict for the test set. In addition to the text and target variables, the dataset may also contain the following features, which can be used for analysis and modeling:

 - **Keyword:** A keyword or tag indicating the topic or theme of the tweet. This field may contain terms related to disasters, emergencies, or other relevant topics.

 - **Location:** The location from which the tweet was sent or refers to. This field may contain the name of a place, coordinates, or other location information.

In this notebook, the classification of disaster-related tweets was explored using various techniques. The notebook covered data preprocessing, feature engineering, and model development. The keyword and location features were analyzed, and meta features such as unigrams and trigrams were investigated. Text cleaning and embeddings were addressed, and mislabeled samples were handled. Cross-validation was employed for model evaluation. The BERT layer was utilized for contextual word representations, and the notebook concluded with saving preprocessed datasets. It provided a comprehensive approach to understanding and classifying disaster tweets.

We initialized a `DisasterDetector` object and trained the model with **10 epochs** using the specified parameters and the provided training data. The model achieved promising results, with a **validation precision of 0.863049, recall of 0.844368, and F1 score of 0.850105 in the 10th epoch.** The training process involved optimizing the loss function and monitoring the accuracy. The model exhibited an **accuracy of 0.8645** on the **training set and 0.8564** on the validation set, demonstrating its ability to effectively classify disaster-related tweets. 

This project showcases the effectiveness of leveraging advanced NLP techniques and BERT embeddings for tweet classification, contributing to the field of disaster response and crisis management.

**Disclaimer:** The dataset for this competition contains text that may be considered profane, vulgar, or offensive.

![Tweet-tweet](https://github.com/LavanyaMuthuraman/NLP-With-Disaster-Tweets/assets/109660074/1a346fbc-9b6c-42f8-bb8e-2af4fe89b797)
