<div align="center">

# 📊 Bank Statement Analyzer

**Parse • Clean • Analyze Indian Bank Statement PDFs**

A Python + Jupyter Notebook project to convert messy bank statement PDFs into
**clean, structured, and analysis-ready data**.

</div>

## ✨ Overview

**Bank Statement Analyzer** is a **Jupyter Notebook–first** project that helps you automatically:

* Extract transactions from Indian bank statement PDFs
* Normalize **Debit / Credit** logic across banks
* Identify and clean **merchant names**
* Generate **merchant-wise expense summaries**
* Export results as **CSV files** for Excel or BI tools

Designed with **data privacy, extensibility, and readability** in mind.

---

## 🚀 Features

| Feature                       | Description                                  |
| ----------------------------- | -------------------------------------------- |
| 📄 PDF Parsing                | Reads structured & semi-structured bank PDFs |
| 🔁 Debit/Credit Normalization | Consistent logic across different banks      |
| 🏷 Merchant Extraction        | Smart extraction from transaction narration  |
| 🧹 Merchant Normalization     | Standardizes names across formats            |
| 📊 Expense Summary            | Merchant-wise & category-wise analysis       |
| 💾 CSV Export                 | Ready for Excel, Sheets, Power BI            |
| 🔐 Privacy-Safe               | No real data included                        |
| 🧩 Extensible                 | Easy to add new banks                        |

---

## 🏦 Supported Banks

* ✅ Kotak Mahindra Bank
* ✅ HDFC Bank

> More banks can be added by implementing a new parser and plugging it into the unified pipeline.

---

## 🧠 How It Works

```text
PDF Statement
     ↓
Bank-specific Parsing
     ↓
Transaction Normalization
     ↓
Merchant Extraction
     ↓
Merchant Cleaning
     ↓
Aggregation & Analysis
     ↓
CSV Output
```

---

## 🛠 Tech Stack

* **Python**
* **Jupyter Notebook (.ipynb)**
* **pandas**
* PDF parsing libraries (`pdfplumber`, `tabula`, etc.)

---

## 📂 Project Structure

```text
Bank-Statement-Analyzer/
│
├── BankStatementAnalyser.ipynb   # Main notebook  
├── README.md
└── .gitignore
```

---

## ⚙️ Quick Start

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/ArkonVennon/bank-statement-analyzer.git
cd bank-statement-analyzer
```

### 2️⃣ Open the Notebook

```bash
jupyter notebook BankStatementAnalyser.ipynb
```

### 3️⃣ Configure Inputs (Top of Notebook)

```python
BANK_TYPE = "HDFC"   # Options: HDFC | KOTAK
PDF_PATH = "sample_statement.pdf"
OUTPUT_CSV = "merchant_summary.csv"
```

### 4️⃣ Run All Cells

Results will be generated automatically 🎉

---

## 📈 Output Files

| File Name                | Description                     |
| ------------------------ | ------------------------------- |
| `transactions_clean.csv` | Cleaned transaction-level data  |
| `merchant_summary.csv`   | Merchant-wise debit aggregation |

Compatible with:

* Excel
* Google Sheets
* Power BI
* Tableau

---

## 🔐 Data Privacy & Security

⚠️ **Important Notice**

* ❌ No real bank statements included
* ❌ No account numbers, UPI IDs, or phone numbers
* ✅ All sample data is **masked or synthetic**
* 🖥 Designed to run **locally only**

**Do not upload real bank statements to public repositories.**

---

## 🧩 Customization

### ➕ Add a New Bank

* Create a bank-specific parser
* Plug it into the unified pipeline

### 🏷 Modify Merchant Rules

Edit:

```python
normalize_merchant()
```

to add:

* New brands
* Subscription tagging
* Category mapping

### 📊 Extend Analysis

* Monthly spend
* Category summaries
* Payment-mode breakdown

---

## 🎯 Use Cases

* 💰 Personal expense tracking
* 📊 Financial analysis & budgeting
* 🧾 Audit & transaction review
* 🧠 Learning PDF data extraction
* 🧪 Data cleaning & normalization practice

---

## ✅ Best Practices

Before committing:

* Clear notebook outputs
* Remove real transaction text
* Use dummy PDFs only
* Verify notebook runs end-to-end

---

## 📜 License

Open for **educational and personal use**.
Feel free to fork, modify, and extend.

---

<div align="center">

⭐ If you find this useful, consider giving the repo a star!

</div>

---

Working on adding :

* 🎨 **Badges + shields**
* 📦 **Template repo version**
* 🧼 **Notebook rewritten to match this README**


Just tell me 👍
