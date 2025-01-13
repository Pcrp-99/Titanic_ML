## Titanic Machine Learning from Kaggle
This project predicts passenger survival on the RMS Titanic using a Random Forest model and GridSearchCV for hyperparameter tuning, implemented in a Jupyter Notebook.

### Tools Used
- Jupyter Notebook
- scikit-learn
  - RandomForestClassifier
  - GridSearchCV
  - SimpleImputer
  - OneHotEncoder
  - StandardScaler
  - Pipeline
- Pandas 
- Seaborn

### Dataset
[Kaggle - Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)

### Project Structure
The project likely consists of a Jupyter Notebook with the following steps:

1. Data Loading and Exploration:
    - Load the Titanic dataset from Kaggle.
    - Explore the data to understand its features and correlation.
2. Data Cleaning and Preprocessing:
    - Handle missing values using SimpleImputer (e.g., imputation, deletion).
    - Encode categorical features (one-hot encoding).
    - Scale numerical data. (StandardScaler)
    - Build Pipeline.
3. Model Building:
    - Define a Random Forest classifier.
    - Use GridSearchCV to tune hyperparameters of the Random Forest model (e.g., number of trees, maximum depth).
4. Model Training and Evaluation:
    - Split the data into training and testing sets.
    - Train the Random Forest model on the training set.
    - Evaluate the model's performance on the testing set.
5. Export and Submit Prediction
    - Export the prediction file as csv.
    - Submit to Kaggle.

### Submission

![image](https://github.com/user-attachments/assets/147da5c3-79fd-456d-b559-cbd70c1cf062)

