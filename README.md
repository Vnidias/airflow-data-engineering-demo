# Airflow Data Engineering Pipeline Demo

A simple, self-contained Airflow DAG demonstrating a mock extract → transform workflow using local data (no internet/email required).

Perfect for interviews or learning how to build pipelines with Apache Airflow.

## 📦 Features

- Uses `PythonOperator`
- Fully offline (mocked API data)
- Works with official Docker Compose setup
- No external dependencies
- Easy to demo or extend

## 🛠️ How to Run

1. Make sure you're using the official Airflow Docker Compose setup
2. Place your DAG in the `dags/` folder
3. Start Airflow: `docker-compose up -d`
4. Open UI at [http://localhost:8080](http://localhost:8080)
5. Trigger the DAG manually

## 🎯 Head Topics of this

- Modular DAG design
- Task communication via XCom
- Airflow Operators and task dependencies
- Running locally with Docker