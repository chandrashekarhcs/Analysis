#  BigBasket Data Analysis

##  Project Overview
This project performs an **exploratory and business-focused data analysis** on BigBasket product data to uncover trends in pricing, categories, discounts, and product distribution.

The goal is to derive **actionable insights** that can help in:
- Pricing strategy
- Product assortment planning
- Customer behavior understanding
- Business decision-making

---

##  Dataset
- **Source:** BigBasket product dataset (Excel)
- **Format:** `.xlsx`
- **Contents include:**
  - Product names
  - Categories
  - Sub-categories
  - Prices
  - Discounts
  - Ratings (if available)

> The raw dataset is stored in the `data/` directory.

---

##  Key Analysis Performed
- Data cleaning and preprocessing
- Category-wise product distribution
- Price range analysis
- Discount patterns across categories
- Identification of premium vs budget segments
- Outlier detection in pricing

---

##  Tools & Technologies
- **Python**
- **Pandas & NumPy** – data manipulation
- **Ms Excel** – visualization
- **Excel (openpyxl)** – data ingestion

---

##  Visualizations
The project includes multiple visualizations such as:
- Bar charts for category distribution
- Price vs discount analysis
- Histograms of product prices
- Comparative analysis across categories

---

##  Key Insights
- Certain categories dominate the product catalog, indicating core business focus.
- Discounts are not uniformly distributed and are heavily skewed toward specific product types.
- Premium-priced products exist across all major categories, not just niche segments.
- A small number of products significantly influence average pricing.

Detailed insights can be found in `analysis/insights_summary.md`.

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bigbasket-data-analysis.git
