# portfolio-part-4-Buchu97

🛒 **Supermarket Sales Analysis and Prediction** 📊

## Introduction 📚
In today's data-centric business environment, extracting meaningful insights from complex datasets is essential. This notebook dives deep into a supermarket sales dataset, applying techniques from linear regression to clustering and classification.

## Python Libraries Used 🐍
- pandas 🐼
- seaborn 🎨
- matplotlib 📊
- LinearRegression, PolynomialFeatures, RFE (from sklearn) 📈
- KMeans (from sklearn) 🌐
- train_test_split, mean_squared_error (from sklearn) 🚄
- StandardScaler, OrdinalEncoder, ColumnTransformer, Pipeline (from sklearn) 🔄

## Exploration and Analysis🧠
1. **Revenue Prediction**: Utilized linear and polynomial regression techniques to forecast 'revenue'.
2. **Feature Importance Analysis**: Determined influential features using Recursive Feature Elimination (RFE).
3. **Sales Trend and Customer Behavior Analysis**: Uncovered sales trends and customer segmentations through k-means clustering.
4. **Optimization of Clustering Parameters**: Determined the optimal number of clusters using the Elbow Method.
5. **Customer Type Classification**: Classified customers into 'Member' and 'Normal' groups using the K-Nearest Neighbors (KNN) algorithm.
6. **Model Assessment and Strategy Refinement**: Evaluated the performance of the applied techniques to draw actionable insights.
   
## Results Summary ✅
#### Baseline Linear Regression:
- **MSE**: 5022.15
- **MAE**: 56.91
- **R^2**: 0.923
Approximately 92.3% of the variability in revenue can be explained by the baseline linear regression model.

#### Polynomial Regression (Degree 2):
- **MSE**: 11.68
- **MAE**: 2.54
- **R^2**: 0.9998
The Polynomial Regression model explains approximately 99.98% of the variability in revenue, with significantly lower errors compared to the baseline model.

#### Feature Importance:
'branch' is ranked as the most influential feature in predicting revenue, followed by 'payment_method' and 'city'. Features like 'gm_pct', 'cogs', and 'unit_cost' are considered less influential in the linear regression model.

#### KNN Classifier:
- **Optimal Hyperparameters**:
  - **Number of Neighbors (k)**: Best number of neighbors is 4.
  - **Distance Metric (p)**: Chebyshev distance (with \( p=3 \)) was optimal.
- **Evaluation Metrics**:
  - **Accuracy**: 49%
- **Classification Report**:
  - **Member**:
    - **Precision**: 0.47
    - **Recall**: 0.45
  - **Normal**:
    - **Precision**: 0.50
    - **Recall**: 0.52

The performance generally decreases as \( k \) increases. The Chebyshev distance performs better for most values of \( k \), especially for smaller \( k \) values.

---

**Happy Analysing!** 🚀
