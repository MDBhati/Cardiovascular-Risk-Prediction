# Cardiovascular-Risk-Prediction

This project uses machine learning on the Framingham Heart Study dataset to predict 10-year cardiovascular disease risk. Classification algorithms are employed, and important risk factors identified. The model aids healthcare professionals in identifying high-risk individuals and taking preventive measures.

## Project Overview
The primary objective of this project is to construct a machine learning model capable of forecasting an individual's 10-year risk of developing cardiovascular disease. This will be accomplished by leveraging a dataset comprising demographic, clinical, and laboratory information.

The dataset employed in this endeavor is sourced from the Framingham Heart Study, a widely utilized resource for cardiovascular risk assessment. This dataset encompasses details from 3,390 participants, who were closely monitored for a decade to monitor occurrences of cardiovascular events. It encompasses a total of 17 variables, encompassing factors such as age, gender, blood pressure, cholesterol levels, smoking habits, and diabetes status.

The initial phase of the project involves data preprocessing, which encompasses addressing missing data, encoding categorical variables, and normalizing numerical data. Following preprocessing, the dataset undergoes a division into training and testing subsets, employing a 80:20 ratio.

Diverse machine learning algorithms are subsequently applied to the training data, including logistic regression, K-nearest neighbors (KNN), XGBoost, Support Vector Classifier (SVC), random forest. These algorithms were selected due to their documented efficacy in cardiovascular risk prediction. The models are trained using the training data, and their performance is meticulously assessed using the testing data.

## Evaluation Metrics
The evaluation metrics used in this project include Accuracy, Precision, Recall, and the area under the receiver operating characteristic curve (AUC-ROC). These metrics help in assessing the performance of the machine learning model.

## Results
The results show that XGBoost performs the best among the tested algorithms, with an accuracy of 0.89, precision of 0.91, recall of 0.87, and AUC-ROC of 0.89. This indicates that the model has a good overall performance in predicting cardiovascular risk.

## Conclusion
In conclusion, this project demonstrates the effectiveness of machine learning techniques in predicting cardiovascular risk using the Framingham Heart Study dataset. The developed machine learning model can be used by healthcare professionals to identify individuals at high risk of cardiovascular disease and take preventive measures to reduce the risk. Early prediction of cardiovascular risk can contribute to timely intervention and improve patient outcomes.
