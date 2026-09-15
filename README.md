# YuvaIntern Week 3,4,5 – Data Analysis & Interpretation

## Fashion Market Research & Competitive Analysis

This project was completed as part of the **YuvaIntern Junior Data Analyst Internship – Week 3: Data Analysis and Interpretation**.

The project focuses on analyzing fashion market research data to identify **pricing patterns, product distribution, category trends, gender-oriented product preferences, price segments, sub-category trends, and brand-level competitive insights**.

---

## 🎯 Project Objective

The objective of this project is to perform a comprehensive analysis of cleaned fashion product data and generate meaningful business insights that can help fashion brands understand their:

* Product assortment
* Pricing strategy
* Category distribution
* Target audience
* Price positioning
* Competitive landscape

The analysis was performed using **Python and Power BI**, supported by Excel-based data preparation.

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Jupyter Notebook**
* **Microsoft Power BI**
* **Microsoft Excel**
* **GitHub**

---

## 📁 Project Structure

```text
YuvaIntern-Week3-Data-Analysis/
│
├── README.md
│
├── data/
│   └── Week3_Clean_Product_Data.csv
│
├── python/
│   └── Week3_Data_Analysis.ipynb
│
├── powerbi/
│   └── Week3_Fashion_Market_Dashboard.pbix
│
├── report/
│   └── Week3_Data_Analysis_Interpretation_Report.docx
│
└── screenshots/
    └── Week3_PowerBI_Dashboard.png
```

---

## 📊 Dataset Overview

The cleaned dataset contains **242 fashion product records** collected across **5 major fashion brands**:

* Nike
* adidas
* Zara
* UNIQLO
* H&M

The dataset contains the following major fields:

* Record ID
* Brand
* Product Name
* Category
* Sub-Category
* Gender
* Selling Price
* Original Price
* Price Segment
* Data Collection Date
* Source URL

---

# 🔍 Analysis Performed

## 1. Product Category Analysis

The product assortment was analyzed across different fashion categories.

| Category    | Products | Percentage |
| ----------- | -------: | ---------: |
| Apparel     |      147 |     60.74% |
| Footwear    |       82 |     33.88% |
| Innerwear   |        8 |      3.31% |
| Accessories |        2 |      0.83% |
| Beauty      |        1 |      0.41% |
| Home        |        1 |      0.41% |
| Sportswear  |        1 |      0.41% |

### Key Insight

**Apparel is the largest category**, with 147 products representing **60.74%** of the dataset.

Footwear is the second-largest category with 82 products.

Together, **Apparel and Footwear account for 94.63%** of the complete product assortment.

---

## 2. Gender-Oriented Product Analysis

The dataset was analyzed based on the intended gender/target audience of products.

| Gender      | Products | Percentage |
| ----------- | -------: | ---------: |
| Women       |      153 |     63.22% |
| Men         |       49 |     20.25% |
| Unspecified |       34 |     14.05% |
| Kids        |        3 |      1.24% |
| Unisex      |        3 |      1.24% |

### Key Insight

Women-oriented products represent the largest segment, accounting for **63.22%** of the analyzed product assortment.

This indicates that the collected dataset has a strong focus on women's fashion products.

---

## 3. Pricing & Price Segment Analysis

Products were classified into different price segments to understand the overall pricing structure.

| Price Segment  | Products | Percentage |
| -------------- | -------: | ---------: |
| Budget         |       66 |     27.27% |
| Mid-range      |       62 |     25.62% |
| Unspecified    |       53 |     21.90% |
| Premium        |       32 |     13.22% |
| Luxury/Premium |       29 |     11.98% |

### Key Insights

* **Budget products:** 66
* **Mid-range products:** 62
* **Premium products:** 32
* **Luxury/Premium products:** 29

Budget and Mid-range products together account for:

**128 products = 52.89%**

Premium and Luxury/Premium products together account for:

**61 products = 25.21%**

This indicates a significant presence of both accessible and higher-priced fashion products.

> The 53 "Unspecified" records represent products where a final price-segment classification was not available. They should not be interpreted as a separate market segment.

