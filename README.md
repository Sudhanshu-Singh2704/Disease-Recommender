# Disease Prediction & Recommendation System

This project is a **Disease Prediction and Recommendation System** built with Python and Streamlit. It allows users to input symptoms and predicts the most likely disease using a pre-trained machine learning model (SVM). It also provides detailed recommendations including disease description, precautions, medications, diets, and workouts.

---

## Features

- Predict diseases based on user-entered symptoms  
- Fetch detailed disease description and recommendations  
- Interactive and user-friendly web interface using Streamlit  
- Uses multiple datasets to provide comprehensive advice  

---

## Project Structure

- `data/` — Contains CSV files with symptoms, precautions, diets, medications, descriptions, and workouts  
- `models/` — Pre-trained SVM model saved as `svc.pkl`  
- `recommender.py` (or your main script) — Streamlit application script  
- Other helper files and scripts  

---

## Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Sudhanshu_singh2704/Disease-Recommender.git
cd Disease-Recommender
