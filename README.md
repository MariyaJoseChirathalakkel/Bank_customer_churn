# Bank_customer_churn

The dataset utilized in this study was sourced from Kaggle, specifically the dataset titled "Predicting churn for bank customers."The aim of the study was to determine the most effective machine learning methodology for accurately identifying clients who have a higher probability of churning.A total of seven distinct strategies were employed in the training process of the dataset.This also involves several methodologies for partitioning the data into training and testing datasets.In order to do the coding, Google Colab was utilized.The model was trained using Python 3.7.1, and the necessary packages are shown below.


<img width="393" alt="Screenshot 2023-09-30 at 15 29 10" src="https://github.com/MariyaJoseChirathalakkel/Bank_customer_churn/assets/57436144/d39991e9-1bf3-40f1-8bc4-2d6a8ccec086">

Presented below is the data dictionary, which serves as a valuable resource for comprehending all of the data variables.

<img width="938" alt="Screenshot 2023-09-30 at 15 54 25" src="https://github.com/MariyaJoseChirathalakkel/Bank_customer_churn/assets/57436144/9e52f49a-1edb-43b7-9c5b-fd37af9fc7ba">

Two ratios, namely 80:20 and 70:30, were employed to partition the data into training and testing sets. Two distinct sampling strategies, namely simple random sampling and stratified random sampling, were employed to collect and subsequently partition the data. The study included hyper-parameter tweaking using GridSearchCV for each machine learning technique utilised.The figure below displays the evaluation histogram of the most optimal models that were selected.

<img width="970" alt="Screenshot 2023-09-30 at 16 03 59" src="https://github.com/MariyaJoseChirathalakkel/Bank_customer_churn/assets/57436144/08c4378e-7773-4f1d-9e39-2acdcaf56ade">

