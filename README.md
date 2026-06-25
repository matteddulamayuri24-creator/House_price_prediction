
# 🏠 House Price Prediction Using Machine Learning
## Author
Name: Matteddula Mayuri

College: Sri Venkateswara College of Engineering

Internship: Machine Learning Internship

Task Number: Task 1 – House price prediction


## Model File

The trained model file exceeds GitHub's upload limit.

Google Drive Link:
https://drive.google.com/file/d/1i4wg4eUsd2AFza1wnXCP8hlQbgoiPtr7/view?usp=sharing


## 📌 Project Description

House price prediction is one of the most common regression problems in machine learning. The objective of this project is to build a machine learning model that predicts house prices based on various house characteristics such as area, number of bedrooms, bathrooms, floors, year built, and other features.

This project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis, visualization, model training, evaluation, and prediction.

---

# 🎯 Objective

The primary objective of this project is to:

* Analyze the house price dataset.
* Perform exploratory data analysis (EDA).
* Visualize relationships between different features.
* Apply data preprocessing techniques.
* Train multiple machine learning models.
* Evaluate model performance using regression metrics.
* Predict house prices using the trained model.
* Save the trained model for future use.

---

# 📂 Dataset Information

The dataset contains various house features and the corresponding selling prices.

### Features:

| Feature       | Description                |
| ------------- | -------------------------- |
| date          | Date of sale               |
| bedrooms      | Number of bedrooms         |
| bathrooms     | Number of bathrooms        |
| sqft_living   | Living area in square feet |
| sqft_lot      | Lot area in square feet    |
| floors        | Number of floors           |
| waterfront    | Waterfront availability    |
| view          | View rating                |
| condition     | House condition            |
| sqft_above    | Area above ground          |
| sqft_basement | Basement area              |
| yr_built      | Year built                 |
| yr_renovated  | Year renovated             |
| street        | Street name                |
| city          | City                       |
| statezip      | State ZIP code             |
| country       | Country                    |
| price         | Target variable            |

---

# 🛠 Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

---

# 📊 Exploratory Data Analysis

The following analyses were performed:

* Dataset preview using `head()`
* Dataset information using `info()`
* Statistical summary using `describe()`
* Missing value analysis
* Feature relationship analysis

---

# 📈 Data Visualization

The following visualizations were generated:

1. Histogram of house prices
2. Scatter plot of living area vs price
3. Box plot of house prices
4. Pair plot of important numerical features
5. Residual analysis plot

---

# ⚙ Data Preprocessing

The following preprocessing steps were performed:

* Checked missing values
* Identified categorical columns
* Converted categorical values using Label Encoding
* Separated features and target variables
* Split the dataset into training and testing sets

Training Data: 80%

Testing Data: 20%

---

# 🤖 Machine Learning Models Used

## 1. Linear Regression

A basic regression model used as the baseline model.

## 2. Random Forest Regressor

An ensemble learning model that combines multiple decision trees.

## 3. Gradient Boosting Regressor

A boosting algorithm that improves prediction accuracy by combining weak learners.

---

# 📏 Evaluation Metrics

The models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

### Linear Regression Results

* MAE: 207816.83
* RMSE: 993048.58

---

# 📉 Residual Analysis

Residual analysis was performed to examine prediction errors.

Residual = Actual Price − Predicted Price

The residual plot helps determine how well the model fits the data.

---


# 🔮 Sample Prediction

```python
sample = X.iloc[[0]]
prediction = rf.predict(sample)

print(prediction[0])
```

Predicted Price:

```text
324862.41
```

---

# 📁 Project Structure

House_Price_Prediction/

│

├── Housepriceprediction.ipynb

├── README.md

├── executive_summary.pdf

├── screenshots/

│   ├── dataset_head.png

│   ├── histogram.png

│   ├── scatter_plot.png

│   ├── boxplot.png

│   ├── pairplot.png

│   ├── model_evaluation.png

│   ├── residual_analysis.png

│   └── prediction_output.png

│

└── house_model.pkl

---



# 📦 Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```



---

# 👩‍💻 Author

**Mayuri Matteddula**

B.Tech Student

Artificial Intelligence and Machine Learning

---

# ✅ Conclusion

This project successfully predicts house prices using machine learning techniques. Multiple regression algorithms were implemented and compared. The trained model can estimate house prices based on various housing features and can be used for future prediction tasks.
