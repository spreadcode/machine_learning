Implementation of https://www.kaggle.com/c/ieee-fraud-detection using Python. Runs on GCP.

Goal: detect online credit card fraud. I implemented some data visualization to explore the data. Next, I decided to use a Deep Learning model. For this, I did some feature engineering, followed by implementing a basic Deep Learning model.

Data: the sponsors gave test and training data

Implementation:

-Basic, 3-layer Deep learning model that ran on GCP using 8 CPUs and 1 GPU.

-ROC AUC of 0.85 using 10 epochs. Finished in 5-7 minutes

-More in the notebook under code/final_submission.ipynb
