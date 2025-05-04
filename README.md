
# ⚡ Combined Cycle Power Plant – Machine Learning Model Performance

> 📌 **Complete end-to-end ML & BI project** – from model development to business-ready dashboard

## 📖 Project Overview
This project focuses on predicting the **net hourly electrical energy output (PE)** of a Combined Cycle Power Plant (CCPP) using historical sensor data. I developed and compared multiple machine learning models (including a custom-built ANN), evaluated their accuracy using standard error metrics, and created an **interactive Power BI dashboard** to visualize insights in a decision-maker-friendly format.

## 🎯 Objectives
- Build and evaluate machine learning models to predict energy output.
- Analyze model performance using MAE, MSE, RMSE, and MAPE.
- Identify the most accurate model.
- Present model comparison and performance through a professional Power BI dashboard.

### 🧠 Workflow Summary

<pre> ```mermaid graph LR A[Data Collection & Cleaning] --> B[Feature Selection] B --> C[Model Building: ANN, Random Forest, XGBoost, Linear Regression] C --> D[Model Evaluation: MAE, RMSE, MAPE, MSE] D --> E[Dashboard Design in Power BI] ``` </pre>

## 🧮 Input Features

| Feature | Description |
|--------|-------------|
| `T`    | Ambient Temperature (°C) |
| `V`    | Exhaust Vacuum (cm Hg) |
| `AP`   | Ambient Pressure (millibar) |
| `RH`   | Relative Humidity (%) |
| `PE`   | Target: Net hourly energy output (MW) |

## 🤖 Machine Learning Models

| Model | Description |
|-------|-------------|
| Linear Regression | Baseline model |
| Random Forest | Tree-based ensemble model |
| XGBoost | Gradient boosting machine |
| Artificial Neural Network (ANN) | Custom-built with Keras, optimized and tuned |

## 📏 Evaluation Metrics
Each model was evaluated using:
- ✅ MAE – Mean Absolute Error  
- ✅ MSE – Mean Squared Error  
- ✅ RMSE – Root Mean Squared Error  
- ✅ MAPE – Mean Absolute Percentage Error  

## 🏆 Key Insights
- **Random Forest** achieved the best performance with the **lowest RMSE**.
- **ANN model** performance improved significantly after tuning.
- Over **90% of predictions** were within ±1% error range.
- Error distributions showed high prediction reliability and minimal bias.

## 💼 Business Impact
- Enables **accurate forecasting** of power output.
- Supports **energy planning, resource optimization**, and **cost reduction**.
- Uses only real-time sensor inputs — no manual data entry needed.
- The **Power BI dashboard** makes results accessible to both technical and non-technical stakeholders.

## 🛠️ Technologies Used

| Tool         | Purpose                     |
|--------------|-----------------------------|
| Python       | Data processing, modeling   |
| Pandas, NumPy| Data manipulation           |
| Scikit-learn | ML baseline models          |
| Keras        | Neural network (ANN)        |
| XGBoost      | Gradient boosting           |
| Power BI     | Dashboard visualization     |
| Jupyter Lab  | Development environment     |
| Git & GitHub | Version control             |


## 📊 Power BI Dashboard

> 🎨 Built a fully interactive dashboard to visualize all model results and error metrics
<img width="1275" alt="image" src="https://github.com/user-attachments/assets/52b25fcb-ba7e-4557-a946-b4471921d43b" />

### 🔍 Highlights:
- Actual vs Predicted Power Output (Line Chart)
- Error Distributions (MW and %)
- KPI Cards for RMSE, MAE, MAPE, MSE
- Best Model Identification (Random Forest)
- Slicers for filtering and comparison

🧾 File: `"C:\Bobby\power Bi\Project\power Bi\Combined Cycle Power Plant – Machine Learning Model Performance Dashboard.pbix"`  
📌 Open in Power BI Desktop to explore interactively

## 📁 Project Structure

```
ccpp-ml-performance/
├── data/
│   └── Folds5x2_pp.csv
├── notebooks/
│   └── model_comparison_ann_rf_xgb.ipynb
├── powerbi/
│   └── Combined_Cycle_Power_Plant_Dashboard.pbix
├── images/
│   └── dashboard_screenshot.png
└── README.md
```

## 🚀 How to Use This Project
1. Clone the repository:
   ```bash
   git clone https://github.com/ypranaykumarreddy/ccpp-ml-performance.git
   ```
2. Explore the code and models in the `notebooks` folder.
3. Open the Power BI `.pbix` file to view and interact with the dashboard.

## ✅ Conclusion
This project demonstrates a complete data science pipeline — from data preprocessing and model development to interactive business visualization. It merges **machine learning** with **business intelligence**, showcasing a real-world use case in the **energy analytics** domain.

## 💬 Let’s Connect
📧 ypranaykumarreddy.0@gmail.com  
🔗 [LinkedIn](www.linkedin.com/in/pranay-kumar-reddy-yammanuru-ba0032227)  

⭐ If you found this project helpful, feel free to fork it or give it a star!
