![GitHub repo size](https://img.shields.io/github/repo-size/Ahamed-Meeran-Dhanish/Car_dekho_ml_Project?style=plastic)
![GitHub language count](https://img.shields.io/github/languages/count/Ahamed-Meeran-Dhanish/Car_dekho_ml_Project?style=plastic)
![GitHub top language](https://img.shields.io/github/languages/top/Ahamed-Meeran-Dhanish/Car_dekho_ml_Project?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/Ahamed-Meeran-Dhanish/Car_dekho_ml_Project?color=red&style=plastic)

# Car Dekho Price Prediction

## Table of Contents

1. [Objective](#objective)
2. [Quick Demo](#quick-demo)
3. [Dataset Preview](#dataset-preview)
4. [Description of Variables](#description-of-variables)
5. [Project Directory Structure](#project-directory-structure)
6. [Installation](#installation)
7. [Technologies Used](#technologies-used)

---

## Objective
The goal of this project is to predict the selling price of used cars based on various features such as Present Price, Kms Driven, Owner, Fuel Type, Seller Type, and Transmission. The dataset used in this project is from [CarDekho](https://www.cardekho.com).

## Quick Demo
![Demo GIF](https://github.com/Ahamed-Meeran-Dhanish/Car_dekho_ml_Project/blob/main/demo.gif)

Users can enter car details through the UI, and the application will predict the car’s selling price.

## Dataset Preview
A preview of the top five rows of the dataset:

| Car_Name | Year | Selling_Price | Present_Price | Kms_Driven | Fuel_Type | Seller_Type | Transmission | Owner |
|----------|------|--------------|---------------|------------|-----------|-------------|--------------|-------|
| Ritz     | 2014 | 3.35         | 5.59          | 27000      | Petrol    | Dealer      | Manual       | 0     |
| SX4      | 2013 | 4.75         | 9.54          | 43000      | Diesel    | Dealer      | Manual       | 0     |
| Ciaz     | 2017 | 7.25         | 9.85          | 6900       | Petrol    | Dealer      | Manual       | 0     |
| Wagon R  | 2011 | 2.85         | 4.15          | 5200       | Petrol    | Dealer      | Manual       | 0     |
| Swift    | 2014 | 4.60         | 6.87          | 42450      | Diesel    | Dealer      | Manual       | 0     |

## Description of Variables
The dataset contains information about used cars listed on [CarDekho](https://www.cardekho.com). It includes:

- **Car_Name:** Name of the car model
- **Year:** Year the car was purchased
- **Selling_Price:** Price at which the car was sold
- **Present_Price:** Current price of the same car model
- **Kms_Driven:** Number of kilometers the car has been driven
- **Fuel_Type:** Type of fuel used (Petrol/Diesel/CNG)
- **Seller_Type:** Type of seller (Dealer/Individual)
- **Transmission:** Transmission type (Manual/Automatic)
- **Owner:** Number of previous owners

## Project Directory Structure
```
Car-Price-Prediction-Project/
├── Templates/
│   └── index.html
│
├── app.py
│
├── demo.gif
│
├── rf_regression_model.pkl
│
├── Car_Dekho_Price_Prediction.ipynb
│
├── car_data.csv
│
├── Procfile
│
├── README.md
│
└── requirements.txt
```

### Folder & File Details:
- **Templates/** - Contains HTML templates for UI
- **app.py** - Backend logic for the web application
- **Car_Dekho_Price_Prediction.ipynb** - Jupyter Notebook with model training and analysis
- **rf_regression_model.pkl** - Pretrained machine learning model
- **requirements.txt** - List of dependencies
- **car_data.csv** - Raw dataset in CSV format
- **Procfile** - Deployment configuration for Heroku

## Installation

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/Ahamed-Meeran-Dhanish/Car_dekho_ml_Project.git
   cd Car_dekho_ml_Project
   ```
2. **Create a Virtual Environment & Activate It**:
   ```sh
   python -m venv env
   source env/bin/activate  # On Mac/Linux
   env\Scripts\activate  # On Windows
   ```
3. **Install Required Dependencies**:
   ```sh
   pip install -r requirements.txt
   ```
4. **Run the Application**:
   ```sh
   python app.py
   ```
5. **Open in Browser**:
   ```
   http://127.0.0.1:5000/
   ```

## Technologies Used
![Made with Python](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/)

---

🚀 **Happy Coding!**

