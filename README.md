# 🚗 Car Price Prediction Model

![Car Price Prediction Banner](https://via.placeholder.com/1200x400.png?text=Car+Price+Prediction+Model)  
*A machine learning model to predict used car prices based on vehicle specifications*

## 📌 Project Overview
This project predicts used car prices in the Indian market using machine learning. It analyzes factors like:
- Vehicle age and mileage
- Brand and model
- Fuel type and transmission
- Showroom price vs selling price
- Ownership history

**Accuracy**: Achieved **96% R² score** using Random Forest Regression

## 📂 Dataset
**Features Used**:
- `Car_Name`: Make and model (e.g., "swift", "amaze")
- `Year`: Manufacturing year
- `Present_Price`: Current showroom price (in lakhs)
- `Driven_kms`: Total kilometers driven
- `Fuel_Type`: Petrol/Diesel/CNG
- `Selling_type`: Dealer/Individual
- `Transmission`: Manual/Automatic
- `Owner`: Number of previous owners

**Sample Data**:
| Car_Name               | Year | Selling_Price | Present_Price | Driven_kms | Fuel_Type | Selling_type | Transmission | Owner |
|------------------------|------|---------------|---------------|------------|-----------|--------------|--------------|-------|
| etios g                | 2014 | 4.10          | 6.80          | 39485      | Petrol    | Dealer       | Manual       | 1     |
| amaze                  | 2015 | 4.00          | 5.80          | 40023      | Petrol    | Dealer       | Manual       | 0     |

## 🛠️ Tech Stack
- **Python 3**
- Libraries: Pandas, Scikit-learn, Matplotlib, Seaborn
- Machine Learning: Random Forest Regressor
- Feature Engineering: Custom age and mileage features
