**Iris Flower Species Classification Project:**

1. **Data Loading and Overview:**
   - Imported necessary libraries: pandas, numpy, matplotlib, seaborn, plotly express.
   - Loaded the Iris dataset using `pd.read_csv()`.

2. **Exploratory Data Analysis (EDA):**
   - Checked basic dataset information using `df.info()` and statistical summaries with `df.describe()`.
   - Examined the presence of missing values using `df.isna().sum()`.
   - Visualized class distribution using `sns.countplot()`.

3. **Feature Engineering:**
   - Encoded categorical target variable ('Species') using LabelEncoder.
   - Identified and handled outliers using the Interquartile Range (IQR) method.

4. **Data Standardization:**
   - Applied StandardScaler to normalize feature values.

5. **Feature Selection and Linearity:**
   - Explored feature correlations through a heatmap using `sns.heatmap()`.
   - Selected features for model training based on correlation analysis.
   - ![H1](https://github.com/Rutuja-Salunke/Iris-Flower-Species-Classification/assets/102023809/7ec99c7a-954d-403b-88a3-6eb094532ad5)


6. **Model Training (Logistic Regression):**
   - Split the data into training and testing sets using `train_test_split()`.
   - Trained a Logistic Regression model using `LogisticRegression()`.

7. **Model Evaluation (Logistic Regression):**
   - Assessed the model's accuracy on both training and testing sets.
   - Utilized metrics such as accuracy score, confusion matrix, and classification report.

8. **Model Training (Decision Tree):**
   - Trained a Decision Tree Classifier using `DecisionTreeClassifier()`.

9. **Model Evaluation (Decision Tree):**
   - Evaluated the Decision Tree model on training and testing sets.
   - Examined accuracy, confusion matrix, and classification report.
   - ![DT1](https://github.com/Rutuja-Salunke/Iris-Flower-Species-Classification/assets/102023809/478416b7-459d-4a01-9046-0ca9d27896f7)

10. **Hyperparameter Tuning (RandomizedSearchCV):**
    - Performed hyperparameter tuning for Decision Tree using `RandomizedSearchCV()`.

11. **K-Nearest Neighbors (KNN):**
    - Introduced K-Nearest Neighbors as an alternative classification approach.

12. **Visualization:**
    - Plotted decision boundaries for Logistic Regression.

13. **Project Impact:**
    - Demonstrated a step-wise approach to iris species classification, incorporating data exploration, preprocessing, model training, and visualization techniques.
