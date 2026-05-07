#  Jumia Product Analysis – Excel & Dashboard Project

##  Project Overview

This project involves scraping, cleaning, and analyzing product data from **Jumia Kenya** to uncover insights around pricing, discounts, customer ratings, and product reviews. The findings are presented through an interactive **Excel dashboard** built to support data-driven decision-making for sellers and buyers on the platform.

---

##  Objectives

- Analyze product **discount patterns** across different categories
- Identify products with the **highest and lowest ratings**
- Understand the relationship between **discounts and customer reviews**
- Categorize products by **discount level** (Low, Medium, High)
- Highlight **missing data** (products with no reviews or ratings)

---

## 📂 Dataset Description

The dataset contains **109 products** scraped from Jumia Kenya across various home and lifestyle categories.

| Column | Description |
|---|---|
| `Product` | Name of the product |
| `Current Price` | Current selling price (KES) |
| `Old Price` | Original price before discount (KES) |
| `Discount Amt` | Amount discounted (KES) |
| `Discount` | Discount percentage (decimal) |
| `Discount Cat` | Discount category — Low, Medium, or High |
| `Review` | Number of customer reviews |
| `Rating /5` | Average customer rating out of 5 |
| `Rating Category` | Rating label — Excellent, Average, Poor, or Missing |

---

## Key Insights

- **Total Products Analyzed:** 109
- **Average Rating:** 3.89 / 5
- **Average Discount:** 36.3%
- **Total Customer Reviews:** 723
- **Highest Discount:** 64% — *6 In 1 Bottle Can Opener*
- **Most Reviewed Product:** *120W Cordless Vacuum Cleaner* with 69 reviews
- Many products had **no reviews or ratings** — categorized as `Missing`, indicating newly listed items

---

##  Dashboard Features

The Excel dashboard includes:

- **Summary KPIs** — Total products, average rating, average discount, total reviews
- **Discount Category Breakdown** — Distribution of Low, Medium, and High discount products
- **Top 10 Most Discounted Products** — Bar chart ranked by discount percentage
- **Rating Category Distribution** — Excellent, Average, Poor, and Missing
- **Products with Most Reviews** — Highlights best-selling/most engaged products
- **Pivot Tables** — For dynamic filtering and slicing of data

---

##  Tools Used

| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Data cleaning, analysis, pivot tables, dashboard |
| **Excel Formulas** | IF, VLOOKUP, AVERAGEIF, COUNTIF, TEXT |
| **Pivot Tables** | Aggregations and cross-tabulations |
| **Excel Charts** | Bar charts, pie charts for visualizations |

---


---

## 💡 Recommendations

1. **Products with High discounts but zero reviews** should be promoted more — they may be newly listed but competitively priced.
2. **Poorly rated products** (below 3.0) with high review counts signal genuine quality issues worth investigating.
3. **Sellers** should aim for ratings above 4.0 — products in the *Excellent* category attract significantly more reviews.

---

## 👤 Author

**Tonny Otieno **

