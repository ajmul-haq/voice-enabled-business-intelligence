# 🎙️ Voice-Enabled Business Intelligence System

This project demonstrates a **Voice-Enabled Business Intelligence (BI) system** built using Python and Power BI.  
Users can interact with business data using **natural language voice commands**, and the system automatically generates analytical insights and dashboards.

---

## 🔄 Project Flow
Voice Command → NLP Intent Parsing → Python Analysis → CSV Output → Power BI Dashboard

---

## 📁 Repository Structure


voice-enabled-business-intelligence/
├── run_voice_bi.py          # Main entry point
├── src/                     # Core Python logic
│   ├── voice_input.py
│   ├── command_parser.py
│   ├── analysis.py
│   └── utils.py
├── data/                    # Raw dataset
│   └── Sales_2014.csv
├── output/                  # Python-generated output
│   └── voice_output.csv
├── notebooks/               # Exploration notebooks
│   └── voice_bi_exploration.ipynb
├── powerbi/                 # Power BI assets
│   ├── voice_bi_dashboard.pbix
│   └── screenshots/

---

## 🧠 What This Project Shows

- Voice-based interaction with business data
- Rule-based NLP intent detection
- Automated data aggregation and visualization
- Integration between Python analytics and Power BI dashboards
- Clean separation between development (notebooks) and production code

---

## 🛠 Technologies Used

- Python
- pandas, matplotlib, seaborn
- SpeechRecognition, PyAudio
- Rule-Based NLP
- Power BI

---

## ▶️ How This Repository Is Used

- Python scripts generate analytical results and export them as CSV files
- Power BI consumes the exported CSV for interactive dashboards
- Jupyter notebooks are used only for exploration and experimentation

> Note: Environment setup steps are standard and intentionally omitted to keep the repository focused on structure and implementation.

---
## 📸 Power BI Dashboard Screenshots
![Dashboard Overview](powerbi/screenshots/dashboard_overview.png)
![Sales by Person](powerbi/screenshots/sales_by_person.png)

---
Run `python run_voice_bi.py` from the project root to start the voice-driven analysis.
---

## 🎯 Project Category

- Business Intelligence Automation
- Voice Interface Application
- Rule-Based NLP System

---

## 👤 Author

**Ajmul Haq**  
Data Analyst (Python | Power BI)

