# 🏀🔮 Predicting NBA Game Outcomes with Machine Learning

This project dives into the exciting world of the NBA, where we use **machine learning** to predict the outcome of games from the **2017–2018** season all the way to **2023–2024**.

Can we predict which team will win based on historical stats and trends? Let’s find out!

---

## 📌 Project Overview

Using data from several NBA seasons, this project builds a machine learning model to forecast the winner of each game. The process involves:

- 🔍 **Scraping** game data from online sources  
- 🧹 **Cleaning and parsing** the data for analysis  
- 🤖 **Training** a predictive model using team statistics  
- 🏆 **Evaluating** performance across multiple seasons  

---

## 🧱 Project Pipeline

Here’s a breakdown of the project flow:

1. **📄 Data Collection** — `get_data.ipynb`  
   Scrapes NBA game data from multiple seasons via web scraping techniques.

2. **🧼 Data Parsing & Cleaning** — `parse_data.ipynb`  
   Transforms raw HTML tables into structured and usable datasets for modeling.

3. **🏀 Model Training & Evaluation** — `prediction.ipynb`  
   Uses historical stats to train a classifier that predicts the outcome of each game.

---

## 🤖 Tools & Technologies

- 🐍 **Python**  
- 🌐 **Requests / BeautifulSoup** – For web scraping  
- 🧹 **Pandas** – Data wrangling  
- 📊 **Matplotlib / Seaborn** – Visualization  
- ⚙️ **Scikit-learn** – ML models and performance evaluation  

---

## 💡 Notes

- The project uses **Scikit-learn** for building and evaluating classification models.  
- You can experiment with different model types (e.g., Logistic Regression, Random Forests) in `prediction.ipynb`.

---

## 🧠 Future Improvements

- Add **player-level stats** to increase prediction accuracy  
- Include **injury reports or back-to-back game indicators**  
- Deploy the model in a simple web app for live predictions  


