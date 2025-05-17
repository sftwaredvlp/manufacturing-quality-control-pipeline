# 🏭 Manufacturing Quality Control Data Pipeline

An end-to-end ETL pipeline for processing manufacturing quality data, validating inputs, and monitoring product defect trends.

## 🚀 Project Highlights
- Built with **Python**, **SQL**, and **Airflow**
- Ingests raw production data from `.csv` files
- Applies validation rules (missing values, outliers)
- Loads cleaned data into a simulated data warehouse
- Sends alerts on high defect rates

## 🛠 Technologies
- Python, Pandas
- Apache Airflow
- SQL
- Matplotlib, Seaborn

## 🧠 Use Case
Optimize manufacturing quality control and reduce defect rate by automating data validation and visualization of anomaly patterns.

## 📊 Data Source
[Kaggle: Predictive Maintenance Dataset](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance)

## 📈 Architecture Diagram
![architecture](architecture_diagram.png)

## 📂 File Structure
- `dags/`: Airflow DAGs for pipeline orchestration
- `data/raw`: Input data
- `data/processed`: Cleaned data
- `notebooks/`: Exploratory and EDA notebooks

## 📬 Contact
[LinkedIn](https://www.linkedin.com/in/hasan-%C3%A7am/) • [GitHub](https://github.com/sftwaredvlp)


manufacturing-quality-control-pipeline/
│
├── dags/
│   └── etl_quality_pipeline.py
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── exploratory_analysis.ipynb
│
├── airflow.cfg (isteğe bağlı dummy)
├── requirements.txt
├── README.md
└── architecture_diagram.png