# heart-failure-prediction

Trong project này, tôi sử dụng Random Forest và Logistic Regression để dự đoán những người có nguy cơ suy tim.

**Thông tin dataset**

[Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction) là bộ dữ liệu được khảo sát trên 918 người khác nhau. Với mục tiêu là dựa vào dữ liệu của những người này để dự đoán họ có bị suy tim hay không. Bộ dữ liệu gồm 11 biến đầu vào như sau:

- Age: tuổi của bệnh nhân.
- Sex: giới tính của bệnh nhân.
- ChestPainType: kiểu đau ngực.
- RestingBP: huyết áp (mm/Hg).
- Cholesterol: nồng độ cholesterol (mm/dl).
- FastingBS: lượng đường trong máu (mg/dl).
- RestingECG: kết quả điện tâm đồ lúc nghỉ.
- MaxHR: nhịp tim tối đa đạt được.
- ExerciseAngina: đau thắt ngực do tập thể dục.
- Oldpeak: đoạn ST trong kết quả điện tâm đồ.
- ST_Slope: độ dốc đoạn ST khi tập thể dục.

Biến mục tiêu là HeartDisease với 0 (bình thường) và 1 (suy tim). Bình thường là negative class và suy tim là positive class.
