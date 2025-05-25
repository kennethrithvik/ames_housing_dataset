# Ames Housing Price Prediction

This project aims to develop a machine learning model to predict house sale prices based on detailed property characteristics and location features from Ames, Iowa (2006–2010). The dataset provides rich information including lot dimensions, building type, neighborhood, quality ratings, and sale conditions.

---

## 📂 Project Structure

```
.
├── data
│   └── ames_transactions__2_.csv   # Raw dataset
├── DataDocumentation.txt           # Data dictionary and feature descriptions
├── models                          # Saved trained models (to be added)
├── notebooks
│   ├── 1_EDA.ipynb                 # Exploratory Data Analysis
│   └── training_prediction.ipynb   # Model training and prediction
├── requirements.txt                # Required Python packages
├── README.md                       # Project overview
```

---

## 📊 Dataset Overview

The dataset contains 2,930 residential property transactions with over 80 features covering:

- **Property structure**: square footage, quality, condition, year built/remodeled  
- **Lot details**: size, shape, zoning, slope  
- **Neighborhood and location**  
- **Amenity indicators**: fireplaces, garage, pool, porches  
- **Sale details**: date, price, sale condition  

---

## 🧠 Objectives

- Predict house sale prices with a focus on **accuracy and interpretability**  
- Identify **key drivers** of property value  
- Understand **where and why the model performs well or poorly**  
- Build a reproducible and transparent modeling pipeline  

---

## 🚀 Usage

1. Clone the repo
2. Create a virtual environment and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run notebooks inside `notebooks/` directory:
   - `1_EDA.ipynb` for exploration
   - `training_prediction.ipynb` for model development

---

## 🔧 Requirements

See `requirements.txt` for a list of required packages.

---

## 📄 License

This project is for educational and demonstration purposes only.
