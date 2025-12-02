# Tunisia Apartment Price Predictor – MLOps End-to-End

**In progress – November 2025**  
Personal project (currently under active development)

Predicting apartment prices in Tunisia using real estate data scraped from Tunisian websites.

## Current Progress (What I have already completed)

- Web scraping of thousands of apartment listings from major Tunisian real estate websites  
- Exploratory Data Analysis (EDA) – price distribution by governorate, surface, rooms, neighborhoods, etc.  
- Data cleaning & feature engineering (location encoding, outlier treatment, missing values, etc.)  
- Preprocessing pipeline (scikit-learn ColumnTransformer + custom transformers)  
- Baseline modeling + advanced models (XGBoost, LightGBM, CatBoost, RandomForest, stacking)  
- Hyperparameter tuning and cross-validation

## Planned / In-Progress MLOps Architecture

- Experiment tracking & model registry → MLflow + DagsHub  
- Data versioning → DagsHub  
- CI/CD → Jenkins  
- Containerization → Docker  
- Model monitoring & drift detection → DeepChecks + Arize AI  
- API serving → FastAPI  
- Interactive dashboard & predictions → Streamlit  
- Deployment → Render (or alternatives)

## Tech Stack

Python • Pandas • Scikit-learn • XGBoost • LightGBM • MLflow • DagsHub • Docker • FastAPI • Streamlit • Jenkins • DeepChecks • Arize • Jupyter

## Project Goals

- Build a robust, production-ready MLOps pipeline from A to Z  
- Deploy a live web app where anyone can estimate an apartment price in Tunisia  
- Showcase best practices: reproducibility, monitoring, automated retraining

**Project still in active development** – new commits coming regularly (model serving, monitoring, CI/CD, and deployment phases are next).

Feel free to star or watch the repo if you're interested in MLOps or real estate price prediction in Tunisia!
