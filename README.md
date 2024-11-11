# Wine Quality Prediction

This project predicts the quality of wine based on various physicochemical attributes using a machine learning model. The dataset used for this project contains information about red wine characteristics, and the model used is a Random Forest Classifier.

## Libraries Used

- **NumPy**: For numerical operations
- **Pandas**: For data manipulation and analysis
- **Matplotlib & Seaborn**: For data visualization
- **scikit-learn**: For machine learning model building and evaluation

## Dataset

The dataset used is the **Wine Quality** dataset, which contains 1599 instances of red wine data with 12 features:
- `fixed acidity`
- `volatile acidity`
- `citric acid`
- `residual sugar`
- `chlorides`
- `free sulfur dioxide`
- `total sulfur dioxide`
- `density`
- `pH`
- `sulphates`
- `alcohol`
- `quality` (Target variable)

### Example Data:
| fixed acidity | volatile acidity | citric acid | residual sugar | chlorides | free sulfur dioxide | total sulfur dioxide | density | pH  | sulphates | alcohol | quality |
|----------------|------------------|-------------|-----------------|-----------|----------------------|----------------------|---------|-----|-----------|---------|---------|
| 7.4            | 0.70             | 0.00        | 1.9             | 0.076     | 11.0                 | 34.0                 | 0.9978  | 3.51| 0.56      | 9.4     | 5       |

## Steps in the Project

1. **Data Collection**:
   - The dataset is loaded from a CSV file.
   
2. **Exploratory Data Analysis (EDA)**:
   - Statistical summary and visualizations are performed to explore the dataset.
   - Inferences are made about correlations between attributes (e.g., acidity and wine quality).
   
3. **Data Preprocessing**:
   - The target variable `quality` is binarized (good or bad wine).
   - Features are separated from the target, and the data is split into training and testing sets.

4. **Model Training**:
   - A **Random Forest Classifier** is trained on the training data.

5. **Model Evaluation**:
   - The accuracy of the model is evaluated on the test data.

6. **Prediction**:
   - A sample input is tested to predict wine quality.


##  Results

The model achieved an accuracy of approximately 93.13% on the test data. The quality prediction system can classify wine as "Good Quality Wine" or "Bad Quality Wine" based on its features.

## License

This project is open-source under the MIT License.
