# Laptop-Price-Prediction-System

A web-based **Laptop Price Prediction System** built using **Python**, **Machine Learning**, and **Streamlit**. It uses a trained **Random Forest Regressor** model to predict the price of a laptop based on user-input features like RAM, storage, processor, and display type.

---

## Project Overview

This project aims to predict laptop prices accurately using machine learning. The system is trained on a real-world dataset of laptops from e-commerce platforms and deployed as an interactive web application using **Streamlit**.

>  Model Score (R² on Test Data): **0.88**

---

##  Tech Stack

- **Language**: Python  
- **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn, streamlit, joblib  
- **ML Algorithm**: Random Forest Regressor  
- **Deployment**: Streamlit (local or cloud via Streamlit Sharing)

---

## Features

✅ Interactive UI to input laptop specifications  
✅ Predicts laptop price instantly  
✅ Uses a trained Random Forest model  
✅ Visualizes feature importances (optional)  
✅ Clean and intuitive interface built with Streamlit

---

##  How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/Shubhangi2002Gaud/Laptop-Price-Prediction.git
cd Laptop-Price-Prediction
2. Install dependencies
pip install -r requirements.txt
3. Run the Streamlit app
streamlit run app.py

 Model Details
Algorithm: Random Forest Regressor

Test Accuracy (R² Score): 0.88

Hyperparameter Tuning: GridSearchCV used

Preprocessing: Label encoding, outlier handling, feature engineering
