# Kafka-Spark ETL Pipeline in Jupyter Notebooks

A simple end-to-end ETL pipeline using **Apache Kafka** and **Apache Spark**, built entirely in **Jupyter Notebooks**.

## 🔍 Overview

This project demonstrates how to:
- Extract data from an API and stream it to Kafka
- Ingest the Kafka stream into Apache Spark
- Apply transformations and save the output as Parquet files

## 📁 Project Structure

kafka-spark-etl/
├── notebooks/
│   └── pipeline.ipynb                # Extract: API to Kafka & Ingest + Transform: Kafka to Spark & Save: Spark output to Parquet
├── requirements.txt                  # Python dependencies
├── README.md                         # Project overview
└── .gitignore                        # Files to exclude from Git


## 🔧 Technologies Used

- **Python**
- **Apache Kafka**
- **Apache Spark (Structured Streaming)**
- **Jupyter Notebooks**
- **Parquet (as output format)**

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/kafka-spark-etl.git
cd kafka-spark-etl

pip install -r requirements.txt
