# 🪙 Gold Price Forecasting using Prophet

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)](https://www.python.org/)
[![Prophet](https://img.shields.io/badge/Forecasting-Prophet-success?logo=meta)](https://facebook.github.io/prophet/)
[![Plotly](https://img.shields.io/badge/Visualization-Plotly-orange?logo=plotly)](https://plotly.com/)
[![License](https://img.shields.io/badge/License-MIT-lightgrey)](LICENSE)

Forecasting gold prices with **Meta’s Prophet** — a powerful time-series model — and visualizing future trends through **interactive Plotly charts**.  
This project also includes exporting forecast results to **Excel (.xlsx)** and **HTML dashboards**, making it ideal for financial analysis and reporting.

---

## 📘 Table of Contents
1. [Overview](#-overview)
2. [Features](#-features)
3. [Project Structure](#-project-structure)
4. [Installation](#-installation)
5. [Usage](#-usage)
6. [Example Output](#-example-output)
7. [Disclaimer](#-disclaimer)
8. [Author](#-author)

---

## 📖 Overview

Predicting gold prices is essential for **investors**, **economists**, and **financial analysts**.  
This project demonstrates how to use **Prophet**, a forecasting model developed by Meta (formerly Facebook), to analyze historical gold price trends and predict future prices.

The model is trained on real historical gold data and produces both:
- **Interactive forecasts** (displayed in Jupyter Notebook)
- **Exportable forecast reports** (Excel + HTML)

---

## 🌟 Features

✅ Load, clean, and prepare historical gold price data  
✅ Train Prophet model for up to **10-year forecast**  
✅ Display **interactive Plotly charts** directly in Jupyter Notebook  
✅ Export forecast results to **Excel (.xlsx)** and **HTML dashboard**  
✅ Clean, modular, and reusable Python code  

---

## 🗂️ Project Structure

```
gold-price-forecast-prophet/
│
├── data/
│   └── XAU USD Gold Price.csv              # Historical dataset
│
├── notebooks/
│   └── Gold_Price_Prediction.ipynb         # Jupyter notebook (interactive analysis)
│
├── scripts/
│   ├── gold_forecast_interactive.py        # Interactive forecast display
│   └── gold_forecast_export.py             # Export forecast to Excel & HTML
│
├── results/
│   ├── Gold_Price_Forecast.xlsx            # Example output file
│   └── Gold_Price_Forecast.html            # Example interactive dashboard
│
├── requirements.txt                         # Required Python packages
├── README.md                                # Project documentation
└── .gitignore                               # Ignore unnecessary files
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/YOUR-USERNAME/gold-price-forecast-prophet.git
cd gold-price-forecast-prophet
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ (Optional) Launch Jupyter Notebook
```bash
jupyter notebook
```

---

## 🚀 Usage

### 🧠 Option 1: Interactive Forecast in Jupyter Notebook
Open:
```
notebooks/Gold_Price_Prediction.ipynb
```

Run all cells to:
- Load and prepare the dataset  
- Train the Prophet model  
- Visualize an **interactive forecast chart** inside the notebook  

### 💼 Option 2: Export Forecast to Excel & HTML
Run from terminal:
```bash
python scripts/gold_forecast_export.py
```

This will generate:
- `results/Gold_Price_Forecast.xlsx` — Excel sheet with forecast data  
- `results/Gold_Price_Forecast.html` — Interactive dashboard  

---

## 📊 Example Output

**Forecast Chart (Sample Preview)**

![Forecast Example](https://user-images.githubusercontent.com/your-image-link-here.png)

The interactive Plotly chart allows zooming, panning, and hovering over forecasted gold price values.

---

## 🧩 Technologies Used

| Category | Library / Tool | Purpose |
|-----------|----------------|----------|
| Data Handling | `pandas` | Loading and processing CSV data |
| Forecasting | `prophet` | Building and training the time-series model |
| Visualization | `plotly` | Interactive charts |
| Exporting | `xlsxwriter` | Writing Excel files |

---

## ⚠️ Disclaimer

> ⚠️ **Note:**  
> This project is for **educational and research purposes only**.  
> Forecasts are based on **historical data** and **statistical modeling**, and do **not guarantee** future financial outcomes.  
> Always conduct independent research before making investment decisions.

---

## 🧑‍💻 Author

**Your Name**  
📧 Email: [your.email@example.com]  
🌐 GitHub: [github.com/YOUR-USERNAME](https://github.com/YOUR-USERNAME)  
🔗 LinkedIn: [linkedin.com/in/yourprofile](https://linkedin.com/in/yourprofile)

---

## ⭐ Contribute & Support

If you found this project helpful:
- ⭐ **Star** the repository  
- 🐛 Submit issues or suggestions  
- 🤝 Pull requests are welcome  

---

### 🏁 License
This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.
