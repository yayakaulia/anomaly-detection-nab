# anomaly-detection-nab
an anomaly detection on Ambient Temperature System Failure from NAB Kaggle Dataset.


This is an Anomaly Detection Machine learning Cases with NAB Kaggle Datasets. The Anomaly Detection is quite unique cases. You could approach it with Supervised and Unsupervised, and I choose using the Unsupervised Learning. For this Machine learning cases of Anomaly Detection, I use two Algorithm to detect the anomaly. K-means and Isolation Forest.


This datasets, contains only 2 feature, timestamp and value (Temperature). From there I did some feature engineering with the date, I also assume this is time-series analysis. The added feature are Year, Month, Day, Hours, Minutes. But it didn't quite of works when I tried with Isolation Forest I think, after I tried with or without it. But I still added anyway if there's anyone like to try.


The result is quite good, I must say, but not great. because it is sucessfully capture the outliers value and consider it as anomaly. The outliers are the temperature with lower value that far from the mean. it is also captured in the boxplot (the lower to lowest value) and considered it as ouliers. But, the thing that makes me said it is not great are some non-anomaly data points are considered as anomaly. It is not that many but it is close to the mean and far from the lower value I mentioned before.


This is the link to the Kaggle:

https://www.kaggle.com/datasets/boltzmannbrain/nab/code

please refer to this page to the main work:

https://github.com/yayakaulia/anomaly-detection-nab/blob/master/app/notebook/main_notebook.ipynb

And this to an Exploratory Data Analysis:

https://github.com/yayakaulia/anomaly-detection-nab/blob/master/app/notebook/EDA.ipynb
