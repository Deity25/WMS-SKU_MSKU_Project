# WMS-SKU_MSKU_Project
I created a Streamlit app to map SKU → MSKU

# 📦 Warehouse Management System (WMS) - MVP

## 👨‍💻 Developed by: Gaurishankar Vhadle

## 🧰 Tech Stack
- Python (Pandas, FuzzyWuzzy)
- Streamlit
- Baserow (as relational DB frontend)
- (Optional) OpenAI GPT API for Text-to-SQL

## 🎯 Features
- CSV Upload for sales data
- SKU → MSKU Mapping with fuzzy matching
- Handles unmapped SKUs, combo products
- Cleaned data export
- Baserow integration for relational view
- (Optional) AI-powered SQL querying

## 📽️ Loom Video
🔗 [Paste your Loom video link here]

## 🔗 Live Tools
- 📁 Google Drive: [Paste drive link]
- 📊 Baserow DB: [Paste baserow view link]
- 📎 Cleaned Sample File: `cleaned_sales.csv`

## 🚀 How to Run the App
```bash
pip install streamlit pandas fuzzywuzzy python-Levenshtein
streamlit run sku_mapping_app.py
