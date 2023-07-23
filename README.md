Module 20 Report

## Credit Risk Analysis Overview
For this challenge, I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Results

1. Machine Learning Model 1:
  * Using the logistical regression model with the original data, the model identifies healthy loans with very high precision and recall. That means that it is identifying true positives and has a low false negative rate. The model is not as good at predicting high-risk loans, with an 85% precision and 91% recall.

1. Machine Learning Model 2:
  * Using the logistic regression model with resampled training data, the model also identifies healthy loans with very high precision and recall. That means that it is identifying true positives and has a low false negative rate. The model is not as good at predicting high-risk loans, with an 85% precision rate, but has a low false negative rate for high-risk loans, which makes it a more accurate model than the first.

## Summary
My recommendation would be to utiliza the second model, using the resampled training data. Although the precision and recall of low-risk loans is equally impressive in both models, high-risk loans were identified with more success in the second model. Recall improved in model 2, with a recall of 99% for false-negative high-risk loans. Although it is important to classify both high and low risk loans appropriately, the organization should go with a model that has a lower change of predicting high-risk loans, so as to avoid the number of loan applicants who default, in turn saving the company money.

### Acknowledgements
I used the following resources to help complete this project:

* AskBCS Learning Assistants
* GitHub
* UCB Coding Bootcamp GitLab
* ChatGPT
* Bootcamp Tutor David Chao
* W3 Schools
