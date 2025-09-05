# 🏡 Bengaluru Home Price Predictor (Regression Project)

🚀 Live App: [Streamlit Deployment](https://homepricepredictor-cp7xxnnk6sdh5mc62qic2c.streamlit.app/)  

## 📌 Project Overview
This project predicts house prices in **Bengaluru, India** based on features such as location, square footage, number of bathrooms, and bedrooms.  
We trained multiple regression models and selected **Random Forest Regressor** as the best performing model for deployment.  

## 📂 Repository Structure
- `Bengaluru_House_Data.csv` → Original dataset  
- `copied.csv` → Cleaned dataset used for the app  
- `model.ipynb` → Jupyter notebook for training & evaluation  
- `frontend.py` → Streamlit app frontend  
- `RFmodel.pkl` → Trained Random Forest model  
- `requirements.txt` → Required dependencies  
- `runtime.txt` → Python runtime version for Streamlit Cloud  
- `home_icon.jpg` → App icon  

## ⚙️ Tech Stack
- Python 🐍  
- Scikit-learn 🤖  
- Pandas & NumPy 📊  
- Matplotlib & Seaborn 📈  
- Streamlit 🌐  

## 📊 Methodology
1. **Data Preprocessing**  
   - Handling missing values  
   - Encoding categorical features (e.g., location, model, fuel type)  
   - Outlier analysis (target variable: Price)  

2. **Model Training**  
   - Linear Regression  
   - Random Forest Regression (best fit)  
   - GridSearchCV for hyperparameter tuning  

3. **Evaluation**  
   - Training R² Score: ~0.90  
   - Testing R² Score: ~0.80  

4. **Deployment**  
   - Saved model (`RFmodel.pkl`) with `pickle`  
   - Streamlit frontend with user input fields for prediction  



