# portfolio-part-1-Buchu97
portfolio-part-1-Buchu97 created by GitHub Classroom


🛍️ **Analysis of an E-commerce Dataset** 📈

**Introduction**: 📚  
This repository contains an analysis of a combined e-commerce dataset. The dataset provides a comprehensive view into user ratings and reviews for products, as well as the trustworthiness of these reviews as evaluated by other users. The dataset encompasses many details for each user, including their profile, gender, city of birth, product ratings and reviews, prices of purchased products, and more.

**Dataset Structure**: 📋  
- `userId` - 🆔 User's ID
- `gender` - ♂️♀️ User's gender
- `rating` - ⭐ User's rating for the item
- `review` - 💬 User's review for the item
- `item` - 📦 Item name
- `category` - 🏷️ Item category
- `helpfulness` - 👍 Average helpfulness of the rating
- `timestamp` - 🕒 Timestamp of the rating
- `item_id` - 🎁 Item ID
- `item_price` - 💸 Item price
- `user_city` - 🌆 User's birth city

**Python Libraries Used**: 🐍  
- `pandas` 🐼
- `numpy` 🔢
- `matplotlib` 📊
- `seaborn` 🎨

**Explorations**: 🔍  
- **Data Cleaning**: 🧹 Initial dataset had 20,000 rows & 11 columns. After cleaning, it was reduced to 19,916 rows & 11 columns.
- **Descriptive Statistics**: 📈
  - Unique users: 8,562 
  - Unique reviews: 19,459 
  - Unique items: 89 
  - Unique categories: 9 


**Results Summary**: ✅  
- 🚻 Both males and females showcase similar rating behaviors, mainly in the 3 to 5 range, indicating satisfaction.
- 📝 Ratings have varied levels of perceived helpfulness, especially ratings between 1 to 3.
- 🎬 "Movies" are favorably rated, 📺 "Media" is less appreciated, 🎮 "Games" are popular, while 📖 "Books" received less feedback.
