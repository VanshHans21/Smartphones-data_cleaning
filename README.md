# Smartphone Data Cleaning & Feature Engineering

A Python-based data cleaning and feature engineering project focused on transforming raw smartphone specification data into a structured, analysis-ready dataset.

## 📌 Project Overview

The raw smartphone dataset contained inconsistent, incomplete, and unstructured specification values across multiple columns. The objective of this project was to clean the data, correct inconsistent records, extract useful features, and convert raw text specifications into structured numerical and categorical variables.

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook

## 📊 Dataset

- Raw records: **1,020**
- Cleaned records: **977**
- Removed invalid/unusable records: **43**
- Created and standardized **30+ structured features**

## 🔧 Data Cleaning

The following cleaning and correction tasks were performed:

- Removed currency symbols and commas from smartphone prices.
- Removed low-price feature-phone records that were not relevant to the analysis.
- Identified and corrected misaligned or inconsistent records.
- Cleaned processor, RAM, ROM, battery, display, camera, and memory-card information.
- Standardized inconsistent text labels and units.
- Converted columns into appropriate numerical, Boolean, categorical, and string data types.
- Removed redundant raw columns after feature extraction.

## ⚙️ Feature Engineering

Extracted structured features from unstructured smartphone specifications, including:

- RAM (GB)
- ROM (GB)
- Processor Name
- Processor Cores
- Processor Speed (GHz)
- Battery Capacity
- Fast Charging
- Display Size
- Display Resolution
- Refresh Rate
- Notch Type
- Primary Rear Camera (MP)
- Primary Front Camera (MP)
- Rear Camera Count
- Front Camera Count
- Expandable Storage
- Memory Card Support
- Brand

### Smartphone Feature Indicators

Created binary indicators for:

- Dual SIM
- 5G Support
- NFC Support
- IR Blaster
- Fast Charging Support
