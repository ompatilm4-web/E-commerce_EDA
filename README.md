<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=E-Commerce%20EDA&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Exploratory%20Data%20Analysis%20%7C%20Python%20%7C%20Pandas%20%7C%20Matplotlib%20%7C%20Seaborn&descAlignY=58&descSize=14&animation=fadeIn" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&pause=1000&color=6C8CFF&center=true&vCenter=true&width=650&lines=Uncovering+patterns+in+E-Commerce+data+%F0%9F%9B%92;Data+Cleaning+%E2%86%92+Analysis+%E2%86%92+Visualization+%F0%9F%93%8A;From+raw+transactions+to+business+insights+%F0%9F%92%A1;Built+as+a+portfolio+EDA+project+%F0%9F%93%81)](https://git.io/typing-svg)

<br/>

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)](https://matplotlib.org)
[![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=for-the-badge)](https://seaborn.pydata.org)
[![Stars](https://img.shields.io/github/stars/ompatilm4-web/E-commerce_EDA?style=for-the-badge&color=fbbf24&logo=github)](https://github.com/ompatilm4-web/E-commerce_EDA/stargazers)

</div>

---

## 📌 About This Project

This project performs **Exploratory Data Analysis (EDA)** on a real-world E-Commerce dataset — starting from raw, uncleaned transaction data and working through to meaningful business insights backed by visualizations.

The full pipeline covered:

```
Raw Data  →  Cleaning & Encoding  →  Analysis  →  Visualization  →  Insights
```

---

## 🗂️ Repository Structure

```
E-commerce_EDA/
│
├── Data/
│   ├── Raw_data.csv          ← Original dataset, unmodified
│   ├── Cleaned.csv           ← After handling nulls, duplicates, type fixes
│   └── Encoded_Data.csv      ← After categorical encoding for analysis
│
├── Notebooks/
│   ├── Analysis.ipynb        ← Data cleaning, EDA, statistical summaries
│   └── Visualization.ipynb   ← All charts, plots, and visual insights
│
├── Project_Goals.md          ← Objectives and scope of the project
├── requirements.txt          ← Python dependencies
└── README.md
```

---

## 📓 Notebooks

### 🔍 `Analysis.ipynb`

The core EDA notebook. Covers the full data preparation and analysis pipeline:

| Stage | What was done |
|---|---|
| **Data Loading** | Loaded `Raw_data.csv`, inspected shape, dtypes, and sample rows |
| **Cleaning** | Handled missing values, removed duplicates, fixed data types |
| **Encoding** | Encoded categorical columns → saved as `Encoded_Data.csv` |
| **Univariate Analysis** | Distribution of individual features — sales, quantity, categories |
| **Bivariate Analysis** | Relationships between price, quantity, revenue, customer segments |
| **Statistical Summary** | `describe()`, correlation matrix, value counts, groupby aggregations |

---

### 📊 `Visualization.ipynb`

All visual outputs from the analysis, built with Matplotlib and Seaborn:

| Chart Type | Insight explored |
|---|---|
| Bar charts | Top-selling products and categories |
| Line plots | Sales trends over time |
| Heatmap | Feature correlation matrix |
| Boxplots | Price and quantity distribution, outlier detection |
| Count plots | Category frequency breakdown |
| Scatter plots | Price vs. quantity relationships |

---

## 📂 Data Pipeline

| File | Description |
|---|---|
| `Raw_data.csv` | Original source data — untouched |
| `Cleaned.csv` | Post-cleaning: nulls handled, types fixed, duplicates removed |
| `Encoded_Data.csv` | Post-encoding: categorical columns converted for numerical analysis |

> Each stage is saved separately so every step of the pipeline is reproducible and auditable.

---

## 🚀 Getting Started

**1 — Clone**
```bash
git clone https://github.com/ompatilm4-web/E-commerce_EDA.git
cd E-commerce_EDA
```

**2 — Create virtual environment**
```bash
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
```

**3 — Install dependencies**
```bash
pip install -r requirements.txt
```

**4 — Open notebooks**
```bash
jupyter notebook
```

Start with `Notebooks/Analysis.ipynb`, then move to `Notebooks/Visualization.ipynb`.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| 🐍 Python | Core language |
| 📓 Jupyter Notebook | Interactive analysis environment |
| 🐼 Pandas | Data cleaning, manipulation, aggregation |
| 📈 Matplotlib | Base plotting and chart customization |
| 🎨 Seaborn | Statistical visualizations |

---

## 🤝 Contributing

```bash
git checkout -b improve/analysis-section
git commit -m "Improve: add RFM segmentation to Analysis notebook"
git push origin improve/analysis-section
```

---

<div align="center">

**Built and maintained by [Om Patil](https://github.com/ompatilm4-web)**

[![GitHub](https://img.shields.io/badge/GitHub-ompatilm4--web-181717?style=flat-square&logo=github)](https://github.com/ompatilm4-web)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer&animation=fadeIn" width="100%"/>

> ⭐ If this project helped you understand EDA, drop a star — it helps others find it.

</div>