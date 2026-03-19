# FIFA-PLAYER-RATING-PREDICTOR
A regression-based ML model to predict FIFA players overall from physical and skill attributes.
# FIFA Player Rating Predictor ⚽️

A Machine Learning application that predicts a football player's **Overall Rating** based on their skill attributes. This project includes a web interface for real-time predictions.

## 📌 Project Overview
This project uses historical FIFA data to build a predictive model for player ratings. By analyzing attributes like Pace, Shooting, and Dribbling, the model estimates a player's performance score. The final model is deployed as an interactive web app.

## 🚀 Features
- **Data Cleaning & EDA:** Comprehensive analysis of player attributes and correlations.
- **Machine Learning:** Regression models built with **Scikit-Learn**.
- **Model Serialization:** Trained models are saved using **Pickle** for fast loading.
- **Web Interface:** Built with **Streamlit** for a user-friendly prediction dashboard.
- **Public Hosting:** Integrated with **Ngrok** to create a secure tunnel for remote access.

## 🛠️ Tech Stack
- **Language:** Python
- **Machine Learning:** Pandas, NumPy, Scikit-Learn
- **Serialization:** Pickle
- **Deployment:** Streamlit
- **Tunneling/Hosting:** Pyngrok (Ngrok)

## 📊 Dataset
The model is trained on the **FIFA Dataset** (Kaggle), featuring thousands of players and their technical/physical stats.

## ⚙️ How to Run Locally
1. **Clone the repo:**
   ```bash
   git clone https://github.com
   cd YOUR_REPO_NAME
