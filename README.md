 Task 6 - K-Nearest Neighbors (KNN) Classification

This repository contains the implementation of the K-Nearest Neighbors (KNN) classification algorithm using the **Iris dataset**, completed as part of the AI & ML Internship by Elevate Labs (Ministry of MSME, Govt of India).

 Objective

- Understand how KNN works
- Normalize features for distance-based algorithms
- Implement KNN with different values of K
- Evaluate performance using accuracy and confusion matrix
- Visualize decision boundaries

 Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

 Dataset Used

- **Name**: Iris Dataset  
- **File**: `Iris.csv`  
- **Source**: UCI Machine Learning Repository  
- **Features**:
  - SepalLengthCm
  - SepalWidthCm
  - PetalLengthCm
  - PetalWidthCm
  - Species (Target)

 Steps Performed

1. Loaded the `Iris.csv` dataset and removed unnecessary columns
2. Encoded the `Species` column using `LabelEncoder`
3. Normalized all feature values using `StandardScaler`
4. Split the data into training and test sets (70:30 ratio)
5. Trained KNN models for K = 1 to 10
6. Chose the best K based on accuracy score
7. Evaluated final model using:
   - Accuracy
   - Confusion Matrix
   - Classification Report
8. Visualized decision boundaries using the first two features

 Output Samples

-  **Best K Value**: Automatically chosen based on highest accuracy
-  **Accuracy Plot**: K vs Accuracy
-  **Confusion Matrix** & Classification Report
-  **Decision Boundary Visualization** (2 features)

 Interview Prep (Q&A Covered)

- How KNN algorithm works
- Choosing the right value of K
- Importance of normalization in KNN
- Time complexity of KNN
- Pros and cons of KNN
- Sensitivity to noise
- Handling multi-class classification
- Distance metrics in KNN

 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/knn-iris-task.git
   cd knn-iris-task
