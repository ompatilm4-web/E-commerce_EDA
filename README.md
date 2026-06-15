
# E-commerce EDA

Exploratory data analysis of an e-commerce sales dataset (17,379 orders, 20 features) covering products, customers, payments, and shipping.

## Dataset

`Data/Cleaned.csv` includes:
- **Order details**: product, quantity, unit price, discount, subtotal, net amount, revenue
- **Customer info**: name, segment (New / Standard / Silver / Gold / Premium)
- **Logistics**: shipping city, method, cost
- **Payment**: method, status
- **Other**: order date (Year/Month/Day), rating, return flag

## Project Goals

See [`Project_Goals.md`](Project_Goals.md) for the full list of questions and findings.

## Key Findings

1. **Standard segment** customers generate the highest total revenue, followed by Silver.
2. **Laptops** generate the highest revenue, followed by Tablets.
3. Shipping costs are highest for **Chennai**, followed by Pune.
4. **Credit Card** is the top payment method by revenue, followed by Debit Card.
5. Revenue grew ~6% from 2023 to 2024.
6. `subtotal`, `discount_amount`, and `unit_price` show the strongest relationship with `Revenue`.

## Notebook

Analysis and visualizations are in [`Notebooks/Visualization.ipynb`](Notebooks/Visualization.ipynb), including distribution plots, revenue breakdowns by segment/product/city/payment method, and a correlation heatmap.

## Setup

```bash
pip install -r requirements.txt
jupyter notebook Notebooks/Visualization.ipynb
```

## Known Limitations

- `shipping_city` contains inconsistent formatting (case, whitespace, abbreviations) and would benefit from further standardization.
- Revenue forecasting is based on a single year-over-year comparison and would need a proper time-series model for reliable predictions.