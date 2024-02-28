# portfolio-part-3-Buchu97
portfolio-part-3-Buchu97 created by GitHub Classroom

🛍️ **Analysis of an E-commerce Dataset Part 3** 📈

## Introduction 📚
This portfolio task continues with the dataset from Portfolio 2, where ratings are converted to 'like' (score 1) and 'dislike' (score 0). The objective is to utilize classification models, such as Logistic Regression and KNN, to predict user preferences. The notebook delves into data exploration, preprocessing, correlation analysis, and model training and evaluation.

## Python Libraries Used 🐍
- pandas 🐼
- numpy 🔢
- matplotlib 📊
- sklearn 🔬
- KNeighborsClassifier (from sklearn) 🚀
- OrdinalEncoder (from sklearn) 🔡
- train_test_split (from sklearn) 🚄
- cross_val_score (from sklearn) ✅
- r2_score (from sklearn) 📐

## Exploration and Analysis 🧠
The dataset underwent a series of exploratory steps:
- Data inspection and cleaning, ensuring quality.
- Conversion of object features to numeric values using encoders.
- Correlation analysis between features.
- Training of a logistic regression model for rating prediction.
- Training of a KNN model with ad-hoc hyper-parameter settings.
- Fine-tuning the K parameter in KNN to optimize prediction performance.

_Note: The emphasis is on the process, not just the model accuracy. Both Logistic Regression and KNN models are explored and discussed in depth._

## Results Summary ✅
- **Logistic Regression**:
    - **Model 1 (Selected Features)**:
      - **MSE**:  0.2159
      - **Root MSE**:  0.4646
      - **R2**: 0.0256
    - **Model 2 (All Features)**:
      - **MSE**:  0.2159
      - **Root MSE**:  0.4646
      - **R2**: 0.0258
    Both models exhibit similar performance, with Model 2 showing a slight edge in \( R^2 \).

- **KNN**:
    - **Model 1 Accuracy**: 64.8%
    - **Model 2 Accuracy**: 62.8%
    Model 1 slightly outperforms Model 2 by 2%.

- **Selection of K in KNN**:
  The chosen \( K = 23 \) is determined by the test size (537). There's potential for performance improvement with further tuning of \( K \).

- **Feature Set**:
  The choice of features significantly affects model performance. The simpler feature set in Model 1 of Logistic Regression yielded nearly comparable results to the comprehensive feature set in Model 2.

- **Comparison**:
  Logistic Regression offers interpretability, while KNN can better manage datasets with complex class boundaries.

---

**Happy Analysing and Predicting!** 🚀
