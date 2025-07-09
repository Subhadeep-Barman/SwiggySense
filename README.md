# SwiggySense – Food Delivery Time Prediction

SwiggySense is a comprehensive machine learning project designed to predict food delivery time in minutes using real-world delivery data. The project is tailored for food delivery platforms such as Swiggy to enhance time estimation accuracy by analyzing features like distance, traffic, weather, restaurant behavior, and delivery agent performance.

The repository implements a scalable and reproducible ML pipeline following industry-standard practices, from raw data ingestion to model evaluation and deployment automation.

---

## Project Overview

**Objective**:  
Build a machine learning model that accurately predicts the estimated delivery time for food orders.

**Dataset**:  
Historical food delivery records containing features such as order location, delivery location, delivery distance, restaurant preparation time, traffic levels, and more.

**Technologies and Tools**:
- Programming Language: Python
- Data Handling & Modeling: Pandas, Scikit-learn, LightGBM
- ML Workflow & MLOps: DVC (Data Version Control), Docker, GitHub Actions, Makefile
- Visualization: Matplotlib, Seaborn
- Environment: Virtualenv, requirements.txt

**Key Features**:
- Modular pipeline for data preprocessing, feature engineering, model training, and evaluation
- End-to-end reproducibility using version control and dependency tracking
- Model experimentation using Jupyter notebooks
- CI/CD enabled with automated testing and linting via GitHub Actions
- Containerized environment for consistent deployment

**Expected Output**:  
A trained and validated machine learning model that can predict delivery time with high accuracy, enabling better operational planning and customer communication.

---
