# Stroke-Risk-Prediction
### Giới thiệu về dataset 
Dữ liệu được lấy trên Kaggle có URL: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset 
Bộ dữ liệu này được lấy từ trang kaggle chứa dữ liệu các bệnh nhân có bị đột quỵ hoặc là không bị đột quỵ và các thông tin liên quan như giới tính, tuổi tác, các bệnh nền và tình trạng hôn nhân, có hút thuốc không, … Mỗi hàng trong dữ liệu cung cấp thông tin liên quan về bệnh nhân.
Bộ dữ liệu gồm 5110 hàng và 12 cột, trong đó gồm 11 cột chứa biến có ích cho việc phân tích và cột id là không cần thiết.
![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/50bde881-4d4c-445b-aeed-a3ab58bd9f50)

## Trực quan hóa dữ liệu (EDA)
![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/df07b1d1-11c0-4735-a9f7-372f8a364edc)

![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/8a71939d-74ea-4ec4-9a77-193df2dacab2)

Xét về tỷ lệ, tư nhân và tự kinh doanhn đều có số lượng người bị đột quỵ cao. Tuy nhiên, những người từ chính phủ có khả năng ít bị đột quỵ hơn 2 nhóm trên và trẻ em cũng không có nhiều khả năng bị đột quỵ. Có lẽ điều đó có thể được giải thích do mức độ áp lực của người lao động


![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/fd2c657f-fbec-42c2-b500-e0bd788a6677)

Từ những biểu đồ trên, có thể kết luận được những người bị đột quỵ có độ tuổi, lượng đường và chỉ số cơ thể cao hơn so với người không mắc bệnh.

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


# Kết luận: 

![image](https://github.com/tansuong2003/Stroke-Risk-Prediction/assets/88469624/92aedaf5-af92-4aad-a327-801bac2fd15b)

Dựa trên tổng thể các chỉ số, mô hình SVM có vẻ là mô hình có hiệu suất dự đoán tốt nhất, với các chỉ số cao nhất về độ chính xác (Accuracy), độ chính xác (Precision), và điểm F1 (F1 Score). Mặc dù ANN có recall cao nhất, nhưng các chỉ số khác của ANN thấp hơn SVM.
Vì vậy, mô hình SVM được đánh giá là mô hình có dự đoán chính xác nhất trong trường hợp này.
