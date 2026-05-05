# 🎓 CO-PO Attainment System (NBA Analytics Tool)

A professional **Streamlit-based web application** for automating Outcome-Based Education (OBE) analytics aligned with **NBA accreditation standards**.
It computes **Course Outcomes (CO), Program Outcomes (PO), and Program Specific Outcomes (PSO)** from student data and generates structured reports.

---

## 🚀 Key Features

* 📊 CO internal, external & final attainment calculation
* 📈 Discrimination Index (DI) analysis with configurable parameters
* 🔗 CO–PO & CO–PSO mapping contribution analysis
* 🧠 Intelligent academic insights & performance evaluation
* 📉 Interactive dashboards (Plotly + Matplotlib)
* 📄 Export reports in **Excel & PDF formats**
* 🔄 Supports both **Theory & Practical modes**

---

## 🏗️ Tech Stack

* **Frontend/UI:** Streamlit
* **Data Processing:** Pandas, NumPy
* **Visualization:** Plotly, Matplotlib
* **Reporting:** ReportLab, OpenPyXL

---

## 📂 Project Structure

```
.
├── app.py                  # Main Streamlit application
├── requirements.txt        # Dependencies
├── README.md               # Project documentation
├── .streamlit/config.toml  # Streamlit configuration
└── .gitignore              # Ignored files
```

---

## ⚙️ Local Setup

### Prerequisites

* Python 3.10 or 3.11
* pip

### Installation

```bash
pip install -r requirements.txt
```

### Run Application

```bash
streamlit run app.py
```

---

## 📌 How to Use

1. Open the app in your browser
2. Select **Assessment Mode** (Theory / Practical)
3. Enter subject & CO details
4. Configure:

   * Weightages
   * DI settings
   * CO mappings
5. Upload student marks Excel file
6. Click **Calculate CO-PO Attainment**
7. View:

   * Results
   * Charts
   * Export reports

---

## 📥 Input Format

### Theory Mode

* Student Name
* Unit Test 1
* Unit Test 2
* Unit Test 3
* Prelim
* Insem
* Endsem

### Practical Mode

* Student Name
* Internal
* External components (configurable)

> ⚡ Tip: Use the in-app **sample template download** for correct format.

---

## 🌐 Deployment

Easily deploy using **Streamlit Community Cloud**:

1. Push this repo to GitHub
2. Go to https://share.streamlit.io
3. Click **New App**
4. Select repo and set:

   * Main file: `app.py`
5. Deploy 🚀

---

## ⚠️ Troubleshooting

* **ModuleNotFoundError** → Check `requirements.txt`
* **Excel upload issues** → Verify column names
* **No output** → Click *Calculate* button

---

## 🎯 Use Case

* NBA Accreditation Documentation
* Academic Performance Analysis
* Faculty Decision Support System
* Outcome-Based Education Implementation

---

## 📜 License

This project is licensed under the **MIT License**.
You are free to use, modify, and distribute it with proper attribution.

---

## 👨‍💻 Author

**Harshvardhan Bharat Mali**
Embedded Systems | AI | VLSI Enthusiast

🔗 LinkedIn: https://www.linkedin.com/in/harshvardhanmali910
🔗 GitHub: https://github.com/harsh9109

---

⭐ If you found this project useful, consider giving it a star!
