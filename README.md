# Earthquake-Analysis-Dashboard
# 🌍 Earthquake Data Analysis and Visualization Using AWS

## 📘 Project Overview

This project presents an **end-to-end data analytics and machine learning pipeline** for earthquake data analysis using **Amazon Web Services (AWS)**.  
It collects, preprocesses, analyzes, and visualizes earthquake data to identify patterns, trends, and regional insights about seismic activities.  

The system integrates **AWS S3**, **AWS Glue**, and **Amazon SageMaker** to automate the workflow from raw data ingestion to interactive visualization.

---

## 🚀 Key Features

- **Automated Data Processing:**  
  Data cleaning and transformation using AWS Glue crawlers and ETL jobs.  

- **Scalable Storage:**  
  Amazon S3 used as the central data lake for all project components — raw, processed, and result data.

- **Machine Learning Integration:**  
  Earthquake prediction and analysis using SageMaker notebooks.  

- **Interactive Dashboard:**  
  Custom-built dashboard (HTML + JSON + JavaScript) for data visualization, featuring:  
  - Search by location  
  - Map highlighting earthquake events  
  - Analytical graphs (frequency, magnitude, and depth distribution)

- **Modular Workflow:**  
  Each stage — ingestion, preprocessing, modeling, and visualization — is independently scalable and reusable.

---

## 🧠 Tech Stack

| Category | Tools / Services |
|-----------|------------------|
| Cloud Platform | **AWS** |
| Storage | Amazon **S3** |
| Data Preprocessing | **AWS Glue** (Crawler + ETL Job) |
| Machine Learning | **Amazon SageMaker** |
| Visualization | **HTML**, **CSS**, **JavaScript**, **Leaflet.js / Plotly** |
| Data Format | CSV → Parquet |
| Language | **Python** |

---

## 🗂️ Project Structure

