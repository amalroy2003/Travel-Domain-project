# ✈️ Flight Price Prediction Web App

This repository contains a complete Machine Learning project that predicts flight prices based on multiple features like airline, source, destination, stops, and journey time. The model is deployed using Streamlit as a web application.

## 📦 Project Structure

- `Travel Domain (Airline) Project.ipynb`: Jupyter notebook for data analysis, visualization, and model training.
- `airline_dataset.xlsx`: The dataset used for training and evaluation.
- `streamlit_app.py`: The Streamlit-based web application script.
- `price_prediction.pkl`: Trained machine learning model (required for predictions).
- `Travel Domain.docx`: Documentation describing project background and objectives.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/amalroy2003/Travel-Domain-project.git
cd flight-price-predictor
```

### 2. Install Dependencies

Install required packages using pip:

```bash
pip install streamlit numpy pandas scikit-learn openpyxl
```

### 3. Run the Web App

```bash
streamlit run streamlit_app.py
```

Ensure that `price_prediction.pkl` is present in the project folder.

## 🧠 Model Details

The model predicts flight fares using:
- Total stops
- Journey and departure details
- Duration of travel
- One-hot encoded airline, source, and destination

Machine learning algorithms used:
- Linear Regression
- Random Forest Regressor
- Others explored in the notebook

## 📊 Dataset Features

The dataset includes:
- Airline
- Source and Destination
- Route and Total Stops
- Journey Dates and Times
- Price (Target Variable)

## 📄 Project Highlights

- End-to-end machine learning pipeline from cleaning to deployment
- Feature engineering including time extraction and duration calculation
- Hypothesis testing for statistical validation
- Streamlit app for real-time user interaction

## 📌 Future Improvements

- Add support for more airlines and routes
- Improve model performance with advanced algorithms like XGBoost
- Deploy on cloud platforms like Heroku or AWS# ✈️ Flight Price Prediction Web App

This repository contains a complete Machine Learning project that predicts flight prices based on multiple features like airline, source, destination, stops, and journey time. The model is deployed using Streamlit as a web application.

## 📦 Project Structure

- `Travel Domain (Airline) Project.ipynb`: Jupyter notebook for data analysis, visualization, and model training.
- `airline_dataset.xlsx`: The dataset used for training and evaluation.
- `streamlit_app.py`: The Streamlit-based web application script.
- `price_prediction.pkl`: Trained machine learning model (required for predictions).
- `Travel Domain.docx`: Documentation describing project background and objectives.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/amalroy2003/Travel-Domain-project.git
cd flight-price-predictor
```

### 2. Install Dependencies

Install required packages using pip:

```bash
pip install streamlit numpy pandas scikit-learn openpyxl
```

### 3. Run the Web App

```bash
streamlit run streamlit_app.py
```

Ensure that `price_prediction.pkl` is present in the project folder.

## 🧠 Model Details

The model predicts flight fares using:
- Total stops
- Journey and departure details
- Duration of travel
- One-hot encoded airline, source, and destination

Machine learning algorithms used:
- Linear Regression
- Random Forest Regressor
- Others explored in the notebook

## 📊 Dataset Features

The dataset includes:
- Airline
- Source and Destination
- Route and Total Stops
- Journey Dates and Times
- Price (Target Variable)

## 📄 Project Highlights

- End-to-end machine learning pipeline from cleaning to deployment
- Feature engineering including time extraction and duration calculation
- Hypothesis testing for statistical validation
- Streamlit app for real-time user interaction

## 📌 Future Improvements

- Add support for more airlines and routes
- Improve model performance with advanced algorithms like XGBoost
- Deploy on cloud platforms like Heroku or AWS

## 📜 License

This project is licensed under the MIT License.

## 🙌 Acknowledgements

Dataset sourced from EaseMyTrip. Project documentation based on insights from the `Travel Domain.docx` file.


## 🙌 Acknowledgements

Dataset sourced from EaseMyTrip. Project documentation based on insights from the `Travel Domain.docx` file.
