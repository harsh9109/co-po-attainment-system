# CO-PO Attainment System (Theory + Practical)

A Streamlit-based NBA analytics and reporting system for Course Outcome (CO), Program Outcome (PO), and Program Specific Outcome (PSO) attainment.

This app supports:
- **Theory Mode**
- **Practical Mode** (dynamic external components such as Practical, Term Work, Oral)

It generates:
- CO internal/external/final attainment tables
- Discrimination Index (DI) analytics
- PO/PSO attainment analytics
- Charts/dashboard
- Exportable **Excel** and **PDF** reports

---

## 1) Features

- NBA attainment level logic (0 to 3)
- Exam-wise attainment computation
- DI using configurable top/bottom percentages
- CO final attainment using internal/external weightages
- CO to PO and CO to PSO contribution mapping
- Modern Streamlit dashboard UI
- Excel + PDF report export

---

## 2) Project Structure

- `app.py` - Main Streamlit application
- `requirements.txt` - Python dependencies
- `.streamlit/config.toml` - Streamlit UI/server config
- `.gitignore` - Ignore local/cache/generated files

---

## 3) Local Setup

### Prerequisites
- Python 3.10+ (recommended)
- `pip`

### Install

```bash
pip install -r requirements.txt
```

### Run

```bash
streamlit run app.py
```

---

## 4) How to Use

1. Open the app in browser (after `streamlit run app.py`).
2. In **Input & Config** tab:
   - Select **Assessment Mode**: `Theory` or `Practical`
   - Enter subject and CO details
   - Configure weightages and DI settings
   - Configure mappings (CO-Exam, CO-PO, CO-PSO)
   - Upload marks Excel (or download sample template first)
3. Click **Calculate CO-PO Attainment**.
4. Review outputs in:
   - **Results**
   - **Charts**
   - **Export**
5. Download Excel/PDF reports from Export tab.

---

## 5) Input Format

### Theory Mode Required Columns
- `Student Name`
- `Unit Test 1`
- `Unit Test 2`
- `Unit Test 3`
- `Prelim`
- `Insem`
- `Endsem`

### Practical Mode Required Columns
- `Student Name`
- `Internal`
- `External_Component_1`
- `External_Component_2`
- ... (based on how many external components you configure in app)

> Tip: use the in-app **Download Sample Template** button for the selected mode.

---

## 6) Deploy on Streamlit Community Cloud

1. Push this project to a GitHub repository.
2. Go to [https://share.streamlit.io](https://share.streamlit.io).
3. Click **New app** and choose your repo/branch.
4. Set:
   - **Main file path**: `app.py`
5. Deploy.

Streamlit Cloud automatically installs packages from `requirements.txt`.

---

## 7) Optional Deployment Notes

- If deploy is slow or fails, confirm package install logs for:
  - `reportlab`
  - `matplotlib`
  - `openpyxl`
- Keep filenames and imports case-sensitive.
- Avoid uploading very large Excel files on free tiers.

---

## 8) Troubleshooting

- **ModuleNotFoundError**  
  Re-run `pip install -r requirements.txt`.

- **Excel upload error**  
  Ensure required columns exist exactly as expected.

- **No results showing**  
  Confirm you clicked **Calculate CO-PO Attainment** after upload/config.

---

## 9) License

Use within your academic/institutional context as needed.
