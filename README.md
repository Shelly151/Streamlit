# ML Monitoring Dashboard with Evidently and Streamlit

This example demonstrates how to set up a Streamlit dashboard for monitoring data and model metrics using [Evidently]


## 📌 Prerequisites
- Python >= 3.9.12 (Recommended)
- Jupyter Notebook installed
- Streamlit version 1.19.0 does **not** work with Python 3.9.7

---

## 👩‍💻 Installation

### 1️⃣ Clone the Repository
First, fork and clone the Evidently repository:
```bash
git clone git@github.com:evidentlyai/evidently.git
cd evidently/examples/integrations/streamlit-dashboard
```

### 2️⃣ Create a Virtual Environment
Set up a virtual environment and install dependencies:
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### 3️⃣ Set Up Jupyter Notebook
Install the necessary Jupyter kernel and extensions:
```bash
python -m ipykernel install --user --name=evidently
jupyter contrib nbextension install --user
```

---

## 📺 Launch Monitoring Dashboards
To start the Streamlit dashboard:
```bash
cd streamlit-app
streamlit run app.py
```
This command launches a local Streamlit server, and the monitoring dashboard will open in a new browser tab.

---

## ▶️ Generate Monitoring Reports with Evidently

### 1️⃣ Run Jupyter Notebook
Navigate to the `bike-sharing` project directory:
```bash
cd projects/bike-sharing
jupyter notebook
```

### 2️⃣ Generate New Reports
- Open the `bicycle_demand_monitoring.ipynb` notebook.
- Run all cells to generate predictions and Evidently reports.

---

## 📚 Additional Resources
- [Evidently Documentation](https://docs.evidentlyai.com/)
- [Streamlit Documentation](https://docs.streamlit.io/)
- [Jupyter Notebook](https://jupyter.org/)

Happy Monitoring! 🚀

