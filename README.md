# WMS-SKU_MSKU_Project
Sub: created a Streamlit app to map SKU → MSKU

# 📦 Warehouse Management System (WMS) - MVP

## 👨‍💻 Developed by: Gaurishankar Vhadle

## 🧰 Tech Stack
- Python (Pandas, FuzzyWuzzy)
- Streamlit
- Baserow (as relational DB frontend)

## 🎯 Features
- CSV Upload for sales data
- SKU → MSKU Mapping with fuzzy matching
- Handles unmapped SKUs, combo products
- Cleaned data export
- Baserow integration for relational view

## 📽️ Loom Video
🔗 [https://www.loom.com/share/a9f21016746f4562a75ffd41333d86fb]

## 🔗 Live Tools
- 📊 Baserow DB: [https://baserow.io/database/258607/table/610694/1142825]
- 📎 Cleaned Sample File: `sku_msku_mapping_cleaned`

## 🚀 How to Run the App
```bash
pip install streamlit pandas fuzzywuzzy python-Levenshtein
streamlit run sku_mapping_app.py
