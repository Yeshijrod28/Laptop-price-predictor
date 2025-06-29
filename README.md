
# 💻 Laptop Price Predictor

A machine learning project that predicts the price of a laptop based on its specifications such as brand, processor, RAM, storage, GPU, operating system, and more.

This project explores data preprocessing, feature engineering, model building, hyperparameter tuning, and deployment.

---

## 📊 Features

- Cleans and preprocesses real-world laptop data
- Converts categorical features to numerical
- Uses GridSearchCV for hyperparameter tuning
- Evaluates model performance using R² Score and MAE
- Saves the best model using `pickle` 
- Provides a Streamlit web interface for predictions

---

## 🧠 Algorithms Used
- Random Forest Regressor

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-Learn
- Matplotlib & Seaborn
- Streamlit (for frontend UI)

---

📈 Sample Prediction
### Input:
- Brand: Dell
- Type:Ultrabook
- RAM: 8 GB
- Weight: 1.5kg
- Touchscreen: No
- IPS: No
- ScreenSize:15.6 inches
- Screen Resolution 1920x1080
- CPU : Intel Core i5
- HDD: 0
- SSD: 512 GB
- GPU: Intel
- OS: Windows

- Predicted Price: ₹73723

