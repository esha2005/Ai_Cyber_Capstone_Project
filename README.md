# Machine Learning Techniques for Cyber Security

## Network Intrusion Detection using NSL-KDD Dataset

### 1. Project Overview
This project focuses on detecting network intrusions using Machine Learning techniques. It uses the NSL-KDD dataset to classify network traffic into normal and different attack categories.

Three supervised machine learning algorithms are implemented and compared:
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

### 2. Objectives
- Understand and analyze network traffic data.
- Identify normal and malicious network activities.
- Apply machine learning algorithms for intrusion detection.
- Compare model performance using evaluation metrics.
- Identify the best-performing classification algorithm.

### 3. Dataset
**Dataset Name:** NSL-KDD

**File Used:** KDDTrain+.txt

**Dataset Source:** [NSL-KDD GitHub Repository](https://github.com/defcom17/NSL_KDD)

Dataset Details:
- Total Records: 125,973
- Total Columns: 43
- Input Features: 41
- Target Classes: 23
- Missing Values: 0

### 4. Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### 5. Machine Learning Algorithms

**Decision Tree:** A tree-based classification algorithm used to identify patterns in network traffic.

**Random Forest:** An ensemble learning algorithm that combines multiple decision trees to improve prediction performance.

**Support Vector Machine (SVM):** A supervised learning algorithm used to classify network traffic using a linear decision boundary.

### 6. Data Preprocessing
The following preprocessing steps were performed:
- Separated input features and target labels.
- Converted target labels into numerical values using Label Encoding.
- Converted categorical features using One-Hot Encoding.
- Split the dataset into 80% training and 20% testing data.
- Applied feature scaling for SVM.

### 7. Model Performance

| Algorithm | Accuracy |
|---|---:|
| Decision Tree | 99.77% |
| Random Forest | 99.84% |
| SVM | 99.00% |

**Best Performing Model:** Random Forest with 99.84% accuracy.

### 8. Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 9. Results and Conclusion
The experimental results show that Random Forest achieved the highest accuracy of 99.84%, followed by Decision Tree with 99.77% and SVM with 99.00%.

Therefore, Random Forest performed best
