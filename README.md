# ✈️ Flight Price – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a flight price dataset to uncover key factors that influence ticket prices. The goal is to gain actionable insights through data cleaning, feature engineering, and visualization.

**Dataset Source:** [Kaggle – Flight Price Prediction](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)

---

## 🧰 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Jupyter Notebook  

---

## 🧪 Steps Performed

1. **Data Cleaning**
   - Removed null values
   - Cleaned columns like `Total_Stops`, `Date_of_Journey`, `Duration`, etc.
   - Converted object types to datetime and numeric where required

2. **Feature Engineering**
   - Extracted new features: journey day, month, duration (in minutes), departure/arrival hours
   - Encoded categorical variables for future modeling
   - Removed redundant columns

3. **EDA (Exploratory Data Analysis)**
   - Analyzed distribution of ticket prices
   - Identified top airlines by average fare
   - Visualized relationships between stops, airline, route, duration, and price
   - Investigated how journey date and duration affect pricing

---

## 📊 Key Insights

- **Jet Airways** had higher average fares compared to other airlines.
- Non-stop flights tend to be more expensive, but the relationship isn't linear.
- Flights with longer durations did not always have higher prices, indicating the importance of the airline and route.
- Most flights were booked in March and May, suggesting seasonal travel spikes.

---

## 📁 Repository Structure
flight-price-eda/
├── flight_price_eda.ipynb # Main Jupyter notebook
├── visuals/ # (Optional) Exported charts/images
├── dataset/ # (Optional) Link or place sample dataset
└── README.md # Project documentation

---

## 🔗 Dataset

- [Kaggle Dataset – Flight Price Prediction](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)

---

## 🚀 Future Improvements

- Build a regression model to predict flight prices
- Add Tableau or Power BI dashboard for business users
- Create custom feature extraction pipeline for reuse

---

## 👨‍💻 Author

**Mihir Jadhav**  
Aspiring Data Analyst | Passionate about analytics and trading  
[LinkedIn](https://www.linkedin.com/in/mihirjadhav04)
