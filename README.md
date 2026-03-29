# azure-demand-capacity-optimization

![Python](https://img.shields.io/badge/-Python-blue?logo=python&logoColor=white) ![License](https://img.shields.io/badge/license-LICENSE-green)

## 📝 Description

Azure Demand & Capacity Optimization is a comprehensive, end-to-end Python-based framework designed to solve the complexities of cloud resource management. It empowers organizations to predict infrastructure needs with precision through automated data preprocessing, intelligent missing-value treatment, and canonical region mapping. By integrating advanced time-series usage analysis, the solution generates granular, per-region visualization dashboards that translate complex telemetry into clear, actionable insights. This tool is essential for cloud architects and finance teams looking to optimize Azure spend, ensure high availability, and eliminate resource bottlenecks through data-driven capacity planning.

## 🛠️ Tech Stack

- 🐍 Python


## 📦 Key Dependencies

```
fastapi: 0.111.0
uvicorn: 0.30.1
pydantic: 2.7.4
pandas: 2.1.4
numpy: 1.26.4
scikit-learn: 1.5.0
xgboost: 2.0.3
statsmodels: 0.14.2
joblib: 1.4.2
schedule: 1.2.2
streamlit: 1.35.0
plotly: 5.22.0
```

## 📁 Project Structure

```
.
├── Arpit_Agile_Template_v0.1.xlsm
├── Arpit_Defect_Tracker Template_v0.1.xlsx
├── Arpit_Unit_Test_Plan_v0.1.xlsx
├── Azure_Demand_Forecasting_Data.csv
├── LICENSE.txt
├── actual_vs_predicted.png
├── api.py
├── api_log.txt
├── azure_demand.py
├── batch_log.txt
├── batch_predict.py
├── best_arima_model.pkl
├── dashboard_app.py
├── demand_forecast_comparison.png
├── feature_importance.png
├── filtered_forecast_20260328.csv.xlsx
├── forecast_output.csv
├── metrics_report_20260328.json
├── milestone_three.py
├── milestone_two.py
├── model_rmse_comparison.png
├── monitoring.py
├── monitoring_log.txt
├── new_data.csv
├── requirements.txt
├── rmse_history.csv
├── scheduler.py
├── scheduler_log.txt
├── usage_units_Central-India.png
├── usage_units_East-Asia.png
├── usage_units_East-US.png
├── usage_units_UK-South.png
└── usage_units_West-US.png
```

## 🛠️ Development Setup

### Python Setup
1. Install Python (v3.8+ recommended)
2. Create a virtual environment: `python -m venv venv`
3. Activate the environment:
   - Windows: `venv\Scripts\activate`
   - Unix/MacOS: `source venv/bin/activate`
4. Install dependencies: `pip install -r requirements.txt`


## 👥 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Clone** your fork: `git clone https://github.com/ArpitKumar07/azure-demand-capacity-optimization.git`
3. **Create** a new branch: `git checkout -b feature/your-feature`
4. **Commit** your changes: `git commit -am 'Add some feature'`
5. **Push** to your branch: `git push origin feature/your-feature`
6. **Open** a pull request

Please ensure your code follows the project's style guidelines and includes tests where applicable.

## 📜 License

This project is licensed under the LICENSE License.
