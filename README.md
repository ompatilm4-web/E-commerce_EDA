# 🛒 E-Commerce Sales Analysis — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter) ![Pandas](https://img.shields.io/badge/Pandas-EDA-green) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📦 Dataset

- **Size:** 17,379 orders · 20 features
- **Domain:** Indian E-Commerce platform
- **Key Columns:** Product Category, Customer Segment, City, Payment Method, Unit Price, Discount, Net Revenue, Order Date (2022–2023)

> The dataset is stored in the `/Data` folder of this repository.

---

## ❓ Business Questions Answered

| # | Question |
|---|----------|
| 1 | Which products generate the most revenue? |
| 2 | Who are the most valuable customers? |
| 3 | What factors most strongly drive sales? |
| 4 | Which cities have the highest shipping costs? |
| 5 | Which payment methods contribute the most revenue? |

---

## 📊 Key Insights

> **1. Laptops dominate revenue** — Laptops ranked #1 in revenue generation across all product categories, followed by Tablets.

> **2. Standard-segment customers are the most valuable** — The Standard customer segment contributed the largest share of total revenue, outperforming both Silver and Gold segments.

> **3. Sales grew ~7–8% year-over-year** — Revenue increased consistently from 2022 to 2023. Credit Card was the top payment method, followed by Debit Card. Chennai and Pune recorded the highest shipping costs.

> **4. Strongest revenue predictors:** Unit Price, Subtotal, Discount Amount, and Net Amount showed the highest correlation with total revenue.

---

## 🗂️ Project Structure

```
E-commerce_EDA/
├── Data/                  # Raw dataset
├── Notebooks/             # Jupyter analysis notebooks
├── Project_Goals.md       # Business questions & conclusions
├── requirements.txt       # Python dependencies
└── README.md
```

---

## 🛠️ Tools & Libraries

| Library | Purpose |
|---------|---------|
| `pandas` | Data loading, cleaning, aggregation |
| `numpy` | Numerical operations |
| `matplotlib` | Base visualizations |
| `seaborn` | Statistical plots & heatmaps |
| `scikit-learn` | Correlation & feature analysis |

---

## 📸 Sample Visualizations

> 📌 **Revenue by Product Category**
> *(Add your chart screenshot here — e.g., `![Revenue Chart](Data/charts/revenue_by_category.png)`)*

> 📌 **Customer Segment Revenue Distribution**
> *(Add your chart screenshot here)*

> 💡 **How to add screenshots:** Export your best notebook chart using `plt.savefig('chart.png')`, upload it to the `/Data` folder, and replace the placeholders above.

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/ompatilm4-web/E-commerce_EDA.git
cd E-commerce_EDA

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook Notebooks/
```

---

## 👤 Author


**Om Patil** · [GitHub](https://github.com/ompatilm4-web)
