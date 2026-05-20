# 🛍️ Myntra Fashion Apparel — Data Analysis Case Study

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power Query](https://img.shields.io/badge/Feature-Power%20Query-F2C811?style=for-the-badge&logo=microsoft&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

## 📌 Overview
Analysis of a 5 lakh+ rows Myntra fashion apparel dataset to gain insights into pricing, discounts, ratings, and product availability using **MS Excel** and **Power Query Editor**.

---

## 📂 Dataset
[Myntra Fashion Clothing Dataset](https://drive.google.com/file/d/1CDaWFvkccjdUw1E_gipTKOfMqiHNhNQL/view)
[Cleaned & Analysed Excel File](https://docs.google.com/spreadsheets/d/1MgoR5qF8uLrX98usT0T3lx7CY2sbQ7N3/edit?usp=drive_link&ouid=100591617236635221238&rtpof=true&sd=true)
| Details | Info |
|---------|------|
| Records | 5,26,564 rows, 13 columns |
| Key Columns | BrandName, Category, DiscountPrice, OriginalPrice, DiscountOffer, Ratings |

---

## 📋 Tasks Completed

### 🔷 A — Data Cleaning (Power Query)
| Task | Action |
|------|--------|
| A1 — Duplicates | Removed duplicates — 0 found |
| A2 — DiscountOffer | Standardized all formats to `"X% OFF"` |
| A3 — DiscountPrice nulls | Filled using DiscountOffer calculation and Category average |
| A4 — SizeOption nulls | Replaced nulls with `"Not Available"` |

### 🔷 B — Data Analysis (Excel Formulas)
| Task | Formula Used | Result |
|------|-------------|--------|
| B1 — Avg Original Price (Rating > 4) | AVERAGEIF | ₹1,966 |
| B2 — Products with > 50% discount | SUMPRODUCT | 2,41,267 products |
| B3 — Products available in size M | COUNTIF | 3,08,460 |
| B4 — High / Low Discount label | Power Query Custom Column | — |

### 🔷 C — Data Lookup (Excel Formulas)
| Task | Formula Used |
|------|-------------|
| C1 — Brand, Price, Rating by Product ID | VLOOKUP |
| C2 — DiscountPrice by Product ID | INDEX / MATCH |
| C3 — Dynamic full product lookup | INDEX / MATCH (all columns) |

---

## 💡 Key Insight
**45.81% of Myntra products** offer more than 50% discount — showing aggressive discounting as a core sales strategy.

---

## 👤 Author
**Som Dubey** — 
www.linkedin.com/in/som-dubey002