---

## 4. Product Sub-Category Analysis

The most represented product sub-categories were analyzed to understand the detailed assortment structure.

| Sub-Category | Products |
| ------------ | -------: |
| Dress        |       48 |
| Lifestyle    |       31 |
| Running      |       16 |
| Originals    |       15 |
| T-Shirt      |       15 |
| Pants        |       12 |
| Top          |        9 |
| Shirt        |        8 |
| Sportswear   |        6 |
| Basketball   |        5 |
| Cricket      |        5 |

### Key Insight

**Dress is the largest individual sub-category**, with 48 products representing approximately **19.83%** of the dataset.

Lifestyle products are the second-largest sub-category with 31 products.

---

# 🏷️ Brand-Level Competitive Analysis

The dataset contains five major brands:

| Brand  | Product Records |
| ------ | --------------: |
| Nike   |              50 |
| Zara   |              50 |
| UNIQLO |              49 |
| adidas |              47 |
| H&M    |              46 |

The brands were compared based on:

* Product assortment
* Category distribution
* Average selling price
* Gender-oriented product distribution
* Price segments
* Sub-category representation

### Brand Pricing Observation

Based on the available priced records, the observed average selling prices were approximately:

| Brand  | Observed Average Selling Price |
| ------ | -----------------------------: |
| Nike   |                     ₹10,483.67 |
| adidas |                      ₹7,325.00 |
| Zara   |                      ₹4,310.42 |
| UNIQLO |                      ₹2,032.86 |
| H&M    |                      ₹1,226.20 |

### Interpretation

Nike and adidas show relatively higher observed average selling prices, indicating a stronger higher-price positioning within the collected data.

Zara occupies a comparatively mid-level pricing position, while UNIQLO and H&M show lower observed average prices.

> These averages are based on records with available observed selling prices and should not be interpreted as complete brand-wide pricing statistics.

---

# 📈 Power BI Dashboard

An interactive Power BI dashboard was developed to present the analysis in a business-friendly format.

### Dashboard Components

* KPI Cards
* Product Distribution by Brand
* Product Mix by Category
* Product Distribution by Gender
* Average Selling Price by Brand
* Price Segment Distribution
* Top Product Sub-Categories
* Category Distribution Across Brands
* Brand Slicer
* Gender Slicer
* Category Slicer
* Price Segment Slicer

### Dashboard Preview

![Power BI Dashboard](screenshots/Week3_PowerBI_Dashboard.png)

---

# 🐍 Python Analysis

Python was used to perform data analysis and generate analytical visualizations.

The Jupyter Notebook includes:

* Dataset loading
* Data inspection
* Data quality checks
* Descriptive analysis
* Brand-level analysis
* Category analysis
* Gender analysis
* Price-segment analysis
* Sub-category analysis
* Group-by analysis
* Data visualizations

Python helped identify numerical patterns and summarize the cleaned dataset before presenting the results through Power BI.

---

# 📊 Power BI Analysis

The cleaned dataset was imported into Microsoft Power BI to create an interactive analytical dashboard.

Power BI was used for:

* KPI analysis
* Product assortment analysis
* Brand comparison
* Category analysis
* Gender analysis
* Price-segment analysis
* Average price comparison
* Interactive filtering
* Business insight generation

The dashboard allows users to filter the analysis by **Brand, Gender, Category, and Price Segment**.

---

# 💡 Key Business Insights

### 1. Apparel Dominates the Product Assortment

Apparel accounts for **147 out of 242 products**, representing **60.74%** of the dataset.

This shows that apparel is the primary product category in the collected market sample.

### 2. Apparel and Footwear Represent the Core Market

Apparel and Footwear together account for **229 products**, or approximately **94.63%** of the dataset.

This suggests that these two categories form the core assortment represented in the research data.

### 3. Women's Products Have the Highest Representation

Women-oriented products account for **153 products**, representing **63.22%** of the dataset.

This indicates strong representation of women's fashion within the collected sample.

### 4. Budget and Mid-Range Products Dominate Classified Segments

