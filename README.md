# Stroke-Risk-Prediction
## Introduction to dataset
Data pulled on Kaggle has URL: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset 

This dataset is taken from the kaggle site containing data on patients who have or have not had a stroke and related information such as gender, age, underlying diseases and marital status, and whether they smoke. no, … Each row in the data provides relevant information about the patient.
The data set consists of 5110 rows and 12 columns, of which 11 columns contain variables useful for analysis and the id column is unnecessary.

![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/50bde881-4d4c-445b-aeed-a3ab58bd9f50)

## Data visualization (EDA)
![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/df07b1d1-11c0-4735-a9f7-372f8a364edc)

![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/8a71939d-74ea-4ec4-9a77-193df2dacab2)

In terms of rate, the self-employed and self-employed both have a high number of people with strokes. However, people from the government were less likely to have a stroke than the above two groups, and children were also not more likely to have a stroke. Perhaps that can be explained by the level of pressure on workers


![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/fd2c657f-fbec-42c2-b500-e0bd788a6677)

From the charts above, it can be concluded that people with stroke have higher age, sugar levels and body mass index than people without the disease.

### Support Vector Machine (SVM)

![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/7686833d-c0c8-44aa-b865-34e56d5dfa95)

### Random Forest

![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/ef34e8d3-9b4a-4303-bfb8-3360b8105ace)

### K-Nearest Neighbors

![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/df27a50e-72ab-4890-a066-12299f09a086)

### Decision Tree and Pytorch

![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/1f6036b3-2325-4469-beb7-9a96453a15f1)

### Logistic Regression
![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/0f53c37a-f332-430c-92a5-5e0dca6ffdcc)

![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/115d7b7c-4414-4d34-ad6b-58f1742611aa)

![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/71020ab0-88cc-4d2b-8dc2-165273e0f32b)

### Extreme Gradient Boosting (XGBoost)
![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/3e39822b-818e-4800-9110-8e98a4f5ac30)

![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/9e815870-db95-4c12-a2c0-c011aa231da0)

![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/38a5fd4f-7d08-4bf0-a461-b0bc9878f972)


## Conclude: 

![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/92aedaf5-af92-4aad-a327-801bac2fd15b)

• SVM (Support Vector Machine): The SVM model achieved very good results on evaluation indicators with 95.22% accuracy, 99.58% positive accuracy, 90.78% sensitivity and F1 score 94.98%. This is the highest performing model among the tested models.

• Random Forest: Although Random Forest's accuracy is also quite high at 95.23%, other indicators such as positive accuracy 28.57%, sensitivity 3.45% and F1 score 6.15% are similar. relatively low. This suggests that the model has limited ability to detect positive cases.

• KNN (K-Nearest Neighbors): Similar to Random Forest, KNN has an overall accuracy of 95.05% but other indicators such as positive accuracy 63.64%, sensitivity 3.89% and F1 score 7.33% is also low. This shows that the KNN model cannot fully detect positive cases.

• PyTorch Model: ANN achieved relatively good results with 90.5% accuracy, 88.57% positive accuracy, 93% sensitivity and 90.73% F1 score. This model can balance well between accuracy and sensitivity.

• Decision Tree: Decision Tree achieved relatively good results with 88.99% accuracy, 85.42% positive accuracy, 94.52% sensitivity and 89.73% F1 score.

• Logistic Regression: Logistic Regression model has relatively poor results with 75.73% accuracy, 14.12% positive accuracy, 69.09% sensitivity and 23.54% F1 score. This is the model with the lowest performance among the models tested.

• XGBoost: XGBoost achieves 86.89% accuracy, 19.37% positive precision, 45.45% sensitivity, and 27.17% F1 score. The results of this model are not really impressive.

• Overall, the SVM model has given very good results and may be the optimal choice for the stroke prediction problem. Models such as ANN, Random Forest and KNN also have potential and can be further improved.

Based on the overall metrics, the SVM model appears to have the best prediction performance, with the highest metrics for accuracy, precision, and F1 score. Score). Although ANN has the highest recall, other metrics of ANN are lower than SVM.

Therefore, the SVM model is considered to be the model with the most accurate prediction in this case.
