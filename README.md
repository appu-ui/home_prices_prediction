# 🏠 Real Estate Price Prediction Web App

This data science project demonstrates the **end-to-end development** of a machine learning-based real estate price prediction website. It is built in three phases:

1. **Model Building** using `scikit-learn` and **Linear Regression**  
2. **Python Flask Server** that serves the model via HTTP  
3. **Web UI** using HTML, CSS, and JavaScript to interact with the Flask API

---

## 🔧 Technologies Used

- **Python** – Core programming language  
- **NumPy & Pandas** – For data manipulation and cleaning  
- **Matplotlib** – For data visualization  
- **Scikit-learn (sklearn)** – For model training and evaluation  
- **Flask** – To build the backend API  
- **HTML/CSS/JavaScript** – To build the frontend user interface  
- **Jupyter Notebook, VS Code, PyCharm** – IDEs for development  

---

## 📈 Data Science Concepts Involved

- Data loading and cleaning  
- Outlier detection and removal  
- Feature engineering  
- Dimensionality reduction  
- Model training using Linear Regression  
- GridSearchCV for hyperparameter tuning  
- K-Fold cross-validation  
- Model persistence using `joblib`

---

## 🗂️ Dataset

- **Source**: [Kaggle - Bangalore Home Prices Dataset](https://www.kaggle.com/datasets)  
- Contains features like square footage, number of bedrooms, bathrooms, location, etc.

---

## 🚀 Project Structure

<pre lang="markdown"><code> ``` real-estate-price-prediction/ ├── client/ # Frontend (HTML/CSS/JS) │ └── index.html ├── server/ # Backend Flask server │ ├── server.py │ └── artifacts/ # Stored model and columns ├── model/ # Jupyter notebooks for model building │ └── real_estate_model.ipynb ├── README.md ├── requirements.txt ``` </code></pre>
