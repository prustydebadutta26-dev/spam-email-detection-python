# Spam Email Detection Using Python

## 1. Project Overview

This project uses machine learning to classify text messages
as spam or ham (legitimate messages).

The model learns patterns from labelled messages and predicts
the category of previously unseen messages.

## 2. Dataset

Dataset: UCI SMS Spam Collection

Source:
https://archive.ics.uci.edu/dataset/228/sms+spam+collection

The dataset contains text messages labelled as spam or ham.

Note: This project uses SMS messages rather than a dataset
of full-length emails.

## 3. Technologies Used

- Python
- Pandas
- Scikit-learn
- TF-IDF
- Multinomial Naive Bayes
- Matplotlib

## 4. Project Workflow

1. Downloaded and loaded the dataset.
2. Explored the data using pandas.
3. Removed duplicate and invalid records.
4. Split the data into training and testing sets.
5. Converted text into numerical features using TF-IDF.
6. Trained a Multinomial Naive Bayes classifier.
7. Evaluated the model using classification metrics.
8. Tested the model on new messages.

## 5. Model Performance

Test accuracy: 96.71%

Spam precision: 1.00

Spam recall: 0.74

Spam F1-score: 0.85

Ham precision: 0.96

Ham recall: 1.00

Ham F1-score: 0.98

These results are based on the test split used in this project.

## 6. Key Learnings

- Data exploration and cleaning
- Text classification
- TF-IDF feature extraction
- Machine learning model training
- Model evaluation
- Confusion matrix analysis

## 7. Limitations

The model was trained on SMS messages.
Its performance on full-length emails or newer spam patterns
may differ.

The model missed some spam messages in the test set.

## 8. Future Improvements

- Experiment with alternative classification algorithms.
- Investigate methods to improve spam recall.
- Evaluate models using cross-validation.
- Test on additional labelled datasets.