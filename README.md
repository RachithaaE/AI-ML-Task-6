# AI-ML-Task-6
# Task 6: K-Nearest Neighbors (KNN) Classification
* Objective :
Understand and implement K-Nearest Neighbors algorithm for classification using the Iris dataset.
# Dataset :
- [Iris Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/iris)
#  Steps Performed :
. Data Loading 
   - Loaded iris.csv using Pandas from a local file path.
. Data Preprocessing
   - Split features (X) and target (y).
   - Encoded target labels to integers using factorize().
   - Normalized features using StandardScaler.
. Model Training
   - Used KNeighborsClassifier from Scikit-learn.
   - Tested different K values from 1 to 10.
   - Selected the best K based on test accuracy.
. Evaluation
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
. Visualization
   - Accuracy vs. K value graph
   - Decision boundary plot using first 2 features
#  Tools & Libraries :
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
# Output :
[K-NearestNeighborsClassificationTask6_Output.pdf](https://github.com/user-attachments/files/20994504/K-NearestNeighborsClassificationTask6_Output.pdf)


