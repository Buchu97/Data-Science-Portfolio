# portfolio-part-2-Buchu97
portfolio-part-2-Buchu97 created by GitHub Classroom

🛍️ **Analysis of an E-commerce Dataset Part 2** 📈

## Introduction 📚
This notebook focuses on the analysis of an e-commerce dataset, aiming to predict user ratings for items through linear regression models. Emphasis is placed on the impact of feature selection and training/testing data size on model performance.

## Dataset Structure 📋
- **userId** - 🆔 User's ID
- **gender** - ♂️♀️ User's gender
- **rating** - ⭐ User's rating
- ... (and other columns)

## Python Libraries Used 🐍
- pandas 🐼
- seaborn 🎨
- matplotlib 📊
- sklearn 🔬
- train_test_split 🚄

## Explorations 🔍
- Explored correlations between columns to identify the most and least correlated features with 'rating'.
- Feature selection was emphasized to enhance model performance. Two most correlated and two least correlated features regarding 'rating' were identified.

## Model Training and Analysis 🤖
- Four linear regression models were trained under different conditions:
  - **model-a**: Trained with data in case 1 using two most correlated features.
  - **model-b**: Trained with data in case 1 using two least correlated features.
  - **model-c**: Trained with data in case 2 using two most correlated features.
  - **model-d**: Trained with data in case 2 using two least correlated features.
  
  These models helped in verifying:
  - Impact of training/testing data size on performance (by comparing model-a vs model-c and model-b vs model-d).
  - Impact of feature selection on performance (by comparing model-a vs model-b and model-c vs model-d).

## Results Summary ✅
- The model performance was evaluated using metrics like MSE and Root MSE.
- **Model c** stood out as the best performer, especially when trained with the most correlated features and a larger dataset. This model showed the lowest MSE, indicating its predictions were more accurate on average.
- **Model b**, on the other hand, had the highest MSE, suggesting it was less accurate in its predictions, especially when trained with the least correlated features.
- These results underscore the importance of feature selection in model training, with models trained on more correlated features (like Model c) generally outperforming those that aren't.