Budget and Mid-range products together account for **52.89%** of all records.

This indicates that accessible and mid-level pricing represents a major part of the analyzed assortment.

### 5. Premium Positioning Has a Significant Presence

Premium and Luxury/Premium products together account for **25.21%** of the dataset.

This indicates that higher-priced products also form a meaningful part of the market assortment.

### 6. Dress Is the Largest Sub-Category

Dress has **48 products**, making it the largest individual sub-category in the dataset.

### 7. Brand Assortments Are Relatively Balanced

Each brand contributes approximately 46–50 product records, allowing a reasonably balanced comparison of the five brands within this collected sample.

---

# 🎯 Strategic Recommendations

Based on the analysis, the following recommendations can be considered:

### 1. Strengthen Core Apparel Assortment

Since apparel represents the majority of the dataset, brands can continue investing in high-demand apparel categories while monitoring assortment diversity.

### 2. Maintain Balanced Pricing

The strong representation of Budget and Mid-range products suggests that accessible pricing can be important for reaching a broader market.

### 3. Develop Premium Product Lines

The presence of Premium and Luxury/Premium products indicates an opportunity to maintain differentiated higher-value product lines for customers seeking premium positioning.

### 4. Focus on Women's Product Segments

Since women's products represent 63.22% of the sample, brands can analyze women's categories and sub-categories for further assortment opportunities.

### 5. Monitor Category Concentration

The high concentration of products in Apparel and Footwear suggests that brands should also evaluate opportunities in smaller categories to diversify their product portfolio.

---

# ⚠️ Data Interpretation & Limitations

The following limitations should be considered while interpreting the analysis:

1. The dataset represents a collected market research sample and may not represent the complete product catalog of each brand.

2. Product count represents **assortment representation**, not actual sales popularity.

3. Transaction-level data such as units sold, revenue, customer orders, and purchase frequency were not available.

4. Gender represents the **target audience of products**, not customer-level demographic information.

5. Some records had unspecified price-segment classifications.

6. Brand-level average selling prices are based on available observed prices and should not be treated as complete official brand pricing statistics.

---

# 📄 Project Deliverables

| File                                             | Description                                 |
| ------------------------------------------------ | ------------------------------------------- |
| `Week3_Clean_Product_Data.csv`                   | Cleaned dataset used for analysis           |
| `Week3_Data_Analysis.ipynb`                      | Python/Jupyter Notebook containing analysis |
| `Week3_Fashion_Market_Dashboard.pbix`            | Interactive Power BI dashboard              |
| `Week3_Data_Analysis_Interpretation_Report.docx` | Detailed analysis report                    |
| `Week3_PowerBI_Dashboard.png`                    | Power BI dashboard preview                  |

---

# 🔄 Analysis Workflow

```text
Raw Fashion Market Data
        ↓
Data Cleaning & Pre-processing
        ↓
Cleaned Dataset
        ↓
Python Analysis
        ↓
Exploratory Analysis & Visualizations
        ↓
Power BI Dashboard
        ↓
Business Insights
        ↓
Strategic Recommendations
```

---

# 🏁 Conclusion

This project provides a structured analysis of fashion market research data across five major brands.

The analysis identified important patterns in **product categories, gender-oriented products, pricing segments, sub-categories, and brand-level pricing**.

The combination of **Python for analytical exploration** and **Power BI for interactive visualization** provides a complete data-analysis workflow from cleaned data to business insights.

The findings can help fashion businesses understand product assortment patterns, pricing positioning, target-market representation, and competitive differences within the collected market sample.

---

## 👩‍💻 Internship Project

**Program:** YuvaIntern – Junior Data Analyst Internship
**Task:** Week 3 – Data Analysis & Interpretation
**Domain:** Apparel, Textiles & Fashion
**Analysis Tools:** Python, Pandas, NumPy, Matplotlib, Jupyter Notebook, Power BI, Excel
**Repository:** YuvaIntern-Week3-Data-Analysis

---

⭐ **This project was developed for internship learning, data analysis, and evaluation purposes.**
