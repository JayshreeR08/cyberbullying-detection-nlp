Cyberbullying Detection using NLP

Overview


This project focuses on building a multiclass cyberbullying detection system using Natural Language Processing (NLP) techniques. The goal is to classify tweets into different cyberbullying categories based on their content. The project demonstrates a complete machine learning pipeline, starting from raw text data to model training and evaluation.


Problem Statement

Cyberbullying on social media platforms has become a serious concern, causing emotional and psychological harm to individuals. Automatically detecting and categorizing cyberbullying content can help platforms moderate harmful interactions more effectively. This project aims to identify various forms of cyberbullying in tweets using machine learning techniques.


Dataset


Dataset: Cyberbullying Classification Dataset (Twitter)
Total samples: ~47,000 tweets
Classes: 6 (age, ethnicity, gender, religion, other_cyberbullying, not_cyberbullying)
The dataset is balanced, ensuring fair representation across all classes.


Methodology



The following steps were implemented in this project:

Data Exploration
Understanding class distribution
Inspecting text samples
Text Preprocessing
Lowercasing text
Removing URLs, mentions, punctuation, and special characters
Handling noise and repeated characters
Feature Extraction
TF-IDF Vectorization
Use of unigrams and bigrams
Vocabulary size tuning for better contextual understanding


Model Training

Logistic Regression classifier
Class balancing to handle ambiguous categories
Evaluation
Accuracy score
Precision, Recall, and F1-score

Confusion Matrix for class-wise analysis


Results

The model achieved strong performance across most cyberbullying categories, particularly in detecting explicit forms of abuse such as age, religion, and ethnicity-related bullying. Some ambiguity remains in distinguishing non-cyberbullying and other-cyberbullying content, which is a known challenge in text classification tasks.


Technologies Used

Python
Pandas, NumPy
Scikit-learn
Matplotlib
Natural Language Processing (NLP)

How to Use

Clone the repository
Open the notebook in Jupyter or Kaggle
Run all cells sequentially to reproduce results

Future Improvements

Experiment with character n-grams
Try advanced classifiers such as Linear SVM
Explore word embeddings or transformer-based models
Improve performance on ambiguous classes

Kaggle Notebook
https://www.kaggle.com/code/jayshreerathore/cyberbullying-detection-from-tweets

Conclusion

This project demonstrates the practical application of NLP and machine learning for real-world text classification problems. It serves as a solid foundation for further experimentation with advanced models and techniques in cyber safety and content moderation.



