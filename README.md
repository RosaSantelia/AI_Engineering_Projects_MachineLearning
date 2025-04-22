# AI_Engineering_Projects_MachineLearning
My AI Engineering Master's Projects - Machine Learning Fundamentals Module

# 🧠 RealEstateAI Solutions: A Predictive Model for the Housing Market

**RealEstateAI Solutions** aims to optimize real estate price assessment by applying advanced **regularization techniques** within linear regression models. The goal is to provide **more accurate and reliable price predictions**, reducing overfitting and improving the model’s ability to generalize to unseen data.

In the real estate sector, precise property price estimates are crucial for informed decision-making. However, traditional linear regression models often suffer from **overfitting**, which undermines predictive accuracy. Therefore, it is necessary to explore **effective regularization methods** to improve predictive performance while managing model complexity.

By implementing and comparing regularized models like **Lasso**, **Ridge**, and **Elastic Net**, RealEstateAI Solutions provides a system capable of delivering **more stable and precise housing price predictions**. This enables real estate agents and investors to make data-driven decisions and gain a competitive edge in the market.

---

## 📌 Project Requirements

### 🛠️ Dataset Preparation
- Load and preprocess housing price data.
- Handle missing values, encode categorical variables, and normalize/scale the data.

### 🧪 Regression Model Implementation
- **Ridge Regression**: Train a model with L2 regularization.
- **Lasso Regression**: Train a model with L1 regularization.
- **Elastic Net Regression**: Train a model with a combination of L1 and L2 regularization.

### 📊 Performance Evaluation
- Apply **cross-validation** techniques.
- Calculate **Mean Squared Error (MSE)** for each model.
- Compare model complexity by evaluating the number of non-zero coefficients.
- Analyze and compare the results of the different regularization approaches.

### 📈 Results Visualization
- Generate plots to visualize and compare model performance.
- Plot residuals to assess model fit.

The project includes **fully commented source code**, with clear explanations of each step, design choice, and outcome — ensuring transparency and reproducibility.

---

## 📂 Dataset

- Publicly available at:  
  [housing.csv](https://proai-datasets.s3.eu-west-3.amazonaws.com/housing.csv)  
  *(based on this [Kaggle dataset](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset))*

### 🏷️ Feature Description

| Feature             | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| `Price`             | Property price (target variable)                                            |
| `Area`              | Total property area                                                         |
| `Bedrooms`          | Number of bedrooms                                                          |
| `Bathrooms`         | Number of bathrooms                                                         |
| `Stories`           | Number of floors                                                            |
| `Mainroad`          | 1 if the house is on the main road, 0 otherwise                             |
| `Guestroom`         | 1 if the house includes a guest room, 0 otherwise                           |
| `Basement`          | 1 if the house includes a basement, 0 otherwise                             |
| `Hotwaterheating`   | 1 if the house has hot water heating, 0 otherwise                           |
| `Airconditioning`   | 1 if the house has air conditioning, 0 otherwise                            |
| `Parking`           | Number of parking spots                                                     |
| `Prefarea`          | 1 if the house is in a prestigious area, 0 otherwise                        |
| `Furnishingstatus`  | 0: Unfurnished, 1: Semi-furnished, 2: Fully-furnished                       |
