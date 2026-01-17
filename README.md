# 🎙️ Voice-Driven Business Intelligence Dashboard  
### Python • NLP • Power BI

---

## 📌 Project Overview

This project demonstrates a **Voice / Text-Driven Business Intelligence (BI) system** where business questions are interpreted using **Natural Language Processing (NLP)** in Python and transformed into **decision-ready analytics** visualized in **Power BI**.

Instead of manually exploring dashboards, users can ask **natural language questions** (voice or text), and the system generates the relevant analytical output for Power BI to visualize.
![Power BI Dashboard]()

---

## 🎯 Business Problem

Business stakeholders often struggle to:

- Ask ad-hoc analytical questions without technical skills  
- Quickly identify product, region, or salesperson performance  
- Translate raw data into **actionable decisions**

Traditional dashboards are static and require manual filtering.

---

## 💡 Solution

This project solves the problem by:

- Using **NLP** to understand business questions  
- Running **Python-based analytics** on sales data  
- Exporting structured results to **Power BI**  
- Allowing decision-makers to explore insights visually  

---

## 🔄 Project Workflow



---

## 📊 Dataset Description

The dataset represents sales transactions with the following columns:

| Column Name   | Description |
|--------------|-------------|
| Date         | Sales transaction date |
| Region       | Sales region (East, West, North, South) |
| Product      | Product name |
| Salesperson  | Sales representative |
| Units_Sold   | Quantity sold |
| Unit_Price   | Price per unit |
| Category     | Product category |
| Revenue      | Total sales revenue |
| Cost         | Total cost |
| Profit       | Revenue − Cost |

---

## 🧹 Data Cleaning & Preparation

Key preprocessing steps include:

- Handling missing values  
- Standardizing text (lowercasing, trimming spaces)  
- Fixing spelling inconsistencies (e.g., `moblie → Mobile`)  
- Ensuring consistent schema for Power BI refresh  

---

## 🧠 NLP & Voice Command Layer

The system uses **rule-based NLP intent detection** to map user queries to analytics.

### Example Voice / Text Commands

- *"Show revenue by salesperson"*  
- *"Product wise sales"*  
- *"Region wise revenue"*  
- *"Monthly revenue trend"*  

Each command triggers a specific analysis function in Python.

---

## 📈 Power BI Dashboard

### Key Visuals Included

- **KPI Cards**
  - Total Revenue  
  - Total Profit  
  - Total Cost  
  - Total Units Sold  

- **Revenue Trend by Month**
- **Revenue by Region**
- **Revenue by Salesperson**
- **Revenue by Product**
- **Product Sales by Region (Matrix)**
- **Month-wise Sales by Product**
- **Top Products by Revenue**

The dashboard remains **generic**, while Python dynamically controls **what data is analyzed**.

---

## 🧠 Key Business Insights

- **Electronics category** contributes over half of total revenue  
- **Tablet** is the top-performing product across regions  
- **West region** generates the highest revenue  
- Sales performance varies significantly among salespersons  
- Revenue shows **seasonal fluctuations**, with mid-year peaks  

---

## 📌 Business Decisions Enabled

Based on insights, the business should:

- Prioritize **Tablet and Electronics** inventory and promotions  
- Strengthen operations in the **West region**  
- Improve sales strategies in underperforming regions  
- Reward and replicate strategies of top salespersons  
- Optimize costs to improve overall profit margin  

---

## 🛠️ Tech Stack

- **Python**
  - pandas, numpy  
  - matplotlib, seaborn  
  - SpeechRecognition  

- **NLP**
  - Rule-based intent parsing  

- **Power BI**
  - Interactive dashboards  
  - KPI monitoring  

---

## 📁 Repository Structure

voice-nlp-powerbi/
│
├── data/
│ ├── raw/
│ └── processed/
│
├── nlp/
│ ├── intent_keywords.py
│ └── parser.py
│
├── analysis/
│ ├── product_analysis.py
│ ├── region_analysis.py
│ └── salesperson_analysis.py
│
├── voice/
│ └── speech_input.py
│
├── powerbi/
│ └── sales_dashboard.pbix
│
├── main.py
├── requirements.txt
└── README.md

---

## 🚀 How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/yourusername/voice-nlp-powerbi.git
