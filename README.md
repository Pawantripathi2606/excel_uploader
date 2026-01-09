# 📤 Excel Uploader – Bulk Data Upload App

**Live App:** https://excel-uploader-1.onrender.com

This application helps users **upload bulk datasets (CSV / Excel files) directly into their database** through a simple web interface.

It is designed to simplify **bulk data ingestion** without writing manual SQL queries, making it useful for data analysts, developers, and database administrators.

---

## 🚀 What This App Does

- Upload **CSV / Excel files** in bulk
- Automatically reads dataset structure
- Creates database tables dynamically
- Inserts large datasets into the connected database
- Saves time compared to manual data entry

---

## 🛠️ Tech Stack

- Python (Flask)
- Pandas
- MySQL
- HTML (Jinja Templates)
- Gunicorn
- Render (Deployment)

---

## 🎯 Use Case

- Bulk upload datasets into databases  
- Data migration and ingestion  
- Backend support for analytics projects  
- Quick database population for testing  

---

## ▶️ Run Locally

```bash
pip install -r requirements.txt
python app.py
